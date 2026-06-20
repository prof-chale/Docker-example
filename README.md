<<<<<<< Updated upstream
# Final Report

This is a generic readme file to help you get started. Always reference the provided assignment material and rubric on Canvas. One important aspect of the github repo, is that you should include all the analysis code and files your group used. Once cloned to any computer, the user should be able to re-run your analysis code without needing to rename or reconfigure your files. That's the beauty of open source collaboration with git. 10 pts are awarded for version control and 10 pts are awarded for repository functionality.

![Example Figure](images/doge-i-see-you.gif)
=======
## **Module 6 - Docker Grand Challenge Tutorial Phase 1**

Icon Progress Bar/Navigation (built in browser, hidden in app)

[Module Name]{.underline}

## Phase 1: Run a Docker Container Locally

#### *You can run your code locally. Containerize it, so you can run it anywhere.*

In Module 1, we practiced running [examples](https://keras.io/examples/) from keras in a local environment. We took the time to install an appropriate version of python and used anaconda to install required libraries. By containerizing an environment, we can easily run it anywhere so long as it docker is installed and the compute resources are available. 

If you would like to follow along with my specific example, it is available on <https://github.com/prof-chale/Docker-example>

#### 0. Install Docker Desktop

Install the appropriate version for your operating system. Creating a docker account is not required, though it comes with convenient features. 

<https://docs.docker.com/desktop/>

You may verify proper installation by running the command in your local CLI

`docker --version  # Verify the Docker CLI is installed`

`docker ps  # Verify Docker Desktop is running and the daemon is reachable`

#### 1.  Pull python 3.13 official image

You can pull the official image from from docker hub using the l*ocal command prompt* *or* from the *docker desktop app*

`docker pull python:3.13`

#### 2. Setup your docker image

#### A. Create a docker requirements.txt file.

The name of this file should be exactly as seen here.

Create this text file in the exact location your code and data will be stored. You will need to know the required packages for your desired python project. While you can certainly create a txt file in the command prompt, I prefer creating it in the windows folder. 

#### B. Create a requirements file

-   The name of this file should be exactly Dockerfile . Ensure there is no .txt suffix.

    -   you can use this command in your local CLI to ensure there is not .txt suffix (which windows sometimes hides)

    -   `Get-ChildItem | Select-Object Name, Extension, Length`

-   This is the blueprint for creating your custom image from the official image. Take a minute to read about [Writing a Dockerfile](https://docs.docker.com/get-started/docker-concepts/building-images/writing-a-dockerfile/). Feel free to use an LLM to write the dockerfile for your needs. 

    -    [Writing a Dockerfile](https://docs.docker.com/get-started/docker-concepts/building-images/writing-a-dockerfile/).

-   Here is my [Dockerfile](https://bostoncollege.instructure.com/courses/1683400/files/77210176?wrap=1 "Dockerfile") ; open it with a text editor.

#### 3. Build the image

This might take about 10 minutes. Much of the bottleneck is internet download speed. 
>>>>>>> Stashed changes
