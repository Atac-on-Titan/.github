# Statistical Learning 2023
This organisation contains all the repositories used by our group for the Statistical Learning course. 

## Final Project - ATAC Predictions
The final project spans multiple repositories:

- [data-gathering](https://github.com/Atac-on-Titan/data-gathering) for gathering the necessary data for the project.

### Project Data
The project data can be downloaded from an AWS S3 bucket:

- [final preprocessed feather dataframe](https://statistical-learning.s3.amazonaws.com/trip_live_final.feather)
- [trip updates](https://statistical-learning.s3.amazonaws.com/trip-updates.feather) a feather dataframe with live data about trips and routes in the ATAC network, scraped from the Roma Open Data portal.
- [vehicle positions](https://statistical-learning.s3.amazonaws.com/vehicle-positions.feather) a feather dataframe live data about ATAC vehicle positions, scraped at the same time as the trip updates from the Roma Open Data portal.
- [weather data](https://statistical-learning.s3.amazonaws.com/weather_df.feather) a feather dataframe with hourly weather data for the city of Rome, matching the times of the trip updates and vehicle positions.
- [static data](https://statistical-learning.s3.amazonaws.com/rome_static_gtfs_test.zip) a `.zip` archive with static ATAC data about stops, routes, etc.

The raw `.pb` files are available here:

- [trip updates raw](https://statistical-learning.s3.amazonaws.com/trip-updates.zip)
- [vehicle positions raw](https://statistical-learning.s3.amazonaws.com/vehicle-positions.zip)
