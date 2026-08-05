For a residential location:

“1. location_imagery_collection” contains Python scripts run in Google Colab to collect Google Street View images, when available, for each MSG residential location.

“2. coding_locations_images_using_gemini” contains Python scripts run in Google Colab to query the Google Gemini API and detect selected items in each image collected during last step.


For each residential location's neighborhood:

“3. radius_image_collection” contains Python scripts run in Google Colab to collect Google Street View images, when available, for a randomly selected location within a half-mile circle area centered around each MSG residential location.

“4. coding_neighborhood_images_using_gemini” contains Python scripts run in Google Colab to query the Google Gemini API and detect selected items in each image collected during last step.


For the nearest intersection:

“5. intersection_collection” contains Python scripts run in Google Colab to identify the closest intersection to each MSG residential location. The four zipped folders contain the collected PUMA-level results, including the map tiles and intersection coordinates.

“6. intersection_imagery_collection” contains Python scripts run in Google Colab to collect Google Street View images, when available, for the closest intersection to each MSG residential location.

“coding_Intersection Images_using_Gemini” folder contains Python scripts run in Google Colab to query the Google Gemini API and detect selected items in each image collected during last step.
