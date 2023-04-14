# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)




### AlgoBulls Frontend Developer Coding Assignment
# November 2022

# Project: Design a simple To-Do List App using React

# Description:

You need to design a web-based to-do list application, as per the given requirements:

1.	Tasks should be displayed in a Tabular format, using the Ant Pro table component.
2.	The table should have the following columns:
a.	Timestamp created: Timestamp at which a task was created.
Should be auto set when creating a new entry. A user should not be able to edit this.
b.	Title: Title of the task to be done.
i.	A user can set this while creating a new entry. A user can also change this updating existing entry.
ii.	Max length: 100 characters.
iii.	Mandatory field
c.	Description: Description of the task to be done.
i.	A user can add details about this task.
ii.	Max length: 1000 characters
iii.	Mandatory field
d.	Due Date: Expected due date to finish the task
i.	A user can set this while creating a new entry. A user can also change this updating existing entry.
ii.	Optional field
e.	Tag: One or more tags which user can add to the entry
i.	A user can set this while creating a new entry. A user can also change this updating existing entry. Multiple tags can be added to the same entry
ii.	Optional field
iii.	Multiple tags with the same value should be saved only once.
f.	Status: Shows status of a task
i.	Should be one of these values.
1.	OPEN (Default value)
2.	WORKING
3.	DONE
4.	OVERDUE
ii.	Mandatory field
3.	The table should support pagination.
4.	User should be able to perform the following operations:
a.	ADD a new to-do entry
 
b.	MODIFY an existing to-do entry
c.	DELETE an existing to-do entry
d.	SORT the table using columns a., b., c. and d. given above in both ascending and descending formats
e.	FILTER the table using e. and f. Columns.
5.	Provide a search bar on the top where a user can perform a case-insensitive search for any task based on the data in any of the above-mentioned columns.
6.	Make use of mock APIs to ensure that the app is fully functional. [No database or backend coding required.]


# Technology to be used for creating this application:

Frontend:
1.	Ant Design Pro v4+ https://github.com/ant-design/ant-design
https://github.com/ant-design/ant-design-pro
Ant Pro Table: https://github.com/ant-design/pro-table
2.	[BONUS] DVA


# Note:
1.	You can assume things that are not defined with a reasonable value. For example, we have not defined the pagination size. You can assume it as 15 or 20 or any other number which is generally acceptable.
2.	Add validation checks anywhere there is a possibility of an obvious violation of general logic. Example: ‘Due Date’ field value cannot be before ‘Timestamp created’ field value
3.	Implement necessary design principles wherever possible. For example, when a user tries to DELETE an existing to-do entry, it is good to ask first for a confirmation from the user before firing the DELETE api. The design should look complete.
4.	Explore Ant Design sufficiently so you can use the available features from the existing widgets smartly. This will be preferred over creating completely new components. Feel free to take design inspiration from https://app.algobulls.com.


# Objective:
1. Please come up with a sleek frontend that can accommodate all the requirements.


# Duration:
The ideal time is 3 days. If you need extra time, please request the same with appropriate reasoning.



# How to submit:
 
1.	Deploy your application on any cloud service provider like AWS, GCP, Azure, etc. and send us a link to your working application.
2.	Please upload your code on a private GitHub repo and share it with the following GitHub user-ids - algobulls-dev, hruturaj-nikam-algobulls
3.	Make sure your code is cleaned up as per standards, before you do the final submission. It is ok to keep pushing any number of intermediate code commits.
4.	Add sufficient comments for complex logic, before you do the final submission.
5.	Include a README that includes basic documentation on how to run the code.
6.	Once done, please send a mail to both developers@algobulls.com & hruturaj.nikam@algobulls.com, mentioning your name and GitHub ID, requesting a review. Attach this coding assignment pdf to the mail as well.
7.	If selected for an interview, we may request you to set up a screen-sharing session for discussion purposes.


# Asking for clarification/hints:
Please send an email to developers@algobulls.com & hruturaj.nikam@algobulls.com with your query and we will get back to you.

### Project Solution Details:

Name: Karthik S
Email ID: karthik04siva@gmail.com
LinkedIn: LinkedIn
Github: Karthik-02 (Karthik S) (github.com)
Project Github Link : Karthik-02/todoantp: A modern Todo list application build with reactJs and antdesign library. (github.com)
Working Project Link: React App (todoantp.vercel.app)


# Screenshots:

![image](https://user-images.githubusercontent.com/81423983/232110354-cfc11e68-5222-4804-8042-4265b69d5ca4.png)

Adding Task:

 
![image](https://user-images.githubusercontent.com/81423983/232110578-639e1587-a8ca-447f-8bc7-039067446fca.png)
![image](https://user-images.githubusercontent.com/81423983/232110798-d287876f-7832-4c82-a2da-39432bdfdda3.png)
![image](https://user-images.githubusercontent.com/81423983/232110905-bdc772b1-86f1-410d-9e84-7898c9bea3b5.png)


Editing Task:
![image](https://user-images.githubusercontent.com/81423983/232110945-8916928e-1aa1-45c9-a136-a795a0050524.png)

Deleting Task:
![image](https://user-images.githubusercontent.com/81423983/232110973-a831add6-cc03-4df6-ba86-1071ef46f70c.png)


Pagination:
![image](https://user-images.githubusercontent.com/81423983/232111041-64a349d1-92b7-4bcb-9545-b96e4b68657b.png)
![image](https://user-images.githubusercontent.com/81423983/232111139-c282d3da-5c1a-4599-b12f-cbe040e56014.png)


Sort Task (Ascending/Descending):

Sorting Timestamp (Descending):
 ![image](https://user-images.githubusercontent.com/81423983/232111171-1f21c7d9-1a84-472c-9354-f104c086057c.png)
![image](https://user-images.githubusercontent.com/81423983/232111199-2218c752-1341-46ef-aea5-7ca94b4b298e.png)


Sorting Title (Descending):
 ![image](https://user-images.githubusercontent.com/81423983/232111251-bc12614b-2214-4cbc-911e-863647386eea.png)
![image](https://user-images.githubusercontent.com/81423983/232111291-9786ea07-2bde-4ee3-9305-65b9ace93632.png)

Searching Title and Tag:
![image](https://user-images.githubusercontent.com/81423983/232111347-943b6551-4dbc-46cb-82f8-974ff8cbe465.png)
![image](https://user-images.githubusercontent.com/81423983/232111379-c5ab8866-afce-4582-af5b-0f69868cd566.png)

 

Filtering Status:
 ![image](https://user-images.githubusercontent.com/81423983/232111471-b8b984a2-8cb4-4604-bb3d-76cdceba57ec.png)
![image](https://user-images.githubusercontent.com/81423983/232111496-f5ab7c7b-ad6a-4ceb-bc56-2f9cfa0fd3ba.png)


 



