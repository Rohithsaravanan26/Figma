# Ex09 Event Registration Web Application
## Date: 19.12.2025

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
#Home
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="pexels-gradienta" src="img/pexels-gradienta-7130475-1.png" />
      <img class="IMG" src="img/IMG-0677-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTER</div>
    </div>
  </body>
</html>

.iphone {
  position: relative;
  width: 393px;
  height: 852px;
  background-color: #ffffff;
}

.iphone .pexels-gradienta {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.iphone .IMG {
  position: absolute;
  top: 236px;
  left: 29px;
  width: 336px;
  height: 224px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 582px;
  left: 45px;
  width: 300px;
  height: 72px;
  background-color: #cddf2f;
  border-radius: 10px;
}

.iphone .text-wrapper {
  position: absolute;
  top: 582px;
  left: 38px;
  width: 317px;
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Jomhuria-Regular", Helvetica;
  font-weight: 400;
  color: #292525;
  font-size: 64px;
  text-align: center;
  letter-spacing: 4.48px;
  line-height: 89.6px;
  white-space: nowrap;
}

Next page
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <div class="div">
        <img class="pexels-gradienta" src="img/pexels-gradienta-7130475-1.png" />
        <div class="text-wrapper">REGISTER</div>
      </div>
      <img class="image" src="img/image-4.png" />
      <div class="text-wrapper-2">AURORA NIGHT 25’</div>
      <div class="text-wrapper-3">Events</div>
      <img class="img" src="img/image-1.png" />
      <img class="image-2" src="img/image-2.png" />
    </div>
  </body>
</html>

.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone .div {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  background-color: #ffffff;
}

.iphone .pexels-gradienta {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 582px;
  left: 38px;
  width: 317px;
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Jomhuria-Regular", Helvetica;
  font-weight: 400;
  color: #292525;
  font-size: 64px;
  text-align: center;
  letter-spacing: 4.48px;
  line-height: 89.6px;
  white-space: nowrap;
}

.iphone .image {
  top: 6px;
  left: 0;
  width: 393px;
  height: 846px;
  aspect-ratio: 1.5;
  position: absolute;
  object-fit: cover;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: -1px;
  left: 24px;
  width: 344px;
  height: 85px;
  display: flex;
  align-items: center;
  justify-content: center;
  -webkit-text-stroke: 1px #fffbfb;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 35px;
  text-align: center;
  letter-spacing: 2.45px;
  line-height: 49.0px;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 46px;
  left: calc(50.00% - 166px);
  width: 329px;
  height: 76px;
  display: flex;
  align-items: center;
  justify-content: center;
  -webkit-text-stroke: 1px #fffbfb;
  font-family: "Jockey One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 35px;
  text-align: center;
  letter-spacing: 2.45px;
  line-height: 49.0px;
}

.iphone .img {
  top: 134px;
  left: 49px;
  width: 295px;
  height: 299px;
  aspect-ratio: 0.99;
  position: absolute;
  object-fit: cover;
}

.iphone .image-2 {
  top: 459px;
  left: 49px;
  width: 295px;
  height: 296px;
  aspect-ratio: 1;
  position: absolute;
  object-fit: cover;
}

registration:
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="image" src="img/image-3.png" />
      <div class="text-wrapper">Event Registration Form:</div>
      <div class="rounded-rectangle"></div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-2">Full Name</div>
      <div class="text-wrapper-3">Register No.</div>
      <div class="text-wrapper-4">Age</div>
      <div class="text-wrapper-5">Gender</div>
      <div class="text-wrapper-6">Department</div>
      <div class="text-wrapper-7">Mobile No.</div>
      <div class="text-wrapper-8">SUBMIT</div>
    </div>
  </body>
</html>
.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: -1px;
  left: 24px;
  width: 344px;
  height: 85px;
  display: flex;
  align-items: center;
  justify-content: center;
  -webkit-text-stroke: 1px #fffbfb;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 1.68px;
  line-height: 33.6px;
}

.iphone .rounded-rectangle {
  position: absolute;
  top: 85px;
  left: calc(50.00% - 158px);
  width: 317px;
  height: 64px;
  background-color: #d9d9d9;
  border-radius: 7px;
}

.iphone .rectangle {
  top: 169px;
  background-color: #d9d9d9;
  position: absolute;
  left: calc(50.00% - 158px);
  width: 317px;
  height: 64px;
  border-radius: 7px;
}

.iphone .div {
  top: 253px;
  background-color: #d9d9d9;
  position: absolute;
  left: calc(50.00% - 158px);
  width: 317px;
  height: 64px;
  border-radius: 7px;
}

.iphone .rectangle-2 {
  top: 337px;
  background-color: #d9d9d9;
  position: absolute;
  left: calc(50.00% - 158px);
  width: 317px;
  height: 64px;
  border-radius: 7px;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 421px;
  left: calc(50.00% - 158px);
  width: 317px;
  height: 64px;
  background-color: #d9d9d9;
  border-radius: 7px;
}

