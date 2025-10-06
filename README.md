# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

```
1index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="1globals.css" />
    <link rel="stylesheet" href="1styleguide.css" />
    <link rel="stylesheet" href="1style.css" />
  </head>
  <body>
    <div class="union">
      <img class="img" src="img/union.svg" />
      <div class="overlap">
        <div class="rectangle"></div>
        <div class="text-wrapper">LOGIN</div>
      </div>
      <div class="overlap-group">
        <div class="div"></div>
        <div class="text-wrapper-2">REGISTER</div>
      </div>
      <div class="text-wrapper-3">Designed by Sifiz A(25010152)</div>
    </div>
  </body>
</html>



1globals.css
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
  text-decoration: none;
}


1styleguide.css

:root {
  --shape-corner-large: 16px;
}

1style.css     
.union {
  width: 1px;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  min-height: 1px;
  background: linear-gradient(
    0deg,
    rgba(255, 2, 2, 1) 0%,
    rgba(255, 2, 2, 1) 100%
  );
}

.union .img {
  width: 1px;
  margin-top: 11px;
  margin-right: -113px;
}

.union .overlap {
  width: 171px;
  margin-top: 546px;
  margin-right: -306px;
  height: 45px;
  position: relative;
}

.union .rectangle {
  width: 171px;
  position: absolute;
  height: 40px;
  top: 5px;
  left: 0;
  background-color: #0000ff;
  border-radius: var(--shape-corner-large);
  border: 1px solid;
  border-color: #ffff02;
}

.union .text-wrapper {
  position: absolute;
  width: 111px;
  top: 0;
  left: 36px;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.union .overlap-group {
  width: 191px;
  margin-top: 42px;
  margin-right: -316px;
  height: 45px;
  position: relative;
}

.union .div {
  width: 191px;
  position: absolute;
  height: 40px;
  top: 5px;
  left: 0;
  background-color: #0000ff;
  border-radius: var(--shape-corner-large);
  border: 1px solid;
  border-color: #ffff02;
}

.union .text-wrapper-2 {
  position: absolute;
  width: 161px;
  top: 0;
  left: 21px;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.union .text-wrapper-3 {
  width: 226px;
  min-height: 34px;
  margin-top: 42px;
  margin-right: -471px;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

2index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="2globals.css" />
    <link rel="stylesheet" href="2style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="text-wrapper">SHORT FILM EVENTS</div>
      <div class="ROUND-shortlisting">ROUND: 1<br />Shortlisting films</div>
      <div class="ROUND-semi-finals">ROUND: 2<br />Semi Finals</div>
      <div class="ROUND-finals">ROUND: 3<br />Finals</div>
      <div class="div">Designed by Sifiz A(25010152)</div>
    </div>
  </body>
</html>

2globals.css

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
  text-decoration: none;
}

2style.css

.android-medium {
  background-color: #08cdff4c;
  overflow: hidden;
  border: 5px solid;
  border-color: #000000;
  width: 100%;
  min-width: 423px;
  min-height: 678px;
  display: flex;
  flex-direction: column;
}

.android-medium .text-wrapper {
  margin-left: 39px;
  width: 461px;
  height: 49px;
  margin-top: 25px;
  -webkit-text-stroke: 1px #fff601;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ROUND-shortlisting {
  margin-left: 97px;
  width: 274px;
  height: 35px;
  margin-top: 85px;
  -webkit-text-stroke: 1px #fff601;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #2204ff;
  font-size: 28px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ROUND-semi-finals {
  margin-left: 94px;
  width: 176px;
  height: 64px;
  margin-top: 94px;
  -webkit-text-stroke: 1px #fff601;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #2204ff;
  font-size: 28px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ROUND-finals {
  margin-left: 97px;
  width: 164px;
  height: 54px;
  margin-top: 74px;
  -webkit-text-stroke: 1px #fff601;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #2204ff;
  font-size: 28px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  margin-left: 202px;
  width: 279px;
  height: 33px;
  margin-top: 165px;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

3.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="3globals.css" />
    <link rel="stylesheet" href="3styleguide.css" />
    <link rel="stylesheet" href="3style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="div">Fill the details</div>
      <div class="rectangle"></div>
      <img class="text-on-a-path" src="img/image.svg" />
      <div class="text-wrapper-2">Name:</div>
      <img class="img" src="img/text-on-a-path.svg" />
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-3">Age:</div>
      <div class="text-wrapper-4">Gender:</div>
      <div class="text-wrapper-5">Register Number:</div>
      <div class="text-wrapper-6">Department:</div>
      <div class="text-wrapper-7">Mobile Number:</div>
      <div class="text-wrapper-8">Email Id:</div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-9">REGISTER</div>
      <div class="text-wrapper-10">Designed by Sifiz A(25010152)</div>
    </div>
  </body>
</html>

3globals.css

3 global.css     @import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
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
  text-decoration: none;
}

3styleguide.css

3 styleguide.css         :root {
  --shape-corner-extra-large: 28px;
  --shape-corner-large: 16px;
}

3style.css

3 style.css     .android-medium {
  background-color: #06c0ff4c;
  overflow: hidden;
  border: 5px solid;
  border-color: #000000;
  width: 100%;
  min-width: 423px;
  min-height: 723px;
  position: relative;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 26px;
  left: 16px;
  width: 390px;
  -webkit-text-stroke: 1px #ffff04;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .div {
  position: absolute;
  top: 76px;
  left: 17px;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle {
  position: absolute;
  top: 127px;
  left: 34px;
  width: 345px;
  height: 37px;
  background-color: #d9d9d9;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 32px;
  left: -34px;
  width: 345px;
  height: 37px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 138px;
  left: 59px;
  opacity: 0.5;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .img {
  position: absolute;
  top: 100px;
  left: -34px;
  width: 345px;
  height: 35px;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 261px;
  left: 34px;
  width: 345px;
  height: 35px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 327px;
  left: 34px;
  width: 345px;
  height: 35px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 393px;
  left: 34px;
  width: 345px;
  height: 35px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 460px;
  left: 34px;
  width: 345px;
  height: 36px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 528px;
  left: 34px;
  width: 345px;
  height: 35px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-7 {
  position: absolute;
  top: 195px;
  left: 34px;
  width: 346px;
  height: 35px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 201px;
  left: 59px;
  width: 312px;
  opacity: 0.5;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 267px;
  left: 59px;
  width: 203px;
  opacity: 0.5;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 334px;
  left: 59px;
  width: 179px;
  opacity: 0.5;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 398px;
  left: 59px;
  width: 179px;
  opacity: 0.5;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 466px;
  left: 58px;
  width: 154px;
  opacity: 0.5;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-8 {
  position: absolute;
  top: 538px;
  left: 58px;
  width: 157px;
  opacity: 0.5;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-8 {
  position: absolute;
  top: 602px;
  left: 116px;
  width: 168px;
  height: 42px;
  background-color: #040cff;
  border-radius: var(--shape-corner-large);
  border: 1px solid;
  border-color: #ffff04;
}

.android-medium .text-wrapper-9 {
  position: absolute;
  top: 605px;
  left: 137px;
  width: 194px;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-10 {
  position: absolute;
  top: 689px;
  left: 207px;
  width: 235px;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}


```

## OUTPUT:

![alt text](<Screenshot (22).png>)

![alt text](<Screenshot (21).png>)

![alt text](<Screenshot (20).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
