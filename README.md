## Overview :

Build a Post Management app using React Native that allows users to organize their posts into
categories such as All Posts, Archived, and Deleted. The app should also include a "Create New"
button that navigates the user to a new screen where they can add a new post by
providing a thumbnail ,title and body. Additionally, there should be a button to generate fake post data using this api
(https://dummyjson.com/docs/posts)

<img width="727" alt="Screenshot 2023-05-21 at 5 38 23 PM" src="https://github.com/elbarryamine/react-native-test/assets/81116690/41418d3d-5656-43d9-9190-b6a50a0b7198">


## check this drawing here 
<a href="https://excalidraw.com/#json=5SDtW5cC8LMCHAwWQIps4,gLHiymXwuRmN-48yWKJO-A">https://excalidraw.com/#json=5SDtW5cC8LMCHAwWQIps4,gLHiymXwuRmN-48yWKJO-A</a>
## Before you start:
- You must use React-query to handle fetching the fake date
- You must react-form-hook & zod to create the form and validate the inputs also use redux to handle the todos state.
- You must use Native-base components <a href="https://nativebase.io/">learn more here</a>

## Instructions:
1. You must use `typescript`
2. create a stack with two screens using react-native-navigation `posts` & `create-post`
3. `create-post` Screen :
  * create a form to create a new post with image, title and
  body.
  * add button that can a generate random post title using the provided api     (https://dummyjson.com/docs/posts) you must use react-query to do that,a normal api call will not be accepted. and make sure you handle error and loading state
  * add another button to save this post.
4. `posts` Screen : 
  * Create a tab view using react-native-tab-view with three tabs (`posts`,`archived`,`deleted`) (check   the drawing)
  *  list all posts in `posts` tab with two buttons one to mark it as complete and another to delete it.
  *  list archived posts in `archived` tab.
  *  list deleted todos in `deleted` tab with a button to restore it.
  *  create a button that navigate to `create-post`.
5. The app should be compatible with both Android and iOS devices.
6. Feel free to use any design and layout that you think works best for this app.


## How to deliver:

- Provide a GitHub repository link with the source code of the app.
- Include a README file with instructions on how to run the app and any other relevant information.
