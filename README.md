# Job Hunter [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Are%20you%20looking%20for%20internship,%20first%20job%20and%20you%20want%20to%20apply%20for%20100%20offers%20everey%20day%20.%20check%20this%20website%20to%20accelerate%20your%20job%20hunting%20&url=www.job-hunter.io&via=Jobhunter&hashtag=Job_Hunter,Intelligent_Job_finding_accelerator,AI_web_service)

We can define this project as a job applying accelerator tool that helps students and job seekers in their journey of job hunting, the idea was inspired when we started our massive search for a Data science internship/traineeship this year.

The mean goal of this project is to help student and job seeker to optimize the time spent in their job applications, The project focuses on the idea of automatic generation of a job application, getting as much information about the companies, job, skills, Technologies, frameworks needed for the target position.

The app creates, edit, customize, and generate a cover letter and a resume adapted to the job description, the user can give the link of a job offer (or LinkedIn search link) and his information as input and then the app gives as output the Resume and the cover letter correspond to this offer. 

### The idea of applying Deep learning in this project is :
            
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
- Use the 'user data' to Suggest new skills required for the job that he is interested in (Favorite) in.
- Use the data to make predictions of jobs that he can apply for.
