# My 4 Months of Experience at UniSA

Welcome to my website, where I share my journey as an international student at the University of South Australia (UniSA). This website aims to provide an overview of my experience over the past 4 months and my current courses that I'm studying at UniSA.

## Table of Contents

1. [Page 1: About Me](#page-1-about-me)
2. [Page 2: My Courses](#page-2-my-courses)
3. [Page 3: My Password](#page-3-my-password)
4. [Page 4: TODO List](#page-4-todo-list)

## Page 1: About Me
### Introduction
Hi! My name is Nguyen Tuan Hung Phan, and I'm an international student at UniSA. Studying abroad at UniSA has been one of the most rewarding decisions of my life. It has provided me with the opportunity to immerse myself in a diverse and vibrant culture. The page contains my academic experience, activity, incidents, friends, and also some difficulties of an international student. I introduced myself and talked a little bit about some weird experiences that I've faced like enrolling in the wrong class (OOB).

### Interactive Features
- **Greeting section:** In the upper right corner of the screen, there is a hello user section that allows typing the user's name. Hit the button "Enter" and then it will display the text *"Hello [user's name]".* 
- **Toggle Theme:** An icon next to the greeting section allows users to switch between dark mode (moon icon) and light mode (sun icon). The current mode will be automatically stored in LocalStorage, so when reloading the website, it will retain the user's preferred mode.
- **Current Date Time:** The current date and time display at the top left corner
- **Navigation Button:**
    - **Courses:** Bring users to the Courses page
    - **TODO List:** Bring users to the TODO List page
- **Experience Buttons:** At the last sheet, there are some buttons when users click the button, it will display different experiences as well as different images and sources:
  - My personal story when enrolling in the wrong class
  - Some activities that I've engaged in
  - Friends I've made

## Page 2: My Courses

### My current Courses
As a freshman at UniSA, I'm enrolled in four subjects:
1. Information Technology Fundamentals (IT)
2. UO Design Thinking and Digital Innovation (DTS)
3. Network Fundamentals (Network)
4. Problem Solving and Programming (PSP)
### Interactive Features
- **Home Icon:** click to the icon to return to the main page
- **Course Information:** Move the mouse to course image will display the course name and an overview about that couse.

## Page 3: My Password

On this page, users have to type a password to be allowed to access the TODO List page.

If users do not type anything or type the wrong password, an alert about the incorrect password will pop up. The default password for this page is *`12345`*. 

## Page 4: TODO List
### TODO List

The last page talks about my to-do list as well as my academic expectations, some goals that I want to achieve by the end of the year, and some relevant programming courses that I want to study during the break session.

### Interactive Features:
- **Home Icon:** click to the icon to return to the main page
- **Add button:** The tasks will be added when users type to do task in the input box and click *add*.
- **Remove Icon:** Each task has a remove icon next to it. A task will be deleted when the icon is clicked.
- **LocalStorage:** the TODO list will automatically update to localStorage after adding a new task or deleting an old task. The load function will display the data from localStorage when refreshing the website.