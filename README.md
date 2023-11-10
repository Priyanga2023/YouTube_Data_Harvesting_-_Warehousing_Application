# YouTube Data Harvesting and Warehousing using SQL, MongoDB, and Streamlit

## Introduction
  The YouTube Data Harvesting and Warehousing project is dedicated to creating an intuitive Streamlit application that harnesses the Google API's power to extract valuable information from YouTube channels. This extracted data is then stored in a MongoDB database and seamlessly migrated to a MySQL data warehouse, all within the same user-friendly Streamlit application.

## Table of Contents
1. Key Technologies and Skills
2. Installation
3. Usage
4. Features
5. Data Retrieval from the YouTube API
6. Storing Data in MongoDB
7. Data Migration to a MySQL Data Warehouse
8. Contribution Guidelines
9. Contact Information

## Key Technologies and Skills
- Python Scripting
- Data Collection
- API Integration
- Streamlit
- Data Management using MongoDB and MySQL

## Usage
To use this project, follow these steps:

1. Clone the repository:
   git clone https://github.com/your-username/your-repo-name.git
2.Install the required packages:
  pip install google-api-python-client
  pip install pymongo
  pip install mysql-connector-python
  pip install streamlit
3.Run the Streamlit app:
  streamlit run app.py
4.Open the app in your web browser. You can access it by opening a new tab and entering the following URL: http://localhost:8501

## Features
  Retrieve data from the YouTube API, including channel information, playlists, videos, and comments.
  Store the collected data in a MongoDB database.
  Migrate the data to a MySQL data warehouse.
  Analyze and visualize data using Streamlit and other Python libraries.
  Perform queries on the MySQL data warehouse.
  Gain insights into channel metrics, video metrics, and top 5 data of the respective channel.
  Answer default 10 queries to provide immediate insights into the data.
  
## Data Retrieval from the YouTube API
  Our project utilizes the Google API to collect comprehensive data from YouTube channels. The data encompasses information on channels, playlists, videos, and comments. By interfacing with the Google API, we gather the data and consolidate it into a structured format for further processing.

## Storing Data in MongoDB
  The retrieved data is securely stored in a MongoDB database, with proper user authorization. If the data already exists in the database, it can be updated with user consent. This storage mechanism ensures efficient data management and preservation, enabling seamless handling of the collected data.

## Data Migration to a MySQL Data Warehouse
  Our application empowers users to transfer data from MongoDB to a MySQL data warehouse. Users can select the channel's data they want to migrate. To ensure compatibility with a structured format, the data is refined using the robust pandas library. After data cleansing, it is organized into distinct tables, including channels, playlists, videos, and comments, using SQL queries.

## Contribution Guidelines
  Contributions to this project are highly encouraged. If you come across any challenges or have ideas for enhancements, we invite you to submit a pull request. Your input is valuable to us, and we appreciate your contributions.

## Contact Information
  Email: sec19ee048@sairamtap.edu.in
  LinkedIn: www.linkedin.com/in/priyanga-a-42a869282

  If you have any more questions or need further information, please don't hesitate to get in touch. We're here to help and answer any inquiries you may have.


