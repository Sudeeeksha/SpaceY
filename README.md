# SpaceY
In this capstone, we will predict if the Falcon 9 first stage will land successfully. if we can determine if the first stage will land, we can determine the cost of a launch. 

1.Data Collection
    The Data was collected usig SpaceX api and webscrapping.
    
2.Data Wrangling
    Calculate the number of launches per site
    Determine the number of occurences of each orbit
    Determine the number of occurrences of outcome per orbit
    Create landing outcome label
    Work out success rate for every landing in the dataset 

3.EDA with Data visualization
    Utilized bar graph and scatter plots

4.Built an Interactive map with Folium
    Map objects were created and added to folium map
     * Markers : Added to mark a specific area with a text label on specific coordinate
     * Circles: Added to highlight circle areas with a text label on a specific coordinate
     * Marker Cluster: Used to simplify containing many markers having the same coordinates

5. Classification model development
     Building the model
      *Load the data into numpy and pandas
      *Standardize features
      *Split data into 80:20 ratio
     Evaluating the model
      *Check accuracy for each model
      *Get tuned hyperparameters for each type of algorithm
      *Plot confusion matrix
     Improving the model
      *Feature engineering
      *Algorithm tuning
     Finding the best performing classification model
      *Selected from the best accuracy score

**Conclusion**
 1.KSC LC-39A had the most successful launches from all site
 2.Heavier payloads performance was less than low weighted payloads 
 3.Orbit GEO, HEO, SSO, ES-L1 had the most successful launches
 4.The tree classifier algorithm is the best for machine learning for this data set . 
