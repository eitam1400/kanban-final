# Pre Course Project - Todo List 📋

This projects is my submission for Cyber4s pre-course final.

A Todo list web application for keeping important tasks in an organized fashion.

Heres a link to the [GitHub Page]

### Interaction

- [ ] When the user clicks on one of the add-task buttons, a new task will be added to the respective list. The task content will be taken from the respective input field.
- [ ] Trying to submit empty tasks should cause an alert.
- [ ] Double clicking a task element will enable the user to edit its text. When the task element loses focus (`blur` event) the change will be saved.
- [ ] Hovering over a task element and pressing `alt + 1-3` will move the task to the appropriate list (`1`: todo, `2`: in-progress, `3`: done).
- [ ] The search input should filter tasks case-**in**sensitively, so that only tasks that match the search string are displayed. The filter will be reapplied every time the user changes the content of the search input (on **every keystroke**).

### Storage

- [ ] The data of all the tasks should be saved to `localStorage` following any changes made to the data. The data should be saved under a storage key named `tasks`. It should be saved in the following format (use the data saved in the local storage to keep the data on the page after refresh):

```json
{
  "todo": [],
  "in-progress": [],
  "done": []
}
```

- [ ] Even if there are no tasks, there should still be a `tasks` key in the `localStorage`, in the above format (the arrays will just be empty).

## Bonuses


  - [ ] If an error occurs show an alert.
  
  - [ ]calendar with time and date
  - [ ] dark mode feature usin css variables
