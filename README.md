# npm-imagerecognition

## Usage

```javascript
var ImageRecognition = require("image-recognition");
new ImageRecognition(imageURL,callback);
```

Example for the picture below:

![President of the USA Barack Obama](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/President_Barack_Obama.jpg/220px-President_Barack_Obama.jpg)

```javascript
var ImageRecognition = require("image-recognition");
new ImageRecognition("https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/President_Barack_Obama.jpg/220px-President_Barack_Obama.jpg",function(res){
  console.log(res); //president obama
});
```
