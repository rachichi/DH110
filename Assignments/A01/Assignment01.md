# Assignment 1: Heuristic Evaluation

Rachel Liu | DH-110 | Fall 2022

## Tentative Title: Building Sustainability Through Competition

### About the project

Building sustainable communities is arguably one of the most important initiatives to ensure our future success. Unfortunately, the path to sustainability is shrouded in mystery and blocked by seemingly unattainable goals. If we truly want to value sustainability, we must begin by educating and engaging our youth. This project aims to make sustainable living accessible by creating a space where students can compete against others in exciting challenges for coveted prizes. This mobile application will not only equip the next generation of city-builders with knowledge on how to build a sustainable city but will generate a community of like-minded people as well. 

### Jakob Nielson's [10 Usability Heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/) Explained

| Number | Heuristic | Description |
|---|---|---|
| 1 | Visibility of System Status | Users should always be informed regarding the status of the app |
| 2 | Match Between System and the Real World | Users should be able to intuitively use the app as if completing a real-life task |
| 3 | User Control and Freedom | Users should be provided an easy way out |
| 4 | Consistency and Standards | Users should experience similar situations similarly |
| 5 | Error Prevention | Users should not experience conditions in which errors are prone to occur |
| 6 | Recognition Rather Than Recall | Users should not have difficulty retrieving relevant information |
| 7 | Flexibility and Efficiency of Use | Provide multiple ways to perform a task to make the platform accessible to all users |
| 8 | Aesthetic and Minimalist Design | Users should not experience visual elements that distract them from their task |
| 9 | Help Users Recognize, Diagnose, and Recover From Errors | Users should understand what went wrong if an error occurs |
| 10 | Help and Documentation | Users should be able to find and recieve help if needed |


### [Severity Ratings](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/) for Usability Problems by Nielsen Norman Group

The following rating scale was used to evaluate severity of usability issues:
| Rating | Description |
|---|---|
| 1 | Cosmetic problem only: need not be fixed unless extra time is available on project |
| 2 | Minor usability problem: fixing this should be given low priority |
| 3 | Major usability problem: important to fix, so should be given high priority |

Ratings are displayed in parentheses after each usability issue.

## Application 1: [Earth Rewards](https://earthrewards.net/)

