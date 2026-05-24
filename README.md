# Ex09 Event Registration Web Application
## Date:24-2-26

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
FRAME 1:
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="initial-scale=1, width=device-width" />

    <link rel="stylesheet" href="./global.css" />
    <link rel="stylesheet" href="./index.css" />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@1,100;1,800&display=swap"
    />
  </head>
  <body>
    <div class="dashboard">
      <section class="logo">
        <img class="logo-icon" alt="" src="./public/logo@2x.png" />
      </section>
      <section class="tech-symposium-2026">
        <i class="tech-symposium-20262">
          TECH<br />
          SYMPOSIUM <br />
          2026</i
        >
      </section>
      <div class="dashboard-inner">
        <div class="frame-child"></div>
      </div>
      <div class="lap-1">
        <img
          class="lap-1-icon"
          loading="lazy"
          alt=""
          src="./public/LAP-1@2x.png"
        />
      </div>
      <div class="dashboard-child">
        <div class="frame-item"></div>
      </div>
      <section class="login-section">
        <div class="login-to-continue">
          <h2 class="login-to-continue2">LOGIN TO CONTINUE</h2>
        </div>
        <div class="frame">
          <div class="frame2">
            <div class="text">
              <h2 class="username-label"></h2>
            </div>
            <button class="login">LOGIN</button>
          </div>
        </div>
        <button class="register-area">
          <h2 class="register">REGISTER</h2>
        </button>
      </section>
    </div>
  </body>
</html>

.dashboard,
.logo {
  display: flex;
  box-sizing: border-box;
}
.dashboard {
  width: 100%;
  position: relative;
  background-color: var(--color-midnightblue);
  flex-direction: column;
  align-items: center;
  padding: var(--padding-36) var(--padding-15) 60px;
  gap: 16.5px;
  line-height: normal;
  letter-spacing: normal;
}
.logo {
  align-self: stretch;
  align-items: flex-start;
  padding: var(--padding-0) var(--padding-0) 34.5px var(--padding-1);
  max-width: 100%;
}
.logo-icon {
  height: 59px;
  flex: 1;
  position: relative;
  max-width: 100%;
  overflow: hidden;
  object-fit: cover;
}
.tech-symposium-2026 {
  align-self: stretch;
  display: flex;
  align-items: flex-start;
  padding: var(--padding-0) 72px var(--padding-0) var(--padding-4);
  text-align: left;
  font-size: 38px;
  color: var(--color-white);
  font-family: var(--font-inter);
}
.tech-symposium-20262 {
  flex: 1;
  position: relative;
  font-weight: 800;
  white-space: pre-wrap;
  flex-shrink: 0;
}
.dashboard-inner {
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: center;
  padding: var(--padding-0) var(--padding-0) 23px;
  max-width: 351px;
}
.dashboard-inner,
.frame-child,
.lap-1 {
  box-sizing: border-box;
}
.frame-child {
  height: var(--height-1);
  flex: 1;
  position: relative;
  border-top: 1px solid var(--color-white);
  transform: rotate(0.3deg);
  max-width: 100%;
}
.lap-1 {
  width: 252px;
  display: flex;
  align-items: flex-start;
  padding: var(--padding-0) 2px var(--padding-36) var(--padding-0);
}
.lap-1-icon {
  width: 250px;
  position: relative;
  max-height: 100%;
  object-fit: cover;
}
.dashboard-child {
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: flex-end;
  padding: var(--padding-0) var(--padding-0) var(--padding-0) 6px;
  box-sizing: border-box;
  max-width: 350.8px;
}
.frame-item {
  height: var(--height-1);
  flex: 1;
  position: relative;
  border-top: 1px solid var(--color-white);
  box-sizing: border-box;
  transform: rotate(-0.3deg);
  max-width: 100%;
}
.login-section {
  align-self: stretch;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: var(--padding-19) var(--padding-4) var(--padding-19) 10px;
  gap: 18.1px;
  text-align: left;
  font-size: 25px;
  color: var(--color-white);
  font-family: var(--font-inter);
}
.login-to-continue {
  width: 100%;
  display: flex;
  align-items: flex-start;
  padding: var(--padding-0) var(--padding-0) 8.9px;
  box-sizing: border-box;
  max-width: 262.9px;
}
.login-to-continue2 {
  margin: 0;
  flex: 1;
  position: relative;
  font-size: inherit;
  font-style: italic;
  font-weight: 100;
  font-family: inherit;
}
.frame {
  width: 100%;
  padding: var(--padding-0) var(--padding-0) var(--padding-0) var(--padding-1);
  max-width: 262.9px;
  top: 0;
  z-index: 99;
  position: sticky;
  font-size: 38px;
  color: var(--color-black);
}
.frame,
.frame2,
.text {
  display: flex;
  align-items: flex-start;
  box-sizing: border-box;
}
.frame2 {
  height: 77.9px;
  flex: 1;
  background-color: var(--color-darkgray);
  padding: 21px 33px var(--padding-0);
  gap: 32px;
}
.text {
  height: 56.9px;
  padding: 10.9px var(--padding-0) var(--padding-0);
}
.username-label {
  margin: 0;
  height: 46px;
  width: 0;
  position: relative;
  font-size: inherit;
  display: inline-block;
  font-style: italic;
  font-weight: 800;
  font-family: inherit;
  white-space: pre-wrap;
}
.login,
.register-area {
  cursor: pointer;
  border: 0;
}
.login {
  padding: 0;
  background-color: transparent;
  position: relative;
  font-size: 38px;
  display: inline-block;
  font-style: italic;
  font-weight: 800;
  font-family: var(--font-inter);
  color: var(--color-black);
  text-align: left;
}
.register-area {
  padding: 14px 25px var(--padding-15);
  background-color: var(--color-gainsboro);
  width: 100%;
  display: flex;
  align-items: center;
  box-sizing: border-box;
  max-width: 258px;
}
.register-area:hover {
  background-color: var(--color-silver);
}
.register {
  margin: 0;
  position: relative;
  font-size: 38px;
  font-style: italic;
  font-weight: 800;
  font-family: var(--font-inter);
  color: var(--color-black);
  text-align: left;
}
@media screen and (max-width: 395px) {
  .tech-symposium-2026 {
    padding-right: 20px;
    box-sizing: border-box;
  }
}
@media screen and (max-width: 254px) {
  .lap-1 {
    max-width: calc(100% - 2px);
  }
}

