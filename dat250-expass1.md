# Dat250 expass 1

Link to container image of the app on DockerHub:
https://hub.docker.com/repository/docker/mathiasskauge/dat250/general

### Technical problems I had

I had the JDK and IDE (Intellij) already installed so no problems there

When downloading gradle i couldnt get SDK to work within the bash terminal, since I downloaded it in the powershell. I had to add it to the $Path to get it to work

I tried to use docker to create the image but I couldnt work out how the Dockerfile should look for that so I just used Podman

### How I have validated the SDE

I have checked that the localhost server works

I wanted to check if I could het it to word from Dockerhub, but I havnt figured out how to do that yet

### Other tecnical problems
I couldnt create the image with podman at first, but I just had to change to the correct filename of gradle.settings to get it to work

I also couldnt build the image with podman while the Dockerfile was in the same folder as the app, so I had to move it out and then it worked




