# Frontend Mentor - rest-countries-api-with-color-theme-switcher

The project was based on the challenge provided by [Frontend Mentor](https://www.frontendmentor.io).

This is a solution to the [rest-countries-api-with-color-theme-switcher](https://www.frontendmentor.io/challenges/rest-countries-api-with-color-theme-switcher-5cacc469fec04111f7b848ca).

## The design provided

![Design preview for the Time tracking dashboard coding challenge](documentation/design/desktop-preview.jpg)

## Table of contents

- [User Stories](#user-stories)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Design](#design)
- [Bugs](#bugs)
- [Testing](#testing)
  - [Compatibility](#compatibility)
  - [Validator testing](#validator-testing)
  - [Lighthouse Report](#lighthouse-report)
- [Deployment](#deployment)
- [Author](#author)
- [Credits](#credits)
- [Acknowledgments](#acknowledgments)

I was using design files provided for this challenge in order to make the result look as similar as possible to the provided images.

I have also added various breakpoints in order to provide the best user experience.

The solution to this challenge can be accessed by this [link]()

![Responsive Mockup](documentation/responsive_mockup.png)

---

## User Stories

### First Time Visitor Goals:

- As a First Time Visitor, I want to easily understand the main purpose of the website, so I can learn more about this website.
- As a First Time Visitor, I want to be able to easily navigate through the website, so I can find the content.
- As a First Time Visitor, I want to find the website useful.

### Frequent Visitor Goals:

- As a Frequent User, I want to get countries information, so I can learn about countries'.
- As a Frequent User, I want to have a chance click on the neighboring countries, so I can learn about neighboring countries.
- As a Frequent User, I want to have a chance so select and search countries, so I can easily find a country needed.

---

## Features

## Features

- ### Main Page

  - Represent:

    - the time tracking dashboard.

  - Consist:

    ![Main Page](documentation/app_features/main_page.png)

    - Navbar with the incentive, and mode control to pick the theme.

    - Search panel to search for a country.

    - Select dropdown menu to select countries by continent

    - summary about each country with its flag.

    - When clicking a country card, the user can learn more about this country, click on boarder countries to be redirected to another country, or go back to the main page.

    ![Modal Window](documentation/app_features/modal.png)

---

## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - was used as the foundation of the site.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/css) - was used to add the styles and layout of the site.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - was used to arrange items symmetrically on the pages.
- [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid) - was used to make "gallery" and "contact" pages responsive.
- [CSS roots](https://developer.mozilla.org/en-US/docs/Web/CSS/:root) - was used to declaring global CSS variables and apply them throughout the project.
- [VSCode](https://code.visualstudio.com/) - was used as the main tool to write and edit code.
- [Git](https://git-scm.com/) - was used for the version control of the website.
- [GitHub](https://github.com/) - was used to host the code of the website.
- [GIMP](https://www.gimp.org/) - was used to make and resize images for the README file.
- [JS](https://www.javascript.com/) - was used to display content on the page.
- [async functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function) - were used to fetch the data from the local json file.

---

## Design

- The design, color scheme and font-family were provided by [Frontend Mentor](https://www.frontendmentor.io).

- Family: [Nunito Sans](https://fonts.google.com/specimen/Nunito+Sans) (Weights: 300, 600, 800).

---

## Bugs

- **Solved bugs**

1. The previous version of the REST COUNTRIES API was not available and the recent one has overwhelming data. Since I was aware of the issues with this data base happening before, I made a decision to use local JSON file + svg images from free source: [Flagpedia.net](https://flagpedia.net/) to keep my code running regardless of the availability of rest countries API.

- **Unsolved bugs**

  - The size of the flags were changed due to the requirements to keep cards with the same size. But in order to make flags more realistic, there is a solution:

  Change width of the .data\_\_card to max-width

---

## Testing

### Compatibility:

- The app was tested on the following browsers: Chrome, Firefox, Brave, Edge:

  - Chrome:

  ![Main Page](documentation/compatibility/browser_chrome.png)

  - Firefox:

  ![Main Page](documentation/compatibility/browser_firefox.png)

  - Brave:

  ![Main Page](documentation/compatibility/browser_brave.png)

  - The app was checked by devtools implemented on Firefox and Chrome browsers.

- The app was checked by devtools implemented on Firefox and Chrome browsers.

- The app was checked with [Responsive Website Design Tester](https://responsivedesignchecker.com/).

  1. Mobile Screens:

  - Mobile 320x480, 320x568, 360x640, 375x667, 384x640, 411x731, 414x736:

  ![Mobile](documentation/responsiveness/responsiveness_mobile_devices.gif)

  1. Tablets Screens:

  - Tablet 600x960, 768x1024, 800x1280, 1366x1024, 1600x900, 1680x1050, 1920x1080, 1920x1200:

  ![Tablet](documentation/responsiveness/responsiveness_tablet_devices.gif)

  1. Desktop Screens:

  - Desktop 1024x600, 1024x800, 1366x768, 1440x900:

  ![Desktop](documentation/responsiveness/responsiveness_desktop_devices.gif)

- The functionality of the links in the app was checked as well by different users.

  ![Functionality](documentation/observe_functionality.gif)

### Validator testing

- #### HTML

  - No errors or warnings were found when passing through the official [W3C](https://validator.w3.org/) validator.

    - Main Page:

    [Main Page HTML Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fiuliiakonovalova.github.io%2Ffrontend-mentor-rest-countries-api%2F)

- #### CSS

  - No errors were found when passing through the official [W3C (Jigsaw)](https://jigsaw.w3.org/css-validator/#validate_by_uri) validator:

  [CSS Validator Errors](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fiuliiakonovalova.github.io%2Ffrontend-mentor-rest-countries-api%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

  - The warnings shown are all regarding the use of webkits. However, the website works normally without any issues.

- #### JS

No errors or warnings were found when passing through the official [JSHint](https://jshint.com/) validator:

![JSHint Validator Main Page](documentation/js_hint.png)

---

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the [GitHub repository](https://github.com/EnebeliEmmanuel/Rest-Api.git), navigate to the Settings tab
  - From the source section drop-down menu, select the **Main** Branch, then click "Save".
  - The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://rest-api-r88spnykl-iemmaenebeli-gmailcom.vercel.app/)

---

### Local Deployment

In order to make a local copy of this project, you can clone it.
In your IDE Terminal, type the following command to clone my repository:

- `git clone`https://github.com/EnebeliEmmanuel/Rest-Api.git

---

## Author

- Website - [koko codes](https://EnebeliEmmanuel.github.io/Rest-Api/)
- Frontend Mentor - [@koko codes](https://www.frontendmentor.io/profile/IuliiaKonovalova)

---

## Credits

- ### Content and Design

  - [Frontend Mentor](https://www.frontendmentor.io) had provided all necessary content and design that was used in order to complete this challenge.

- ### Flags

  - [Flagpedia.net](https://flagpedia.net/) had provided a free access to flags of all countries around the world.

- ### Font

  - [Google Fonts](https://fonts.google.com/) was used in order to implement required font.

---

## Acknowledgement

- [Frontend Mentor](https://www.frontendmentor.io) for inspiring to improve my skills.

---

## Wireframes

- Desktop:

  - [Design preview for the rest Countries API](documentation/design/desktop-design-home-dark.jpg);

  - [Design preview for the rest Countries API](documentation/design/desktop-design-home-light.jpg);

  - [Design preview for modal the rest Countries API](documentation/design/desktop-design-detail-dark.jpg);

  - [Design preview for modal the rest Countries API](documentation/design/desktop-design-detail-light.jpg);

- Mobile:

  - [Design preview for the rest Countries API](documentation/design/mobile-design-home-dark.jpg);

  - [Design preview for the rest Countries API](documentation/design/mobile-design-home-light.jpg);

  - [Design preview for modal the rest Countries API](documentation/design/mobile-design-detail-dark.jpg);

  - [Design preview for modal the rest Countries API](documentation/design/mobile-design-detail-light.jpg);

---
