# **Cohort 4 Final Project**

---

Congratulations! You have made it to the final stretch of your journey here at Kura Labs. 

This Final Project will be a culmination of all of your efforts throughout Kura and combine many of the DevOps technologies you have learned throughout the last few months.

---

Contents:

1- Requirements 

2- Extra Credit

3- Budget

4- Teams

5- Roles and Responsibilities

6- Deliverables

7- Progress Check-In Timeline

8- Team Dynamics Check-ins

---

## **Requirements**

Your project must contain all of the components below but the specific technologies you use and how you use them is up to your team to decide. The guidelines below are meant as possible technology choices but are not meant to be an exhaustive list. Discuss with your team what you would want to include from each category and start building!


### 1. Communication
 - Plan your project using a communication platform like Asana, Jira, Trello, Github Projects, etc.

### 2. Application
- A flask app is recommended (Python) but you can also choose an application that utilizes NodeJS or any other programming language.

### 3. Containerization
- Teams must use some element of using containers whether Docker or Kubernetes.

### 4. Infrastructure as Code (IaC)
- with Terraform or CloudFormation.

### 5. CI/CD Pipeline
- Jenkins, CircleCI, GitHub Actions, GitLab, CodePipeline etc.

### 6. Monitoring & Alerting
- Cloudwatch logging for the service, Jenkins to trigger some actionable message to email, Slack channel, SMS, etc., or any other technology that will give you insight as to what is going on behind the scenes (and warn you before things get out of hand)

### 7. Scalability
- Must include a way to scale your application in your production environment

### 8. Fault Tolerance
- Must include some form of fault tolerance in your production environment

### 9. Documentation
- Project Overview, choice of technology, how to operate the system.  There should be technical AND non-technical documentation as well as a slide deck prepared for presentation day

### 10. Systems Design
- Cleanly drawn network architecture diagram using draw.io, Lucidchart, or your preferred diagramming tool

---

## **Extra Credit**

### Serverless
- Use AWS Lambda in your project

### Provisioner
- Any provisioning tool may be included in any stage of your pipeline (Chef, Ansible, Puppet)

### Scripting
- Create Python or BASH scripts to automate processes

### ETL Pipeline
- All applications store data.  Create an ETL pipeline that will automatically extract, transform, and load data into another resource like an S3 bucket or Redshift warehouse.  

### Deployment Strategy
- This is an application/infrastructure deployment.  Implement a deployment strategy and demonstrate that you can execute a pipeline without interrupting service.  Errors? Rollbacks are cool too.

---

## Budget

Each Team MUST NOT exceed a total budget of $400 spent for testing, staging, production, monitoring, etc.

---

## **Teams**

Refer to the list below to see who you are going to be working with:

Team 1-  Belinda, Aubrey, Ethan, Jorge, Nehemiah

Team 2-  Dwayne, Khalil, Andrew, Nalani

Team 3-  Kevin G, Saraswati, Darrielle, Luis

Team 4-  Danielle, Annie, Jo, Sameen

Your team is expected to meet as needed and conduct standups, mimicking what your team would be doing in an agile DevOps role. Tasks need to be broken down into discrete, actionable items using your project board of choice and work must be assigned to each team member. 

---

## Roles/Responsibilities

### Project Manager
Responsible for checking in on each person's progress, managing the communication platform, setting deadlines, evaluating the project, and presenting. 

### Administrator
Responsible for overseeing IT accounts, permissions, and access to technology. 

### Lead Architect
Responsible for creating diagrams for the infrastructure, application, and pipeline.

### Team Director
Responsible for overseeing each role, budget, architecture design, application, infrastructure, and making final decisions.

There should be ONE person per group in each role and you must decide amongst yourselves who is assigned each role.  Please note: These responsibilities/descriptions are not all-inclusive of the tasks that need to be completed.  Those should be discussed with the team, assigned by the Project Manager, and organized in the project board.  After this has been decided, email the instructors with those details.  

---

## **Deliverables**

The Final Project is divided into discrete deliverables, each building on top of skills learned previously to scaffold students' learning over the entire course.

### Part 1: Agree on a Project & Plan it Out
Pitch us on potential ideas for an end-to-end DevOps project. Think of topics you’re passionate about, knowledge you’re familiar with, or problems relevant to to industries you’d like to work with.

- Requirements: Come up with a few project ideas, including a specific app, and potential technologies for each category, as well as some sample code. Remember, if you can’t find an app, you can’t start on your project.
- Deliverable: Choose a specific app to work on and submit a rough draft of systems design brainstorming (could be drawn out on paper at this stage)

DUE DATE: Wednesday, Nov 29th @ 5:00PM EST

### Part 2: Deploy the App & Start Iterating
Use your newfound skills to kickstart your project by deploying the app in one of the ways we learned in class. At this stage, it could be using a basic deployment method – just focus on getting it out there for the world to see.

