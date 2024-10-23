# STATION GUIDE : YOUR PLATFORM GUIDE
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

<!-- ALL-CONTRIBUTORS-BADGE:END -->

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-11-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->



<!-- ALL-CONTRIBUTORS-BADGE:END -->

<a href="[https://github.com/Dhairyagoth](https://github.com/dhairyagothi)i"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=DEF72C&random=false&center=false &width=1000&lines=Station Saarthi %2C+Your+Platform+Guide" alt="Typing SVG" /></a>
Welcome to repository of Station Guide

- To get to know about Station Guide Check : - [StationGuide.md](https://github.com/dhairyagothi/StationGuide/blob/f2d4795cf3d3c57ffafb6ce007f47173d7010b1e/StationGuide.md)

- To check UI Prototype Figma design :- [StationGuideFigma.md](https://github.com/dhairyagothi/StationGuide/blob/f2d4795cf3d3c57ffafb6ce007f47173d7010b1e/StationGuideFigma.md)

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

<!-- Added the GSSoc Accepted image -->
### This project is now OFFICIALLY accepted for

<div align="center">
  <img src="https://github.com/apu52/METAVERSE/assets/114172928/e79eb6de-81b1-4ffb-b6ed-f018bb977e88" alt="GSSoC 2024 Extd" width="80%">
</div>
<br>

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## Table of Content

- **[Using Station Guide](#using-station-guide)**
- **[Getting Started](#getting-started)**
- **[Project Structure](#project-structure)**
- **[How to Contribute](#how-to-contribute)**
- **[Code of Conduct](#code-of-conduct)**
- **[How to Fork](#how-to-fork)**
- **[Contributors](#contributors)**
- **[Contact Information](#contact-information)**

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## Using Station Guide

This project utilizes React for the frontend and Express for the backend, providing a robust foundation for your web application development.

### Prerequisites

To get started, you'll need the following:

- Node.js (version 14 or later): https://nodejs.org/en/
- npm (Node Package Manager) comes bundled with Node.js

<br>

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## Getting Started

### 1. Clone the Repository

**Understanding Cloning:**

Cloning creates a local copy of the project on your computer, allowing you to work on it independently. This local copy is a mirror image of the original repository on GitHub or similar platforms.

Use Git to clone this repository into your local development environment:

```bash
git clone https://github.com/dhairyagothi/StationGuide.git
```

**After Cloning**
You will see this interface in your system :

![image](https://github.com/user-attachments/assets/20961ae0-2d63-45e7-9aa4-9adc01fcc4d0)

### 2. Running the Development Server

#### Frontend:

- Open a terminal or command prompt window.
- Navigate to the frontend directory:

```Bash
cd frontend
```

- Start the frontend development server :

```Bash
npm run dev
```

This will typically launch the React application on http://localhost:3000 (or the specified port) in your browser.

#### Backend:

- Open another terminal or command prompt window (separate from the frontend window).
- Navigate to the backend directory:

```Bash
cd backend
```

Start the backend development server (typically using nodemon server.js or a similar command):

```Bash
npm run start
```

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## Project Structure

<!-- START_STRUCTURE -->
```
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── Learn.md
├── README.md
├── SECURITY.md
├── StationGuide.md
├── StationGuideFigma.md
├── backend/
│   ├── config/
│   │   ├── config.js
│   │   └── dbConnection.js
│   ├── controllers/
│   │   ├── StationController.js
│   │   ├── WheelchairController.js
│   │   ├── authController.js
│   │   ├── cloakroomController.js
│   │   ├── coolieController.js
│   │   ├── stationBookingsController.js
│   │   └── stationsController.js
│   ├── dataset/
│   │   └── stations.js
│   ├── dockerfile
│   ├── index.js
│   ├── middleware/
│   │   └── auth.middleware.js
│   ├── models/
│   │   ├── CloakroomBooking.js
│   │   ├── CoolieBooking.js
│   │   ├── Stations.js
│   │   ├── User.js
│   │   └── WheelchairBooking.js
│   ├── package-lock.json
│   ├── package.json
│   ├── public/
│   │   └── test.html
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── stationRoutes.js
│   └── utils/
│       ├── ApiError.js
│       ├── asyncHandler.js
│       └── authFunctions.js
├── docker-compose.yml
├── frontend/
│   ├── README.md
│   ├── dockerfile
│   ├── eslint.config.js
│   ├── index.html
│   ├── package-lock.json
│   ├── package.json
│   ├── postcss.config.js
│   ├── public/
│   │   └── vite.svg
│   ├── src/
│   │   ├── App.css
│   │   ├── App.jsx
│   │   ├── Pages/
│   │   │   ├── 3Dmaps.jsx
│   │   │   ├── AboutUs.jsx
│   │   │   ├── ContactUs.jsx
│   │   │   ├── Emergency.jsx
│   │   │   ├── ForaFriend.jsx
│   │   │   ├── HelpandSupport.jsx
│   │   │   ├── Herosection.css
│   │   │   ├── Herosection.jsx
│   │   │   ├── LoginPage.jsx
│   │   │   ├── Payment.jsx
│   │   │   ├── Register.jsx
│   │   │   ├── booking.jsx
│   │   │   ├── contributor.jsx
│   │   │   ├── hamburger.css
│   │   │   ├── hamburger.jsx
│   │   │   ├── navigation.jsx
│   │   │   ├── notification.jsx
│   │   │   ├── schedule.jsx
│   │   │   └── stations.jsx
│   │   ├── assets/
│   │   │   ├── bg.png
│   │   │   ├── bgmobile.png
│   │   │   ├── hero.png
│   │   │   ├── mixbg.png
│   │   │   ├── stationsaarthi.svg
│   │   │   └── svg/
│   │   │       ├── 3dmap.svg
│   │   │       ├── backicon.svg
│   │   │       ├── bookings.svg
│   │   │       ├── chatbot.svg
│   │   │       ├── contributor.svg
│   │   │       ├── navigation.svg
│   │   │       ├── notification.svg
│   │   │       ├── schedule.svg
│   │   │       ├── search.svg
│   │   │       └── station.svg
│   │   ├── components/
│   │   │   ├── Bookingform.jsx
│   │   │   ├── MapComponent.jsx
│   │   │   ├── Settings.jsx
│   │   │   ├── about.css
│   │   │   ├── about.jsx
│   │   │   ├── chatbot.css
│   │   │   ├── chatbot.jsx
│   │   │   ├── footer.jsx
│   │   │   ├── help.jsx
│   │   │   ├── navbar.jsx
│   │   │   ├── scrollToTop.css
│   │   │   └── scrollToTop.jsx
│   │   ├── dataset/
│   │   │   └── stations.js
│   │   ├── index.css
│   │   ├── main.jsx
│   │   └── validations/
│   │       └── validation.js
│   ├── tailwind.config.js
│   └── vite.config.js
├── notification_system/
│   ├── backend/
│   │   ├── config/
│   │   │   └── db.js
│   │   ├── controllers/
│   │   │   └── notificationController.js
│   │   ├── models/
│   │   │   ├── Notification.js
│   │   │   └── User.js
│   │   ├── package.json
│   │   ├── routes/
│   │   │   ├── notificationRoutes.js
│   │   │   └── userRoutes.js
│   │   ├── server.js
│   │   └── services/
│   │       └── emailServices.js
│   └── frontend/
│       ├── package.json
│       ├── public/
│       │   └── service-worker.js
│       └── src/
│           ├── app.js
│           ├── components/
│           │   ├── NotificationCentre.js
│           │   └── NotificationSettings.js
│           └── index.js
├── package-lock.json
├── package.json
├── repo_structure.txt
└── tailwind.config.js
```
<!-- END_STRUCTURE -->


<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## How to Contribute

Contributions are always welcome!
To ensure a smooth collaboration process, Follow these steps:


1. **Fork the Repository:**

   - Click the "Fork" button on the top right of the repository page. This creates a copy of the repository under your GitHub account.

2. **Clone Your Fork:**

   - Run the following command in your terminal:
     ```bash
     git clone https://github.com/YOUR_USERNAME/Awesome-Github-Profiles.git
     ```
   - This command downloads your fork to your local machine.

3. **Create a Branch:**

   - Navigate into the cloned repository:
     ```bash
     cd Awesome-Github-Profiles
     ```
   - Create a new branch for your feature or fix:
     ```bash
     git checkout -b your-feature-branch
     ```

4. **Make Your Changes:**

   - Implement your changes in your local repository. Make sure your code is clean and follows the project's coding style guidelines.

5. **Test Your Changes:**

   - If applicable, run tests to ensure that your changes do not break existing functionality.

6. **Commit Your Changes:**

   - Commit your changes with a clear and descriptive message:
     ```bash
     git commit -m "Add a feature or fix a bug"
     ```

7. **Push to Your Fork:**

   - Push your changes back to your forked repository:
     ```bash
     git push origin your-feature-branch
     ```

8. **Create a Pull Request:**
   - Navigate to the original repository where you want to propose your changes.
   - Click on "New Pull Request" and follow the instructions to submit your changes for review.

Please refer to the detailed [contribution guidelines](CONTRIBUTING.md) for more information.

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## Code of Conduct

To foster a positive and inclusive community, please adhere to the following guidelines:

- **Be Respectful:** Treat everyone with respect. Engage in constructive conversations.
- **No Harassment:** Harassment, bullying, or discrimination will not be tolerated.
- **Report Issues:** If you witness or experience any unacceptable behavior, please report it to the project maintainers.

Please read the [code of Conduct](CODE_OF_CONDUCT.md) for more clear understanding.

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## How to Fork

Forking allows you to create a personal copy of the repository, where you can experiment and make changes without affecting the original project. Here’s how to do it:

### Navigate to the Repository:

- Go to the Awesome GitHub Profiles repository.

### Click on Fork:

- On the top right corner, click the "Fork" button.

### Select Your Account:

- Choose your GitHub account to create the fork.

### Clone Your Fork:

- Use the command below to clone your fork to your local machine:
  ```bash
  git clone https://github.com/YOUR_USERNAME/Awesome-Github-Profiles.git
  ```
<br>

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## Our Valuable Contributors ❤️✨

[![Contributors](https://contrib.rocks/image?repo=dhairyagothi/StationGuide)](https://github.com/dhairyagothi/StationGuide/graphs/contributors)

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">



## Stargazers ❤️

<div align='left'>

[![Stargazers repo roster for @dhairyagothi/StationGuide](https://reporoster.com/stars/dhairyagothi/StationGuide)](https://github.com/dhairyagothi/StationGuide/stargazers)

</div>

## Forkers ❤️

[![Forkers repo roster for @dhairyagothi/StationGuide](https://reporoster.com/forks/dhairyagothi/StationGuide)](https://github.com/dhairyagothi/StationGuide/network/members)


<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

<!-- Added the Team section -->
## 👥 Team

| ![Dhairya Gothi](https://avatars.githubusercontent.com/u/142989448?v=4&s=80)|
|:--:|
| **Dhairya Gothi** <br> <sub>Project Admin</sub> | 
| [![LinkedIn](https://img.icons8.com/fluency/32/000000/linkedin.png)](https://www.linkedin.com/in/dhairya-gothi-65945b288/) | 

If you have questions, suggestions, or feedback, please reach out via email at dhairyag31@gmail.com. You can also join our [discussion forum](https://github.com/dhairyagothi/StationGuide/discussions).

We value open communication and are happy to help!

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

<!-- Added a Support section for the project README -->
## ⭐️ Support the Project
If you find this project helpful, please consider giving it a ⭐ on GitHub! Your support helps to grow the project and reach more contributors.