FRAME 2:
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="initial-scale=1, width=device-width" />

    <link rel="stylesheet" href="./global.css" />
    <link rel="stylesheet" href="./index.css" />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@1,600;1,800&display=swap"
    />
  </head>
  <body>
    <div class="desktop">
      <div class="logo">
        <img class="logo-icon" alt="" src="./public/logo@2x.png" />
      </div>
      <h1 class="event-list">EVENT LIST</h1>
      <section class="event-items-list">
        <div class="frame">
          <button class="frame2">
            <h3 class="presentation">📄PRESENTATION</h3>
          </button>
        </div>
        <button class="frame3">
          <div class="frame4">
            <h3 class="coding-contest">💻CODING CONTEST<br /></h3>
          </div>
        </button>
        <div class="event-items-list-inner">
          <button class="frame-child"></button>
        </div>
        <div class="event-items-list-inner">
          <button class="frame-child"></button>
        </div>
        <button class="frame-child"></button>
      </section>
    </div>
  </body>
</html>


.desktop {
  width: 100%;
  position: relative;
  background-color: var(--color-midnightblue);
  overflow: hidden;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 36px 16px 254px;
  gap: 53px;
  line-height: normal;
  letter-spacing: normal;
  text-align: left;
  font-size: 38px;
  color: var(--color-white);
  font-family: var(--font-inter);
}
.desktop,
.frame2:hover,
.logo {
  box-sizing: border-box;
}
.logo {
  align-self: stretch;
  display: flex;
  align-items: flex-start;
  padding: var(--padding-0) var(--padding-0) 6px;
  max-width: 100%;
}
.logo-icon {
  height: 59px;
  flex: 1;
  position: relative;
  max-width: 100%;
  overflow: hidden;
  object-fit: cover;
}
.event-list {
  margin: 0;
  width: 100%;
  position: relative;
  font-size: inherit;
  display: inline-block;
  font-style: italic;
  font-weight: 800;
  font-family: inherit;
  max-width: 246px;
}
.event-items-list {
  align-self: stretch;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: var(--padding-0) 4px var(--padding-0) 18px;
  gap: 13px;
}
.frame,
.frame2 {
  box-sizing: border-box;
  display: flex;
}
.frame {
  width: 100%;
  align-items: flex-start;
  padding: var(--padding-0) var(--padding-0) var(--padding-2);
  max-width: 273px;
}
.frame2 {
  cursor: pointer;
  border: var(--border-1);
  padding: 27px 20px 9px;
  background-color: var(--color-steelblue-200);
  height: var(--height-70);
  flex: 1;
  box-shadow: var(--shadow-drop);
  align-items: center;
  justify-content: center;
}
.frame2:hover {
  background-color: var(--color-steelblue-100);
  border: 1px solid var(--color-dimgray);
}
.presentation {
  margin: 0;
  flex: 1;
  position: relative;
  font-size: var(--fs-24);
  display: inline-block;
  font-style: italic;
  font-weight: 600;
  font-family: var(--font-inter);
  color: var(--color-gray-300);
  text-align: left;
  max-width: 219px;
}
.frame3,
.frame4 {
  box-shadow: var(--shadow-drop);
  background-color: var(--color-steelblue-200);
  border: var(--border-1);
  box-sizing: border-box;
  display: flex;
  align-items: flex-start;
}
.frame3 {
  cursor: pointer;
  padding: 0;
  width: 100%;
  height: var(--height-72);
  max-width: 273px;
}
.frame4 {
  height: var(--height-70);
  flex: 1;
  padding: 12px 23px 24px;
}
.coding-contest {
  margin: 0;
  position: relative;
  font-size: var(--fs-24);
  font-style: italic;
  font-weight: 600;
  font-family: var(--font-inter);
  color: var(--color-gray-200);
  text-align: left;
  flex-shrink: 0;
}
.event-items-list-inner,
.frame-child {
  width: var(--width-272);
  box-sizing: border-box;
}
.event-items-list-inner {
  height: var(--height-72);
  display: flex;
  align-items: flex-start;
  padding: var(--padding-0) var(--padding-0) var(--padding-2);
}
.frame-child {
  cursor: pointer;
  border: var(--border-1);
  padding: 0;
  background-color: var(--color-steelblue-200);
  height: var(--height-70);
  position: relative;
  box-shadow: var(--shadow-drop);
}


