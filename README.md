# ShadeMyRun
This project took aerial lidar data, processed it into depth metrics for tree height. 

It then overlaps that data with images from Google earth to create an overlay of images with the areas of trees and the tree height. 

This combined data was used to create a model that can detect the height of trees simply based on an aerial image. It can use this height/width data to detect what area of shade coverage would be present. 

Finally this is overlayed with directions from the Google Maps API to detect the routes to a destination with the maximum shade coverage for runners to stay out of constant sun/heat. 



Collaborative git for CSE5214 Project Group #7
### Resources

- Data:  [LiDAR-Derived Aboveground Biomass and Uncertainty for California Forests, 2005-2014](https://daac.ornl.gov/cgi-bin/dsviewer.pl?ds_id=1537)
- Data User guide: [guide](https://daac.ornl.gov/CMS/guides/CMS_LiDAR_AGB_California.html)
- Inspiration: [Mapping All of the Trees with Machine Learning](https://nam04.safelinks.protection.outlook.com/?url=https%3A%2F%2Fmedium.com%2Fdescarteslabs-team%2Fdescartes-labs-urban-trees-tree-canopy-mapping-3b6c85c5c9cc&data=02%7C01%7CConstant.Marks%40unt.edu%7C5a3cfaddd4c54ee2fbc208d84a10c256%7C70de199207c6480fa318a1afcba03983%7C0%7C0%7C637340783132992276&sdata=XmLkPSxdSVcC4gzoyDWennTw5dalA2C5OsfJCLgTcBQ%3D&reserved=0)
