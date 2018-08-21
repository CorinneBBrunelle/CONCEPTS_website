# CONCEPTS_website
Images production for CONCEPTS_website
GIOPS Daily Images: average of the first 24 hrs of forecast [0-24]
GIOPS 10d forecast: daily average for the 10 days of forecast [0-24, 24-48, 48-72…]
 
Animations are produced using the 10 plots from the GIOPS 10d forecast
 
Arctic zoom coordinates:
[66.854593725666, -127.31241594006615], [67.27130760980332, -54.83951460589132], [67.63068535797869, 53.47604143072642], [67.43513534183177, 129.00978351534692]
 
Atlantic:
[39.92459761658699, -74.89700973033904], [40.05926969760134, -19.525915980339025], [71.30700407995491, -20.404822230339036], [71.13725323231671, -75.95169723033902]
 
Pacific:
[61.782285969603606, -159.43181574344632], [47.23272693335352, -159.60759699344632], [47.23272693335352, -121.63884699344632], [61.823814620677126, -122.07830011844631]
 

	
Variable in NetCDF
	
Model Depth : 0, sub-surface (-15 ou 17 meters)
	
variables : Temperature, currents, salinity, Ice concentration (only Arctic and Atlanctic)

Regions : Arctic, Atlantic, Pacific,
	
  
* The model depth listed above I pulled from our python scripts that use the Navigator API. If these depths don’t make sense for you, just pull the model depth level that best represents the sub-surface 15m and 50m variable.
 
