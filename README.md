# Ex09 Event Registration Web Application
# Date: 25/11/2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:

# HOME PAGE:
    <style>
    .event-container {
    background-color: #fff;
    display: flex;
    max-width: 480px;
    width: 100%;
    flex-direction: column;
    overflow: hidden;
    color: #fff;
    text-align: center;
    margin: 0 auto;
    font: 400 40px Gorditas, sans-serif;
    }

    .header-logo {
    aspect-ratio: 6.71;
    object-fit: contain;
    object-position: center;
    width: 100%;
    margin: 5px 0 0;
    }

    .main-content {
    display: flex;
    flex-direction: column;
    position: relative;
    aspect-ratio: 0.497;
    width: 100%;
    padding: 64px 0;
    }

    .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
    }

    .event-title {
    position: relative;
    color: #f5eaea;
    align-self: start;
    font: 60px JejuHallasan, sans-serif;
    }

    .event-hero {
    aspect-ratio: 1.36;
    object-fit: contain;
    object-position: center;
    width: 100%;
    margin: 65px 0 0;
    }

    .nav-button {
    position: relative;
    width: 100%;
    border-radius: 30px;
    background-color: #d9d9d9;
    align-self: center;
    max-width: 319px;
    white-space: nowrap;
    cursor: pointer;
    }

    .events-button {
    composes: nav-button;
    margin: 123px 0 0;
    padding: 4px 70px 30px;
    }

    .register-button {
    composes: nav-button;
    margin: 28px 0 0;
    padding: 11px 56px 23px;
    }

    .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    }
    </style>

    <div class="event-container">
    <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/54dde1fb9ecb47c8aaa45d131af83a70/826d819d795ea8579e317b00f0a8426af414714b6d6eac34e963fcfd96713e5c?apiKey=54dde1fb9ecb47c8aaa45d131af83a70&"
        class="header-logo"
        alt="Drestein event header logo"
    />
    <div class="main-content">
        <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/54dde1fb9ecb47c8aaa45d131af83a70/9e9734338e6a57f7d2997366ee12cdfef71c261289c8ca2178ea98d5a40ca128?apiKey=54dde1fb9ecb47c8aaa45d131af83a70&"
        class="background-image"
        alt=""
        />
        <h1 class="event-title">DRESTEIN -25</h1>
        <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/54dde1fb9ecb47c8aaa45d131af83a70/3cbdf0a1a1094a5975553df9ee91761aebaa0feceb017f340bf982ccd0472633?apiKey=54dde1fb9ecb47c8aaa45d131af83a70&"
        class="event-hero"
        alt="Drestein event hero image"
        />
        <button class="events-button" tabindex="0">
        EVENTS
        </button>
        <button class="register-button" tabindex="0">
        REGISTER
        </button>
    </div>
    </div>

# EVENTS PAGE:

    <style>
    .events-container {
    background-color: #fff;
    display: flex;
    max-width: 480px;
    width: 100%;
    padding: 12px 0 0;
    flex-direction: column;
    overflow: hidden;
    color: #fff;
    text-align: center;
    margin: 0 auto;
    font: 400 35px Gorditas, sans-serif;
    }

    .header-image {
    aspect-ratio: 6.71;
    object-fit: contain;
    object-position: center;
    width: 100%;
    }

    .content-wrapper {
    display: flex;
    flex-direction: column;
    position: relative;
    aspect-ratio: 0.501;
    width: 100%;
    padding: 61px 48px 111px;
    }

    .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
    }

    .events-title {
    position: relative;
    color: #f5eaea;
    align-self: center;
    font: 60px JejuHallasan, sans-serif;
    }

    .event-category {
    position: relative;
    border-radius: 30px;
    background-color: #d9d9d9;
    margin-top: 57px;
    padding: 11px 28px 27px;
    white-space: nowrap;
    }

    .event-category:first-of-type {
    margin-top: 43px;
    }

    .event-category:last-child {
    margin: 57px 0 -22px;
    padding: 8px 60px 30px;
    }
    </style>

    <div class="events-container">
    <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/54dde1fb9ecb47c8aaa45d131af83a70/826d819d795ea8579e317b00f0a8426af414714b6d6eac34e963fcfd96713e5c?apiKey=54dde1fb9ecb47c8aaa45d131af83a70&"
        class="header-image"
        alt="Events section header decoration"
    />
    <div class="content-wrapper">
        <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/54dde1fb9ecb47c8aaa45d131af83a70/9fe183db714935ee3633530f708f284897d0703cba5f9e32993c6a32915402f1?apiKey=54dde1fb9ecb47c8aaa45d131af83a70&"
        class="background-image"
        alt="Events section background"
        />
        <div class="events-title">EVENTS</div>
        <div class="event-category" tabindex="0">
        WEB HACKING
        <br />
        </div>
        <div class="event-category" tabindex="0">
        DRONE
        <br />
        </div>
        <div class="event-category" tabindex="0">
        CYBERSECURITY
        <br />
        </div>
        <div class="event-category" tabindex="0">
        PC-HARDWARE
        <br />
        </div>
        <div class="event-category" tabindex="0">
        FORENSICS
        <br />
        </div>
    </div>
    </div>
