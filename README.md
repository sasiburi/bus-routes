# bus-routes
The City of Kingston promotes and fosters open government principles of participation, innovation, transparency and accountability. It provides a data catalogue to support these principles and as a first step in making it easier to view, obtain and use the information the City has gathered. The datasets are available at: https://www.cityofkingston.ca/explore/data-catalogue.


Routes Information can be extracted from routeInfo.pkl.
You can use the code:
'''
pkl_file = open('routeInfo.pkl', 'rb')
Routes = pickle.load(pkl_file)
pkl_file.close()

print(Routes)
'''
,where the Routes format is {route#: {"latitude":[...], "longitude": []}, ...., ....}
