# DH110 - Rachel Liu

## Helping Busineses Improve Sustainability Impact 
### Rachel Liu in DH110 Fall 2022
This project surrounds sustainability and follows the following rubric...

https://drive.google.com/file/d/1osfn4W441-0e0JkM66creKbx06Rs8PBa/view

![Screenshot of Site 1](site1.png)

# Exploring Stories of Asian America

## Assignment 1: Heuristic Evaluation
Chu Yin Wen | DH-150 | Spring 2020

Project description:

Understanding the history of our people empowers us to stand in solidarity with our contemporary communities. For Asian Americans, our histories are not always easily accessible through mainstream institutions. Throughout the history of the US, the narratives of Asian Americans have been marginalized and erased. With this project, I want to create a digital space for those narratives to be shared. Specifically, I want to create a digital museum that is accessible by people of diverse backgrounds. This includes people of different ethnicities, ages, and technological abilities. 

By creating this digital museum, I hope to amplify the voices of the Asian American community within the public sphere.


### Severity Ratings in Heuristic Evaluation - [Nielson Norman Group](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/)  
1 = Cosmetic problem only: need not be fixed unless extra time is available on project  
2 = Minor usability problem: fixing this should be given low priority  
3 = Major usability problem: important to fix, so should be given high priority

## Website 1: [Virtual Asian American Art Museum (VAAAM)](https://vaaam.tome.press/)

The VAAAM is a digital humanities project that features curated materials from US and international archives and aims to visualize and analyze Asian American art history. By creating this digital museum, the VAAAM enables researchers, art educators, and the public to access these narratives.

Why I chose this website:

This was one of the few websites which shared my vision of giving voice to Asian American stories through a virtual museum. 
In particular, it provides rich context for each piece and focuses on the Asian American artist as an individual rather than just focusing on their art as pieces in a digital archive. 
It will serve as a reference for my final project, and I hope to use it as material for usability testing. 

Overall evaluation:

At first glance, the website seems to offer a creative and modern take on an online museum.
It is innovative in its aspirations, although its execution could be improved. The homepage appears to be blank at first, which puzzled me a bit.
This museum appears to be targeted to academic consumers, given the many citations and intellectual discussion of the theory and politics behind the art. 


#### 1. Visibility of System Status 
* Immediately on landing on the home page, there is no text or content on the screen, but just a fullscreen image of a painting and a hamburger menu icon in the top left. Though it makes for a unique and creative opening for a digital museum, it is a little disorienting and could make the user wonder if the page has fully loaded. The user has to hover over the hamburger menu before seeing the title and description of the website. 
 **(2)**    
 
 ![homepage](/images/vaaam_homepage.png)
 
*Recommendation: Do not show the forwards and backwards buttons when the user hovers over the side menu to eliminate confusion. This way, users know that they cannot interact with the buttons while hovering over the side menu.*
  
* A forward and backwards navigation button both appear onscreen when the user hovers over the side menu. This suggests that the user can interact with these buttons while hovering over the menu. However, when the user tries to click them from here, the buttons disappear and the user is unable to navigate forwards/backwards. In order to advance or go back, the user must directly hover over the left or right arrows themselves (not while side menu is open).
**(2)**    
  
  ![navigation](/images/vaaam_menuLinks.png)
  
*Recommendation: Do not show the forwards and backwards buttons when the user hovers over the side menu to eliminate confusion. This way, users know that they cannot interact with the buttons while hovering over the side menu.*
  
#### 2. Match between system and the real world
* To navigate backwards and forwards, websites usually allow users to click a forwards/backwards button. However, on this site, users can navigate through the entire site by scrolling up and down or by clicking the forwards and backwards arrows. This does not match the user's initial spatial conception of the site map, as it is unintuitive to think that navigating backwards/forwards on the horizontal axis is equivalent to navigating up/down on the site's vertical axis.
**(3)**  

*You can scroll down or click the next arrow to get to the About page*

