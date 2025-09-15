What triggers this workflow to run?- A push to the main branch is what triggers the workflow to run

What are the four main steps this workflow performs? (List each step name)
-Retrieving the repository code
-Setting up the environment 
-Checks the HTML for errors by running tests, then validates it
-Publishes the website

What does the "Checkout code" step do and why is it necessary?- The checout code pulls the repository code into the workflow. This is what the steps from the above question have so that they can access and work with the files. If this didnt happen,
the workflow wouldn't have any code to build and run.

What is the purpose of the environment configuration?- to ensure the workflow has the proper runtime needed for correct deployment. It needs the necessary tools to validate the steps that are needed for real execution

How does this automated deployment improve reliability compared to manual deployment?-tests are constantly ran before execution. This is important because it reduces error which ensures that the website is only deploying when there is optimal code to do so

What would happen if you pushed code to a different branch (not main)?-Since the workflow is only configured to main, it will not run. If we make changes to other branches, they must become merged into main in order to execute.
