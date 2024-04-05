# 05-TaskBoard

## User Story
As a project team member with multiple tasks to organize, I want a task board 
So that I can add individual project tasks, manage their state of progress and track overall project progress accordingly

## Acceptance Criteria
GIVEN a task board to manage a project
WHEN I open the task board
THEN the list of project tasks is displayed in columns representing the task progress state (Not Yet Started, In Progress, Completed)
WHEN I view the task board for the project
THEN each task is color coded to indicate whether it is nearing the deadline (yellow) or is overdue (red)
WHEN I click on the button to define a new task
THEN I can enter the title, description and deadline date for the new task into a modal dialog
WHEN I click the save button for that task
THEN the properties for that task are saved in localStorage
WHEN I drag a task to a different progress column
THEN the task's progress state is updated accordingly and will stay in the new column after refreshing
WHEN I click the delete button for a task
THEN the task is removed from the task board and will not be added back after refreshing
WHEN I refresh the page
THEN the saved tasks persist


## Link to deployed application
- https://github.com/CrystalC19/05-TaskBoard.git
- https://crystalc19.github.io/05-TaskBoard/index.html



## Resources
- Setting up my Modal: https://getbootstrap.com/docs/5.3/components/modal/ ,https://youtu.be/ahglWgTnyXI?si=J45UJwUh8WE6JLph
- Form: https://getbootstrap.com/docs/5.3/forms/input-group/



