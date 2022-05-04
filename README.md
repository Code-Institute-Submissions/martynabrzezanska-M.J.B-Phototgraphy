# M.J.B Photography

## User stories
This website is for people who are wanting to hire a professional wedding photographer to capture the photos, moments, and details of life's most sentimental event. While on the website they will be able to learn more about the various wedding packages available, view the gallery of previous customer's photography, and contact a photographer by filling out a quick and simple form. In addition, the user will be able to build initial connections by reading a brief introduction to the person behind the curtain.

>- **The typical end user wants to:**
>- Find the perfect photographer for their special day.
>- Find out more about different wedding packages available.
>- To see the possible end result by viewing the gallery section on the website. 
>- Be able to make contact with the photographer in an simple and straightforward manner.
>- Check out the social media accounts, and read the reviews given my previous customers.
>- Find out more about the services from checking the social media accounts. 

>- **A typical returning/previous user wants to:**
>- A previous customer would like to come back and use the services for another occasion.
>- A previous customer would recommend the services to others.

# Approach 
## Wireframes 
Three sub-pages present content for instant consumption on desktop, iPad, and mobile. The most critical content is found on the **home** page. From there, the user can enter the other two sub-pages by either clicking the links on the navigation menu or by interacting with the buttons or responsive packages boxes. From the footer area, the user can also access the other two pages through the choice of buttons, one for the gallery and the other for the contact page from where the user can make contact through form.  

# Developer Story and Goals
Hands-on experience to built a web development portfolio that looks and works flawlessly. Implementation of features, run test and gain valuable experience and problem-solving practice.

# Website Features 
## **Header**
The header is designed to be large enough to give breathing room to its elements and feel relaxed, while still hint that there are information visible below that you can navigate to. **The header contains the following elements:**

## Navigation Menu
A simple navigation system with clear names allows visitors to easily access the most useful pages. On the left side of the bar is a responsive logo, as well as a list of internal page links to the right. 

![Navigation Menu](/assets/images/readme%20images%20/navigationMenu.png)
## Background Image 
A background image serves as a user's first glimpse of the company and it's offering. A CSS gradient overlay was added to the image to obtain a better balance between the image and the overlay text and button.  

![Background Image](/assets/images/readme%20images%20/backgroundImage.png)

The background image contains the following: 

>- **Welcome Heading** 
A heading that greets visitors, and gives a positive connotation.

>- **Text Area** 
This area consists of a short poem about love.

>- **Click To Action Button**
A responsive button that changes the color on hovering. When the user clicks the button, they are taken to the contact page where they can learn about the person behind the curtain, and contact a photographer by filling out a quick and easy form.

**What is accomplished:**

1. The user knows more about the website and what is offers.
2. The user can easily navigate around the website. 
3. A shortcut to the contact section is provided to the user.

## **Wedding Packages**
In this section, the user is able to find out about the various types of wedding packages available. The transition attribute is used in this section so that when the user interacts with one of the three items, the property value changes gradually over a set period of time. Each element of this section also contain a responsive button with a fade in effect that when clicked takes the user to the contact page. 

![Wedding Packages](/assets/images/readme%20images%20/weddingPackages.png)

**What is accomplished:**

1. Lets the user know about the various types of wedding packages available.
2. When the user clicks on the link, they are directed to a contact page where they can make fill in a contact form. 

## **Image HTML**
This section includes an image that corresponds to the wedding's theme. It's black and white, and blends in well with the rest ot the website's content. 


![Wedding Packages](/assets/images/readme%20images%20/imageHTML.png)

**What is accomplished:**

1. It neatly complements the website's content.
2. The colors are constant and cohesive across the site.
3. It gives the user a glimpse of the gallery as well as the final product.

## **Footer**
The footer provides a gateway to information about the location and the telephone number, two responsive buttons that lead to either a gallery/ contact page, and links to the website's social media platforms. This section serves as an extension to the navigation menu by encapsulating the most significant sections of it and providing quick access to a well-structured list of navigational options.

The footer also contains copy right text for the website.

The footer had a black backdrop with white text, creating a great contrast that complements the navigation menu nicely. More importantly, the colors used are consistent with the rest of the content on the page.

![Footer](/assets/images/readme%20images%20/footer.png)

**What is accomplished:**

1. Lets the user connect to website's social media platform.
2. Gives the site owner a way to promote their business on social media.
3. Lets the user navigate around website content.

## **Gallery Page**
The gallery page consists of multiples of images arranged using the flex property. Each photo highlights the final products and services featured on the site. The gallery page allows the user to view several images at once, capturing the user's attention and eliciting feelings that will hopefully lead to the user wanting to make use of the services and contact the photographer by clicking either on the navigation bar or footer area with clickable contact button. 

![Gallery Page](/assets/images/readme%20images%20/galleryPage.png)

**What is accomplished:**

1. The user can see the final product of previous customer's photography.
2. The user can make judgement based on what they see and make initial decision whether or not they want to use the services. 

## **Meet Me Section**


## **Contact Form**
New visitor either hesitant and those wanting to make use of the service they can contact a photographer via contact form found on contact page. 

The contact form contains the following elements:

1. Basic personal information for both the main user and partner *required*.
2. Email address *required*.
3. Event type *required*.
4. Event date *required*.
5. Where did you hear about us? (checkbox).
6. Your love story (textarea).
7. Submit button.

The form itself is vertically stacked where label and inputs are placed on top of each other, making the sections looking clean while keeping functionality. The placeholder attribute indicate to the user what is expected in the input field. 

The form also has a bluish-colored background image, which goes well with the dark and white hues used throughout the website. By adding the background image the form stands out a little more and encourages users to send a message. 

![Contact Form](/assets/images/readme%20images%20/contactForm.png)

**What is accomplished:**

1. The user can make contact with the photographer in an easy, uncomplicated manner. 
2. The form is user-friendly, with suggestions on what to expect in each field and which        elements of the form must be completed before it can be submitted.

# Form Field Validation
The form fields are validated by HTML. All form fields are also type specific if applicable, meaning if a form field expects an email address, its input will not be accepted as valid if it is missing a correct email formatting.  

![Form Validation](/assets/images/readme%20images%20/form-validation.png)

# Deployment
The repository of this project is stored at GitHub and the site is deployed as GitHub page. Please (Click here!) to visit the project site.

# Testing
>- I tested that this website works in different browsers such as Chrome, Firefox and Safari.
>- I can confirm that the website is responsive, looks presentable and functions on all standard screen sizes using the devtools device toolbar. 
>- The content on the website contains clear information and structure. 
>- I verified that the form functions properly and that the most critical details require validation, which means that the input must contain the correct type value.

# Bugs 

# Validator Testing
>- HTML 
No errors were detected when passing the code through the official W3C validator.
>- CSS
No errors were found when passing through the official Jigsaw validator. 
>- Accessibility 
I confirmed that the colors and fonts are easy to read and accessible by running the website through the lighthouse in devtools. Here is the result: 

![Accessibility Score](/assets/images/readme%20images%20/accessibilityScore.png)

# Fonts and icons 
> - Fonts for text and headings has been imported through [Google Fonts](https://fonts.google.com/).
> - The icons in the footer were taken from [Font Awesome](https://fontawesome.com/).

# Credits 
**Content**
>- 

**Media**
>- The images used throughout the website were taken from [Pexels](https://www.pexels.com)


