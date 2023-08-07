1. used the create next app command to create a new Next JS application which runs on a default 3000 port
2. create a Dockerfile, where the list of commands are given
3. In the Dockerfile, commands to create and setup the Environment and creating the App directory and then copy pasting the files and installing the dependencies and then running the app are written
4. command `build docker -latest t-nextjs:multistage .` is used to build and command `docker run -p 3001:3000 -d nextjs-multistage:latest` is used to run the application in detached mode.
5. verified the running application using `docker ps` command and visiting `localhost:3001`
