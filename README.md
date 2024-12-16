# Ex09 Event Registration Web Application
# Date:
15/12/24
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
~~~
<style>
  .visually-hidden {
    clip: rect(0 0 0 0);
    clip-path: inset(50%);
    height: 1px;
    overflow: hidden;
    position: absolute;
    white-space: nowrap;
    width: 1px;
  }

  .celebration-container {
    border-radius: 50px;
    background-color: #fff;
    display: flex;
    max-width: 652px;
    flex-direction: column;
    overflow: hidden;
    color: #fff;
    font: 400 45px Henny Penny, sans-serif;
  }

  .content-wrapper {
    display: flex;
    flex-direction: column;
    position: relative;
    min-height: 917px;
    width: 100%;
    align-items: center;
    padding: 58px 46px 192px;
  }

  .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }

  .banner-image {
    aspect-ratio: 4.95;
    object-fit: contain;
    object-position: center;
    width: 100%;
    align-self: stretch;
  }

  .festival-title {
    position: relative;
    color: #F0B96C;
    margin-top: 58px;
    font: 110px Italianno, sans-serif;
    border: 1px solid #000;
  }

  .event-button {
    position: relative;
    border-radius: 30px;
    background-color: rgba(0, 0, 0, 0.9);
    margin-top: 141px;
    width: 360px;
    max-width: 100%;
    white-space: nowrap;
    padding: 15px 70px;
    border: 5px solid #000;
    cursor: pointer;
  }

  .registration-button {
    position: relative;
    border-radius: 30px;
    background-color: rgba(0, 0, 0, 0.85);
    width: 350px;
    max-width: 100%;
    white-space: nowrap;
    margin: 39px 0 -38px;
    padding: 10px 35px;
    border: 5px solid #000;
    cursor: pointer;
  }

  @media (max-width: 991px) {
    .celebration-container {
      font-size: 40px;
    }

    .content-wrapper {
      max-width: 100%;
      font-size: 40px;
      padding: 0 20px 100px;
    }

    .banner-image {
      max-width: 100%;
    }

    .festival-title {
      max-width: 100%;
      margin-top: 40px;
      font-size: 40px;
    }

    .event-button {
      font-size: 40px;
      margin-top: 40px;
      white-space: initial;
      padding: 0 20px;
    }

    .registration-button {
      font-size: 40px;
      margin-bottom: 10px;
      white-space: initial;
      padding: 0 20px;
    }
  }
</style>

<div class="celebration-container">
  <div class="content-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/2d1ef81b825a4c899b270a450057bd17/f63da8d3f7ea94074aac1095a578874b783414b42ac2f9ea52c8aceb7a5fe92c?apiKey=2d1ef81b825a4c899b270a450057bd17&"
      class="background-image"
      alt="Diwali celebration background"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/2d1ef81b825a4c899b270a450057bd17/e6eaea621991f045e2785af08aa97bca9a5b431a879a388f473685e3e2643cf2?apiKey=2d1ef81b825a4c899b270a450057bd17&"
      class="banner-image"
      alt="Diwali festival banner"
    />
    <h1 class="festival-title">Happy Diwali</h1>
    <button class="event-button" tabindex="0">Events</button>
    <button class="registration-button" tabindex="0">Registrations</button>
  </div>
