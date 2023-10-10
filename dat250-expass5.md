# DAT250 Expassignment 5 Report

Link to repositories: 

(I made a new project for each to practise using the springboot initizialiser, 
I also was not sure if having several @SpringBootApplication in a project would mess things up)

1. https://github.com/mathiasskauge/dat250_expass5.1
2. https://github.com/mathiasskauge/dat250expass5.2
3. https://github.com/mathiasskauge/dat250expass5.3
4. https://github.com/mathiasskauge/dat250expass5.4

Problems:

When I had several @SpringBootApplication in the same project I got an error saying it couldnt recognize which one was correct

When I first tried to make the JAR in the intellij I could find where the har-file actually went, and I also got this error:

![bilde](https://github.com/mathiasskauge/dat250assignment1/assets/143606784/94fb1e0d-37e9-48ee-9754-06ba87a6e71c)

But then I used the command prompt and navigated to the project, and after running gradle build I could find the correct name with ls in target/libs
Then I ran java -jar "correct JAR name" and it worked


![bilde](https://github.com/mathiasskauge/dat250assignment1/assets/143606784/3f4d2309-b3a6-4f54-aaca-ef6da23e0c6f)







