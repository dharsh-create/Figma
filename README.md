# Ex09 Event Registration Web Application

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
### Index.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <div class="div">
        <img class="image" src="img/image-2.png" />
        <div class="overlap-group">
          <img class="img" src="img/image-3.png" />
          <p class="text-wrapper">THIS WILL REDIRECT YOU TO GMAPS</p>
          <p class="p">WE ARE EAGER TO SEE YOU AT THE VENUE</p>
          <p class="FACING-TROUBLE">
            <span class="span">FACING TROUBLE ? </span> <span class="text-wrapper-2">CONTACT US</span>
          </p>
        </div>
        <div class="overlap">
          <img class="tick" src="img/tick-1.png" />
          <div class="text-wrapper-3">YOU’RE REGISTERED SUCCESSFULLY</div>
        </div>
        <p class="ALL-DETAILS-HAVE">ALL DETAILS HAVE BEEN SENT TO THE <br />REGISTERED EMAIL-ID</p>
        <div class="text-wrapper-4">REGISTRATION SUCCESSFUL</div>
      </div>
    </div>
  </body>
</html>
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <div class="div">
        <img class="image" src="img/image-2.png" />
        <div class="text-wrapper">LIST OF EVENTS</div>
        <div class="BADMINTON-CRICKET">
          ➡️&nbsp;&nbsp;BADMINTON<br />➡️&nbsp;&nbsp;CRICKET<br />➡️&nbsp;&nbsp;VOLLEY BALL<br />➡️&nbsp;&nbsp;ATHLETICS<br />➡️&nbsp;&nbsp;HAND
          BALL<br />➡️&nbsp;&nbsp;HACKATHON<br />➡️&nbsp;&nbsp;PAPER PRESENTATION<br />➡️&nbsp;&nbsp;WORKSHOPS
        </div>
        <div class="overlap-group">
          <p class="CONTACT-US">
            <span class="span"><br /></span> <span class="text-wrapper-2">CONTACT US</span>
          </p>
          <div class="text-wrapper-3">FUN GUARANTEED EVENTS</div>
        </div>
        <div class="text-wrapper-4">CLICK TO REDIRECT ✔️</div>
      </div>
    </div>
  </body>
</html>
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <div class="div">
        <img class="image" src="img/image-1.png" />
        <div class="text-wrapper">LOGIN / SIGN UP</div>
        <div class="EMAIL-ID-PASSWORD">EMAIL ID&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :<br />PASSWORD&nbsp;&nbsp;:</div>
        <div class="rectangle"></div>
        <div class="rectangle-2"></div>
        <p class="FACING-TROUBLE">
          <span class="span">FACING TROUBLE ?<br /></span> <span class="text-wrapper-2">CONTACT US</span>
        </p>
        <div class="overlap-group">
          <div class="rectangle-3"></div>
          <div class="rectangle-4"></div>
          <div class="text-wrapper-3">SUBMIT</div>
        </div>
      </div>
    </div>
  </body>
</html>
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <div class="div">
        <img class="image" src="img/image-2.png" />
        <div class="text-wrapper">PERSONAL DETAILS</div>
        <p class="FULL-NAME-GENDER-AGE">
          FULL NAME&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />GENDER&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          <br />AGE<br />COLLEGE<br />DEPARTMENT<br />MOBILE NO<br />EMAIL ID
        </p>
        <div class="overlap">
          <p class="CONTACT-US">
            <span class="span"><br /></span> <span class="text-wrapper-2">CONTACT US</span>
          </p>
          <div class="rectangle"></div>
          <div class="text-wrapper-3">PROCEED TO PAY</div>
        </div>
        <div class="rectangle-2"></div>
        <div class="rectangle-3"></div>
        <div class="rectangle-4"></div>
        <div class="rectangle-5"></div>
        <div class="rectangle-6"></div>
        <div class="rectangle-7"></div>
        <div class="rectangle-8"></div>
        <div class="text-wrapper-4">PAYMENT GATEWAY</div>
        <img class="download" src="img/download-1.png" />
        <div class="overlap-group"><div class="ellipse"></div></div>
        <img class="img" src="img/download-2.png" />
        <div class="ellipse-2"></div>
      </div>
    </div>
  </body>
</html>
```
### Css
```
.android-compact {
  background-color: transparent;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.android-compact .div {
  overflow: hidden;
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 1) 100%
  );
  width: 412px;
  height: 917px;
  position: relative;
}

.android-compact .image {
  width: 358px;
  height: 96px;
  top: 19px;
  left: 27px;
  position: absolute;
  object-fit: cover;
}

.android-compact .overlap-group {
  position: absolute;
  width: 384px;
  height: 322px;
  top: 600px;
  left: 14px;
}

.android-compact .img {
  width: 257px;
  height: 178px;
  top: 0;
  left: 63px;
  position: absolute;
  object-fit: cover;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 177px;
  left: 22px;
  font-family: "NATS-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .p {
  position: absolute;
  top: 211px;
  left: 0;
  font-family: "NATS-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .FACING-TROUBLE {
  position: absolute;
  top: 271px;
  left: 45px;
  font-family: "NATS-Regular", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .span {
  color: #000000;
}

.android-compact .text-wrapper-2 {
  color: #e3070a;
}

.android-compact .overlap {
  position: absolute;
  width: 330px;
  height: 291px;
  top: 148px;
  left: 41px;
}

.android-compact .tick {
  position: absolute;
  width: 256px;
  height: 256px;
  top: 0;
  left: 31px;
  object-fit: cover;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 240px;
  left: 0;
  font-family: "NATS-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .ALL-DETAILS-HAVE {
  position: absolute;
  top: 463px;
  left: 41px;
  font-family: "NATS-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 123px;
  left: 4px;
  font-family: "Nico Moji-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
```

## OUTPUT:
<img width="1999" height="4451" alt="img" src="https://github.com/user-attachments/assets/9836d98c-11e2-4f12-b7d9-a4843fb68447" />
<img width="1999" height="4451" alt="img3" src="https://github.com/user-attachments/assets/d4cb2e64-f904-4175-8044-234c80386069" />
<img width="1999" height="4451" alt="img2" src="https://github.com/user-attachments/assets/451785d5-b012-4080-8e7a-366f6afee76a" />
<img width="1999" height="4451" alt="img4" src="https://github.com/user-attachments/assets/91e32f32-3345-4faf-8faa-f15db7aafff6" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
