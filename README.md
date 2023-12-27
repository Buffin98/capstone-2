# capstone-2
# Phonepe_pulse Data Visualization and Exploration

### Data Visualization and Exploration : A User-Friendly Tool Using Streamlit and Plotly

# Introduction:
  PhonePe has become a leader among digital payment platforms, serving millions of users for their daily transactions. Known for its easy-to-use design, fast and secure payment processing, and creative features, PhonePe has gained praise and recognition in the industry. The PhonePe Pulse Data Visualization and Exploration project aims to gather valuable information from PhonePe's GitHub repository, process the data, and present it using an interactive dashboard that's visually appealing. This is accomplished using Python, Streamlit, and Plotly.


# Libraries/Modules needed for the project!

 1. [Plotly](https://plotly.com/python/) - (To plot and visualize the data)
 2. [Pandas](https://pandas.pydata.org/docs/) - (To Create a DataFrame with the scraped data)
 3. mysql.connector - (To store and retrieve the data)
 4. [Streamlit](https://docs.streamlit.io/library/api-reference) - (To Create Graphical user Interface)
 5. json - (To load the json files)
 6. git.repo.base - (To clone the GitHub repository)
 
 # Workflow
 
 **Importing the Libraries:**
 
   Importing the libraries. As I have already mentioned above the list of libraries/modules needed for the project. First we have to import all those libraries. If the libraries are not installed already use the below piece of code to install.

        !pip install ["Name of the library"]
    
   If the libraries are already installed then we have to import those into our script by mentioning the below codes.

        import pandas as pd
        import mysql.connector 
        import streamlit as st
        import plotly.express as px
        import os
        import json
        from streamlit_option_menu import option_menu
        from PIL import Image
        from git.repo.base import Repo
        

- **Data Collection:** Effortlessly clone PhonePe Pulse data from the GitHub repository to your local directory for seamless access.

- **Data Overview:** Dive into comprehensive insights about the collected data, including detailed breakdowns by states, years, quarters, transaction types, user devices, and more.

- **Migrating Data to SQL Database:** Streamline your data by converting PhonePe Pulse data from JSON format to a structured DataFrame and efficiently store it in a MySQL Database.

- **Streamlit:** The Streamlit app provides an intuitive interface to interact with the charts and explore the data visually. Users can customize the visualizations, filter data, and zoom in or out to focus on specific aspects of the analysis.

- **Plotly:** Utilizing the power of Plotly, users can create various types of charts, including line charts, bar charts, scatter plots, pie charts, and more. These visualizations enhance the understanding of the data and make it easier to identify patterns, trends, and correlations.

- **Data Insights and Exploration:** Embark on an analytical journey with interactive Plotly charts and maps, offering insights across states, years, quarters, districts, transaction types, and user brands.

- **Live Geo Visualization Dashboard:** Create a live geo visualization dashboard using Streamlit and Plotly for interactive data exploration, allowing you to dynamically interact with the data on maps.

- **Top Performers Highlight:** Easily spot top 10 states, districts, and pincodes through user-friendly visualizations.

- **User-Focused Dashboard:** Navigate through an intuitive Streamlit dashboard designed for user convenience, making exploration a breeze.

- **Data-Driven Decision Making:** Empower your decision-making process by leveraging valuable trends, patterns, and statistics derived from the PhonePe Pulse data.

  **Contact**

📧 Email: buffinmuff98@gmail.com 