### About
[Earth Rewards](https://earthrewards.net/) is a carbon footprint calculator application that encourages purchases from listed retailers to offset users' own carbon footprint. Although I do not align with the intentions of this app, as it is inherently for-profit, I believe the point system is a similar structure to the one I had in mind for my final project. 

<i> Note: The application must be downloaded to compare comments listed below to page-specific UI/UX. For ease, I have included screenshots where possible. <i> 

### Heuristic Evaluation

#### 1. Visibility of System Status
* Within the <i> My balance <i> section, the “Transaction is being processed…” notification is not automatically updated when complete. It is up to the user to reload the page to see any changes in status.  (?)

* Similarly, within the <i> Retailers <i> section, the response from marking a store as “favorited” is not immediate and may lead to rapid, frustrated clicking from the user. (?)

<p align="center">
  <img src="../Images/search-query-2.PNG" alt="Search query no immediate results" width = "300px"/>
  <img src="../Images/search-query.png" alt="Search query irrelevant results" width = "300px"/>
</p>

> *Recommendation: Display continuous and immediate updates so users are always aware of current app status. Within the <i> My balance <i> section, this means automatic updating the page before users feel the need to manually reload. On the other hand, on the <i> Retailers <i> page, speed up feedback time in response to clicking the heart.*

* The structure of the app is not clear. Besides the home page, each individual section has no visible tie back to the previous. (?)

<p align="center">
  <img src="../Images/appointment-request-progress.PNG" alt="Appointment request progress capture" height = "300px"/>
</p>

> *Recommendation: Create a more effective menu bar by optimizing use of icons, decreasing menu size, and apply it to all pages possible so users are always aware of their location in the application.*

#### 2. Match Between System and the Real World
* There is an overload of jargon and various metrics on the page with no simple method to understand them. Within one section, vocabulary includes “Blockchain,” “Offset CO2,” “Pre-Populated Offsets,” “Custom Offset,” “Quick Offsets,” and “Personal Offsets.” Metrics include “Kg of CO2,” “pints,” “Liters,” “dollars,” “points,” E-missions,” “Lessons,” “Impacts,” and “Earth Rewards.” The feeling of overwhelmingness is immediate and obvious. (?)

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation: Decrease vocabulary to increase learnability. For example, establish <i> one <i> obvious point system, such as "Earth Rewards", and stick with it. For example, Khan Academy (energy points) and Reddit (Reddit karma) are websites/webapps which have found success in using a single point system.*

#### 3. User Control and Freedom
* When accidental pop-ups occur, a user's automatic and intuitive action is to click outside of the popup to quickly remove themselves from the situation. Unfortunately, in this app, clicking on the darkened area around the pop-up does nothing but cause frustration. (1)

> *Recommendation: Provide users with an easy emergency exit by making the darkened area around the pop-up a clickable area to exit. *

#### 4. Consistency and Standards
* There are a few small standardization issues within the app. Firstly, clicking the “x” on the right side of a search bar typically clears existing text within the search space. In this app, that “x” exits the user out of the search area and collapses the keyboard. Secondly, it is standard to expect that clicking on a user's profile picture allows them to change it. Thirdly, clicking a section icon more than once typically scrolls users up to the top of a section. This app does not fulfill any of the mentioned expectations.(2)

<p align="center">
  <img src="../Images/homepage.PNG" alt="Mayo Clinic homepage"/>
  <img src="../Images/covid-19-page.PNG" alt="Mayo Clinic COVID-19 page"/>
</p>

> *Recommendation: There exists quite a few instances within the app where users expect outcomes that are not received. First, re-establish functionality to the status-quo by allowing the “x” on the search bar to clear the text in the search space. Second, make the profile picture clickable along with a popup which allows quick profile photo changes. Thirdly, automatically route users to the top of the page, along with an automatic reload when the section icon is clicked.*

* The white space between a menu item and the edge of the phone differs between pages and seemingly at random.  (3)

> *Recommendation: Design with visual consistency. All pages should have the same or similar formats, colors, and feel. This will increase trust in the product.*

#### 5. Error Prevention
* In the “Lessons” section, users can learn about how certain actions contribute to sustainability. Yet it is easy to accidentally swipe out of a lesson and lose progress. 

<p align="center">
  <img src="../Images/appointment-modal-window.PNG" alt="Modal window asking about COVID-19 vaccine" width="700px"/>
</p>

> *Recommendation: Despite providing users with a mark that represents progress, users are not able to swipe left of right to continue forwards/backwards with the lesson. Enable users to use the swipe function when swiping in the middle of the page, and allow them to swipe out (with a warning pop up that progress will be lost) only when doing a full swipe from the edge of the page.*
  
* While clicking around the app I accidentally clicked the “Log out” button. Without warning, I was automatically logged out of my account. Having to go through the whole sign in process again is an immediate deterrent.  

<p align="center">
  <img src="../Images/appointment-modal-window.PNG" alt="Modal window asking about COVID-19 vaccine" width="700px"/>
</p>

> *Recommendation: Provide pop up messages which warn users about outcomes of a possible accidetal action and provides an option to return to the application. This is important because repetitive log-in processes are cumbersome and frustrating.*

#### 6. Recognition Rather Than Recall
* The Search function acts more like a filter rather than an actual search function. Storefront icons dissapear as letters are typed but it is not obvious what stores are still available. 

<p align="center">
  <img src="../Images/diseases-and-conditions.PNG" alt="Diseases and conditions page" width="500px"/>
</p>

> *Recommendation: As a user types into the search bar, recommend stores in a clickable dropdown menu underneath.*

#### 7. Flexibility and Efficiency of Use
* The app is static and unchanging. Assuming a user has fulfilled the lengthy learning curve in order to learn how to use this app, there are no options for customization if it is wanted or needed

![Homepage of Mayo Clinic showing search box](../Images/homepage.PNG)

> *Recommendation: In addition to currently existing sections in the "Edit Profile" section, create a section for customization and accessibility where users can toggle options on and off.*

#### 8. Aesthetic and Minimalist Design
*Icons used in the “Offset” section are designed with a variety of unnecessary colors. At first glance, it seems as if the colors contribute to the categorization of the items on the page, but further scrutiny shows it does not. 

<p align="center">
  <img src="../Images/nav-care-at-mayo-clinic.PNG" alt="Navigation menu (Care at Mayo Clinic)" width="250px"/>
  <img src="../Images/nav-research.PNG" alt="Navigation menu (Care at Mayo Clinic)" width="250px"/>
</p>

> *Recommendation: Refine the theme of the app to a smaller list of icons and colors. Only use colors where necessary. For example, the list of icons should be one color.*

#### 9. Help Users Recognize, Diagnose, and Recover From Errors
* If a user is unable to log into their account using the menu options at the bottom of the screen, the error message that pops up is uninformative; simply stating “There was an error while trying to log you in.” 

![After clicking Yes in the modal window box](../Images/clicked-yes.PNG)

> *Recommendation: Provide users some direction in the error message by including a button which says “try a different log-in method.”*

#### 10. Help and Documentation
* The FAQ is short and difficult to access. If by chance your question is not available, there is no simple way to contact the creators. Every “get in touch here” hyperlink automatically routes users to Apple’s “Mail” app. Since I am not signed into that application, and no email address is actually listed, I may not ever get my questions answered. 

<p align="center">
  <img src="../Images/appointment-faq.PNG" alt="Appointment FAQ page" width="500px"/>
</p>

> *Recommendation: Provide live chat function to provide immediate help to users. If there is no budget or bandwidth to do so, state the company email at the top of the FAQ, hyperlinked if users prefer to click. *

### Overall Assessment

<mark> NOT COMPLETE!! </mark>



## Website 2: [Chinatown Service Center (CSC)](https://www.cscla.org/)

### About
[Chinatown Service Center (CSC)](https://www.cscla.org/) is a community-based Chinese-American health and human services organization that advocates for and provides services to immigrants and other communities. CSC's resources, including a Community Health Center that provides comprehensive healthcare, dental services, and behavioral services, are available in various Chinese dialects like Cantonese, Mandarin, Toishan, and Chiu Jou, as well as other languages like Vietnamese and Spanish.

My goal is to make their website much more usable, especially for primary users of CSC's services, including low-income, non-English speaking, and elderly users.

### Heuristic Evaluation

#### 1. Visibility of System Status
* When a user hovers over the top navigation menu, only the "Home" button changes color. The rest of the menu items do not provide color feedback, and simply displays the dropdown for each. Furthermore, it takes a while to load each dropdown at times. Users would have difficulty understanding whether the website is responding to their movement or clicks. There is, however, a color change to help the user recognize the page they are currently on. (3)

<p align="center">
  <img src="../Images/nav-services.PNG" alt="Navigation Menu, Services" width="350px"/>
</p>

> *Recommendation: Make sure that there is some kind of feedback (e.g. color change) when the cursor hovers over each menu item.*

#### 2. Match Between System and the Real World
* Some of the icons for the Community Health Center page do not entirely match our perception for each category. The happy face doesn't really reflect Behavioral Health and the Medical Clinic icon just looks like a house (the medical cross is very small). The tooth is also difficult to see when Dental Clinic is selected (and inconsistent with the other icons). (1)

<p align="center">
  <img src="../Images/community-health-center-icons.PNG" alt="Community Health Center icons"/>
</p>

*Recommendation: Use more literal and commonly accepted icons for the Behavioral Health and Medical Clinic icons (see examples [here](https://thenounproject.com/term/mental-health/3306335/) and [here](https://thenounproject.com/search/?q=medical&i=2468231)). Make sure icon styles are consistent as well.*

#### 3. User Control and Freedom
* The image carousel on the homepage moves very slowly and also responds to clicks very slowly, so users are surprised when they actually animate. It can be frustrating if users want to look through the gallery at their pace. (3)
* The image carousel on the Community Health Center page auto-forwards and moves much too quickly, to the point that clicking the small arrow controls doesn't allow the user to view the image they want to see (unless they realize they can click the image to see it in full screen), which is very frustrating. The carousel looks almost like an advertisement, which means it will likely be ignored. (3)

> *Recommendation: Test users to see what the right timing for carousels would be. There should be enough time for users to read the text and process the information on each image. Use bigger arrows so that users can easily click them, and make sure the carousel is responsive to clicks. Add a visual indicator to show where the user is in the image gallery.*

#### 4. Consistency and Standards
* The top navigation menu is not consistent with normal webpages, which makes it difficult to use and grow accustomed to. (3)

<p align="center">
  <img src="../Images/nav-bar.PNG" alt="Top Navigation Menu"/>
</p>

> *Recommendation: Reorganize the top navigation so that it complies with standards. For example, Hours & Locations can go under "About", Gala 2020 does not need to be displayed, and Vita 2021 should be kept under services (and should be renamed Free Tax Prep or something recognizable, since not everyone will know what VITA is).*

#### 5. Error Prevention
* Phone numbers change based on which tab of the Community Health Center page the user is on. However, it is difficult to recognize this because these phone numbers aren't displayed below the tabs. It is easy for users to call the wrong number or send an email to the wrong email address. (3)

<p align="center">
  <img src="../Images/behavioral-health-contact.PNG" alt="Contact information for Behavioral Health" width="550px"/>
  
  <img src="../Images/dental-clinic-contact.PNG" alt="Contact information for Dental Clinic" width="550px"/>
</p>

> *Recommendation: Put the tabs above the content so that users know what information is relevant to which department. Put the contact information in a consistent and easy-to-find location for each tap. Alternatively, direct users to a contact page where they can easily find where they should contact.*

#### 6. Recognition Rather Than Recall
* When you hover over the top navigation menu, there is no indication of which menu item's dropdown is being displayed, forcing users to recall which of the menu items they were looking at. This also makes it more difficult for users to remember how they got to a certain page in the future. (2)

<p align="center">
  <img src="../Images/nav-services.PNG" alt="Navigation Menu, Services" width="350px"/>
</p>

> *Recommendation: Connect the dropdown box with the menu item title to show that the dropdown is under that header.*

#### 7. Flexibility and Efficiency of Use
* There is no search bar on the website. Given the extent of content and resources they provide, it would be very helpful to be able to search keywords that will lead users to the information they are looking for. (2)

> *Recommendation: Implement a search function to allow users another option to efficiently navigate through the website.*

* On the homepage, the first image is about free COVID-19 vaccines. The image, however, is not clickable and does not lead to another page with the details, as one would expect. Instead, the user must look through the website to find the full image/pdf. (3)

<p align="center">
  <img src="../Images/csc-homepage.PNG" alt="CSC homepage"/>
</p>

* I was able to find it under "Upcoming Events" at the bottom of the homepage, where users are unlikely to scroll to. Even then, the information was elusive - the carousel constantly autorotates through random images/pdfs of different events, and the only way to navigate through them is through the left and right arrow keys. Furthermore, although there is an Events category under "More" in the top navigation menu, it is not clickable. (3)

<p align="center">
  <img src="../Images/upcoming-events-2.PNG" alt="Upcoming Events carousel with free vaccine event information"/>
</p>

> *Recommendation: Because these free events are an integral part of CSC services, it makes sense to put a working Events link in the top navigation menu. On the Events page, separate upcoming events from past events. If possible, provide the information directly on the page rather than in image or pdf format so that users don't have to open another tab or window to view the information. Organize events by category, clearly provide dates and times, show relevant pictures.*

#### 8. Aesthetics and Minimalist Design
* Throughout the website, we see an unappealing interface due to incorrect placement of features, inconsistent fonts, colors, and other design aspects, low-quality images, cluttered and conflicting elements, and web developer mistakes. Altogether, the website is confusing for any user and lowers the credibility of the organization. The Community Health Center homepage, in particular, demonstrates this well. (3)

![CSC Community Health Center homepage](../Images/community-health-center-homepage.PNG)

> *Recommendation: Firstly, we need to fix the web developer mistakes so that the features are at least visible. For instance, the language switch needs to be fully visible so that users know they can switch the language of the website (important for the large, nonnative English-speaking user base). Next, de-clutter the website by reorganizing the information presented. For example, it is unnecessary to place the Community Health Center description at the beginning of every tab's page; use that real estate for the menu itself. Lastly, make sure that a design guideline is used so that font sizes, spacing, and colors are appropriate for seniors and consistent throughout.*

* The transparency of the tall fixed navigation menu dominates the layout of the page, and is very distracting. The menu is difficult to see and use, especially as users scroll down the page and there is text under the menu. (3)
* The social media icons don't need to be fixed because they can interrupt content. The user base likely doesn't use much social media anyways. (1)

> *Recommendation: Make the navigation menu opaque, and make it thinner by using the full width of the page and including only the necessary menu items so that more information can be displayed at a given time. Put social media icons in the footer, or at the top right if social media is actually used a lot by users (unlikely).*

#### 9. Help Users Recognize, Diagnose, and Recover From Errors
* When the wrong account information is entered on the patient portal, there is no indication of whether the username or password was incorrect (or both). (1)

> *Recommendation: Tell users which field is incorrect so that they can only fix what's needed.*

#### 10. Help and Documentation
* Virtually no help or documentation is provided on the website; the email and phone number are prominently displayed, so it is assumed that people would simply call or email to make an appointment or request information. Common information (such as what insurance they accept, phone numbers for different departments, how to request a "token" to access the patient portal) is randomly dispersed throughout the website. (3)

* A lot of information tends to be displayed via images and brochures, but it is difficult to find them. (3)

> *Recommendation: Consolidate important general information on one page so that users are not completely confused. Provide a link to the contact page instead of randomly displaying the phone number and email. Provide more guidance to users on each page; there are many different departments, phone numbers, and locations. For example, who, where, and when exactly should a person contact if they are a new patient?*

### Overall Assessment

A lot of work needs to be done in many areas, but the areas to focus on first are probably flexibility & efficiency of use and aesthetics & minimalist design. Their health resources are invaluable to many low-income, immigrant families and their seniors, so being able to access that information easily should be prioritized. Also, an important feature to fix first is the visibility of the language switch, since many of their users may be Chinese monolinguals. The website is very harsh to look at in general, making it very difficult to use and makes CSC look unreliable. An update on aesthetics should therefore be one of their next steps.

