# Job Hunter

We can define this project as a job applying accelerator tool that helps student and job seeker in their journey of job hunting, the idea was inspired when we started our massive search for a Data science internship/traineeship this year.

The mean goal of this project is to help student and job seeker to optimize the time spent in their job applications, The project focus on the  idea of automatic generation of job application, getting as much information about the campanies, job, skills, Technologies, frameworks needed for target postion.

The app create , edit, costumize, and generate a cover letter and a resume adabted to the job description, the user can give the link of job offre (or linkedin search link) and his information as input and then the app gives as output the Resume and the cover letter correspond to this offer. 

### The idea of applying Deep learning in this project is :
            
- Achieving the goal of understanding the job description, 
            
- Extract the key words to create the list of required skills, the job sector, type, Level of education...etc. 
            
- mach the extracted information with the skills of the job seeker (user).
            
- Generate text using OpenAI GP-2 for our fist prototype.

Our prototype skrap the data from Linkedin and store it in Google Sheet immediately, from the data in the G sheet (the job data table we create) we send the information like the name of company, the date of publication, the Job ID, Adress, of to Two Google Docs which are the cover letter and Resume that will be generated. the tags is located in the G DOC Templates will much the information set from the G sheet.


### Current Tasks in our TODO list: 
-  Use and Review some data Skraping API that can skrap data from linkedIn.
-  Build our own linkedin data Skrapper API.
-  Deploy the first prototype as Web App.
-  Extract information from the users uploaded 'Resume'.         
-  Create graph data of the extracted data in Neo4j Graph database.


### Next Challenges 
- Use the 'user data' to Suggest new skills required for the job that he is interested (Favorite) in.
- Use the data to make prediction of jobs that he can apply for.

