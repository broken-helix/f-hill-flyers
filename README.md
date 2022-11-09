# **Forest Hill Flyers**
## **Site Overview**

Forest Hill Flyers is a local drone flying club in Forest Hill, a town and area in south-east London.  
They offer drone pilots places to fly, technical support and advice and community events, such as social events and day trips out of London.  
Whilst open to all members, the club has a great deal to offer people who are relatively recent to the world of drones.  
The creators of the club have asked for a web site to spread the word about what they have to offer and allow prospective members to complete a form to make contact and get more information about the group and events.<br><br>
​
![Responsive Screenshot](/docs/am-i-responsive-screenshot.jpg)
***

## Table of contents:
1. [**Site Overview**](#site-overview)
1. [**Planning stage**](#planning-stage)
    * [***Target Audiences***](#target-audiences)
    * [***User Stories***](#user-stories)
    * [***Site Aims***](#site-aims)
    * [***Color Scheme***](#color-scheme)
    * [***Typography**](#typography)
1. [**Current Features**](#current-features)
    * [***Header Section:***](#header-section)
    * [***Page Title:***](#page-title)
    * [***Navigation Bar***](#navigation-bar)
    * [***Header Image***](#header-image)
    * [***About Section***](#about-section)
    * [***Why Fly Section***](#why-fly-section)
    * [***Events Section***](#events-section)
    * [***Contact Section***](#contact-section)
    * [**Footer**](#footer)
1. [**Future-Enhancements**](#future-enhancements)
1. [**Testing Phase**](#testing-phase)
1. [**Deployment**](#deployment)
1. [**Tech**](#tech)
1. [**Credits**](#credits)
    * [**Honorable mentions**](#honorable-mentions)
    * [**General reference**](#general-reference)
    * [**Content**](#content)
    * [**Media**](#media)
***

## **Planning stage**
### **Target Audiences:**

* New owners of drones with no experience
* Drone pilots with some experience 
* Professional drone pilots looking to network with other pilots
***
### **User Stories:**

* As a user, I want to see the subject matter of the page.
* As a user, I want to navigate the page to find what I require quickly and easily.
* As a user, I want to learn more about the benefits of joining the club
* As a user, I want to be able to contact the club
***

### **Site Aims:**

* To inform the user of the existence of the club
* To inform the user about the benefits of joining an established club
* To inform the user of the events they can get involved with
* To offer the user an opportunity to get in contact
***

### **Color Scheme:**

The color scheme was designed to incorporate blues (#00063D and #0A6ACB) and warm colors (#F26419 and #F6A02D).  
The colors were selected to associate with blue skies and sunsets, which are desirable for photography, with a complementary neutral background (#EBEBEB).  
Sections alternate between blue and orange, to assist in separating the different sections as the user scrolls down the page.
Colors were selected using the coolors color palette generator.  <br><br>

![Coolors Palette](/docs/blue-orange-palette.jpg)
***

## **Typography**

* Throughout the page, there are two fonts used:
  * Poppins - For all headings. 
  * Quicksand - for all content text.
​
* Quicksand was chosen for its less formal sans serif style and incorporation of less formal 'rounded' letter 'a'.
* Poppins was selected as a complementary font for the titles, as Quicksand lacked the impact for headings when scaled up in size.
* All fonts were sourced from Google fonts, as stated in the credits.
***

## **Current Features**

#### *Header Section:*

* The Header section contains the H1 page title and navigation links.
* The section is 'sticky', so remains in place at the top of the page when scrolling down or selecting the navigation links.
* A bold orange color (#F26419) was used for the background to provide a clear contrast with the rest of the page.

#### *Page Title:*

* The H1 page title contains the name of the clu for whom the website is built.
* On smaller screen sizes, the title is centered to provide a consistent centered view in keeping with the rest of the page on narrower screen sizes.
* On larger screen sizes, the title is positioned to the left hand side, to provide a clear break between the title text and the navigation links.
​
#### *Navigation Bar:*

* The user is given links to each section of the page in the header section, which scroll the page down to the relevant section for easy navigation.
* The navigation links, along with the header, have been made 'sticky' so that they are always visible on the page, allowing the user to link to other sections without having to scroll to the top.
* On smaller devices, the navigation links are centered and well-spaced across the page, with padding below the links, to facilitate their selection on a mobile phone.
* On larger screen sizes, the navigation links are positioned to the right and grouped together, to seperate them from the site title.

![Mobile Header](/docs/mobile-header.jpg)

![Desktop Header](/docs/desktop-header.jpg)

#### *Header Image*

* The header image, displayed below the header content, is an aerial photograph above Forest Hill, where the club is based.
* The image is responsive, growing in size as the viewport increases, whilst maintaining proportions.
​
#### *About Section:*

* The about section provides users with a brief overview of what the club is about.  
* The section is split into three parts, an introduction, a central image and a brief overview of activities the club offers.
* On smaller screen sizes, the parts are displayed in a row down the page.
* On larger screen sizes, the parts are displayed as columns across the page, with text either side of the central image.

![Mobile About Section](/docs/mobile-who-section.jpg)

![Desktop About Section](/docs/desktop-who-section.jpg)

#### *Why Fly Section:*

* This section provides users with more detailed examples of activities and opportunities the club offers.
* The section again features a central image, with left and right sub-headings split into two parts each.
* Each sub-heading has an icon which provides a visual cue to the user as the the subject of the sub-heading.
* On smaller screens, the parts are displayed in a row down the page.
* On larger screen sizes the parts are displayed in a column across the page, with two sub-headings either side of the central image.

![Mobile Why Fly Section](/docs/mobile-why-fly-section.jpg)

![Desktop Why Fly Section](/docs/desktop-why-fly-section.jpg)

#### *Events Section:*

* This section shows users examples of regular events the club offers and an example 'one-off' day trip out of London.
* Users get an impression of the sorts of events they can expect from being a member of the club.
* The section shows that the club is currently active.
* On smaller screen sizes, the events are displayed vertically down the page.
* On larger screen sizes, the events cards are displayed horizontally across the page.

![Mobile Events Section](/docs/mobile-events.jpg)

![Desktop Events Section](/docs/desktop-events.jpg)

#### *Contact Us Section*

* This section provides users with a method of making contact with the club, via a form.
* On smaller screen sizes, the form is styled to fit narrower viewports, with form labels and inputs stacked vertically.
* On larger screen sizes, the form is stretched across the page, with labels displayed horizontally, in line with inputs.
* Users are able to provide their name and contact email address and submit a message to ask questions or show their interest in the club.
* Upon submitting the completed form, users are taken to a thank you page which shows users that their form has been submitted.

![Mobile Contact Section](/docs/mobile-contact-section.jpg)

![Desktop Contact Section](/docs/desktop-contact-section.jpg)

![Mobile Thank You Page](/docs/thank-you-page.jpg)

![Desktop Thank You Page](/docs/desktop-thank-you-page.jpg)

#### *Footer Section*

* The footer section contains links to social media platforms where the club uploads images and video.
* The social media links allow users to see more detail about past events and provide further ways to connect with the group.
* The links are styled to display as icons and increase in size and the page size increases.
* The icons were sourced from FontAwesome.
***

## **Future-Enhancements**

* The club have expressed a desire to host a blog page in the future, which will discuss events, information about flying drones and legal considerations.  This could be in the form of inclusion of social media posts, automatically added to a page, to allow the owners control over adding the content.
***

## **Testing Phase**

* Responsiveness - The page was tested for responsiveness on screen sizes throughout the development stages, using chrome dev tools, which allowed the page to be adjusted to display on small and large screen sizes.  The site was also tested using firefox on a desktop, on an android mobile phone using chrome, on an ipad and iphone 6 using safari and found to display correctly.
​
* Functionality - The links in the navigation have been selected individually to ensure they connect to the correct sections.  The form has been submitted without each input being completed to ensure that error messages are displayed, including entering email addresses without the '@' symbol.  The form has been submitted with correct entries to ensure that the Thank You page is displayed after submission.  The link returning users to the main page has been selected to make sure it is functioning correctly.

* Contrast - The contrast on the page was checked using the WCAG Color contrast checker plugin in chrome and found to pass the tests.

![wcag color contrast checker results](/docs/contrast-check-screenshot.jpg)

* Lighthouse - The site was checked using the Lighthouse chrome plugin and found to pas the tests.

![lighthouse results](/docs/lighthouse-results-screenshot.jpg)
​
* Validators

![html validator](/docs/html-validator.jpg)

![css validator](/docs/css-validation.jpg)
***
​
## **Bugs**

* Issue - When using the links to navigate the page, the top parts of sections were hidden by the sticky header.
* Cause - The sections were displayed at the top of the page and the sticky header remained in place.
* Resolution - Sections were given a class called scroll and styled in the css file to have a margin equal to or greater than the height of the header section.<br><br>
  
* Issue - When displaying the events card horizontally on larger screen sizes, some cards displayed with a different height to others, dependent on the text contained within.
* Cause - The events cards sizing was dependent on the text formatting within the card.
* Resolution - A css style of 'flex-grow: 1' was added to the cards so that they expanded vertically to take up the available space.  
***

## **Deployment**

I deployed the page on GitHub pages via the following procedure:
​
1. From the project's [repository](https://github.com/broken-helix/f-hill-flyers), go to the **Settings** tab.
2. From the left-hand menu, select the **Pages** tab.
3. Under the **Source** section, select the **Main** branch from the drop-down menu and click **Save**.
4. A message will be displayed to indicate a successful deployment to GitHub pages and provide the live link.
​
The live site can be found at the following URL - [Forest Hill Flyers](https://broken-helix.github.io/f-hill-flyers/).
***

## **Tech**
​
The following technologies were employed in the creation of the site:
​
- HTML
- CSS
***

## **Credits**

### **Honorable mentions**

* The input from my mentor, Richard Wells, was invaluable in providing support, directing me towards such technologies such as flexbox and showing me ways to check text contrast, use lighthouse and guiding me through the ReadMe file process.
***

### **Content:**

* Fonts were sourced from [Google Fonts](https://fonts.google.com/).

* Icons for the social media links and why fly section were sourced from [Font Awesome](https://fontawesome.com/icons).

* Problems with sections displaying under the sticky header were resolved based on support offered on this [stack overflow submission](https://stackoverflow.com/questions/13036142/anchor-links-to-start-below-the-header-which-is-fixed-at-the-top/), which gave clues about using a margin-top to position the content below the header.
***

### **Media:**

* The main header image was provided by the web page author
* The circular images contained in the About and Why Fly sections were located on [Pexels](https://www.pexels.com/) and available for free useage.
* About Image: [Kobe- - Man Standing Beside Woman Playing Drone](https://www.pexels.com/photo/man-standing-beside-woman-playing-drone-1334517/)
* Why Fly Image: [Matt Holobar - Flying Drone](https://www.pexels.com/photo/flying-drone-1757697/)