FRAME 3:
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="initial-scale=1, width=device-width" />

    <link rel="stylesheet" href="./global.css" />
    <link rel="stylesheet" href="./index.css" />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@1,500;1,800&display=swap"
    />
  </head>
  <body>
    <div class="phone-view">
      <img class="logo-icon" loading="lazy" alt="" src="./public/logo@2x.png" />

      <section class="image-1">
        <img
          class="image-1-icon"
          loading="lazy"
          alt=""
          src="./public/image-1@2x.png"
        />
      </section>
      <section class="frame">
        <button class="frame-row-0">
          <div class="frame-row-0-child"></div>
          <input class="full-name" placeholder="👤 Full Name" type="text" />
        </button>
        <div class="frame-row-1">
          <div class="frame-row-1-child"></div>
          <input
            class="register-number"
            placeholder="🆔 Register Number"
            type="text"
          />
        </div>
        <div class="frame-row-2">
          <div class="frame-row-2-child"></div>
          <i class="department">🏫 Department </i>
        </div>
        <div class="frame-row-3">
          <div class="frame-row-0-child"></div>
          <h2 class="select-event">📅 Select Event</h2>
        </div>
        <div class="frame-row-4">
          <div class="frame-row-4-child"></div>
          <input
            class="mobile-number"
            placeholder="📞 Mobile Number"
            type="text"
          />
        </div>
        <button class="frame2">
          <h2 class="register-now">REGISTER NOW</h2>
        </button>
      </section>
    </div>
  </body>
