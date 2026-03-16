# AI 6001 Project Specification

The overall goal of this project is to get you familiar with modern AI tools, software development, and application deployment. As such, you are allowed to use any amount of AI / LLM tools to create the code for this project in order to create the application. The reason for this is that the final video presentation will be worth the vast majority of the marks for the project, and will go into detail about the overall process of making the software with the AI tools. All of the specifications for the project code and final presentation can be found in the relevant sections below.

Note: DO NOT just copy and paste this specification into whatever AI tool you end up using. You should start from scratch building the system incrementally and documenting that process for the video presentation

## Marking Scheme

- **Project Demo** (20%)
  - A hosted version of the project that I can play to test the functionality
- **Project Code / Gameplay** (10%)
  - The final source code of the project that you have created
- **Project Report Video** (70%)
  - The final video explaining everything that is required in the specification below

## Project Overview

  - The project should be done in a group of 2 people (unless a serious reason prevents this somehow)
  - You MUST use AI tools to write the code for this project, since the point is to get you to learn to use them
  - You can use any amount of AI tools to write the code, website, dockerfile, etc for this project
  - The game must be somewhat intuitive and enjoyable to play / iteract with

## Required Game Functionality

  - You must create a web application that implements the user interface for a game that is playable with in the browser
    - You must use either html canvas or three.js as the main rendering system for your game
  - You must create a non-trivial AI system for that game that controls a significant amount of gameplay for an AI agent
  - Your game must have a user login system where people can log in to save or continue their progress since their last play session
    - Usernames, passwords, and all data must be stored in a database (mongodb, for example)
    - Security is not of great concern with this project, as long as the functionality works
  - Your game does not need to be able to be played by 2 humans at the same time, but you need to have an AI player that you either play with or against in some way
   
## Docker Deployment

As this project will be a web-hosted application, it is natural that it will depend on other applications such as web server(s), database(s), and other libraries. 

As part of the project source code delivery, you must create a Dockerfile that is able to launch and run your application.
     
## Project Presentation Video

Since you can get AI to write all the code for you, the final project presentation video is by far the most important part of this project. The project video should contain human-generated audio narration with your group members spending an equal amount of time narrating about the parts they worked on.

Your comments into the workflow / usage of the AI tools, how you used them, whether or not they made mistakes, whether you like this sort of development, is the most important part of the video. I want to get YOUR insights into the process of making an application with AI tools.

Your video must contain the following information:

- Project Demo
  - You should give a brief demo of your project and all the features you implemented
  - Since I cannot fully test every project, if a feature is not in the video it does not exist
  - The demo should be around 5 minutes and show all functionality
  - You should specifically showcase the smart behavior of the AI system in your game
- Changes Over Time
  - I want to see examples of the user interface / game over time as new features were added or the design was changed
  - Explain how you experimented with different UIs and how you got the AI to
  - Keep recordings or screenshots of different versions throughout development
- AI Tools Workflow / Usage Demonstration
  - Overall AI tooling workflow, how it writes code, how you interact with it
  - Examples of prompts you gave it (especially the initial prompt) and how it generates code / files
  - You should describe whether or not you like this process, and how you think it would feel if you did this professionally
- AI Mistakes / Architecture
  - You must include examples where the AI made a mistake, or made an architectural decision that you disagreed with and needed to fix somehow
  - You should show what the AI did, how you interacted with it to fix it, and the prompts you gave to get it to do exactly what you wanted

