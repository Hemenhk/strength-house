# Strength House

Welcome to Strength House!

## Description

Strength House is a project designed to aid newcomers to the gym in finding an easy routine to follow. Through years of experience, I, Hemen Hiwa Kamal, have structured a simplified workout programme that allows the user to ease in to the gym. Through different pages and colors themes, the user is able to distinguish between different muscle groups. Feel free to use the routine as a template for further modifications along the way in your fitness journey!

Some of the features used in this project are meant to give the user a sense of security. An example is the color changes in the hover effect of the menu lists, and the color change of the hamburger menu for each page (Push, Pull and Legs). These details are meant to provide the user with a great experience, and hopefully see them revisit the website. You can access the site here: [Strength House](https://hemenhk.github.io/strength-house/index.html).
 
![responsive design](assets/images/Screenshot%202022-06-04%20at%2021.05.48.jpg)

## Technology used on project

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
    - HTML was used as the basic structure for building this project.
- [CSS](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
    - CSS was used to give this project styles and a way to give the visitor a good user experience.
- [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
    - Javascript was used to add the hamburger side menu for smaller screens.
- [Google Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
    - Google Developer Tools was used to identify bugs, and to test performance of the website.
- [Tiny.png](https://tinypng.com/)
    - Tiny.png was used to compress images, thus increasing performance of this website.
- [Font Awesome](https://fontawesome.com/)
    - Font Aweome was used to add icons to different elements.
- [GitHub](https://github.com/)
    - Github was used to store the project after it had been pushed.
- [Gitpod](https://www.gitpod.io/)
    - Gitpod was used to write the code and style the project.
- [Git](https://git-scm.com/)
    - Git was used for version control by commiting to Git and pushing to Github.
- [W3C Markup Validation Service](https://validator.w3.org/)
    - W3C was used to validate all the HTML code written in this project. 
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input)
    - W3C CSS validation was used to validate the CSS written in this project.
- [AmIResponsive](http://ami.responsivedesign.is/)
    - AMIResponsive was used to add an image showcasing the responsivness in the README.md file.
    
# UX

## Strategy

Regarding the core UX principles I began contemplating the strategy behind this website and defined the target audience, and what features and technologies they would benefit most from. The user is quickly able to understand the information displayed on the home page, and the subsequent pages. The reasoning behind this project was straightforward, and was inspired by a renowned fitness icon amongst the YouTube community, Elliott Hulse. Through his guidance in my youth, I found the neccessary tools to use in my journey. With that in mind, I wished to create a website where I could help people of similar situations begin their journey in fitness.

### Target Audience of Strength House are:

- Everyone from the ages 15 and  upwards.
- People that find fitness to be too complicated.

### User's Reasons For Using Strength House
- Wanting to commit to a fitness routine
- Wanting to increase their confidence 
- Wanting to develop discipline through continuous hard work.

## Scope

To achieve the goal set in mind, this project will include:
- A header with a responsive navbar for desktop, tablets and phones.
- A home page introducing the reasons why one should pursue fitness.
- Different pages detailing a workout regiment.

## Structure

The reasons behind using a multi-page website was to give the user an opportunity to access the information in an organized and structured manner. The use of a hamburger navbar (tablet and phone users) is to allow the user to navigate the website with the comfort of only one hand and without over-extending the thumb (right-hand users). By ordering the pages from Push, Pull and Legs, respectively, the user is able to understand the order of which the muscle groups should be trained (left-side priority). All pages are styled with an image relevant to the muscle groups trained, deadlift for pull and squats for legs. The "About Us" page is the only page with a single section. This was done to display a clean and simple page, describing the story behind this website. Further, the footer is simple, with only an address and social media icons, This was done, as the website is a non-commercial website that is meant to be shared freely with everyone interested. 

## Skeleton

This website is structured using 5 pages; Home, Push, Pull, Legs and About Us. All menu links are spread out over different pages, so as to give the user a sense of organization.

## Surface

I chose to give this website a more elegant feel to it, as most fitness websites are rigid. This was done to give the user a feel of competency, through the effort it took to create Strength House. The color theme of this website varies depending on the page selected. The colors were used depending on the most prominent color on the hero image. For example, in the page titled Legs, the female is wearing a suit of green, as such the hover effect and columns have been made to match it, thus giving the page a structured feel.


# Features

This is a fully responsive website. Headings from h2-h6 are styled using 'Bebas Neue', whilst the h1 is styled with 'Squada One'. This is to differentiate between the hero content and the subsequent sections. 'Noto Sans' is used for paragraphs, as it is clean and elegant. The Website is comprised of five pages, provided in the navigation bar: 

## Navigation Bar

The navigation bar on the top right is used to access different pages of the website. The font is the same used for "h1". The hover effect has a distinct color, depending on which page you are on, and has a slight delay in it's width, giving each page a sense of uniqueness. When viewed on smaller devices such as tablets and phones, the navigation bar turns into a hamburger menu, to make navigating this website a lot easier. 


![Navigation Bar](assets/images/thumbnail_Screenshot%202022-06-05%20at%2000.47.35.png)

## Pull Page

This page, similar in structure as Push and Legs, is where I structure and introduce the workout exercises for the user's easy access. 

![Pull Page](assets/images/thumbnail_Screenshot%202022-06-05%20at%2000.48.18.png)

## About Us Page

This is where I've explained in simple design, the reason for Strength House's existence.

![About US](assets/images/thumbnail_Screenshot%202022-06-05%20at%2000.48.24.png)

## Future Features 

In the future, I intend to expand upon the number of exercises available, and link videos explaining how to perform each one properly, so that the user also has visual aid. 

## Testing

Throughout the project I have repeatedly tested the validity of the code written and have also tested the performance of the many pages through Google Lighthouse. The website was tested on many different devices and browsers such as Safari, Chrome, iPhone 5, iPhone X, iPhone 12 Pro, iPad and Samsung Galaxy Fold. This was done to ensure optimal responsiveness of the website across different screens. Some issues identified where:

- Some images were not showing. This was fixed when realizing that they were avif images and not jpegs or pngs. 
- The text in the "About Us" page was bleeding into the footer on smaller screens. This was resolved by reducing the size of the fonts, so that they would not take too much space. 
- Slow performance on smaller screens. This was due to the image sizes (already compressed) and the use of videos. This cannot be resolved and is an accepted quality of the website.

# Validator Tests

I ran tests of the integrity of the HTML and CSS codes on W3C Validator and performance tests on Google Lighthouse. Provided below are screenshots of these tests.

### W3C HTML

I used W3C validator for HTML and the results are found here [W3C Validator](https://validator.w3.org/nu/#textarea)

![W3C HTML Validator](assets/images/thumbnail_Screenshot%202022-06-05%20at%2001.10.38.png)

### W3C CSS

I also used W3C validator for CSS and the results can be seen here [W3C Validator CSS](https://validator.w3.org/nu/#textarea)

![W3C CSS Validator](assets/images/thumbnail_Screenshot%202022-06-05%20at%2001.11.20.png)

### Google Lighthouse Desktop

![Google Lighthouse Desktop](assets/images/thumbnail_Screenshot%202022-06-05%20at%2001.12.51.png)

### Google Lighthouse Mobile 

![Google Lighthouse Mobile](assets/images/thumbnail_Screenshot%202022-06-05%20at%2001.12.25.png)


### Unfixed Bugs

- There are not unfixed bugs in this project.

# Deployment

This project was created using Gitpod, and committed to git and pushed to Github by the use of git commands.

To deploy this project to GitHub Pages from the Github repository, the following steps were taken:

1. Log into Github
2. Go to repositories and select on "strength-house".
3. Select "settings" on the menu.
4. Scroll down to "pages" and select it. 
5. In the "source" section click on "branch" and select "main".
6. Click save and wait for the repository to be published.
7. Click on the link provided to access the finished website.

The live link is found here https://hemenhk.github.io/strength-house/.

### Clone This Project 

- Under repository press "code" and select "clone".
- Open Git Bash.
- Change current working directory to the location where you wish to have the cloned directory.
- Type "git clone" and paste the URL which you copied previously.
- Press "enter" to create a local clone.



### Access This Project On Local Desktop

- Under repository press the "code" button next to "add file".
- Select "download zip".
- Extract the content onto your desktop.
- Click on any file to access the pages.

# Credits

## Coding Content
- Most of the coding was done by myself from knowledge gained throughout the code modules.
- The layout of the website was inspired by [Shear Revival](https://www.shearrevival.com/), which I found to be clean and user friendly.
- Instructions on how to implement hover effects on the navigation links and the hamburger menu, click button, as well as how to add hero images through CSS where taken from the great [
Easy Tutorials](https://www.youtube.com/watch?v=oYRda7UtuhA).

## Media

### Images

All images used on this project were downloaded from [Unsplash](https://unsplash.com/)

### Video content 

Video on Pull page was taken from [Strength Camp](https://www.youtube.com/watch?v=P-vNNjYQulg&t=6s)

Videos on Push and Legs were taken from Jeff Nippard
- https://www.youtube.com/watch?v=vcBig73ojpE&t=101s
- https://www.youtube.com/watch?v=bEv6CCg2BC8