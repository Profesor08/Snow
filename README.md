# Snowfall

Snowfall animation for your website

### Installation
```html
<script type="text/javascript" src="js/Flake.js"></script>
<script type="text/javascript" src="js/Snowfall.js"></script>
```

### Usage
```javascript
let snow = new Snowfall("#snowfall", {
    images: [
      "img/flake1.png",
      "img/flake2.png",
      "img/flake3.png",
      "img/flake4.png",
      "img/flake5.png",
      "img/flake6.png",
      "img/flake7.png"
    ],
    count: 250,
    size: {
      min: 10,
      max: 30
    }
});
  
snow.start();
```