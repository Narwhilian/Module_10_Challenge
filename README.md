# Unsupervised_Crypto

This application uses unsupervised learning to cluster the performances of various crypto currencies  

---

## Technologies

This project uses the Python Programming language in a Jupyter Notebook as well as the following libraries
    
    - pandas
    - hvplot
    - Path
    - sklearn
      * KMeans
      * PCA
      * Standard Scaler


---

## Installation Guide

To install you will want to pull the entire Unsupervised_Crypto folder from github including its subfolder
    
    * Subfolder
        * Resources (the folder containing the csv data of the historical crpyto performance)
        * crypto_investments.ipynb (the jupyter notebook itself)
        * ReadMe (This file)


---

## How it works

1) First the user will open the crypto_investments.ipynb notebook in the Unsupervised_Crypto folder
2) Then the user will simply run each cell in the notebook in order to get its output

    i) The app will load the crypto data into a dataframe and prepare the data for the KMeans function using the StandardScaler tool
    
    ii) Then run the KMeans function with k set at 4 and analyze the output

    
    iii) Then it will check the inertia value of the result of the KMeans function for all values of k between 1 and 11 to determine the best value of k

    
    iv) It will then use the PCA function to break down the variables into 3 dimensions for easier analysis while still accurately representing the original data
    
    
    v) Finally it will compare the results by plotting the clusters produced when k=4 and k=5 using the PCA values to determine which of the 2 k values is the best fit for unsupervised learning.
    





---

## Usage

Overall it should be a very simple application to use, all you need to do is open the crypto_investments.ipynb notebook in the Unsupervised_Crypto folder and run each cell in order


---

## Contributors

Colin Benjamin

Linkedin: [Colin Benjamin](https://www.linkedin.com/in/colinbenjamin/)
    
email: cbenjamin33@gmail.com

---

## License

MIT
