# CustomBorderForTwitch

You can use this code to customize the animated border. E.g. you can use it for your streams at Twitch.

You can changes variables located in `:root` css selector in style.css file to adjust the border:

The size:
`--borderWidth: 10px; // thickness of the border` <br>
`--borderRadius: 10px; // sharpness of the corners`<br>
`--width: 400px; // size`<br>
`--height: 225px; // size`<br>

The colors:
`--hue: 300; // range is from 0 to 360`<br>
`--hueOffset: 120;  // range is from 0 to 360`<br>
`--level: 50%; // range is from 0 to 100%`<br>
`--brightness: 75%; // range is from 0 to 100%`<br>

The speed of animation:
`--duration: 5s; // any number - the lower number, the faster animation`

How to apply it in OBS:

1. In your Scene -> Add source -> Custom Widget:
   ![ Scene -> Add source -> Custom Widget](obs-custom-widget.png)

2. Browser Setting -> edit the width and heigth for your border to fit in:
   ![Browser Setting](browser-setting.png)

3. Custom Code -> Edit Custom Code:
   ![Custom Widget Setting](custom-code.png)

Add this line of code into html code:
`<div class="gradient-border" id="box"></div>`
![HTML tab](html-tab.png)

4. Add everything from style.css into css tab.

Feel free to contact me in case of any questions.
