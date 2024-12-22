Grazioso Salvare Dashboard - README 

Project Description 

This project involves the development of a functional web application dashboard for Grazioso Salvare, the rescue-animal training company. The dashboard enables the client to interact with and visualize data from the Austin Animal Center Outcomes dataset stored in a MongoDB database. Using the dashboard, users can filter rescue dogs based on rescue type (e.g., Water Rescue, Mountain or Wilderness Rescue, Disaster or Individual Tracking), view distribution charts, and see geolocation data for selected animals. The application ensures that Grazioso Salvare can efficiently identify potential rescue animals. 

Tools and Technologies Used 

The dashboard was developed using Python, with the Dash framework providing the view and controller structure. Dash offers flexibility in building interactive web applications with integrated Plotly components for data visualization. MongoDB was used as the database system due to its NoSQL structure, which supports flexible schema designs and efficient querying for large datasets. Dash Leaflet was implemented to create the geolocation map, allowing for dynamic mapping functionality. Additionally, Pandas was used for data manipulation, ensuring seamless interaction between the database and the dashboard components. 

MongoDB as the Model Component 

MongoDB serves as the database backend due to its compatibility with Python and its ability to store and query JSON-like documents. This structure allows easy integration with the CRUD Python module, enabling efficient data retrieval and updates. The database's flexibility ensures that Grazioso Salvare can adapt its schema as data needs evolve. MongoDB's robust query language supports complex filtering, which is critical for identifying suitable rescue animals based on specific criteria. 

Dash Framework 

The Dash framework was chosen for its simplicity and versatility in creating interactive dashboards. Dash's ability to integrate Plotly charts, HTML components, and callback functions provides a seamless experience for both developers and users. It allows for real-time updates to the dashboard based on user inputs, such as dropdown selections for rescue type filters. This ensures an intuitive interface for Grazioso Salvare's users, reducing training time and user errors. 

Steps to Complete the Project 

Database Setup: A MongoDB database was created with the Austin Animal Center Outcomes dataset. Data import and testing ensured the database was correctly configured. 

CRUD Python Module: A Python module was developed to enable Create, Read, Update, and Delete operations with the MongoDB database. This module formed the backbone of the data interaction. 

Dashboard Development: The dashboard layout was designed using Dash components, with sections for filters, data tables, charts, and geolocation maps. 

Integration: The CRUD Python module was integrated with Dash callbacks to ensure dynamic updates based on user inputs. 

Testing and Debugging: Each component was tested for functionality, and issues were resolved, including missing map data and chart updates. 

Documentation and Deployment: Screenshots and a screencast were created to demonstrate the dashboard's functionality. The project was deployed in a local environment. 

Challenges and Solutions 

One challenge was ensuring the geolocation map dynamically updated based on the selected row in the data table. This was resolved by implementing error handling and default values for missing data. Another challenge involved integrating the Dash callbacks for real-time updates, which required careful debugging to ensure the correct flow of data between components. Additionally, aligning the layout for charts and maps to appear side-by-side required CSS styling adjustments to achieve the desired visual result. 

How to Reproduce the Project 

Clone the repository containing the project files. 

Install the required Python libraries, including Dash, Dash Leaflet, Pandas, and Plotly. 

Set up a MongoDB database and import the Austin Animal Center Outcomes dataset. 

Update the CRUD Python module with your MongoDB credentials. 

Run the dashboard application in a Jupyter Notebook or Python environment. 

Interact with the dashboard to filter rescue types, view breed distribution charts, and explore geolocation data. 

 

Screenshots and Screencast 

Screenshots and a screencast demonstrating the dashboard's functionality, including filtering options and geolocation mapping, are included in the project repository. These provide a screenshots to the completed application.  

 ![Dash app](https://github.com/user-attachments/assets/03b8c90e-754f-4037-8d39-01904664c9d2)


^^^ Dashboard Code executing properly without any errors^^^  
![Logo and filter](https://github.com/user-attachments/assets/fa42a2fd-c702-4102-8a47-c0287e4772cf)

 

^^^Logo and Unique Identifier ^^^  

 ![Rescue Type All](https://github.com/user-attachments/assets/1a2f18c5-279a-463b-befa-66d2208b85a4)


^^^ Rescue Filter set to All: Pi graph showing percentage of all breeds in entire database and map location of first animal in database^^  

 ![Rescue Type Water](https://github.com/user-attachments/assets/05d33455-96e1-4bb8-9569-6619c65ef6ec)


^^^ Rescue Filter set to Water Rescue: Pi graph showing which breeds make up the Water Rescue database and map location of first animal in database^^   
![Rescue Type Mountain andWilderness](https://github.com/user-attachments/assets/9020d051-a9b4-4534-9cc2-3bc057615019)

 

^^^ Rescue Filter set to Mountain and Wilderness Rescue: Pi graph showing which breeds make up the Mountain and Wilderness Rescue database and map location of first animal in database^^  
![Rescue Type Disaster and Individual Tracking](https://github.com/user-attachments/assets/d33ae7cd-6b8c-4775-b9c5-fe99dd168b6c)

 

^^^ Rescue Filter set to Rescue Type Disaster/Individual Tracking Rescue: Pi graph showing which breeds make up the Rescue Type Disaster/Individual Tracking Rescue database and map location of first animal in database^^ 

 
