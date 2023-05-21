## Overview :

Build a Todo Management app using React Native that allows users to organize their tasks into
categories such as Todos, Completed, and Deleted. The app should also include a "Create New"
button that navigates the user to a new screen where they can add a new todo by
providing a title and description. Additionally, there should be a button to generate fake todo data using this api
(https://dummyjson.com/docs/todos)

<img width="826" alt="Screenshot 2023-05-21 at 5 01 39 PM" src="https://github.com/elbarryamine/react-native-test/assets/81116690/1bca28c3-52d3-4785-adb3-5545e839ac45">

## check this drawing here 
<a href="https://excalidraw.com/#json=52N4Z5gMe_IeHmz9rcYEo,r168bti9_MmMBApQsMC8jA">https://excalidraw.com/#json=52N4Z5gMe_IeHmz9rcYEo,r168bti9_MmMBApQsMC8jA</a>

## Before you start:
- You must use React-query to handle fetching the fake date
- You must react-form-hook & zod to create the form and validate the inputs also use redux to handle the todos state.
- You must use Native-base components <a href="https://nativebase.io/">learn more here</a>

## Instructions:
1. You must use `typescript`
2. create a stack with two screens using react-native-navigation `todos` & `create-todo`
3. `create-todo` Screen :
  * create a form to create a new todo with title and
  description.
  * add button that can a generate random todo title using the provided api     (https://dummyjson.com/docs/todos) you must use react-query to do that,a normal api call will not be accepted. and make sure you handle error and loading state
  * add another button to save this todo.
4. `todos` Screen : 
  * Create a tab view using react-native-tab-view with three tabs (`todos`,`completed`,`delete`) (check   the drawing)
  *  list all todos in `todos` tab with two buttons one to mark it as complete and another to delete it.
  *  list completed todos in `completed` tab.
  *  list deleted todos in `delete` tab with a button to restore it.
  *  create a button that navigate to `create-todo`.
5. The app should be compatible with both Android and iOS devices.
6. Feel free to use any design and layout that you think works best for this app.


## How to deliver:

- Provide a GitHub repository link with the source code of the app.
- Include a README file with instructions on how to run the app and any other relevant information.
