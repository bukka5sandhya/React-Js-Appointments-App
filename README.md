In this project, let's build an Appointments App by applying the concepts we have learned till now.

Refer to the image below:

![image](https://github.com/bukka5sandhya/React-Js-Appointments-App/assets/133884532/bcd706fe-3994-47ce-a8f5-de7381882780)

https://assets.ccbp.in/frontend/content/react-js/appointments-app-output.gif

Design Files

Click to view

Extra Small (Size < 576px) and Small (Size >= 576px)

Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)

Set Up Instructions

Click to view

Download dependencies by running npm install

Start up the app using npm start

Completion Instructions

Functionality to be added

The app must have the following functionalities

Initially, the list of appointments should be empty and the title input and date input should be empty

When non-empty values are provided for title and date and the Add button is clicked,

A new appointment should be added to the list of appointments

The value inside the input elements for title and date should be updated to their initial values

When the Star on an appointment is clicked, the appointment should be starred

The status of the Starred filter is updated by clicking on it

When the Starred filter is active, all the starred appointments should be filtered and displayed

When the Starred filter is inactive, the list of all appointments should be displayed

Components Structure

![image](https://github.com/bukka5sandhya/React-Js-Appointments-App/assets/133884532/3ffa3d07-fc67-4f22-befa-5ed2bccd629c)

Implementation Files

Use these files to complete the implementation:

src/components/Appointments/index.js

src/components/Appointments/index.css

src/components/AppointmentItem/index.js

src/components/AppointmentItem/index.css

Quick Tips

Click to view

<input type="date" />

The format function in the date-fns package can be used to get the formatted date string in the given format


import {format} from 'date-fns'

console.log(format(new Date(2021, 19, 07), 'dd MMMM yyyy, EEEE')) // 19 July 2021, Monday

Important Note

Click to view

The following instructions are required for the tests to pass

For the format function, pass the format string dd MMMM yyyy, EEEE as the second argument

The star button in each appointment should have the data-testid as star

The star image in each appointment should have alt as star

Resources

Image URLs

https://assets.ccbp.in/frontend/react-js/appointments-app/appointments-img.png alt should be appointments

https://assets.ccbp.in/frontend/react-js/appointments-app/star-img.png

https://assets.ccbp.in/frontend/react-js/appointments-app/filled-star-img.png

Colors

Hex: #9796f0

Hex: #fbc7d4

Hex: #ffffff

Hex: #171f46

Hex: #8b5cf6

Hex: #b5b7c4

Hex: #9897f0

Font-families

Things to Keep in Mind

All components you implement should go in the src/components directory.

Don't change the component folder names as those are the files being imported into the tests.

Do not remove the pre-filled code

Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.

The HTML input element with the type date is designed for the user to select the date from a date picker
