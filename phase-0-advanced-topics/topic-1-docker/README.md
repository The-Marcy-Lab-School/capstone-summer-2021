# Intro to Docker

## Resources
* **Documentation**: [Official Docker Docs](https://docs.docker.com/get-started/)
* [**Docker Notes and Code-Along**](https://github.com/The-Marcy-Lab-School/docker-basics-1-container) from [Mike Cronin](https://github.com/MostlyFocusedMike) 

## Seminar Questions
* What problem does Docker seek to solve?
* How does Docker solve this problem? 
* What is Docker's _architecure_?
* Applications running in Docker are said to be running in a _container_. How does Docker handle applications that are comprised of multiple clients/servers that each need their own container? (i.e. a container for the application server, another for the database)
* Multiple redundant instances of an application may be deployed on multiple distributed servers for scalability purposes. Sometimes, instances have to be spun up and wound down in real-time in responses to variable traffic to the application. How do we handle the orchestration multiple containers and their needs to scale?

## Assignments
### Dockerize Your Demo Day Project
|     |     |
| --- | --- |
| **Task** | Fork your own copy of your group's Demo Day Project. Get it running on containers on your local machine. |
| **Purpose** | To gain fluency working with Docker commands. |
| **Due Date** | Tuesday, June 22 @ 3 |
| **Submission Guidelines** | Submit GitHub repo link to Canvas |

### Deploy Dockerized Project to AWS
|     |     |
| --- | --- |
| **Task** | Now that your app is running in a container, you are to redeploy it. <br />**Note:** If you are a Sytems Design Capstone Fellow, this time, you are to deploy it to [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/). This is AWS' managed deployment solution. It is a competitor to Heroku for AWS.|
| **Purpose** | To gain experience deploying Docker containers to production. |
| **Due Date** | Wednesday, June 23 @ 3 |
| **Submission Guidelines** | Submit deployed link to Canvas |

