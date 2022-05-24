# Example of Creating an Animated Wildfire Progression Map Video
This is some sample code that uses Mapbox GL JS to export an animated wildfire progression map as an mp4 video file. It is heavily based off the [video export example by Volodymyr Agafonkin](https://github.com/mapbox/mapbox-gl-js/blob/main/debug/video-export.html). The wildfire data is from [NASA FIRMS](https://firms.modaps.eosdis.nasa.gov/). 

## Example video of the Dixie and Beckwourth Complex fires from 2021
https://user-images.githubusercontent.com/1069954/170116861-39ab7c90-1c3f-43b1-a019-6d959d5d717d.mp4

## How to use
1. First, you need a local web server. I like [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en) because it's dead simple and gets the job done. 
2. Edit index.html and replace YOUR_TOKEN_HERE with your own Mapbox API token. You can [sign up and get one from Mapbox](https://account.mapbox.com/auth/signup). 
3. Open the index.html file in your local web server. 
4. Wait for the video to render frame by frame. It takes a while. Once it's done it will automatically download a file called fire-progression.mp4. 
