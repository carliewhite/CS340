# CS340
SNHU Client/Server Development 22EW4

## Functionality: 

Grazioso Salvare is a business that looks for dogs that would be good for search and rescue training. They have a list of specific types of dogs that are good for certain conditions, as well and preferred sex. These specifications help them find the perfect dogs to train for search and rescue. Grazioso Salvare is looking for a software application that can work with their existing data in order to categorize and identify dogs that would be a good fit. They also wish for the data to be presented in an interactive dashboard that lets them filter and query in a user-friendly way based on their specifications. 

Some key pieces that Grazioso Salvare would like to include are filter options (buttons or dropdowns) based on rescue type breeds, a data table that dynamically updates based on the given filter, and a geolocation chart with another chart that dynamically responds to filtering options. 

## Tools used to complete the project:

In order to complete this project, it was necessary to use MongoDB, dash plotly, and JupyterNotebook. MongoDB was used in order to store the data provided by Grazioso Salvare and the app was developed using Python and the dash library in JupyterNotebook.

## Design

In order to write programs that are maintainable, readable, and adaptable, it is crucial to insert comments when necesarry in order to outline ewaht each proccess does. In this project, it was important write comments for each different function in both the crud module and the application file because each piece was respsonsible for something specific and without comments, it is very easy to get lost in the code. The next best thing is naming. It is important to name things that match up with what their doing so that if the comments are a little unclear to the reader, they can at least use the name of the object to understand what the piece of code is for. Many times when I develope, I write the pseudocode as commented out lines. This then helps me and reminds me to add comments and stay on track with what that piece of code is for. 

## Purpose

Generally speaking, the job of a computer scientist is to make peoples lives easier. This can be done a multitude of different ways, but for this project we were asked to develop a dashboard for a database so that the end user can easily query the data as well as visualize it. This helps to cut down on a lot of extra time for the customer and that is often the goal of a computer scientist. 

## Process of Completing the project:

1. Load the data into a new database
	Using mongoimport, I was able to successfully load the data given to us by Grazioso 	Salvare into a new database called 'AAC' and into a collection called 'animals'. I took the 	time to make sure that queries and updates were possible and then I moved on. 
2. Create users in the database
	I then had to create an admin user for all the databases and then I was able to create a user 	called 'aacuser'. This user has readWrite privileges and it is the user that we will use to 	log into the database on the application.
3. Create a CRUD file
	In order to manipulate and use data in the database using python, it was necessary to 		create a CRUD class. This class will be used to access data through the application. 
4. Create a JupyterNotebook file
	The app was developed using Jupyter Notebook in order to get live results while 	developing. This helped to visualize the changes being made. The first thing I did was 	make a connection to the CRUD class in order to access the database. Then, I created a 	data so that I could view the data. In the data table, I made it possible for the user to 	query each value to help find the most optimal dog
  

