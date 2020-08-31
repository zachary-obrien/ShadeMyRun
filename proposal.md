## Shade My Run 
#### A Project Proposal for CSCE 5214 
Group Participants | Contact Information 
------------------ | -------------------
Constant Marks |
Daniel Mata | 
Zachary O\'Brien |
Jason Gillette | JasonGillette@my.unt.edu

**Executive Summary**

The purpose of *Shade My Run* is to assist runners in identifying routes with ample shade provided by tree cover. This project will use a segment of LiDAR imagery data to successfully train a model to identify tree cover within more widely available sattelite imagery data. With the simple entry of a turn-around point, the user will gain a shaded route on low-volume roadways, and route details such as distance and elevation. 

**Project Abstract**

**Inputs:** The data being utilized in the project is *LiDAR-Derived Aboveground Biomass and Uncertainty for California Forests, 2005-2014* from the Oak Ridge National Laboratory (ORNL) Distributed Active Archive Center (DAAC). This dataset provides estimates of aboveground biomass and spatially explicit uncertainty from 53 airborne LiDAR surveys of locations throughout California between 2005 and 2014. Additional data being utilized includes sattelite imagery from...

**Project Design:** In order to...\*Jupyter notebooks, AWS, etc.\*

**Milestones**
1. Train model with lidar dataset
2. Use model to score satalite data
  * 2a. Use satalite data to measure distance straight line  
  * 2b. Road Features - Get width and type of roads (Google api?, Street data) \*<28ft is standard non-highway two-lane\*
3. Merge to make one Object
  * 4a. Merging multiple road segments (Test routes)
  * 4b. Gathering multiple paths from google maps for a route
5. Combine 4a and 4b to get a score for multiple routes
6. Basic interface that takes two text addresses and outputs text route options
7. Display route on maps
8. Input turn-around based on maps
9. Input takes you halfway and automatically takes you back

**Resources**
* Inspiration:[Mapping All Trees With Machine Learning](https://medium.com/descarteslabs-team/descartes-labs-urban-trees-tree-canopy-mapping-3b6c85c5c9cc)
* Data:[LiDAR-Derived Aboveground Biomass and Uncertainty for California Forests, 2005-2014](https://daac.ornl.gov/cgi-bin/dsviewer.pl?ds_id=1537)
* Data:[LiDAR Data User Guide](https://daac.ornl.gov/CMS/guides/CMS_LiDAR_AGB_California.html)