Create a shared repo for the team. Ensure all members have access to push changes to the repo. How does a deployment work? What does the flow look like? What tools are involved? Finally, deploy the app. It doesn't have to be fancy yet... that will come later.

- Requirements: The app is deployed locally, and a rough draft of the physical design is due
- Deliverable: The app can be demoed, and a more detailed overview of how various technologies will work together (physical design) is due

DUE DATE: Wednesday, Nov 29th @ 5:00 PM EST

### Part 3: Create a Pipeline
Now that you have your app deployed and have an idea of how the various technologies can work together, let's add a CI/CD pipeline to automate the process of building, testing, and deploying. Use your favorite CI/CD tool (examples above) to integrate your processes into a single system.

- Requirements: The CI/CD pipeline is created using a tool of your choice and a draft of the pipeline design is due. The objective is that the previous deployment is now automated based on a certain trigger, for example, pushes to a GitHub repo trigger a build, test, deploy
- Deliverable: Code for a basic CI/CD pipeline is available and the CI/CD process can be demoed

DUE DATE: Wednesday, Dec 6th @ 5:00 PM EST

### Part 4: Let's Make it Fancy: Containers & IaC
Now that we have a basic pipeline going, let's take some time to add some bells and whistles. If the app is not Dockerized already, this is the time to build a Dockerfile and add it to the pipeline. Figure out what pieces of infrastructure you can rewrite as IaC. Create a runbook or describe the process for running the IaC.

- Requirements: The app is containerized and is added into the pipeline, Infrastructure as Code is written to replace some of the existing infrastructure that was deployed manually
- Deliverable: Code for containerizing the app is available (Dockerfile), Infrastructure as Code is added (Terraform or CloudFormation)

DUE DATE: Wednesday, Dec 6th @ 5:00 PM EST

### Part 5: Define Operational Procedures, Monitoring & Alerting
Let's take a look back on your project and document processes that are crucial to its operation. If you were a new team member who needed to operate the system, what would you need to know? Create a runbook for common commands and how to run the stack as if you knew nothing.

If an error is introduced into the system, how would an engineer know? Is there alerting on errors? How can you identify the bug and address it? Create a monitoring and alerting system and manually inject an error into the stack. Trace back the error and explain how an engineer would be alerted and solve the root cause of the issue.

- Requirements: Create documentation for operating the system, add meaningful logging messages, create a system for monitoring and alerting
- Deliverable: "Runbook" documentation available, demo of monitoring and alerting system

DUE DATE: Wednesday, Dec 13th

### Part 6: Dry Run of Your Project Presentation
Just like the purpose of the mock interviews, we want to practice before the actual presentation on Dec 16.  With your team, create a 30-minute presentation, based on a slide deck, that showcases the most important aspects of your project. Start at a high level and give an overview of the system. Discuss why you chose each piece of technology. Then dive in and show a demo of the system in operation. Explain the steps of the CI/CD pipeline and show how the app is deployed. Show what happens if an error occurs. Give an overview of the infrastructure. Explain your thought process and how the project evolved.

- Requirements: Convey your goals, limits/assumptions, methods and their justification, findings, and conclusions. Define technical terms. Include graphics and visualizations.
- Deliverable: Slide deck containing presentation as well as a demo showcasing the highlights of the stack in operation

DUE DATE: Wednesday, December 13, 2023

### Part 7: Presentation Day!

It’s show time!  The work is done and you’ve practiced your lines.  This day is for you to showcase what you’ve accomplished in the past 6 months to the Kura Team, your peers, yourselves… and a panel of judges alongside friends and family who are invited to join.  Each group will present their projects which will be reviewed and scored by the judges.  Be prepared to answer any questions that they might have of your deployment.  After each group has gone, the judges will discuss and choose a team whom they think had the best deployment.  There will be a cash prize for the winning team!

---

## Progress Check-in Timeline

### Proposal and System Design
Wednesday, Nov 29 - Thursday, Nov 30 

Teams will have to show: 
- Project boards
- System Design
- Application running locally

### CICD, Containers, IaC
Wednesday, Dec 6th - Thursday, Dec 7

Teams will have to show:
- CICD Pipeline
- Images of the application created
- Containers running application
- IaC files that create (staging or production) infrastructure

### Monitoring, Documentation, Optimization
Wednesday, Dec 13 - Thursday, Dec 14

Teams will have to show:
- Monitoring/alerting implemented
- Plan for being able to scale the application
- Plan for fault tolerance
- Technical and Non-Technical Documentation
- Live diagram of the infrastructure/CICD pipeline

### Final Project Presentation Dry Run 
Wednesday, Dec 13th

Teams will have to show:
- 30-minute presentation based on a slide deck and a demo of the application being deployed into a production environment.

---

## Team Dynamic Check-Ins
Every Friday a Google form will be given out to the members of each group.  The purpose of the form is to survey how the group dynamics are and if intervention by Kura staff is necessary.

If there are any issues do not wait for this check-in form.  Communicate major issues with the team so that they can be resolved promptly.

Otherwise, Good luck!