</html>


.logo-icon,
.phone-view {
  max-width: 100%;
  overflow: hidden;
}
.phone-view {
  width: 100%;
  background-color: var(--color-midnightblue);
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: var(--padding-36) var(--padding-12) 15px 16px;
  box-sizing: border-box;
  gap: 38px;
  line-height: normal;
  letter-spacing: normal;
}
.logo-icon {
  align-self: stretch;
  position: relative;
  max-height: 100%;
  object-fit: cover;
}
.image-1 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  padding: 0 26px 23px 3px;
  box-sizing: border-box;
  max-width: 348px;
}
.image-1-icon {
  flex: 1;
  position: relative;
  max-width: 100%;
  overflow: hidden;
  max-height: 100%;
  object-fit: cover;
}
.frame {
  align-self: stretch;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 34px 20px var(--padding-36) var(--padding-12);
  gap: 1.6px;
  background-image: url(./public/Frame@3x.png);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: top;
  text-align: left;
  font-size: var(--fs-32);
  color: var(--color-gainsboro-100);
  font-family: var(--font-inter);
}
.frame-row-0 {
  cursor: pointer;
  border: 0;
  padding: 0;
  background-color: transparent;
  width: 100%;
  height: 61px;
  position: relative;
  max-width: var(--max-w-359_8);
}
.frame-row-0-child {
  position: absolute;
  height: 100%;
  top: 0;
  bottom: 0;
  left: 7.9px;
  background-color: var(--color-gainsboro-200);
  width: var(--width-352);
  opacity: var(--opacity-0_2);
}
.full-name {
  border: 0;
  outline: 0;
  display: inline-block;
  font-weight: 500;
  font-family: var(--font-inter);
  font-size: var(--fs-32);
  background-color: transparent;
  position: absolute;
  top: 15px;
  left: 83.9px;
  font-style: italic;
  color: var(--color-white);
  text-align: left;
  padding: 0;
}
.frame-row-1 {
  width: 100%;
  height: 77.8px;
  position: relative;
  max-width: var(--max-w-359_8);
}
.frame-row-1-child {
  position: absolute;
  height: calc(100% - 16.8px);
  top: 8.4px;
  bottom: 8.4px;
  left: 7.9px;
  background-color: var(--color-gainsboro-200);
  width: var(--width-352);
  opacity: var(--opacity-0_2);
}
.register-number {
  border: 0;
  outline: 0;
  display: inline-block;
  font-weight: 500;
  font-family: var(--font-inter);
  font-size: var(--fs-32);
  background-color: transparent;
  position: absolute;
  top: 19.4px;
  left: 48.9px;
  font-style: italic;
  color: var(--color-white);
  text-align: left;
  padding: 0;
}
.frame-row-2 {
  width: 100%;
  height: 93.4px;
  position: relative;
  max-width: var(--max-w-359_8);
}
.frame-row-2-child {
  position: absolute;
  top: 17px;
  left: 7.9px;
  background-color: var(--color-gainsboro-200);
  width: var(--width-352);
  height: 61px;
  opacity: var(--opacity-0_2);
}
.department {
  position: absolute;
  top: 28px;
  left: 59.9px;
  font-weight: 500;
}
.frame-row-3 {
  width: 100%;
  height: 61px;
  position: relative;
  max-width: var(--max-w-359_8);
  color: var(--color-white);
}
.select-event {
  margin: 0;
  position: absolute;
  top: 10px;
  left: 55.9px;
  font-size: inherit;
  font-style: italic;
  font-weight: 500;
  font-family: inherit;
}
.frame-row-4 {
  width: 100%;
  height: 90.8px;
  position: relative;
  max-width: var(--max-w-359_8);
}
.frame-row-4-child {
  position: absolute;
  top: 14.4px;
  left: 7.9px;
  background-color: var(--color-gainsboro-200);
  width: var(--width-352);
  height: 61px;
  opacity: var(--opacity-0_2);
}
.mobile-number {
  border: 0;
  outline: 0;
  display: inline-block;
  font-weight: 500;
  font-family: var(--font-inter);
  font-size: var(--fs-32);
  background-color: transparent;
  position: absolute;
  top: 25.4px;
  left: 48.9px;
  font-style: italic;
  color: var(--color-white);
  text-align: left;
  padding: 0;
}
.frame2 {
  cursor: pointer;
  border: 0;
  padding: 27px 0 13px;
  background-color: var(--color-steelblue-100);
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  box-sizing: border-box;
  max-width: 270px;
}
.frame2:hover {
  background-color: var(--color-steelblue-200);
}
.register-now {
  margin: 0;
  position: relative;
  font-size: var(--fs-32);
  font-style: italic;
  font-weight: 800;
  font-family: var(--font-inter);
  color: var(--color-black);
  text-align: left;
}