![scrolling navigation system](/images/vaaam_scrollingNav.png)
  
 *Recommendation: Either remove the forwards/backwards arrows that allow the user to move left and right, or remove the ability to scroll up and down to access the previous and next pages.*

* On the side menu, there are links labeled with names "Michiko Itatani" and "James Numata." Unless the user has already visited the site or knew of them beforehand, they would not know that these are the artists featured in the museum. The links are ambiguous and do not clearly communicate their purpose to the user.*
**(3)**  
  
  ![menu links](/images/vaaam_menuLinks.png)
  
 *Recommendation: Add a header in the menu that reads "Artist Collections" and include the links under this header.*
 
 #### 3. User control and freedom
 
 * There is no way to skip to a specific piece of art in the exhibit. The user must step through each screen. This is very cumbersome and drastically reduces the amount of user control and freedom.
 **(3)**
 
 *Recommendation: Add a menu that allows users to select which piece of art to view next.*
 
 * Because this site is focused around the narrative of an artist and the story behind the process of creating a piece, there are lengthy passages. Many photographs and related art pieces are buried among these passages, and there is no way to navigate directly to the visual content.
 **(3)**
 
 *Recommendation: Include an outline of the page at the top, which will allow users to get an overview of what the page contains.*
 
 #### 4. Consistency and standards
 * To open the side menu, the user must hover over the left side of the screen. They cannot open it by clicking the hamburger menu icon. To close it, the user can either stop hovering over it or click the hamburger menu icon to close it. This shows a lack of consistency in the way the user can interact with the same icon.
 **(2)**
 
 *Recommendation: Allow the user to click on the menu icon to open the menu. A click will result in the menu staying on screen regardless of where the user's cursor is, while just hovering over the menu will make the menu's visibility contingent on the position of the cursor.*
 
 * Some images on the site are embedded in the page alongside text, while others are hidden behind captions that toggle open. This does not appear to be systematically done, with no clear differences between the former and latter types of images.
 **(2)**
 
*Before toggle* ![toggled before](/images/vaam_beforeToggle.png) *After toggle* ![toggled after](/images/vaam_afterToggle.png) 
 
 *Recommendation: Keep consistency by embedding all of the images directly on the page and removing the need to toggle to view them.*
 
 #### 5. Error prevention
 
 * There is little user text input on this site, so there is not too much risk of the user making an error in submitting something. However, because of the confusing navigation layout, there is a possibility that users will accidentally scroll down and end up on the next page when their intention was to stay on the same page.
 **(2)**
 
 *Recommendation: Add in floating text that notifies you when scrolling down will take you to the next page.*
 
 #### 6. Recognition rather than recall
 
 * The side navigation menu disappears every time the user moves their mouse off of it. This menu is the only way to navigate the site, and having it continually appear and disappear can be jarring. The user cannot reference it without hovering over it. 
 **(2)**
 
 *Recommendation: Do not make the menu automatically disappear when the user hovers off of it. Instead, add in an exit button to allow users to click out of it manually.*
 
 * Similarly, there is a button labeled with the next page's title and an arrow indicating that the user should click on it to advance. When the user does not hover over it, the title disappears. This requires the user to recall the title of the next page to decide whether or not to advance.
 **(2)**
 
 *Recommendation: Keep the title visible in small text above the arrow, and do not make its visibility contingent on the user's hover.*
 
 #### 7. Flexibility and efficiency of use
 
 * There is no way for more experienced visitors of the site to filter art pieces by specific category, artist, or collection. All users can only step through page by page.
 **(3)**
 
 *Recommendation: Add a search feature or a menu that allows users to find a piece quickly by author, genre, or collection.*
 
 #### 8. Aesthetic and minimalist design
 * At first glance, the site is very aesthetically minimal and sophisticated. However, once the user hovers over the side menu, nearly all of the screen gets covered with navigation buttons and labels that have generous padding and a black background. 
 **(1)**
 
 *Recommendation: Do not make the labels of all navigations appear on hover. Instead, just make them either perpetually visible and non-obtrusive by removing the black background.*
 
 #### 9. Help users recognize, diagnose, and recover from errors
 
 * Under the "Selected Map of Exhibitions and Publications," there is an error loading the Google Map content. There is no explanation of why this error occurred nor how to address it. Additionally, the map is overlaid with text that says "For development purposes only." This is vague and out of context for users. There is no clear purpose for the map. The map is not a main feature of the site, but it is still distracting and takes up a large portion of the page. 
 **(2)**
 
 ![map error](/images/vaaam_mapError.png)
 
 *Recommendation: Remove the map completely, or replace it with a list of locations where the artist has exhibitions and publications.*
 
 * There are pages that are password protected. Given that the site is supposed to mimic a public museum, it seems odd to have any password protected exhibits. Even more so, there is no explanation as to why it is password protected. This may be off-putting to users.
 **(2)**
 
 ![password protected](/images/vaaam_password.png)
 
 *Recommendation: Hide password protected pages entirely, or add a description as to why these pages have been password protected.*
 
 #### 10. Help and documentation
 
 * Despite the rather unique layout and purpose of the site, there is no guide/onboarding process to help users become familiar with the site. As this is supposed to be a fully digital museum experience, it is important to guide the users through the process in a clear and well-documented way. The site does a poor job of this.
 **(2)**
 
 *Recommendation: Incorporate a walkthrough or onboarding screens to help the user understand the features of the site.*
 
 
 ## Website 2: [The Frick Virtual Museum Tour](https://www.frick.org/visit/virtual_tour/west_gallery)
 
