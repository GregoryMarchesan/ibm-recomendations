# Recommendations with IBM

## Summary

The project uses IBM articles dataset to build a recommendation algorithm, based on colaborative filtering. 
Additionally, it uses SVD to implement machine learning in the algorithm.

## Folder organization

The project is organized as follows:
 
- data  
|- articles_community.csv        # data with articles description 
|- user-item-interactions.csv    # data with user-articles interactions

  
- project_tests.py 				 # test python file
- Recommendations_with_IBM.ipynb # notebook with the recommendation system

- README.md

## Instalation

The code runs in Python 3.7.3 and requires the following libraries:
- Numpy (1.16.2)
- Pandas (0.24.2)
- Sklearn (0.20.3)
- Plotly (4.14.3)
- Tqdm (4.31.1)

### Instructions:
Run the Python Notebook with the data provided to explore the data, go through the
recommendation systems, train a SVD algorithm and see the colaborative filtering

## To do
1. Content-based recommendation
2. Knowledge-based recommendation
3. Put it all together into a web app, like Flask

## Acknowledgements & Licensing

The code provided here is free to use and it is under MIT Licensing.