body {
  margin: 0;
  line-height: normal;
}

:root {
  /* Common Style Variables */

  /* Color */
  --color-black: #000;
  --color-gainsboro-100: #e6e6e6;
  --color-gainsboro-200: #d9d9d9;
  --color-midnightblue: #040d46;
  --color-steelblue-100: #748fc0;
  --color-steelblue-200: #5c75a6;
  --color-white: #fff;

  /* Padding */
  --padding-12: 12px;
  --padding-36: 36px;

  /* Font */
  --font-inter: Inter;

  /* FontSize */
  --fs-32: 32px;

  /* WidthHeights */
  --max-w-359_8: 359.8px;
  --width-352: 352px;

  /* Opacities */
  --opacity-0_2: 0.2;

  --left-7_9: 7.9px;
}
FRAME 4:
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="initial-scale=1, width=device-width" />

    <link rel="stylesheet" href="./global.css" />
    <link rel="stylesheet" href="./index.css" />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@1,500;1,700&display=swap"
    />
  </head>
  <body>
    <div class="mdulo-de-inicio-onboarding">
      <section class="logo-parent">
        <img class="logo-icon" alt="" src="./public/logo@2x.png" />

        <div class="frame-wrapper">
          <div class="registration-parent">
            <h1 class="registration">REGISTRATION<br /></h1>
            <div class="successful-wrapper">
              <h2 class="registration">SUCCESSFUL</h2>
            </div>
            <div class="image-2-wrapper">
              <img
                class="image-2-icon"
                loading="lazy"
                alt=""
                src="./public/image-2@2x.png"
              />
            </div>
          </div>
        </div>
        <div class="frame-container">
          <div class="rectangle-parent">
            <div class="frame-child"></div>
            <i class="thank-you-for"
              >Thank you for registering<br />for the Tech Symposium 2026.</i
            >
            <div class="get-ready-to-explore-learn-an-wrapper">
              <i class="get-ready-to"
                >Get ready to explore,<br />learn and innovate!</i
              >
            </div>
          </div>
        </div>
      </section>
      <section class="mdulo-de-inicio-onboarding-inner">
        <div class="rectangle-group">
          <div class="frame-item"></div>
          <button class="back-to-home">🏠 BACK TO HOME</button>
        </div>
      </section>
    </div>
  </body>
</html>


