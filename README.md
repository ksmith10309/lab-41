![CF](http://i.imgur.com/7v5ASc8.png) LAB 41
=================================================

## React Native

### Author: Katherine Smith

### Links and Resources
* [repository](https://github.com/ksmith10309/rna)

### Modules
#### `App.js`
- Contains App component
  - Contains state for image, width, height, and text
  - Contains _increaseWidth() method which allows user to increase width of image
  - Contains _decreaseWidth() method which allows user to decrease width of image
  - Contains _increaseHeight() method which allows user to increase height of image
  - Contains _decreaseHeight() method which allows user to decrease height of image
  - Contains _pickImage() method which allows user to choose an image from device
  - Renders buttons for choosing an image and image size manipulation
  - Renders input field for user to add a caption to the image
  - Renders image and caption

### Setup
#### Running the app
* Clone rna repository
* Ensure node.js is installed
  * If not, run the command `brew install node` in the terminal
* Ensure Expo command line tool is installed
  * If not, run the command `npm i -g expo-cli` in the terminal
* Navigate to the cloned repository in the terminal
  * Run the command `npm i` to install dependencies
  * Run the command `npm start` to start Expo