.iphone .rectangle-4 {
  top: 505px;
  background-color: #d9d9d9;
  position: absolute;
  left: calc(50.00% - 158px);
  width: 317px;
  height: 64px;
  border-radius: 7px;
}

.iphone .rectangle-5 {
  top: 652px;
  background-color: #ba2929;
  position: absolute;
  left: calc(50.00% - 158px);
  width: 317px;
  height: 64px;
  border-radius: 7px;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 85px;
  left: 38px;
  width: 317px;
  height: 65px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.59;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #292525;
  font-size: 24px;
  text-align: center;
  letter-spacing: 1.68px;
  line-height: 33.6px;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 168px;
  left: 38px;
  width: 317px;
  height: 65px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.59;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #292525;
  font-size: 24px;
  text-align: center;
  letter-spacing: 1.68px;
  line-height: 33.6px;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 251px;
  left: 38px;
  width: 317px;
  height: 65px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.59;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #292525;
  font-size: 24px;
  text-align: center;
  letter-spacing: 1.68px;
  line-height: 33.6px;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 334px;
  left: 38px;
  width: 317px;
  height: 65px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.59;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #292525;
  font-size: 24px;
  text-align: center;
  letter-spacing: 1.68px;
  line-height: 33.6px;
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 417px;
  left: 38px;
  width: 317px;
  height: 65px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.59;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #292525;
  font-size: 24px;
  text-align: center;
  letter-spacing: 1.68px;
  line-height: 33.6px;
}

.iphone .text-wrapper-7 {
  position: absolute;
  top: 501px;
  left: 38px;
  width: 317px;
  height: 65px;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0.59;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #292525;
  font-size: 24px;
  text-align: center;
  letter-spacing: 1.68px;
  line-height: 33.6px;
}

.iphone .text-wrapper-8 {
  position: absolute;
  top: 639px;
  left: 38px;
  width: 317px;
  height: 90px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Jomhuria-Regular", Helvetica;
  font-weight: 400;
  color: #292525;
  font-size: 64px;
  text-align: center;
  letter-spacing: 4.48px;
  line-height: 89.6px;
}
thank you:
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <div class="div">
        <img class="pexels-gradienta" src="img/pexels-gradienta-7130475-1.png" />
        <div class="text-wrapper">REGISTER</div>
      </div>
      <img class="image" src="img/image-5.png" />
      <img class="IMG" src="img/IMG-0280-1.png" />
      <div class="text-wrapper-2">THANK YOU</div>
      <p class="p">we are eagerly waiting for your participation in the sports meet</p>
      <div class="rectangle"></div>
      <div class="text-wrapper-3">contact us :</div>
      <div class="text-wrapper-4">email : auroranight @gmail.com</div>
      <div class="text-wrapper-5">phone no. 987654321 /987634567</div>
    </div>
  </body>
</html>
.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone .div {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  background-color: #ffffff;
}

.iphone .pexels-gradienta {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 582px;
  left: 38px;
  width: 317px;
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Jomhuria-Regular", Helvetica;
  font-weight: 400;
  color: #292525;
  font-size: 64px;
  text-align: center;
  letter-spacing: 4.48px;
  line-height: 89.6px;
  white-space: nowrap;
}

.iphone .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 1.55;
  object-fit: cover;
}

.iphone .IMG {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 127px;
  aspect-ratio: 3.33;
  object-fit: cover;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 211px;
  left: calc(50.00% - 168px);
  width: 334px;
  height: 142px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-shadow: 0px 4px 4px #00000040;
  -webkit-text-stroke: 1px #fffbfb;
  font-family: "Inria Serif-Bold", Helvetica;
  font-weight: 700;
  color: #120efe;
  font-size: 48px;
  text-align: center;
  letter-spacing: 3.36px;
  line-height: 67.2px;
}

.iphone .p {
  position: absolute;
  top: 300px;
  left: calc(50.00% - 168px);
  width: 334px;
  height: 142px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-shadow: 0px 4px 4px #00000040;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Inknut Antiqua-Bold", Helvetica;
  font-weight: 700;
  color: #0b0b0b;
  font-size: 20px;
  text-align: center;
  letter-spacing: 1.40px;
  line-height: 28.0px;
}

.iphone .rectangle {
  position: absolute;
  top: 633px;
  left: 0;
  width: 398px;
  height: 219px;
  background-color: #000000;
  opacity: 0.56;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 659px;
  left: -11px;
  width: 235px;
  height: 29px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Madimi One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  text-align: center;
  letter-spacing: 2.24px;
  line-height: 44.8px;
  white-space: nowrap;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 714px;
  left: 0;
  width: 375px;
  height: 29px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Madimi One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  text-align: center;
  letter-spacing: 1.40px;
  line-height: 28.0px;
  white-space: nowrap;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 769px;
  left: 9px;
  width: 375px;
  height: 29px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Madimi One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  text-align: center;
  letter-spacing: 1.40px;
  line-height: 28.0px;
  white-space: nowrap;
}
## OUTPUT:


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
