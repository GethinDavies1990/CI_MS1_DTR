# Duck's Tap room

Duck's Tap room is a craft brewery aimed at people in the craft beer scene. Each week the brewery makes exciting new flavours and experiments these exciting new creation's with their punters. Duck's tap room's website will be useful to find the opening times of the establishment and also to get in touch to book a table. 

![Mock up](docs/features/mock-up.png)

- __Homepage__

  - The home page is split into 5 separate sections. Each section features a different UI component while keeping the branding consistent throughout the page. Each section is separated in blocks and is evidently noticeable. An ID tag was used for 'our story', 'How to find us' section to scroll the user to that point of the page.


### Features

- __Navigation Menu__

  - Featured on all pages, the navigation is fully responsive on all devices. It includes the 'Duck's Taproom' logo, a link to the 'book-table.html'form. And ID links to the 'our-story.html and how-to-find-us.html'

![Nav Bar](docs/features/nav.png)

-__Hero Section__

- The hero section includes a h1 which advertises the brewery making a new beer weekly and for visitors to visit to try these exciting new flavours.
-The hero section includes a CTA button which will take the user to the book table form.
-The image used is relevant to the website, including an ale and hops. hops are used in the craft beer scene to add exciting flavours to the beers.The image has an opaque overlay over the image to allow for the CTA button to be the main feature of this section to push user to book a table. 

![Hero Image](docs/features/hero.png)


- __Testimonial Section__

- This section will allow the user to see the testimonial's of recent visitors of the tap room. 
- It was styled using the rows and col classes with bootstrap to allow it to be responsive on all device size types.
- The testimonials are fictional made up by myself, the images of the customers were taken from envato.

![testimonial image](docs/features/testimonial.png)


- __Our Story Section__

  - This section showcases how the tap room started, this was styled with the bootstrap carousel.
  - The carousel has indicators to show the user which slide image they are currently on and toggle switches to go to the next and previous image.
  - Each carousel has a new image and new content to explain the growth the tap room has achieved.
  - Their is a container over the carousel to make the images have an opaque overlay. This was done so the content on each carousel item can stand out more against the image.

![Our Story](docs/features/our-story.png)

- __Want to Visit us section__ 

  - The 'Want to visit us' Section includes a google map through an embed link in a iframe element, it was placed in a div container to allow for it to be automatically resized on smaller devices.
  - This section also includes some relevant information for the user, Address/email/telephone information in the case the user will need these details. 

![Want to visit us](docs/features/how-to-find-us.png)

- __Footer__

  - The footer includes the taproom's logo and the social media icons, eac icon is a link to the respective's website. the links go directly to the social websites homepage. They include a aria attribute to allow users who use screen readers to understand what they are for. 

![Footer](docs/features/footer.png)

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- __The Sign Up Page__

  - This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address. 

![Sign Up](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Another feature idea

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process!