</div>
.container--0- {
  position: absolute;
  left: -288px;
  top: -356px;
  width: 652px;
  height: 917px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
  border-radius: 50px;
  border-top-left-radius: 50px;
  border-top-right-radius: 50px;
  border-bottom-left-radius: 50px;
  border-bottom-right-radius: 50px;
}
.text-0-1-3 {
  width: 132px;
  height: 80px;
  color: #ffffff;
  font-size: 45px;
  font-family: Henny Penny, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-4 {
  width: 512px;
  height: 218px;
  color: #f0b96c;
  border-width: 1px;
  border-style: solid;
  border-color: #000000;
  box-shadow: 0px 4px 4px 0 #000000;
  font-size: 110px;
  font-family: Italianno, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-7 {
  width: 280px;
  height: 80px;
  color: #ffffff;
  border-width: 1px;
  border-style: solid;
  border-color: #000000;
  font-size: 45px;
  font-family: Henny Penny, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
<style>
.events-card {
  border-radius: 50px;
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  max-width: 652px;
  flex-direction: column;
  overflow: hidden;
}

.events-container {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 917px;
  align-items: flex-start;
  gap: 12px;
  flex-wrap: wrap;
  padding: 55px 65px 347px;
}

.events-background {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.icon-list {
  position: relative;
  align-self: end;
  display: flex;
  margin-top: 225px;
  flex-direction: column;
}

.event-icon {
  aspect-ratio: 1.04;
  object-fit: contain;
  object-position: center;
  width: 47px;
}

.event-icon-spacing {
  margin-top: 15px;
}

.event-icon-alt {
  margin-top: 17px;
}

.content-wrapper {
  position: relative;
  align-self: start;
  display: flex;
  flex-direction: column;
  color: rgba(255, 255, 255, 1);
  font-weight: 400;
  flex: 1 0 auto;
  width: fit-content;
}

.events-title {
  align-self: end;
  font: 75px Lakki Reddy, sans-serif;
}

.events-list {
  margin-top: 95px;
  font: 50px Lacquer, sans-serif;
}

@media (max-width: 991px) {
  .events-container {
    padding: 0 20px 100px;
  }
  
  .icon-list {
    margin-top: 40px;
  }
  
  .events-title {
    font-size: 40px;
  }
  
  .events-list {
    font-size: 40px;
    margin: 40px 6px 0 0;
  }
}
</style>

<div class="events-card">
  <div class="events-container">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/2d1ef81b825a4c899b270a450057bd17/985c3a6529c28ee8d79b18b6db83ff664adfe0449079b1902e668a20bd83e8a9?apiKey=2d1ef81b825a4c899b270a450057bd17&"
      class="events-background"
      alt="Events background image"
    />
    <div class="icon-list">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/2d1ef81b825a4c899b270a450057bd17/28f456d09e110dec9085ec5fd9462c6338f23006d31ede5b5d63919e73247c93?apiKey=2d1ef81b825a4c899b270a450057bd17&"
        class="event-icon"
        alt="Contest event icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/2d1ef81b825a4c899b270a450057bd17/28f456d09e110dec9085ec5fd9462c6338f23006d31ede5b5d63919e73247c93?apiKey=2d1ef81b825a4c899b270a450057bd17&"
        class="event-icon event-icon-alt"
        alt="Essay writing event icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/2d1ef81b825a4c899b270a450057bd17/28f456d09e110dec9085ec5fd9462c6338f23006d31ede5b5d63919e73247c93?apiKey=2d1ef81b825a4c899b270a450057bd17&"
        class="event-icon event-icon-spacing"
        alt="Rangoli event icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/2d1ef81b825a4c899b270a450057bd17/28f456d09e110dec9085ec5fd9462c6338f23006d31ede5b5d63919e73247c93?apiKey=2d1ef81b825a4c899b270a450057bd17&"
        class="event-icon event-icon-spacing"
        alt="Decorations event icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/2d1ef81b825a4c899b270a450057bd17/28f456d09e110dec9085ec5fd9462c6338f23006d31ede5b5d63919e73247c93?apiKey=2d1ef81b825a4c899b270a450057bd17&"
        class="event-icon event-icon-spacing"
        alt="DJ event icon"
      />
    </div>
    <div class="content-wrapper">
      <h2 class="events-title">Events</h2>
      <div class="events-list">
        contest
        <br />
        Essay Writing
        <br />
        Rangoli
        <br />
        Decorations
        <br />
        DJ
      </div>
    </div>
  </div>
</div>
<style>
.registration-container {
  border-radius: 50px;
  background-color: #fff;
  display: flex;
  max-width: 652px;
  flex-direction: column;
  overflow: hidden;
  color: #fff;
  font: 400 25px Luxurious Roman, sans-serif;
}

.registration-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 917px;
  width: 100%;
  align-items: start;
  padding: 73px 80px 119px;
}

.registration-bg {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.registration-title {
  position: relative;
  font-size: 55px;
  align-self: center;
}

.form-field {
  position: relative;
  background-color: rgba(0, 0, 0, 0.75);
  width: 299px;
  max-width: 100%;
  padding: 12px 22px;
}

.field-name {
  margin-top: 79px;
  font-size: 35px;
}

.field-regid {
  margin-top: 19px;
}

.field-department {
  margin-top: 19px;
}

.field-event {
  margin-top: 19px;
}

.submit-button {
  position: relative;
  border-radius: 25px;
  align-self: center;
  width: 284px;
  max-width: 100%;
  margin: 162px 0 -24px 11px;
  padding: 18px 56px;
  font: 40px Macondo, sans-serif;
  border: 1px solid #000;
  background: transparent;
  color: #fff;
  cursor: pointer;
}

@media (max-width: 991px) {
  .registration-wrapper {
    max-width: 100%;
    padding: 0 20px 100px;
  }

  .registration-title {
    max-width: 100%;
    font-size: 40px;
  }

  .field-name {
    margin-top: 40px;
  }

  .form-field {
    padding: 10px 20px;
  }

  .submit-button {
    margin: 40px 0 10px;
    padding: 15px 20px;
  }
}
</style>

<div class="registration-container">
  <form class="registration-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/2d1ef81b825a4c899b270a450057bd17/5477389af41e7fa5f3c85425d10921788f1bdc4d62ee16565a3ac532f64ff22f?apiKey=2d1ef81b825a4c899b270a450057bd17&"
      class="registration-bg"
      alt=""
    />
    <h1 class="registration-title">
      Event registration
      <br />
      form
    </h1>

    <div class="form-field field-name">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" aria-label="Enter your name">
    </div>

    <div class="form-field field-regid">
      <label for="regid">Reg Id:</label>
      <input type="text" id="regid" name="regid" aria-label="Enter your registration ID">
    </div>

    <div class="form-field field-department">
      <label for="department">Department:</label>
      <input type="text" id="department" name="department" aria-label="Enter your department">
    </div>

    <div class="form-field field-event">
      <label for="event">Event:</label>
      <input type="text" id="event" name="event" aria-label="Enter event name">
    </div>

    <button type="submit" class="submit-button">REGISTER</button>
  </form>
</div>
<style>
  .celebration-section {
    border-radius: 50px;
    background-color: rgba(255, 255, 255, 1);
    display: flex;
    max-width: 652px;
    flex-direction: column;
    overflow: hidden;
    font-family: Mansalva, sans-serif;
    color: rgba(255, 255, 255, 1);
    font-weight: 400;
  }

  .celebration-content {
    display: flex;
    flex-direction: column;
    position: relative;
    min-height: 917px;
    width: 100%;
    padding: 135px 80px 472px;
  }

  .celebration-background {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }

  .celebration-title {
    position: relative;
    font-size: 80px;
    align-self: center;
  }

  .celebration-message {
    position: relative;
    font-size: 45px;
    align-self: end;
    margin: 89px 0 -94px;
  }

  @media (max-width: 991px) {
    .celebration-content {
      max-width: 100%;
      padding: 100px 20px;
    }

    .celebration-title {
      font-size: 40px;
    }

    .celebration-message {
      max-width: 100%;
      font-size: 40px;
      margin: 40px 0 10px;
    }
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

<div class="celebration-section">
  <div class="celebration-content">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/2d1ef81b825a4c899b270a450057bd17/95b19f10bce43987dcd46ddd68a8ca8dae1f66ef32cb6e569b7fe261240df8e9?apiKey=2d1ef81b825a4c899b270a450057bd17&"
      class="celebration-background"
      alt="Diwali celebration background"
    />
    <h1 class="celebration-title">Thank You</h1>
    <p class="celebration-message">
      We are eagerly waiting
      <br />
      for your participation
      <br />
      in the Diwali celebration.
    </p>
  </div>
</div>
~~~
# OUTPUT:

![Screenshot 2024-12-14 235820](https://github.com/user-attachments/assets/7001a712-04b3-4cc1-a413-a1b67eda43a3)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
