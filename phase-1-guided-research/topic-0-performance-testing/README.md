# Phase 1 - Topic 0: Performance Testing

## Purpose
If you are a frontend engineer, you want to ensure that your UI is fast, accessible, responsive, conforms to best practices, and is SEO optimized. Likewise, as a backend engineer, you want to ensure that your site has fast response times, high "uptime", and low failure rates. Most importantly, as aspiring engineers of scalable software, you want all of this to be true when your application is serving many hundreds of thousands (or millions 😳) of requests per seconds.

The purpose of this section is for you to get an understanding of how your application is performing now by leveraging performance testing tools. You will run tests on your application, carefully documenting the testing parameters and the outcomes of the test. Over the next several weeks, you will be exploring tools and strategies that are designed to make your software more _performant_. When appropriate, you will implement these tools into existing applications. Then, you will be able to see how these tools impacted the performance of your application.

# Frontend Performance Testing  

## Resources
* **Documentation**: [Google Lighthouse Docs](https://developers.google.com/web/tools/lighthouse)

## Questions to Get You Started
> _**Reminder:** These have now changed from "Seminar Questions" to "Questions to Get You Started". I can no longer give you the definiitive guide to the key concepts for these given topics. Consider these as a very important starting point and let your curiosity carry you further. 🙂_ 
* What is Google Lighthouse?
* How do we use it to test our applications?
* What does Lighthouse measure?
* How can we use Lighthouse to build better webpages? To become better developers?

## Assignments
### Conduct Lighthouse Performance Tests of Your React App
|     |     |
| --- | --- |
| **Task** | Choose one app that you will run a Lighthouse test on the application. If there are multiple pages, be sure to run test on each. |
| **Purpose** |  To gain familiarity with this ubiquitous frontend testing tool. |
| **Due Date** | Thursday, July 1 at 8AM |
| **Submission Guidelines** | N/A |

### Complete Lighthouse Test Reflections
|     |     |
| --- | --- |
| **Task** | Once you have run these tests, do the following:<ol><li>Export your test data so that you have it in raw form</li><li>**Write a test summary** In a short report (about a page), share your thoughts on the following: <ul><li>Where did your application perform well? (your best scores)</li><li>What were your lowest scores and why? (Give specific examples based on report)</li><li>What are areas that you are interested in exploring in order to improve the performance of your app?</li></ul></li></ol> |
| **Purpose** | You will be improving applications over time. We want to have a well-documented starting point to refer back to so that we can see improvements over time (and add them to our resumes 😉)|
| **Due Date** | Thursday, July 1 at 8AM |
| **Submission Guidelines** | You can write this up in your format of choice (Google Doc, txt file, Markdown file, etc). Submit on Canvas. |


# Backend Performance Testing  

## Resources
* **Article**: [What is load testing?](https://stackify.com/what-is-load-testing/)
* **Article:** [How to Check, Measure, and Improve Server and Application Response Time With Monitoring Tools](https://www.dnsstuff.com/response-time-monitoring)
* **Article:** [What is the average server response time?](https://www.littledata.io/average/server-response-time)
* **Documentation**: [Locust Docs](https://locust.io/)
* **Documentation**: [Using Locust on AWS Elastic Beanstalk for Distributed Load Generation and Testing](https://aws.amazon.com/blogs/devops/using-locust-on-aws-elastic-beanstalk-for-distributed-load-generation-and-testing/)

## Questions to Get You Started
> _**Reminder:** These have now changed from "Seminar Questions" to "Questions to Get You Started". I can no longer give you the definiitive guide to the key concepts for these given topics. Consider these as a very important starting point and let your curiosity carry you further. 🙂_ 
* What are the metrics we could use to measure the performance of our applications?
* What is _load testing_?
* What type of response times would we expect from performant web applications?
* How can we use Locust to stress test our applications? 

## Assignments
### Conduct Stress Tests of Your App
|     |     |
| --- | --- |
| **Task** | Choose one app that you will run a thorough stress test of the application, using Locust to test multiple key API endpoints.|
| **Purpose** |  To get an initial guauge of how your application performs under heavy load. |
| **Due Date** | Thursday, July 1 at 8AM |
| **Submission Guidelines** | N/A |

### Complete Stress Test Reflections
|     |     |
| --- | --- |
| **Task** | Once you have run these tests, do the following:<ol><li>Export your test data as CSV and save it to ensure that you can always go back and view the data in raw form</li><li>**Write a test summary** In a short report (about a page), share your thoughts on the following: <ul><li>Where did your application perform well? (your best performance metrics, API endpoints, etc.)</li><li>Where did you application fail? (i.e. Which endpoints experienced unexpected exceptions and high fail rates?)</li><li>What are areas that you are interested in exploring in order to improve the performance of your app?</li></ul></li></ol> |
| **Purpose** | You will be improving this application over time. We want to have a well-documented starting point to refer back to so that we can see improvements over time (and add them to our resumes 😉)|
| **Due Date** | Thursday, July 1 at 8AM |
| **Submission Guidelines** | You can write this up in your format of choice (Google Doc, txt file, Markdown file, etc). Submit on Canvas. |
