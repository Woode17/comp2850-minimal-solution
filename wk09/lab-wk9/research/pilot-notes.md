# Pilot Data — Week 9

## Participant P1 - Using all modes of input
**Mode**: HTMX
**Date**: [2025-12-04 15:39]
**Consent**: ✅ Verbal confirmed
**Duration**: 10 minutes


---

### **Task 1: Create a New Task**

**Start**: 15:42:00 → **End**: 15:42:54 = **54 seconds**
**Success**: 1
**Errors**: 1 (pressed submit without typing anything)
**Confidence**: 5/5
**Observations**:

- Error message displayed clearly (“Title cannot be empty”).
- Enter key submitted successfully after correction.
- “Task added” status announced correctly.

2025-12-04T15:42:54.126592179Z,P1_274e,r_b5c1501d,T3_add,success,,14,200,on

---

### **Task 2: Edit The task you just created and save it**

**Start**: 15:48:00 → **End**: 15:48:35 = **35 seconds**
**Success**: 1
**Errors**: 0
**Confidence**: 4/5
**Observations**:

- Found the edit button quickly.
- Smooth inline edit; saved without issues.
- Mentioned: “Good, focus went back where I expected.”

---
2025-12-04T15:48:35.371471654Z,P1_274e,r_dc272368,T2_edit,success,,7,200,on


### **Task 3: Delete Completed Task**

**Start**: 15:49:00 → **End**: 15:49:12 = **20 seconds**
**Success**: 1
**Errors**: 0
**Confidence**: 5/5
**Observations**:

- Used the mouse to click delete.
- HTMX confirm box appeared; user approved.
- Task disappeared instantly; status message read correctly.
- Tool a while to ensure the task was deleted

---
2025-12-04T15:49:12.084316787Z,P1_274e,r_efa53f08,T4_delete,success,,7,200,on

### **Task 4: Sort or Filter Tasks**

**Start**: 15:51:40 → **End**: 15:52:47 = **67 seconds**
**Success**: 1
**Errors**: 1 (clicked sort, expected filter)
**Confidence**: 3/5
**Observations**:

- Tried to use sort when asked to filter, then corrected.
- Said filter changes were “clear enough once I noticed the list moving.”

---
025-12-04T15:52:39.913225719Z,P1_274e,r_af671b72,T3_add,success,,16,200,on
2025-12-04T15:52:43.531363661Z,P1_274e,r_9d79e9ec,T1_filter,success,,11,200,on
2025-12-04T15:52:44.092725320Z,P1_274e,r_06f33964,T1_filter,success,,8,200,on
2025-12-04T15:52:46.568789532Z,P1_274e,r_50fb09ba,T1_filter,success,,8,200,on
2025-12-04T15:52:47.257799662Z,P1_274e,r_ea0e0901,T1_filter,success,,9,200,on

### **Debrief Notes**

**Most confusing**: Unsure which option was sort vs filter at first.
**Most helpful**: Status messages after create/delete actions.
**Accessibility**: Completed tasks with keyboard only. Focus indicators worked well.

---

## **Participant P2** 

**Mode**: No JS
**Date**: [2025-12-04 16:15]
**Consent**: ✅ Verbal confirmed
**Duration**: 9 minutes

---

### **Task 1: Create a task**

**Start**: 16:19:10 → 16:19:22 = **12 seconds**
**Success**: 1
**Errors**: 0
**Confidence**: 4/5
**Observations**:

-Typed title and used the submit button.
-Page reload displayed new task at the bottom.
-No-JS version showed confirmation message at top of page—user commented “easy to miss.”

---

2025-12-04T16:19:22.779390003Z,P2_893f,r_e3ae14f8,T3_add,success,,3,200,off
2025-12-04T16:19:22.804989138Z,P2_893f,r_9fda5bc1,T0_list,success,,22,200,off


### **Task 2: Edit Task Inline**

**Start**: 16:20:20 → 16:24:40 = **260 seconds**
**Success**: 1
**Errors**: 1 (clicked “Cancel” thinking it would save)
**Confidence**: 3/5
**Observations**:

- Edit opened on new page due to no-JS flow.
- User said “Cancel is confusing, I thought it might keep my changes.”
- The edit button was not behaving like it should do
- Using no JS doesnt allow it to make changes

---
2025-12-04T16:20:51.855618778Z,P2_893f,r_6dfffc39,T0_list,success,,25,200,off
2025-12-04T16:20:54.435431096Z,P2_893f,r_d2fe35f2,T0_list,success,,23,200,off
2025-12-04T16:20:57.897030476Z,P2_893f,r_505995e9,T0_list,success,,19,200,off
2025-12-04T16:21:03.747732472Z,P2_893f,r_54c73deb,T0_list,success,,19,200,off
2025-12-04T16:24:40.054623007Z,P2_893f,r_21697224,T0_list,success,,26,200,off

### **Task 3: Delete Completed Task**

**Start**: 16:26:16 → 16:27:02 = **46 seconds**
**Success**: 1
**Errors**: 0
**Confidence**: 5/5
**Observations**:

- No confirmation because no-JS.
- Page reloaded with task removed.
- User said it felt “a bit abrupt” but understandable.
- They said they wanted the colour of the delete to be red

---

