# Solar 
Website made to display benefits of using solar power and with a gallery displaying the 3 types of solar panel materials that can be used, and with a contact form for further questions.
Clients intrested in solar pannel types and wanting to know more. 

![Responsice Mockup](https://i.imgur.com/BsYmwpm.png)

## Features

### Existing Features
 

- __The landing page image__
  - Well filmed intro for the landing page, presenting the user with the goal of the website they are on.
  - Solar roof designing / installation.
![Landing Page](https://i.imgur.com/AABV3Le.png)

- __Navigation Bar__
  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Contact form page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.
![Nav Bar](https://i.imgur.com/oBn3UBp.png)

- __4 Detailed Benefits__
  - This section will allow the user to see exactly in more detail the several major benefits. 
  - This section will be updated as with more benfits over time.
![Detailed Benefits](https://i.imgur.com/liXhvwu.png)

- __5 Completed projects__
  - This section is displaying the company's finished projects with solar installment.
![Projects Done](https://i.imgur.com/aVdcSP4.png)

- __The Footer__ 
  - The footer section includes links to the relevant social media sites for Solar. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media
![Footer](https://i.imgur.com/mLXFhPN.png)

- __Gallery and Inspiration Images__
  - The gallery will provide the user with solar panel materials to see what they wish for aesthetically . 
  - This section is valuable to the user as they will be able to easily identify the types of solar roofs they can encounter.
  - User is presented with realistic and aesthethic designing for inspirational purposes.
![Gallery](https://i.imgur.com/DCs2a8C.png)


- __Panel Information and technology__
  - User is also presented at the bottom of the gallery page with additional information about the product quality and the technology behind each panel type.
![panel](https://i.imgur.com/UdDLa1o.png)

- __Contact Form__
  - This page will allow the user to get contact Solar to start their journey with the community. The user will be asked to submit their full name and email address, on top of that he/she can choose what type of inquiry they are about.
![contact](https://i.imgur.com/Z2SWWHO.png)


## Bugs/UserFeedback
- <h1>Early stage development</h1>
- When opening from some IOS devices the panel header miss-aligns
<img src="https://i.imgur.com/1VZ4SIu.png">

- On mobile device display ratio, the menu tab 'Home' is under contact form and not forming all 3 in row. This problem is only in Gallery and Contact Form pages
- This seems to have been fixed by adding the block-size: fit-content rule to body for 950px and down, code line 460.</p>


Menu bug
- I have fixed this by changing the margin-right of #menu li from 30px to 25px, code line 59.

<img src="https://i.imgur.com/qBZvLmi.png">
<img src="https://i.imgur.com/xYrFqdg.png">

### Testing
- The website was tested manually with Google dev tools on the following devices:

- iPhone SE (2nd generation)
- iPhone 11 pro
- iPhone 12/13 pro max
- iPad
- Galaxy S10
- Galaxy S20 Ultra
- Galaxy Note 20


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Credits 
- I want to credit Code Institute for the navigation bar design and hero image animation:
  - https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/4d85cd1a2c57485abbd8ccec8c00732c/?child=last

- To Css-tricks for the projects grids hover border effect: 
  - https://css-tricks.com/animating-border
- Panel information credit to: 
  - https://news.energysage.com/monocrystalline-vs-polycrystalline-solar
- For the animated hover underline I credit to 
  - https://www.w3resource.com/html-css-exercise/html-css-practical-exercises/html-css-practical-exercise-15.php#:~:text=Using%20HTML%2C%20CSS%20create%20an,place%20it%20below%20the%20content.
### Content 

- The text for the Home page was taken from Wikipedia Article.
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

__Programs Used__
  - Git was used for using the Gitpod terminal to commit to Git and push to Github.
  - Github - Github was used to store the project code and display the project in Github Pages. (https://github.com/)
  - Font Awesome - Font Awesome was used to add icons for the social links in the footer.
  - Google Dev Tools- Google dev tools where used to test and troubleshoot the webpage as well as fix problems with responsive design   and styling.
  - Google Fonts - Google fonts where used to import every font used in the website.
  - Imgur was used to store the images used for the snippets in this readme document. (https://imgur.com/)
  - Google devs lighthouse testing.

### Deployment
This game was deployed to github pages.

- Open the repository settings.
- Go to "pages" (found under "code and automation").
- Choose which branch to build from. You want to choose "main". Do not forget to save the settings.
- (If needed, choose a custom domain)
- Open the repository in github desktop (I used github desktop. You can do this in git too.)
- Choose to create a local clone (the first time you open your repository in github desktop, there should be a window asking if you want to create a clone)
- Copy the link to your deployed website (which can be found in the github pages settings, where you chose which branch to build from) and make sure it is operating as expected.
- The deployed website will now be updated when you push anything new to the repository.

#### Forking and cloning
- Forking is creating a new repository with the same content as the one you forked. 
    - This is done by going to the repository you want to clone, and clicking the "fork" icon in the top right corner.
- Cloning is used for making local copies of your code.
    - Cloning a repository with github desktop is easily done by clicking the green "code" button and choosing the "open in github desktop" option. If you do not have a clone already, github desktop will ask if you want to create a local clone. Click yes.
    - If you do it with git you have to write "git clone" and then specify what you want to clone.

The live link can be found here - https://bogdan933.github.io/Project-1/ 

### Screens
  - The quiz app has responsive design.
      - Normal desktop
      - 1280px wide and down
      - 992px wide and down
      - 748px wide and down


- Lighthouse scores 


- Desktop score
<img src="https://i.imgur.com/I4OZ5ke.png">
- Mobile score
<img src="https://i.imgur.com/nd9qNCk.png">

