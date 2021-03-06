## Spots back-end
Spots is an app that helps people meet up at a central location. Simply click to detect your current location, and/or enter addresses of your own/your friends'/other locations, then click a destination category. Spots will calculate the average point between your group and find the closest restaurant, bar or movie theatre. In addition, users can add new destinations to their own spots database, and the app's calculation will include the new ones. This is the back-end, it requires [Spots front-end](https://github.com/rainANDshine/spots) to run.

## Technical Aspects
+ Integrated Mapbox API and Google API for displaying the map and address search
+ Created algorithm to find the average point between multiple geographic coordinates
+ Built back-end JSON API server with full CRUD functions with Ruby on Rails

## Latest Stable Branch
Master

## Installation
1. git clone https://github.com/rainANDshine/spots

2. Create a **secrets.yml** file in the **config** folder, and write: <code>development: apikey: *your own Google API key*</code>

3. bundle

4. rails s

## Live App
https://spots-1.herokuapp.com/index.html

## Youtube Video Demo
https://www.youtube.com/watch?v=JuedMMu2Ky8

## Screenshots
<img src="1.png" alt="1">
<img src="2.png" alt="2">
<img src="3.png" alt="3">
<img src="4.png" alt="4">

## Credits
Built by [Lane Miller](https://github.com/LaneMiller), [Jesse Horwitz](https://github.com/SuperJesseH), and [Shun Yao](https://github.com/rainANDshine)

## License
MIT ©
