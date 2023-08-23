PhonePe Pulse Data Visualization 2018-2022:
            ❗️This project is a data visualization tool for PhonePe's pulse data from 2018 to 2022. It allows users to explore and analyze various metrics related to PhonePe's business performance.

Data extraction:
            ❗️ Clone the Github using scripting to fetch the data from the Phonepe pulse Github repository and store it in a suitable format such as JSON. Use the below syntax to clone the phonepe github repository into your local drive. from git.repo.base import Repo Repo.clone_from("GitHub Clone URL","Path to get the cloded files")

Data retrieval:
            ❗️Finally if needed Using the "mysql-connector-python" library to connect to the MySQL database and fetch the data into a Pandas dataframe.

EXPLORE:
            ❗️Run python Phonepe_Pulse.py to start the application(streamlit run Phonepe_Pulse.py). Access the application in your web browser by navigating to http://localhost:8501 Select the desired date range and metrics to visualize. Explore the data using the interactive charts provided by Plotly Express.
