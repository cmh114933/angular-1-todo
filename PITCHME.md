## To Do List Requirements

+++

- generate a todo list
    - use divs
    - list kept in js object or array
- default color is white with box shadow
- when you click an item,
     - bgColor will toggle between white and black
     - text color will toggle between black and white
- when you hover over an item
     - bgColor will become blue

 ---

 ### Component ( Initialization and State)
 - Give it a `title`, and a list of tasks
 - Each task is a string

+++ 

### Component Template
- Use `interpolation` to obtain task string from Component and display in HTML 

+++

### Structural Directive (*ngFor)
- Use `*ngFor` to loop through the list of tasks

---

### Data binding 
- parent-child property binding (`{{task}}`, `[]`)
- child-parent event binding (`click`, `mouseover`)

+++

- Configure list of task `string` to list of task `object`
- Each object has `taskTitle` and `completed`, which by default is `false`
- On click task, toggle `completed` value of task
- Use the task's `completed` value to decide whether or not to have bgColor and textColor
- On `mouseover`, bgColor as `blue`
- On `mouseleave`, bgColor as `white`

+++ 

### Structural Directive (*ngIf)
- Add a button to delete task
- If no task left to delete, show special notification `No tasks available`
- Use `*ngIf` for conditional rendering

---

## Use Angular to create a Tic Tac Toe 

---

### Multiple To Do List V1
- Copy the HTML and create 3 To Do List
    - Grocery List
    - Homework List
    - Work List

+++
### Multiple To Do List V2
- ng generate component `<component-name>`
- Create 3 Components
    - GroceryListComponent
    - HomeworkListComponent
    - WorkListComponent

+++
### Multiple To Do List V3
- create one ToDoListComponent
- Remove all other list components
- Multi Component interaction
