<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
<title>Adapt.js Jump Start</title>
<script>
    // Edit to suit your needs.
var ADAPT_CONFIG = {
  // Where is your CSS?
  path: 'assets/css/',

  // false = Only run once, when page first loads.
  // true = Change on window resize and page tilt.
  dynamic: true,

  // Optional callback... myCallback(i, width)
  callback: myCallback,

  // First range entry is the minimum.
  // Last range entry is the maximum.
  // Separate ranges by "to" keyword.
  range: [
    '0px    to 760px  = mobile.css',
    '760px  to 980px  = 720.css',
    '980px  to 1280px = 960.css',
    '1280px to 1600px = 1200.css',
    '1600px to 1920px = 1560.css',
    '1940px to 2540px = 1920.css',
    '2540px           = 2520.css'
  ]
};
</script>
<script src="js/adapt.min.js" ></script>
</head>
<body>
    <h1>Adapt.js Jump Start</h1>
</body>
</html>