.mdulo-de-inicio-onboarding {
  width: 100%;
  position: relative;
  background-color: var(--color-midnightblue);
  overflow: hidden;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  padding: 36px var(--padding-16) 33px;
  box-sizing: border-box;
  gap: 75px;
  line-height: normal;
  letter-spacing: normal;
}
.logo-icon,
.logo-parent {
  align-self: stretch;
  max-width: 100%;
}
.logo-parent {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: var(--padding-0) var(--padding-0) var(--padding-0) var(--padding-1);
  box-sizing: border-box;
  gap: 32.5px;
  text-align: left;
  font-size: var(--fs-32);
  color: var(--color-white);
  font-family: var(--font-inter);
}
.logo-icon {
  position: relative;
  overflow: hidden;
  max-height: 100%;
  object-fit: cover;
}
.frame-wrapper {
  display: flex;
  align-items: flex-start;
  padding: var(--padding-0) 70px;
  box-sizing: border-box;
  max-width: 100%;
}
.registration-parent {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 18px;
}
.registration {
  margin: 0;
  position: relative;
  font-size: inherit;
  font-style: italic;
  font-weight: 500;
  font-family: inherit;
}
.image-2-wrapper,
.successful-wrapper {
  display: flex;
  align-items: flex-start;
  padding: var(--padding-0) var(--padding-11) var(--padding-0) 10px;
}
.image-2-wrapper {
  padding: var(--padding-0) 5px var(--padding-0) 4px;
}
.image-2-icon {
  width: 225px;
  position: relative;
  max-height: 100%;
  object-fit: cover;
}
.frame-container,
.rectangle-parent {
  display: flex;
  align-items: flex-start;
  box-sizing: border-box;
  max-width: 100%;
}
.frame-container {
  padding: var(--padding-0) 2px;
  font-size: 24px;
  color: var(--color-black);
}
.rectangle-parent {
  background-color: var(--color-lightslategray);
  flex-direction: column;
  padding: 14px var(--padding-11) 13px 13px;
  gap: 44px;
}
.frame-child,
.thank-you-for {
  position: relative;
  flex-shrink: 0;
}
.frame-child {
  width: 376px;
  height: 207px;
  background-color: var(--color-lightslategray);
  display: none;
  max-width: 100%;
}
.thank-you-for {
  font-weight: 500;
  z-index: 1;
}
.get-ready-to-explore-learn-an-wrapper {
  display: flex;
  align-items: flex-start;
  padding: var(--padding-0) var(--padding-1) var(--padding-0) var(--padding-16);
  flex-shrink: 0;
  font-size: var(--fs-32);
  color: var(--color-white);
}
.get-ready-to {
  position: relative;
  font-weight: 700;
  z-index: 1;
}
.mdulo-de-inicio-onboarding-inner {
  width: 367px;
  display: flex;
  align-items: flex-start;
  justify-content: flex-end;
  padding: var(--padding-0) 26px;
  box-sizing: border-box;
  max-width: 100%;
}
.rectangle-group {
  height: 102px;
  flex: 1;
  position: relative;
}
.frame-item {
  position: absolute;
  top: 0;
  left: 0;
  background-color: var(--color-gainsboro);
  width: 315px;
  height: 79px;
}
.back-to-home {
  cursor: pointer;
  border: 0;
  padding: 0;
  background-color: transparent;
  position: absolute;
  top: 20px;
  left: 23px;
  font-size: var(--fs-32);
  line-height: 82px;
  display: inline-block;
  font-style: italic;
  font-weight: 700;
  font-family: var(--font-inter);
  color: var(--color-black);
  text-align: left;
  z-index: 1;
}
@media screen and (max-width: 393px) {
  .logo-parent {
    gap: 16px;
  }
}
@media screen and (max-width: 376px) {
  .rectangle-parent {
    gap: 22px;
  }
}
@media screen and (max-width: 374px) {
  .frame-wrapper {
    padding-left: var(--padding-20);
    padding-right: var(--padding-20);
    box-sizing: border-box;
  }
}


body {
  margin: 0;
  line-height: normal;
}

:root {
  /* Common Style Variables */

  /* Color */
  --color-black: #000;
  --color-gainsboro: #d9d9d9;
  --color-lightslategray: #6d8a8f;
  --color-midnightblue: #040d46;
  --color-white: #fff;

  /* Padding */
  --padding-0: 0px;
  --padding-1: 1px;
  --padding-11: 11px;
  --padding-16: 16px;
  --padding-20: 20px;

  /* Font */
  --font-inter: Inter;

  /* FontSize */
  --fs-32: 32px;
}




```
## OUTPUT:
![alt text](<Screenshot 2026-05-24 152344-1.png>) 
![alt text](<Screenshot 2026-05-24 152354-1.png>)
 ![alt text](<Screenshot 2026-05-24 152419-1.png>) 
 ![alt text](<Screenshot 2026-05-24 152401-1.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
