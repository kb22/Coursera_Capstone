# Data Science Capstone Project
The repository will include code for the Capstone project in Applied Data Science Capstone course on Coursera. This includes various notebooks, reports and the complete data science project.


### Capstone Project description
The project includes **exploring venues in Chandigarh, India using datasets from two APIs - Foursquare API and Zomato API**. The aim of this project is to allow any visitor to select from a range of venues based on their venue rating and average price preferences.
- [Report](https://github.com/kb22/Coursera_Capstone/blob/master/Coursera%20Capstone%20Report.pdf)
- [Notebook](https://github.com/kb22/Coursera_Capstone/blob/master/Exploring%20venues%20in%20Chandigarh.ipynb)
- [Article](https://towardsdatascience.com/exploring-chandigarh-india-using-foursquare-and-zomato-api-1d4501291320)

### Set up
1. Clone the repository
```
git clone https://github.com/kb22/Coursera_Capstone.git
```
2. Move inside the newly created repository
```
cd Coursera_Capstone
```
3. Create a virtual environment and activate it (optional)
```
virtualenv -p $(which python) .
source bin/activate
```
4. Install all libraries
```
pip install -r requirements.txt
```
5. Start jupyter
```
jupyter notebook
```
6. Run jupyter files you want
  - Exploring venues in Chandigarh.ipynb
  - Clustering on Toronto.ipynb
  - Getting coordinates.ipynb
  - Data Collection.ipynb
7. Deactivate environment (if created and activated before)
```
deactivate
```

### Maps
Maps generated in the notebooks have been placed inside the `maps` folder. Download/clone the repository and access the maps on your local machine.
