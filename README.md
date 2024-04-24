# Culinary Academy

[View live project here!](https://dimmanzo.github.io/culinary-academy/)

Culinary Academy is a FICTIONAL site about a cooking school. Website design is simple, allowing users to easily access all of the information. This site will be targeted towards people who want to learn or improve their cooking skills. It introduces visitors to the main goal of the school and the skills that can be acquired or improved through our courses. Visitors will also have the opportunity to meet the mentors of the Culinary Academy and become acquainted with their professional skills.

![Responsive Mockup](https://github.com/Dimmanzo/culinary-academy/blob/main/media/culinary-academy-mockup.png)


## Features 

### Existing Features

- __Navigation Bar__

  - Featured on all 5 pages, responsive navigation bar includes links to the
  Home, About us, Sign up and Contacts pages and is identical in each page to allow for easy navigation.
  - This section allows users to easily navigate from page to page across all devices without having to revert back to the previous page.

![Nav Bar](https://github.com/Dimmanzo/culinary-academy/blob/main/media/nav-bar.png)

- __Home page__

  - The home page features a logo, background image, and an image of chefs. It contains all the information about the school and serves as an introduction to the website for users.
  - This page is valuable to users because it serves as their first impression of Culinary Academy, providing essential information about the school. 

![Home page](https://github.com/Dimmanzo/culinary-academy/blob/main/media/home-page.png)  

- __Footer__ 

  - The Footer section includes links to relevant social media sites, all of which open in new tabs for easy navigation. Additionally, the footer includes copyright information to deter unauthorized use of the website's content.
  - The footer is valuable to users as it encourages them to stay connected via social media and also serves to secure the webpage with copyright protection.

![Footer](https://github.com/Dimmanzo/culinary-academy/blob/main/media/footer.png)

- __About us page__

  - The About Us page offers users additional information about the school and its history.
  - This section is valuable to users as it helps them identify the skills they can acquire through our courses, and provides insights into the school's foundation and main goals. 

![About us](https://github.com/Dimmanzo/culinary-academy/blob/main/media/about-us-page.png)

- __Sign Up page__

  - This page allows the user to sign up for Culinary Academy studies. The user will be asked to submit their full name, email address, age and country. 
  - This page is valuable to users as it provides a convenient and straightforward way for them to enroll in Culinary Academy's courses.

![Sign up](https://github.com/Dimmanzo/culinary-academy/blob/main/media/sign-up-page.png)

- __Confirmation page__

  - After signing up, the user is redirected to this page, where they receive a confirmation along with a thank-you message.
  - This page is valuable because it confirms to users that their sign-up was successful and thanks them for joining.

![Confirmation](https://github.com/Dimmanzo/culinary-academy/blob/main/media/confirmation-page.png)

- __Contacts page__

  - This page allows users to access all the contact information for the school.
  - This page is valuable because it gives users all the school's contact details, making it easy for them to get in touch when needed.

![Contacts](https://github.com/Dimmanzo/culinary-academy/blob/main/media/contacts-page.png)


## Testing 

| Action  | Result | Pass or Fail  |
| :-: | :-: | :-: |
| Press on Logo | Redirected to index.html page | ✅ |
| Press on Home | Redirected to index.html page | ✅ |
| Press on About us | Redirected to about-us.html page | ✅ |
| Press on Sign up | Redirected to sign-up.html page | ✅ |
| Press on Contacts | Redirected to contacts.html page | ✅ |
| No text in Sign up form inputs | Enter empty inputs notification | ✅ |
| No age selection in Sign up form | Select one of the radio buttons notification | ✅ |
| No country selection in Sign up form | Select one of the countries notification | ✅ |
| Wrong email input in Sign up form | Include '@' in the email address notification | ✅ |
| Press on Submit button after all inputs entered | Redirected to confirmation.html | ✅ |
| Press on Email link in Contacts page | Opens the default email application | ✅ |
| Press on Facebook icon in footer | Opens Facebook page in a new tab | ✅ |
| Press on X(Twitter) icon in footer | Opens X(Twitter) page in a new tab | ✅ |
| Press on Youtube icon in footer | Opens Youtube page in a new tab | ✅ |
| Press on Instagram icon in footer | Opens Instagram page in a new tab | ✅ |

- All functions of the website have been thoroughly tested on various screen sizes and to ensure seamless performance across different devices.

- All functions of the website have been tested across multiple browsers, including: Google Chrome, Microsoft Edge, Mozilla Firefox, Opera.

- After testing the website with a Lighthouse tool, I noticed that the performance score was below 80%, so I had to spend some time finding ways to improve it. Compressing images and preloading them helped resolve the issue.


## Bugs

- Solved bugs
  - After deploying project to GitHub, images on About us page would not load. 
  - The error was in my images file path. href="/assets/images/abus-1.webp".
  - Removing "/" in file path before assets, fixed my problem.

### Validator Testing 

- HTML

  - Home page - no errors found when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdimmanzo.github.io%2Fculinary-academy%2Findex.html)
  - About us page - no errors found when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdimmanzo.github.io%2Fculinary-academy%2Fabout-us.html)
  - Sign up page - no errors found when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdimmanzo.github.io%2Fculinary-academy%2Fsign-up.html)
  - Confirmation page - no errors found when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdimmanzo.github.io%2Fculinary-academy%2Fconfirmation.html)
  - Contacts page - no errors found when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdimmanzo.github.io%2Fculinary-academy%2Fcontacts.html)

- CSS

  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdimmanzo.github.io%2Fculinary-academy%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

- Lighthouse testing was done on both Mobile and Desktop (Google Chrome - Incognito mode).

  - ![Home page](https://github.com/Dimmanzo/culinary-academy/blob/main/media/lighthouse-home-page.png) ![About us page](https://github.com/Dimmanzo/culinary-academy/blob/main/media/lighthouse-about-us-page.png) ![Sign up page](https://github.com/Dimmanzo/culinary-academy/blob/main/media/lighthouse-sign-up-page.png) ![Confirmation page](https://github.com/Dimmanzo/culinary-academy/blob/main/media/lighthouse-confirmation-page.png) ![Contacts page](https://github.com/Dimmanzo/culinary-academy/blob/main/media/lighthouse-contacts-page.png)


### Unfixed Bugs

- No bugs were found


## Deployment

- The site was deployed to GitHub pages. These steps were applied: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

Live project can be found here - https://dimmanzo.github.io/culinary-academy/index.html 


## Publishing

### Cloning

- Cloning a repository means making a copy of a project from GitHub onto your computer, so you can work on it locally.
  - On GitHub.com, navigate to the main page of the repository.
  - Above the list of files, click <> Code.
  - Copy the URL for the repository.
  - Type git clone, and then paste the URL you copied earlier.
  - Press Enter to create your local clone.

### Forking

- Forking a repository involves creating your own version of someone else's project on GitHub, allowing you to modify it without altering the original.
  - On GitHub.com, navigate to the main page of the repository.
  - In the top-right corner of the page, click Fork.
  - Under "Owner," select the dropdown menu and click an owner for the forked repository.
  - Click Create fork.

## Technologies used

- HTML
- CSS
- JavaScript

## Credits 

### Content 

- The text for all of the pages was written by me with help of [ChatGPT](https://chat.openai.com/).
- Help with the code from resources I found online, mostly through [Google](https://www.google.com/) searches, [Code Institute](https://learn.codeinstitute.net/ci_program/diplomainfullstacksoftwarecommoncurriculum) HTML, CSS training material.
- Some ideas were taken from the Love Running project: [Love Running](https://github.com/Code-Institute-Solutions/love-running-v3).
- The icons in the footer were taken from: [Font Awesome](https://fontawesome.com/).
- Cloning idea was given by Mentor and taken from: [Cloning](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).
- Forking idea was given by Mentor and taken from: [Forking](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).


### Media

- Favicon and logo on the main page was made by me: [Logo.com](https://logo.com/).
- The images used as backgrounds for the pages were taken from these open-source sites:
[Home](https://www.pexels.com/photo/fruit-salads-in-plate-1640774/), [About us](https://unsplash.com/photos/three-round-white-plates-with-pasta-near-two-glass-cuups--F_5g8EEHYE), [Sign up](https://pixabay.com/photos/cooking-ingredients-flat-lay-bake-5880136/), [Contacts](https://unsplash.com/photos/variety-of-sliced-fruits-08bOYnH_r_E).
- The images used for the home and about us pages were taken from another open-source site: [Home - 1](https://www.stockfood.com/images/00264056-Three-chefs-examining-the-contents-of-a-pan), [About us - 1](https://www.pexels.com/photo/men-cooking-in-the-kitchen-6823598/), [About us - 2](https://www.pexels.com/photo/happy-asian-women-with-dish-in-plate-5908197/), [About us - 3](https://www.pexels.com/photo/a-chef-tossing-fried-rice-from-the-pan-6937437/), [About us - 4](https://www.pexels.com/photo/man-in-white-dress-shirt-holding-silver-bowl-4253312/).


### Features

- Usage of image preload function was taken from: [Preload](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/rel/preload).
