# Testing environment for javascript and web coding!

Please download or clone this git repository and then follow steps below and try to create some cool stuff. 

1. Clone this repository to your filesystem
2. See the folder /original-app. There are screenshots from app you should create. There is also one video to see behaviour of resizing screen or scrolling - animated menu gets visible.
3. Create Less or Sass precompiler files and style the site with them, if you can. Helping them generate some style.css to /css folder and link it to your index.html
4. Link also some javascript you creates. On the main page you can see today's date. Create this with javascript.
5. There is also today's forecast. Fetch data about today's weather with Ajax. Easiest way is use jQuery for that. API endpoint for data is [here](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20(select%20woeid%20from%20geo.places(1)%20where%20text%3D%22prague%22)&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys "endpoint"). Structure of that javascript object you will get from that API you can see [here](https://developer.yahoo.com/weather/ "endpoint"). Get the string of today's forecat from it and put it to your page with JS!
6. Feel free to use any tool you want and code!