The Frick is a museum and research center that houses Old Master paintings and European art. Its virtual tour allows the public to access many of its exhibitions from home.

Why I chose this website:

I wanted to get a glimpse of what well-established museums were using as a medium for virtual tours. Because the previous website I evaluated stuck to a two-dimension approach to the virtual museum, I decided to explore what a virtual three-dimensional museum tour would look like. 

Overall evaluation:

Overall, it seems to be a rather clunky and bare-bones virtual museum experience. While it is cool to be able to virtually walk through the museum's halls, the experience is not that immersive and makes it difficult to view the art pieces in high-resolution.

![frick virtual museum tour](/images/frick_homepage.png)

#### 1. Visibility of System Status 
* Since it is a virtual tour there should be a map available to let the user know what direction to take to get to a specific room. However, the map cannot be accessed from the virtual tour screen. The user must navigate away from the page to view the museum layout.
 **(3)**    
 
 *The user must scroll down past the virtual tour window to access the floorplan button*
 
 ![map button](/images/frick_floorplan.png)
 
 ![museum map](/images/frick_floorplan_map.png)
 
*Recommendation: Add a small map widget that the user can enlarge upon clicking to show them where they are with respect to the museum layout.*
 
  
#### 2. Match between system and the real world
* In virtual 3D environments, the user can typically drag to move towards a certain location (eg. Google Street View). However, this virtual tour only allows you to rotate in a fixed position. Given that the point of this virtual tour is to simulate a real-life museum tour, this inability to move forward to get closer to an art piece is quite frustrating.
**(3)**  

