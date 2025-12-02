# **Evaluation Tasks — Week 9**

## **Task 1: Add a new task**

**Scenario**: You want to add a new task as a reminder for later in the week.

**Instructions**:

1. Add a new task: **"Plan weekend schedule"**
2. Confirm it appears in the task list

**Success criteria**:

* Form submission works (HTMX and no-JS)
* New task shows up immediately or after a reload
* Confirmation or status message appears

**Inclusion focus**: Handling blank title errors, ARIA live announcements

**Explanation**: This task tests how you create a new task. You’ll need to submit the form correctly and make sure the task shows up in the list with a confirmation message.

---

## **Task 2: Edit Task Inline**

**Scenario**: You made a typo in a task title and need to correct it.

**Instructions**:

1. Find the task **"Buy milk"**
2. Edit it to **"Buy oat milk"**
3. Save the change

**Success criteria**:

* Edit mode activates and input appears
* Save updates the title
* Focus returns to the task

**Inclusion focus**: Focus management, keyboard-only editing, Cancel button

**Explanation**: This task is about editing a task. You’ll be tested on how easily you can change a task title and how well the system saves those changes while ensuring focus is maintained.

---

## **Task 3: Delete Completed Task**

**Scenario**: You’ve completed the task **"Email supervisor"** and want to remove it.

**Instructions**:

1. Find the task **"Email supervisor"**
2. Delete it
3. Confirm it’s gone from the list

**Success criteria**:

* Confirmation shows (HTMX) OR form submits in no-JS
* Task is removed from the list
* Status message is announced

**Inclusion focus**: Confirmation workflow differences (HTMX vs no-JS)

**Explanation**: This task tests how you delete a completed task. You’ll need to confirm deletion and ensure the task is removed from the list correctly.

---

## **Task 4: Sort or Filter Tasks**

**Scenario**: You want to tidy up your task view by applying filters or sorting.

**Instructions**:

1. Apply a filter or sort option (e.g., **"Show completed"** or **"Sort by due date"**)
2. Confirm the list updates to reflect the new filter or sort order

**Success criteria**:

* Sorting/filter controls are accessible via keyboard
* Visual change in task order or filtering
* Screen reader announces the updated list state

**Inclusion focus**: ARIA roles for sort/filter controls, focus preservation after action

**Explanation**: This task checks how well you can organize your tasks. You’ll need to apply a filter or sorting option and ensure the list updates properly.

---

## **Metrics per Task**

For each task, record:

* **Time-on-task** (seconds from start to completion)
* **Success** (1 = completed, 0 = abandoned)
* **Error count** (validation errors, wrong clicks)
* **Mode** (HTMX or no-JS)

