# Agriculture_Data_Analytics_Project
The Crop Recommendation System, powered by Django and diverse libraries, suggests optimal crops based on parameters. Integrated with dataset visualizations and EDA, it provides a user-friendly interface for informed agricultural decisions. The README guides users through easy setup, and the system's dashboard showcases historical trends. 
Crop Recommendation and Analysis Django Project - README*

Project Overview:
The Crop Recommendation and Analysis Django project is designed to assist farmers in making informed decisions regarding crop selection and optimizing agricultural practices. Leveraging diverse datasets such as soil, temperature, production, price, area, rainfall, yield, season, pesticide, state, and fertilizer, the project aims to provide crop recommendations based on various parameters. Additionally, the project performs historical data analysis, offering insights into trends and optimizing agricultural strategies for better yields and economic returns.

Repository Structure:
The GitHub repository is organized as follows:
- crop_yield: Contains datasets related to soil, temperature, production, price, area, rainfall, yield, season, pesticide, state, and fertilizer.
- data_analysis_project: Holds the Django project source code.
- Documentation_Group1: Documentation files, including this README.

Commits:
The commit history reflects a logical progression of the project. Each commit is accompanied by a meaningful message describing the changes made. Commits are organized to maintain a clean and comprehensible development history.

Installation Instructions:

1. Setup Environment:
   - Install Python and Django.
   - Create a virtual environment for project isolation.

2. Database Setup:
   - Run migrations: python manage.py migrate.

3. Load Data:
   - Load datasets into the database: python manage.py loaddata data/*.json.

4. Run Server:
   - Start the Django development server: python manage.py runserver.

5. Access the Application:
   - Open a web browser and go to http://127.0.0.1:8000/data-analysis/data to use the application.

Usage Guidelines:

- Crop Recommendation:
  - Input parameters such as Nitrogen, Potassium and phosphorous content in your soil to receive personalized crop recommendations.
- Data Analysis:
  - Explore historical trends and insights through the provided dynamic charts.

Contributing:

If you wish to contribute to the project, please follow the standard GitHub workflow:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make changes and submit a pull request.

License:
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


Contributors of the project
1. Driti Arun Singhania
2. Siddharth R Bhardwaj
3. Ria Ann Bijo
4. Sejal Saluja

![image](https://github.com/DritiS/Agriculture_Data_Analytics_Project/assets/118894837/8323cde3-a385-44f6-88fe-f7fc9783e7e9)
![image](https://github.com/DritiS/Agriculture_Data_Analytics_Project/assets/118894837/50498b0a-2b62-463e-83e0-0f6802893412)
![image](https://github.com/DritiS/Agriculture_Data_Analytics_Project/assets/118894837/653846aa-b0d9-4d68-a432-4408c115acaf)
![image](https://github.com/DritiS/Agriculture_Data_Analytics_Project/assets/118894837/edb01614-5397-46bf-a9b1-e3c820849147)
![image](https://github.com/DritiS/Agriculture_Data_Analytics_Project/assets/118894837/c9de8810-2d4f-4c78-9d60-18d59b82d353)
![image](https://github.com/DritiS/Agriculture_Data_Analytics_Project/assets/118894837/cf6bfd2d-ac0b-4af8-b3ee-9c95b1f82c9d)





Acknowledgments:
https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset
https://www.kaggle.com/datasets/akshatgupta7/crop-yield-in-indian-states-dataset/
