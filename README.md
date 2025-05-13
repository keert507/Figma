# Ex09 Event Registration Web Application
## Date: 13/05/2025

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

HomePage:

<style>
.event-container {
  background-color: rgba(231, 126, 94, 1);
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  margin: 0 auto;
  padding: 60px 0 269px;
}

.banner-image {
  aspect-ratio: 5.71;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.logo-image {
  aspect-ratio: 1.06;
  object-fit: contain;
  object-position: center;
  width: 204px;
  margin-top: 40px;
  max-width: 100%;
}

.event-title {
  margin-top: 33px;
  font: 400 24px Lexend Exa, sans-serif;
}

.title-primary {
  color: rgba(113, 237, 227, 1);
}

.title-secondary {
  color: rgba(97, 229, 218, 1);
}

.title-tertiary {
  color: rgba(93, 246, 233, 1);
}

.action-button {
  background-color: rgba(25, 240, 25, 1);
  font: 400 24px Lalezar, sans-serif;
  color: rgba(252, 18, 18, 1);
  text-align: center;
  width: 150px;
  max-width: 100%;
  white-space: nowrap;
  cursor: pointer;
}

.register-button {
  composes: action-button;
  margin-top: 109px;
  padding: 0 27px;
}

.login-button {
  composes: action-button;
  margin-top: 70px;
  width: 122px;
  padding: 0 31px 24px;
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
    src="https://cdn.builder.io/api/v1/image/assets/a02dbdbe01964471b17f5bdc9fc7e101/757faac94db11066bfebfaafc5ac00b67df21bcbf5f7b07f484e4e743ef6937a?apiKey=a02dbdbe01964471b17f5bdc9fc7e101&"
    class="banner-image"
    alt="Event banner"
  />
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/a02dbdbe01964471b17f5bdc9fc7e101/5f156df1fc4c7ce573b43f38527c5a56a4d3d24c70f29796982da23758aaeddf?apiKey=a02dbdbe01964471b17f5bdc9fc7e101&"
    class="logo-image"
    alt="Event logo"
  />
  <div class="event-title">
    <span class="title-primary">EVENT</span>
    <span class="title-secondary">DAY</span>
    <span class="title-tertiary">EVENTS</span>
  </div>
  <button class="register-button" tabindex="0">REGISTER</button>
  <button class="login-button" tabindex="0">LOGIN</button>
</div>

List of contents page:

<style>
.events-container {
  background-color: rgba(231, 126, 94, 1);
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  font-family: Lalezar, sans-serif;
  font-weight: 400;
  margin: 0 auto;
  padding: 118px 80px 329px 20px;
}

.events-title {
  color: rgba(203, 50, 50, 1);
  font-size: 36px;
  align-self: center;
}

.events-list {
  display: flex;
  margin-top: 98px;
  width: 231px;
  max-width: 100%;
  flex-direction: column;
  align-items: start;
  font-size: 29px;
}

.event-icon {
  aspect-ratio: 1.37;
  object-fit: contain;
  object-position: center;
  width: 41px;
}

.event-name {
  align-self: end;
  z-index: 10;
  margin-top: -30px;
}

.linux-event {
  color: rgba(54, 93, 223, 1);
}

.mystery-event {
  color: rgba(254, 218, 15, 1);
}

.event-group {
  display: flex;
  margin-top: 45px;
  width: 100%;
  flex-direction: column;
}

.event-row {
  display: flex;
  gap: 30px;
}

.thief-event {
  flex-grow: 1;
  width: 143px;
  color: rgba(85, 223, 129, 1);
}

.puzzle-event {
  flex-grow: 1;
  width: 138px;
  color: rgba(45, 20, 20, 1);
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

<div class="events-container">
  <h1 class="events-title">LIST OF EVENTS</h1>
  <div class="events-list">
    <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/a02dbdbe01964471b17f5bdc9fc7e101/96207af316ffa6bc7e6a017811a97e35265b224c370396aedb17c1f8b793b257?apiKey=a02dbdbe01964471b17f5bdc9fc7e101&" alt="Linux Games event icon" />
    <div class="event-name linux-event" tabindex="0">Linux Games</div>
    
    <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/a02dbdbe01964471b17f5bdc9fc7e101/96207af316ffa6bc7e6a017811a97e35265b224c370396aedb17c1f8b793b257?apiKey=a02dbdbe01964471b17f5bdc9fc7e101&" alt="Mystery Club event icon" />
    <div class="event-name mystery-event" tabindex="0">Mystery Club</div>
    
    <div class="event-group">
      <div class="event-row">
        <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/a02dbdbe01964471b17f5bdc9fc7e101/96207af316ffa6bc7e6a017811a97e35265b224c370396aedb17c1f8b793b257?apiKey=a02dbdbe01964471b17f5bdc9fc7e101&" alt="Thief Hunter event icon" />
        <div class="thief-event" tabindex="0">Thief Hunter</div>
      </div>
      
      <div class="event-row">
        <img class="event-icon" src="https://cdn.builder.io/api/v1/image/assets/a02dbdbe01964471b17f5bdc9fc7e101/96207af316ffa6bc7e6a017811a97e35265b224c370396aedb17c1f8b793b257?apiKey=a02dbdbe01964471b17f5bdc9fc7e101&" alt="Puzzle Rush event icon" />
        <div class="puzzle-event" tabindex="0">Puzzle Rush</div>
      </div>
    </div>
  </div>
</div>

Registration page:

<style>
.registration-container {
  background-color: rgba(231, 126, 94, 1);
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  padding: 141px 36px;
  font: 400 24px Lalezar, sans-serif;
}

.registration-title {
  color: rgba(213, 45, 188, 1);
  font-size: 32px;
  align-self: center;
}

.form-field {
  background-color: rgba(255, 255, 255, 1);
  margin-top: 13px;
  padding: 5px 9px;
}

.form-field-name {
  background-color: rgba(254, 252, 252, 1);
  margin-top: 59px;
}

.form-field-gender {
  width: 199px;
  max-width: 100%;
}

.form-field-age {
  width: 172px;
  max-width: 100%;
}

.form-field-register {
  background-color: rgba(254, 252, 252, 1);
  margin-top: 22px;
}

.form-field-mobile {
  margin-top: 28px;
}

.form-field-email {
  margin-top: 13px;
}

.form-field-event {
  margin-top: 19px;
}

.submit-button {
  background-color: rgba(25, 240, 25, 1);
  align-self: center;
  margin-top: 63px;
  width: 122px;
  max-width: 100%;
  font-size: 32px;
  color: rgba(237, 31, 31, 1);
  border: none;
  cursor: pointer;
  padding: 10px;
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

<div class="registration-container">
  <h1 class="registration-title">Event Registration Form</h1>
  <form>
    <div class="form-field form-field-name">
      <label for="fullName">Full Name:</label>
      <input type="text" id="fullName" name="fullName" required aria-label="Full Name">
    </div>

    <div class="form-field form-field-gender">
      <label for="gender">Gender:</label>
      <select id="gender" name="gender" required aria-label="Gender">
        <option value="">Select Gender</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
      </select>
    </div>

    <div class="form-field form-field-age">
      <label for="age">Age:</label>
      <input type="number" id="age" name="age" required aria-label="Age">
    </div>

    <div class="form-field form-field-register">
      <label for="registerNumber">Register Number:</label>
      <input type="text" id="registerNumber" name="registerNumber" required aria-label="Register Number">
    </div>

    <div class="form-field form-field-mobile">
      <label for="mobileNumber">Mobile No:</label>
      <input type="tel" id="mobileNumber" name="mobileNumber" required aria-label="Mobile Number">
    </div>

    <div class="form-field form-field-email">
      <label for="email">Email id:</label>
      <input type="email" id="email" name="email" required aria-label="Email Address">
    </div>

    <div class="form-field form-field-event">
      <label for="event">Event to Register:</label>
      <select id="event" name="event" required aria-label="Event Selection">
        <option value="">Select Event</option>
        <option value="event1">Event 1</option>
        <option value="event2">Event 2</option>
        <option value="event3">Event 3</option>
      </select>
    </div>

    <button type="submit" class="submit-button">Submit</button>
  </form>
</div>

Thank You page:

<style>
.registration-container {
  background-color: rgba(231, 126, 94, 1);
  display: flex;
  max-width: 480px;
  width: 100%;
  padding: 60px 0 0;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  margin: 0 auto;
}

.logo-image {
  aspect-ratio: 4.65;
  object-fit: contain;
  object-position: center;
  width: 391px;
  max-width: 391px;
}

.confirmation-heading {
  color: rgba(65, 54, 211, 1);
  margin: 144px 0 0;
  font: 380 32px Lemonada, sans-serif;
}

.contact-footer {
  background-color: rgba(254, 218, 15, 1);
  align-self: stretch;
  display: flex;
  margin: 291px 0 0;
  width: 100%;
  flex-direction: column;
  align-items: flex-start;
  padding: 18px 80px 18px 17px;
}

.contact-info {
  color: rgba(0, 0, 0, 1);
  font: 400 32px League Spartan, sans-serif;
}

.developer-credit {
  color: rgba(0, 0, 0, 1);
  margin: 14px 0 0;
  font: 400 24px Lexend, sans-serif;
}
</style>

<div class="registration-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/a02dbdbe01964471b17f5bdc9fc7e101/6acd03c9316b2b3c8c5cfa065d1dba5e51aadd47ec058038d1212ff936a5fd9f?apiKey=a02dbdbe01964471b17f5bdc9fc7e101&"
    class="logo-image"
    alt="Saveetha Engineering College logo"
  />
  <h1 class="confirmation-heading">THANK YOU FOR REGISTERING</h1>
  <footer class="contact-footer">
    <address class="contact-info">
      Contact us at:
      <br />
      www.saveetha.ac.in
      <br />
      9491089XXX
    </address>
    <p class="developer-credit">
      DESIGNED AND DEVELOPED BY
      <br />
      T Rajkumar(24004992)
    </p>
  </footer>
</div>



```
## OUTPUT:

![Screenshot 2025-05-13 131746](https://github.com/user-attachments/assets/0ecaef0e-9a1b-45fd-bc65-d870ce3c0f36)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
