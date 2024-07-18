# Web-Analysis

Travel Review Data Set
pip install ucimlrepo

from ucimlrepo import fetch_ucirepo 

# fetch dataset 
travel_reviews = fetch_ucirepo(id=484) 
  
# data (as pandas dataframes) 
X = travel_reviews.data.features 
y = travel_reviews.data.targets 
  
# metadata 
print(travel_reviews.metadata) 
  
# variable information 
print(travel_reviews.variables) 


Student Performance
pip install ucimlrepo

from ucimlrepo import fetch_ucirepo 
  
# fetch dataset 
student_performance = fetch_ucirepo(id=320) 
  
# data (as pandas dataframes) 
X = student_performance.data.features 
y = student_performance.data.targets 
  
# metadata 
print(student_performance.metadata) 
  
# variable information 
print(student_performance.variables) 