2025-12-04T16:26:52.774129797Z,P2_893f,r_0fb991ac,T3_add,success,,3,200,off
2025-12-04T16:26:52.802973787Z,P2_893f,r_c6ab0478,T0_list,success,,26,200,off
2025-12-04T16:27:02.430960987Z,P2_893f,r_a5bfc964,T4_delete,success,,10,200,off
2025-12-04T16:27:02.457035115Z,P2_893f,r_37c652e1,T0_list,success,,24,200,off


### **Task 4: Sort or Filter Tasks**

**Start**: 16:28:03 → 16:28:26 = **23 seconds**
**Success**: 1
**Errors**: 1 (applied sort twice thinking it didn’t work due to reload delay)
**Confidence**: 3/5
**Observations**:

- Sorting required full reload; delay caused confusion.
- Eventually saw ordered list correctly.

---

2025-12-04T16:28:03.143831171Z,P2_893f,r_21aea0a6,T0_list,success,,13,200,off
2025-12-04T16:28:07.312343216Z,P2_893f,r_09d5fad1,T0_list,success,,13,200,off
2025-12-04T16:28:26.297628639Z,P2_893f,r_1f1df289,T0_list,success,,13,200,off


### **Debrief Notes**

**Most confusing**: Not knowing whether actions saved after page reloads.
**Most helpful**: Red error message for empty title.
**Accessibility**: Could tab through everything, but reloads broke focus position each time.

---



## **Participant P3**

**Mode**: HTMX but no keyboard
**Date**: 2025-01-12 16:58
**Consent**: ✅
**Duration**: 17 minutes

---

### **Task 1: Create a task**

**Start**: 17:01:02  → 17:01:43 = **22 seconds**
**Success**: 1
**Errors**: 0
**Confidence**: 5/5
**Observations**:

- Fast: typed and pressed Enter.
- Instant list update worked well.
- However tabbed through all the actions and skipped the initial search bar which increased time by 30 odd seconds

---
2025-12-04T17:01:43.717711329Z,P3_298i,r_6f75f1d4,T3_add,success,,20,200,on

### **Task 2: Edit Task Inline**

**Start**: 17:02:20 → 17:03:42 = **82 seconds**
**Success**: 1
**Errors**: 0
**Confidence**: 4/5
**Observations**:

- Minor hesitation locating the save icon.
- After saving: “Oh it jumped back, good.”
- Had to tab through all the tasks however had to go through to the next page as we had exceeded the list space

---

025-12-04T17:03:15.659589385Z,P3_298i,r_d00679ea,T3_add,success,,27,200,on
2025-12-04T17:03:32.397411024Z,P3_298i,r_42d92f23,T1_filter,success,,6,200,on
2025-12-04T17:03:42.503489846Z,P3_298i,r_0176c525,T2_edit,success,,8,200,on


### **Task 3: Delete Completed Task**

**Start**: 17:06:38 → 17:07:04 = **26 seconds**
**Success**: 1
**Errors**: 0
**Confidence**: 5/5
**Observations**:

- Immediate confirm → deleted cleanly.
- Again had to tab through the next page and also referenced a larger contrast between the other buttons perhaps making it red
---
025-12-04T17:06:38.147950424Z,P3_298i,r_8800cfde,T1_filter,success,,14,200,on
2025-12-04T17:06:55.261584793Z,P3_298i,r_ab461a58,T3_add,success,,16,200,on
2025-12-04T17:06:57.772121034Z,P3_298i,r_95b5a52d,T1_filter,success,,7,200,on
2025-12-04T17:07:04.186974280Z,P3_298i,r_9ab7afb7,T4_delete,success,,5,200,on


### **Task 4: Sort or Filter Tasks**

**Start**: 17:09:40 → 17:10:04 = **24 seconds**
**Success**: 1
**Errors**: 0
**Confidence**: 4/5
**Observations**:

- Used “Show completed” filter.
- Said “Nice, the list shrank exactly how I expected.”
- Had a hard time manipulating the screen and using page up and page down and so couldnt see the filter
---

2025-12-04T17:09:40.961949996Z,P3_298i,r_371cfab6,T1_filter,success,,10,200,on
2025-12-04T17:09:41.295663694Z,P3_298i,r_bc94b443,T1_filter,success,,4,200,on
2025-12-04T17:09:44.447096751Z,P3_298i,r_101fcb96,T1_filter,success,,4,200,on
2025-12-04T17:09:53.789967030Z,P3_298i,r_37a162c2,T1_filter,success,,14,200,on
2025-12-04T17:09:55.005561497Z,P3_298i,r_6f2e11e2,T1_filter,success,,7,200,on
2025-12-04T17:09:55.486501862Z,P3_298i,r_2895bce4,T1_filter,success,,7,200,on
2025-12-04T17:09:55.986311769Z,P3_298i,r_8e412fdd,T1_filter,success,,7,200,on
2025-12-04T17:10:04.265201803Z,P3_298i,r_ce6e1b7c,T4_delete,success,,6,200,on


### **Debrief Notes**

**Most confusing**: Unsure when filter had been applied until they saw list shrink.
**Most helpful**: Edit mode being inline instead of on a separate page.
**Accessibility**: Voiceover tested; announcements worked consistently.
