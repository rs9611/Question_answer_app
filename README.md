# Question_answer_app
 
Note: This application has been made using HTML, Bootstrap and CSS for front end developement and Flask (Python framework) and SQLIte (Database) for back-end developement. 

The aim of this application is to create a platform where users ask questions and experts answer those questions. Some of these questions are either open-ended which means any expert can answer them while other questions and strictly directed to a specific expert. Experts can view the questions directed to them on the "Answer questions" (this tab si only visible to admins) tab of the webpage. As experts answer questions, those questions and their respective answers are then displayed on the homepage for the public to view. 

Key features of this appilication:
-Users can register as well as login. Upon registeration, new user login details are stored in the database. 
-A session is created for each logged-in user (where an expert or a regular user). 
-Users can ask questions through the "Ask question" tab. Here, users can type in their question and then pick (through a drop-down list) which expert they want to ask this question to . 
-Each expert can view a "Answer questiosn" tab where they can see the questions directed to them. Each question is accompained by the name of the user who asked the question. Once the expert answers the question, it appears on the homepage along with the answer they typed in. 
-The home page contains all the questions and the answers. For each question, the name of the user who asked the question is displayed and for each answer, the name of the expert who answered the question is displayed. 
-Admins have special access. There is a page called 'User Setup" which only admins can view. On this page, admins can choose which users are experts. So basically, a user intially registers as a regular user and then an admin can make that user an expert if the admin wishes. This action can be reversed as well. In each case, the database is updated and which pages a user and experts can see are also updated.



