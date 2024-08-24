# Into space for biodiversity! Deciphering Lemu NGE satellite data with Python
Can you imagine having a space superhero watching over our forests and oceans? Well, such a superhero already exists: it’s called Lemu NGE, the first Chilean satellite dedicated exclusively to studying the biodiversity of our planet, and best of all, we can follow its adventures and analyze its data from the comfort of our own home!

## What is Lemu NGE and why is it important?
The Lemu NGE, whose name means “Eye of the Forest” in Mapudungún, is a Chilean nanosatellite orbiting the Earth with a clear mission: to observe the biodiversity of our planet. Thanks to its hyperspectral camera, it can detect changes in vegetation, identify species and measure the quality of ecosystems, among many other things. This information is crucial to understanding the impacts of climate change and taking action to protect our planet. 😊

LEMU NGE blasted off into space last August 16 on SpaceX’s Transporter-11 mission from Vandenberg Space Force Base, California. I had the opportunity to follow the live broadcast of the liftoff on Youtube, and even more, to have a great detailed explanation of the whole project narrated by the members of the LEMU team. To tell the truth, I felt very proud as a Latin American and I was thrilled to live this great milestone. 😊

## Let’s explore the data with Python!
Want to know where the Lemu NGE is at this very moment? With a little Python we can find out! We’ll use the SatNOGS API to get the satellite’s orbit data and the skyfield library to calculate its exact position. Then, with plotly we’ll create a 3D visualization of the globe and watch the Lemu NGE in action.

## Step by step:

- Get the data: We will use the requests library to make a request to the SatNOGS API and get the two-line elements (TLEs) of the Lemu NGE. TLEs are like a kind of “recipe” that describes the orbit of a satellite.
- Calculate position: With skyfield, we will calculate the latitude and longitude of the satellite in real time.
- Visualize: We will use plotly to create an interactive 3D map of the Earth. We will add a marker at the exact position of the Lemu NGE and customize the map with colors and labels.

### This academic exercise is part of my continuous learning path in the areas of Data Engineering, Data Science and Remote Sensing with spatial data. 🛰️

[![Dataviz](https://javierladino.com/es/wp-content/uploads/2024/08/lemu_2v.gif)]([https://enlace.com](https://javierladino.com/portfolio/into-space-for-biodiversity-deciphering-lemu-nge-satellite-data-with-python/))
