#Dat250 expass 1

Link to container image of the app on DockerHub:

https://hub.docker.com/layers/mathiasskauge/dat250/latest/images/sha256-fe7055025e38def14e9e1d857e8cecdf1579a1f6b9a3bcbf1ec4ffdadf7e5048?context=repo

##Technical problems I had

I had the JDK and IDE (Intellij) already installed so no problems there

When downloading gradle i couldnt get SDK to work within the bash terminal, since I downloaded it in the powershell. I had to add it to the $Path to get it to work

I tried to use docker to create the image but I couldnt work out how the Dockerfile should look for that so I just used Podman

##How I have validated the SDE

I have checked that the localhost server works
I wanted to check if I could het it to word from Dockerhub, but I havnt figured out how to do that yet

## Other tecnical problems
I couldnt create the image with podman at first, but I just had to change to the correct filename of gradle.settings to get it to work