![navigation controls](/images/frick_nav.png)

 *Recommendation: Allow the user to move in four cardinal directions.*
 
 
 #### 3. User control and freedom
 
 * There is sufficient user control on the site. The user can easily navigate back to the virtual tour if they accidentally click to view an object. All links open in a new tab instead of navigating away from the current page, allowing them to easily return to the content they were previously viewing.
 
 
 #### 4. Consistency and standards
 * The direction in which you drag to rotate your point of view is counterintuitive to most other similar programs. Typically, the user would drag left to move right, and vice versa. In this tour, the user must drag left to move left and drag right to move right.
 **(3)**
 
 *Recommendation: Adhere to the typical convention of movement seen in other virtual settings.*
 
 
 #### 5. Error prevention
 
 * Because the virtual tour is hosted on the main museum website, there is a possibility that the user may misclick and be sent away from the virtual tour page on accident. There is no warning or confirmation message that prevents the user from navigating away if it was an unintentional click.
 **(2)**
 
 *Recommendation: When the user clicks on an external link, add in a confirmation message letting them know they are navigating away.*
 
 #### 6. Recognition rather than recall
 
 * In fullscreen mode, there is no indication of what room you are currently viewing for most pages. Because the museum is so extensive, it can be disorienting for the user not to know what room they are in. For a couple rooms, there is a helpful modal in the top right that says which room the user is in.
 **(2)**
 
 *The Portico Gallery is one of the few rooms that is labeled in fullscreen mode*
 
 ![portico gallery](/images/frick_portico.png)
 
 *Recommendation: Add a floating title of the current room to fullscreen mode for all rooms.*
 
 * There is a dropdown menu above the virtual tour module which lists the rooms in the museum. However, there is no way to know what collections are housed in which locations. This is especially crucial for the museum experience, as most rooms in museums are organized around some theme or collection.
 **(3)**
 
 ![locations menu](/images/frick_menu.png)
 
 *Recommendation: Add a menu option to see what collections are located in each room.*
 
 #### 7. Flexibility and efficiency of use
 
 * If the user already knows what art piece they want to view, there is no easy way to navigate directly to that piece. The menu to navigate only lists the rooms available to view, but does not allow users to select specific pieces to navigate to.
 **(2)**
 
 *Recommendation: Add a list of pieces located in each room and allow the user to "jump" to that piece in the museum by clicking on the name of the piece.*
 
  * There is no search feature to allow users to search for a specific piece or filter by collection/subject. More experienced users or return visitors may wish to expedite their tour by selectively visiting certain collections, but the site does support this.
 **(2)**
 
 *Recommendation: Add a search and filter function to allow users to get to specific collections.*
 
 * Also, if the user wants to view all the pieces in a room, they must click on the object in the virtual tour, and for each piece, a new window is opened. This is vastly inefficient and leaves the user stuck with tons of tabs they must close. Additionally, it drastically reduces the immersive quality of the virtual tour experience.
 **(3)**
 
 *Recommendation: For each piece, allow the user to open a pop-up modal with its details and description.*
 
 #### 8. Aesthetic and minimalist design
 * The main window where the rooms are displayed provides a fairly clean and minimalist design. There are only 7 small icons at the bottom, which allows the user to navigate and interact with the room. These are functional and unobtrusive. 
 * Once the user opens a page for a specific piece, however, the layout is cluttered and not immersive. This page is hosted on the main website, so the top navigation links are present and detract from the viewing experience. Additionally, the art piece itself is presented as a small, unimpressive image. It is not the focal point of the page, which it should be.
 **(3)**
 
 ![art piece description page](/images/frick_artpage.png)
 
 *Recommendation: Allow the art piece to take up the majority of the screen and eliminate all unnecessary text.*
 
 #### 9. Help users recognize, diagnose, and recover from errors
 
 * On the page for a specific art piece, there is no direct link back to the virtual tour window, nor does the page tell you how to get back to the virtual tour. If the user does not realize that this page opened in a new tab, and that the virtual tour is likely on a separate tab, it may be very confusing to figure out how to navigate back. Also, because it is a new tab, the user cannot simply press the back button in the browser to return to the tour.
 **(2)**
 
 *Recommendation: Add a link back to the main virtual tour from the art piece's details page.*
 
 #### 10. Help and documentation
 
 * There is no help or documentation for the virtual tour. If a user is confused about how to view specific pieces in the tour or about how to navigate, there is no documentation on these processes.
 **(2)**
 
 *Recommendation: Include a help icon on the bottom menu to document frequently asked questions. Additionally, when the user first launches the virtual tour, include a tutorial to orient the user.*
 
