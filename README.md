# thankx
Demo Graphic Mobile App

## Requirements

1. We value a *clean*, *simple*, working solution.
2. The application must be built on React Native and you can use Expo
3. Candidates must submit the project as a git repository (github.com, bitbucket.com, gitlab.com). The repository must avoid containing the works.
4. Having unit tests is a strong bonus.
5. The solution must be production ready.

## Problem Statement

1. A user should be able to spawn an infinite number of squares or circles filled with random colours or images.
2. Application consists of 4 screens using a tab bar. The tabs are as follows:
    1. Squares - this screen only spawns squares.
    2. Circles - this screen only spawns circles.
    3. Triangles - this screen only spawns triangles.
    4. All - this screen spawns squares, circles and triangles randomly.
3. Create squares, circles or triangles which randomly fill with random colours or images when the user taps on the main background.
4. Created shapes are placed at the user's tapped location.
5. Create a shape at a random size within appropriate ranges. A shape should not be more than 45% the width or height of the screen size and should never be less than 10% the width or height.
6. Fill circles with a colour that is generated by calling the API from http://www.colourlovers.com/api/colors/random?format=json using either the RGB or Hex value
7. Fill squares with an image that is generated by calling the API from http://www.colourlovers.com/api/patterns/random?format=json using the imageUrl value
8. Fill triangles randomly either using the fill circle or fill square requirements above.
9. If no connection is available from the above API urls, use code to generate random colours
10. Double tapping the shape replaces the colour or image based on the above mentioned rules.

## Extra tasks (if time allows)

1. When a user taps the screen, add an animation for the shapes that appear
2. Remove all shapes when shaking the device
3. Be able to move a shape around
4. Allow a user to use the pinch action to enlarge or shrink the size of a shape
5. Working app for both iOS and Android


http://www.colourlovers.com/api/colors/random?format=json
http://www.colourlovers.com

http://www.colourlovers.com/api/patterns/random?format=json
http://www.colourlovers.com
