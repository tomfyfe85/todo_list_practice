TODO APP PLANS:

HIGH LEVEL:
Add/delete todos displayed in the browser
Mark todos as complete

-) create TodoList Component
- TodoList displays a list of todo OBJECTS in the browser {id, todo}
- User can input todos in a box and submit
- The todo should appear in the browser
- When another todo is added, it should be represented in the browser

-) create Todo Component
each todo can display a motivational message from an api when created
each todo has a delete button 
todos can be marked complete
incomplete todo's are styled represented
completed are styled green

Phase 1 
-create TodoList component
-) get TodoList to display a list of placeHolder todos on the page
-2) todos need a unique id, 
-3) create input field. useState event.taget.value 
-4) addTodo display new todo on the list on submit with a unique id
-5) input field should return to empty on submit

-6) create a delete all button


Phase 2
-) create todo compoment, pass id and to it as props
-)Todo list would map todo componets instead of the the todo useState
-) todo has a delete button which removes specific todos from list on click
) user can't submit a blank form
<!-- Use conditional rendering. Only submit for is  -->
) todo has a mark complete button - this moves the todo to a 'completed' section (CSS, green for completed and red for not)
) on creation, each todo could call an API and show the data. Could be a motivational quote API?
) delete all completed/uncompleted

