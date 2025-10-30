
What the project does ?

- This project is a simple Node.js application containerized using Docker and automated using GitHub Actions.  
- It demonstrates how to build, test, and deploy a Node.js app inside a Docker container using a CI/CD pipeline.

How to run it locally ?
- this project can be cloned in a local repository.
- install all the dependencies.
- and run it using node js or inside docker container
- It runs on port 3000 and displays a hello world message on http://localhost:3000/

Pipeline flow (step-by-step explanation) 
- the workflow automatically is triggered by a push on the develop branch.
- the entire repo is clone on the github runner.
- node environment is configured (node 22).
- all the dependencies in the package file are installed using the command npm i.
- after all the dependencies are sucessfully installed test are run. (in the current assignent its just dummy text echoed in the terminal).
  simulating all test cases passed.
- the web app is then containerized using docker.
- the container is then started to verify if it works correctly.

Any challenges faced and how you resolved them 
was new to Github Actions
- so I understood it to create a simple ci/cd pipeline using online tutorials and documentation.




