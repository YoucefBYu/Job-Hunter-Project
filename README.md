# Job Hunter [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Are%20you%20looking%20for%20internship,%20first%20job%20and%20you%20want%20to%20apply%20for%20100%20offers%20every%20day.%20check%20out%20this%20web%20service%20to%20accelerate%20your%20job%20hunting%20&url=www.job-hunter.io&via=Jobhunter&hashtags=Job_Hunter,Intelligent_Job_finding_accelerator,AI_web_service)

In order to help students and job seekers in their journey of job hunting, from our experience we got the idea to start the project after the successful result of the first prototype that we build for personal use (massive job hunting).  
The mean goal of this project is to help student and job seeker to optimize the time spent in their job applications, The project focuses on the idea of automatic generation of a job application, getting as much information about the companies, job, skills, Technologies, frameworks needed for the target position.

The app extract the data of given job (link of Linkedin or any job search platform) and use it to build a short insight that focus on the important key words, required Skills, level of education and  information about the company. 

The extracted job data and the user data (Resume, Profile) used as input of the processing box (the sniper agency), here we meet Intelligente agent that use many tools and technique to produce results  for example : 
- The philosopher : NLP text generator that produces a perfect motivation letter based on the input and some other predefined data. 
- The advisor : it help the user to know the job skill-set that he needs to master before applying to the job he is interested in, even we suggest online courses based on users rating, in general we use prediction models in this part.


### The ideas of applying NLP Deep learning in this project are :
            
- Achieving the goal of understanding the job description, 
            
- Extract the keywords to create the list of required skills, the job sector, type, Level of education...etc. 
            
- match the extracted information with the skills of the job seeker (user).
            
- Generate text using OpenAI GP-2 for our fist prototype.

Our prototype scrapes the data from Linkedin and stores it in Google Sheet immediately, from the data in the G sheet (the job data table we create) we send the information like the name of the company, the date of publication, the Job ID, Adress, of to Two Google Docs which are the cover letter and 'Resume' that will be generated. the tags are located in the G DOC Templates will much the information set from the G sheet.

### Current Tasks in our TODO list: 
-  Use and Review some data Scraping API that can scrape data from Linkedin.
-  Build our own Linkedin data Scrapper API.
-  Deploy the prototype as a Web App.
-  Extract information from the users uploaded 'Resume'.         
-  Create graph data of the extracted data in the Neo4j Graph Database.


### Next Challenges 
- Use the 'user data' to Suggest new skills required for the job that he is interested in (Favorite).
- Use the data to make predictions of jobs that he can apply for.


## Note :
in this repository we share the datasets and processing code only in order to:
- help the community to get new NLP craftred dataset.
- accelerate the the work on the data processing and model building.