# REGISTRATION PAGE:
    <style>
    .registration-container {
    background-color: #fff;
    display: flex;
    max-width: 480px;
    width: 100%;
    padding: 12px 0 0;
    flex-direction: column;
    overflow: hidden;
    color: #fff;
    text-align: center;
    margin: 0 auto;
    font: 400 35px Gorditas, sans-serif;
    }

    .header-image {
    aspect-ratio: 6.71;
    object-fit: contain;
    object-position: center;
    width: 100%;
    }

    .form-wrapper {
    display: flex;
    flex-direction: column;
    position: relative;
    aspect-ratio: 0.501;
    width: 100%;
    padding: 61px 41px 115px;
    }

    .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
    }

    .form-title {
    position: relative;
    color: #f5eaea;
    align-self: center;
    font: 60px JejuHallasan, sans-serif;
    }

    .form-field {
    position: relative;
    border-radius: 30px;
    background-color: #d9d9d9;
    margin: 40px 0;
    padding: 15px 65px 24px;
    color: #fff;
    }

    .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
    }
    </style>

    <form class="registration-container" role="form">
    <img 
        src="https://cdn.builder.io/api/v1/image/assets/54dde1fb9ecb47c8aaa45d131af83a70/826d819d795ea8579e317b00f0a8426af414714b6d6eac34e963fcfd96713e5c?apiKey=54dde1fb9ecb47c8aaa45d131af83a70&" 
        alt="" 
        class="header-image"
    />
    <div class="form-wrapper">
        <img
        src="https://cdn.builder.io/api/v1/image/assets/54dde1fb9ecb47c8aaa45d131af83a70/9fe183db714935ee3633530f708f284897d0703cba5f9e32993c6a32915402f1?apiKey=54dde1fb9ecb47c8aaa45d131af83a70&"
        alt=""
        class="background-image"
        />
        <h1 class="form-title">REGISTER</h1>
        
        <label for="fullName" class="visually-hidden">Full Name</label>
        <input 
        type="text" 
        id="fullName" 
        class="form-field" 
        placeholder="FULL NAME"
        required
        />

        <label for="gender" class="visually-hidden">Gender</label>
        <select id="gender" class="form-field" required>
        <option value="">GENDER</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
        </select>

        <label for="department" class="visually-hidden">Department</label>
        <select id="department" class="form-field" required>
        <option value="">DEPARTMENT</option>
        </select>

        <label for="registerId" class="visually-hidden">Register ID</label>
        <input 
        type="text" 
        id="registerId" 
        class="form-field" 
        placeholder="REGISTER - ID"
        required
        />

        <label for="event" class="visually-hidden">Event</label>
        <select id="event" class="form-field" required>
        <option value="">EVENT</option>
        </select>
    </div>
    </form>

# CONTACT PAGE:
    <div class="thank-you-container">
    <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/54dde1fb9ecb47c8aaa45d131af83a70/826d819d795ea8579e317b00f0a8426af414714b6d6eac34e963fcfd96713e5c?apiKey=54dde1fb9ecb47c8aaa45d131af83a70&"
        class="header-image"
        alt=""
    />
    <div class="content-wrapper">
        <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/54dde1fb9ecb47c8aaa45d131af83a70/9e9734338e6a57f7d2997366ee12cdfef71c261289c8ca2178ea98d5a40ca128?apiKey=54dde1fb9ecb47c8aaa45d131af83a70&"
        class="background-image"
        alt=""
        />
        <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/54dde1fb9ecb47c8aaa45d131af83a70/db703c231e5aafd4436a660f35a930a5bc1d7ec863d2d17b0723b1300e6dacf8?apiKey=54dde1fb9ecb47c8aaa45d131af83a70&"
        class="main-image"
        alt=""
        />
        <div class="thank-you-text" tabindex="0">THANK YOU !!</div>
    </div>
    </div>

    <style>
    .thank-you-container {
    background-color: #fff;
    display: flex;
    max-width: 480px;
    width: 100%;
    flex-direction: column;
    overflow: hidden;
    color: #fff;
    text-align: center;
    margin: 0 auto;
    font: 700 35px Gorditas, sans-serif;
    }

    .header-image {
    aspect-ratio: 6.71;
    object-fit: contain;
    object-position: center;
    width: 100%;
    margin-top: 5px;
    }

    .content-wrapper {
    display: flex;
    flex-direction: column;
    position: relative;
    aspect-ratio: 0.497;
    width: 100%;
    padding: 50px 0 188px;
    }

    .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
    }

    .main-image {
    aspect-ratio: 0.91;
    object-fit: contain;
    object-position: center;
    width: 100%;
    }

    .thank-you-text {
    position: relative;
    align-self: center;
    margin: 102px 0 -38px;
    }

    .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border: 0;
    }
    </style>
# OUTPUT:

!['Result'](IMAGE.png)
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
