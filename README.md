# Ex08 Event Registration Web Application
## Date:24.03.2026

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="ipad-mini">
      <img class="hero" src="img/ignite2026-bg1-hero-1.png" />
      <div class="text-wrapper">IGNITE26</div>
      <div class="div">BUILD.</div>
      <div class="text-wrapper-2">BREAK.</div>
      <div class="text-wrapper-3">IGNITE.</div>
      <div class="rectangle"></div>
      <div class="text-wrapper-4">regiseter</div>
      <div class="text-wrapper-4">regiseter</div>
    </div>
  </body>
</html>
global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
/* @FONTWARNING[{"type": "restricted", "family": "Irish Grover-Regular", "weight": "400", "style": "normal", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Irish Grover-Regular";
  src: local("Irish Grover-Regular");
}
style.css
.ipad-mini {
  background-color: #ffffff;
  width: 100%;
  min-width: 744px;
  min-height: 1133px;
  position: relative;
}

.ipad-mini .hero {
  position: absolute;
  top: 0;
  left: 0;
  width: 744px;
  height: 1133px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

.ipad-mini .text-wrapper {
  position: absolute;
  top: 296px;
  left: 155px;
  width: 504px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #64c352;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.ipad-mini .div {
  position: absolute;
  top: 454px;
  left: 191px;
  width: 325px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ac5818;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.ipad-mini .text-wrapper-2 {
  position: absolute;
  top: 567px;
  left: 196px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #28b4d0;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.ipad-mini .text-wrapper-3 {
  position: absolute;
  top: 683px;
  left: 196px;
  width: 421px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #fed016;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.ipad-mini .rectangle {
  position: absolute;
  top: 887px;
  left: 173px;
  width: 444px;
  height: 77px;
  background-color: #f14343;
  filter: blur(10.1px);
}

.ipad-mini .text-wrapper-4 {
  position: absolute;
  top: 856px;
  left: 191px;
  width: 483px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="ipad-mini">
      <img class="ignite-bg" src="img/ignite2026-bg3-register-1.png" />
      <div class="text-wrapper">SIGN IN</div>
      <div class="div">Email:</div>
      <div class="text-wrapper-2">password:</div>
      <div class="rectangle"></div>
    </div>
  </body>
</html>
global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
/* @FONTWARNING[{"type": "restricted", "family": "Irish Grover-Regular", "weight": "400", "style": "normal", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Irish Grover-Regular";
  src: local("Irish Grover-Regular");
}
style.css
.ipad-mini {
  background-color: #ffffff;
  width: 100%;
  min-width: 744px;
  min-height: 1133px;
  position: relative;
}

.ipad-mini .ignite-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 744px;
  height: 1133px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

.ipad-mini .text-wrapper {
  position: absolute;
  top: 241px;
  left: 186px;
  width: 377px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.ipad-mini .div {
  position: absolute;
  top: 486px;
  left: 73px;
  width: 396px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.ipad-mini .text-wrapper-2 {
  position: absolute;
  top: 698px;
  left: 56px;
  width: 466px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.ipad-mini .rectangle {
  position: absolute;
  top: 490px;
  left: 271px;
  width: 444px;
  height: 77px;
  background-color: #f14343;
  filter: blur(10.1px);
}
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="ipad-mini">
      <img class="ignite-bg" src="img/ignite2026-bg2-schedule-1.png" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper">Schedule</div>
      <div class="text-wrapper-2">Guest Speech</div>
      <div class="intro-welcome">Intro &amp; Welcome</div>
      <div class="text-wrapper-3">Demo Presentation</div>
      <div class="text-wrapper-4">Award Ceremony</div>
    </div>
  </body>
</html>
global.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
/* @FONTWARNING[{"type": "restricted", "family": "Irish Grover-Regular", "weight": "400", "style": "normal", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Irish Grover-Regular";
  src: local("Irish Grover-Regular");
}
style.css
.ipad-mini {
  background-color: #ffffff;
  width: 100%;
  min-width: 744px;
  min-height: 1133px;
  position: relative;
}

.ipad-mini .ignite-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 744px;
  height: 1133px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

.ipad-mini .rectangle {
  position: absolute;
  top: 100px;
  left: 147px;
  width: 381px;
  height: 92px;
  background-color: #bcbe29;
  border: 1px solid;
  border-color: #000000;
  filter: blur(2px);
  opacity: 0.63;
}

.ipad-mini .div {
  position: absolute;
  top: 316px;
  left: 127px;
  width: 444px;
  height: 77px;
  background-color: #f14343;
  filter: blur(10.1px);
}

.ipad-mini .rectangle-2 {
  position: absolute;
  top: 490px;
  left: 127px;
  width: 444px;
  height: 77px;
  background-color: #f14343;
  filter: blur(10.1px);
}

.ipad-mini .rectangle-3 {
  position: absolute;
  top: 664px;
  left: 127px;
  width: 444px;
  height: 77px;
  background-color: #f14343;
  filter: blur(10.1px);
}

.ipad-mini .rectangle-4 {
  position: absolute;
  top: 838px;
  left: 127px;
  width: 444px;
  height: 77px;
  background-color: #f14343;
  filter: blur(10.1px);
}

.ipad-mini .text-wrapper {
  position: absolute;
  top: 80px;
  left: 147px;
  width: 483px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.ipad-mini .text-wrapper-2 {
  position: absolute;
  top: 316px;
  left: 130px;
  width: 483px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.ipad-mini .intro-welcome {
  position: absolute;
  top: 490px;
  left: 130px;
  width: 483px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.ipad-mini .text-wrapper-3 {
  position: absolute;
  top: 664px;
  left: 130px;
  width: 483px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.ipad-mini .text-wrapper-4 {
  position: absolute;
  top: 845px;
  left: 162px;
  width: 483px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}


```

## OUTPUT:

![alt text](<Screenshot (43).png>)
## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
