# Sustainable Cities and Communities

## Assignment 1: Heuristic Evaluation

Patrick Khoury | DH110 | Fall 2022

### About the project

According to the United Nations, cities occupy just 3 percent of the Earth’s land, but account for 60-80 percent of energy consumption and 75 percent of carbon emissions. Inequality and the levels of urban energy consumption emissions are sprawling all suburbs all over the world.This has become such an issue that 9 in 10 people living in urban areas worldwide were breathing air that did not meet the World Health Organization’s air quality guidelines. By choosing to act sustainably, we choose to build cities where all citizens live a decent quality of life, and form a part of the city’s productive dynamic, creating shared prosperity and social stability without harming the environment. The cost of implementing sustainable practices in place is minimal in comparison with the benefits. For example, there is a cost to creating a functional public transport network, but the benefits are huge in terms of economic activity, quality of life, the environment, and the overall success of a networked city. All these issues facing sustainability will eventually affect every citizen. Inequality can lead to unrest and insecurity, pollution deteriorates everyone’s health and affects workers’ productivity and therefore the economy, and natural disasters have the potential to disrupt everyone’s lifestyles. In my project, I hope to present a social-media-type app concept which incentivizes target users to be environmentally conscious, promotes activities and sustainable brands, allows for information to be presented to users, connects people who are existing or potential friends, and so much more. In the following assignment, I will evaluate the heuristics of two websites, one pertaining to my project subject and one not, based on Jakob Nielson’s 10 general principles for interaction design.

### Jakob Nielson's [10 Usability Heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/) Explained

| Number | Heuristic | Description |
|---|---|---|
| 1 | Visibility of System Status | Users should always be informed about what is going on and should be given appropriate feedback to their actions |
| 2 | Match Between System and the Real World | Use concepts and language that are familiar and logical to the user |
| 3 | User Control and Freedom | Allow users to make mistakes; give them options to undo and redo tasks |
| 4 | Consistency and Standards | Follow conventions and make sure design is consistent across the platform |
| 5 | Error Prevention | Get rid of error-prone conditions and provide users with safety nets for high-cost errors |
| 6 | Recognition Rather Than Recall | Minimize user's memory load by giving them suggestions and help in context |
| 7 | Flexibility and Efficiency of Use | Provide multiple ways to perform a task to make the platform accessible to all users |
| 8 | Aesthetic and Minimalist Design | Provide only relevant content and features |
| 9 | Help Users Recognize, Diagnose, and Recover From Errors | Tell users what the problem is and provide suggestions to fix it |
| 10 | Help and Documentation | Supply users with extra help to complete their tasks |


### [Severity Ratings](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/) for Usability Problems by Nielsen Norman Group

The following rating scale, based upon Nielson's own scale, can be used to evaluate the severity of usability issues:

| Rating | Description |
|---|---|
| 0 | I don't agree that this is a usability problem at all |
| 1 | Cosmetic problem only: need not be fixed unless extra time is available on project |
| 2 | Minor usability problem: fixing this should be given low priority |
| 3 | Major usability problem: important to fix, so should be given high priority |
| 4 | Usability catastrophe: imperative to fix this before product can be released |

Ratings are displayed in parentheses after each usability issue. 

### Reasons for Utilization of Severity Ratings: 
| Number | Reason | 
|---|---|
| 1 | Used to allocate the most resources to fix the most serious problems. |
| 2 | Can provide a rough estimate of the need for additional usability efforts. |

## Website 1: [The Department of Economic and Social Affairs Sustainable Development](https://sdgs.un.org/)

### About
[The Department of Economic and Social Affairs (DESA) Sustainable Development](https://sdgs.un.org/) is a department run by the United Nations, an intergovernmental organization made up of 193 member states committed to maintaining peace, dignity, and equality on a healthy planet. Based on a global survey, conducted by international research agency Glocalities, indicates that the United Nations is trusted significantly more by the world population than any other international or governmental organization. 

In this sector, the United Nations defines 17 Sustainable Department Goals (SDG) for all. The purpose of this website is to help inspire and mobilize actions promoting the implementation of SDGs around the world. Using the latest data and estimates, the annual SDG report provides an overview of the world’s implementation efforts to date. 


### Heuristic Evaluation

#### 1. Visibility of System Status
* As you type in the search bar, the possible recommendations are extremely flawed, displaying random letters, numbers, and symbols which mean nothing and lead to nowhere. Upon clicking on one of these suggestions, the site fed back a message stating that they were too long for the search bar character limit. After finding one within the character limit, I got a message stating that there were no matching results. These suggestions are constant for every letter in the alphabet. (3)


<p align="center">
  <img src="../Images/search-query-2.PNG" alt="Search query no immediate results" width = "300px"/>
  <img src="../Images/search-query.png" alt="Search query irrelevant results" width = "300px"/>
</p>

> *Recommendation: Vet the system for all random letters, numbers, and symbols in the search bar. Cleaning this up will allow users to make relevant searches and find topics of interest more easily.*

* Furthermore, the recommended results shown are mostly completely unrelated to sustainable development, which doesn't help the user navigate the website or effectively find information about the topic. (2)

> *Recommendation: Optimize search results so that they are relevant to sustainable development only.*

<p align="center">
  <img src="../Images/appointment-request-progress.PNG" alt="Appointment request progress capture" height = "300px"/>
</p>

* Lastly, the search bar does not feed out suggestions in real time. Instead, a loading icon pops up after you are done typing, and it takes time to offer any autocomplete results. This could be particularly troublesome to users who may not know the exact term they want to look up, or to those who have accidentally misspelled a word (2)
![Appointment Request Progress Capture](../Images/appointment-request-progress-2.PNG)

> *Recommendation: Display results as the user types. This allows the user to find the information they were looking for much easier and helps them stay engaged.*

#### 2. Match Between System and the Real World
* The site lists the related Sustainable Development Goals (SGDs) for each article and event as numbers, with no text displaying what the numbers are referring to. The goals the numbers represent are not known to the vast majority of viewers. To be able to view the meaning behind each number, the user would have to scroll down to the very bottom of the website to see the info. (2)

> *Recommendation: Write out the actual SDG for each article and event rather than displaying it as a number. This will enhance viewer comprehension, as it is impossible to expect new viewers to understand what each number represents.*

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

* Additionally, the navigation bar uses acronyms that first-time visitors might be unfamiliar with. For example, the terms “HLPF” and “SIDS” are items featured on the navigation menu, but do not provide any insight on what those letters stand for. (2)

<p align="center">
  <img src="../Images/appointment-request-progress.PNG" alt="Appointment request progress capture" height = "300px"/>
</p>

> *Recommendation: As stated by Jakob Nielson himself, “use words, phrases, and concepts familiar to the user, rather than internal jargon”*

#### 3. User Control and Freedom
* There are no “return to last page” buttons throughout the website. To be able to backtrack to the last page, the viewer would have to hit the search engine’s “click to go back” arrow. However this feature does not always work exactly at its intended use in this website. Some sub-pages aren’t registered as distinct pages according to the search engine, and the click to go back arrow skips pages at times. The mechanic on this site is rather faulty and can be frustrating to viewers attempting to go back and forth between pages. (2)

> *Recommendation: Add a "review to last page button" or register sub-pages as distinct pages with differing URLs so the "click to go back" arrow on the top left of the search engine allows you to view the previous page.*

#### 4. Consistency and Standards
* Most sections on this website follow completely different formats. This makes it difficult for users to navigate through the pages to find relevant information, as the design is inconsistent across all pages and subpages. (2)

<p align="center">
  <img src="../Images/homepage.PNG" alt="Mayo Clinic homepage"/>
  <img src="../Images/covid-19-page.PNG" alt="Mayo Clinic COVID-19 page"/>
</p>

> *Recommendation: Maintain some form of consistency within each page in the main website, so that users are able to navigate throughout the website without any issue.*

* The HLPF page features a completely different menu than the majority of the website, with different navigation options. This does not allow you to go back to any of the primary sections of the website. This issue is particularly frustrating, as the HLPF page is featured as a key proponent of the Sustainable Development website, but has no option to navigate to any of the other pages. (2)

> *Recommendation: Maintain consistency within all branches of the main website so that users are able to navigate understand they are still in the same space. Keep the same navigation options for all pages within the main website, so users can navigate freely without any issues.*

* The logo on the top-left corner on several pages does not take you to the homepage by clicking it. Instead, it takes you to a language prompt which directs you to the standard UN page. To get back to the Sustainable Development section, you’d have to navigate through the “Our Work” section on the navigation bar. This can be frustrating to those who intend to reach the homepage by clicking the logo in the top left. This isn’t an unreasonable action of the user, as many of the pages function in this correct way. (3)

> *Recommendation: Make sure that clicking the logo will go back to the Sustainable Development homepage on every page within the website. Maintain consistency with functionalities so users don't get 'lost' on a certain page and are always able to return to the homepage.*

#### 5. Error Prevention
* As mentioned above, the possible recommendations in the search bar are extremely flawed, displaying random letters, numbers, and symbols which mean nothing and lead to nowhere. This is an error-prone condition, as the two outcomes from clicking on one of these flawed suggestions are not being within the character limit or getting an error message saying no matching results. (2)

<p align="center">
  <img src="../Images/appointment-modal-window.PNG" alt="Modal window asking about COVID-19 vaccine" width="700px"/>
</p>

> *Recommendation: Get rid of the modal window and provide radio buttons to get users to make a deliberate choice between "Yes" and "No". It would also be helpful to display the error message again if the user clicks "Yes" rather than force them onto a page that doesn't explain the error they made.*

#### 6. Recognition Rather Than Recall
* The suggestions given in the search bar are not relevant to the website whatsoever. The majority of key terms, goals, etc that are relevant to the website do not come up as suggestions in the search bar. This makes it difficult for users who may not know or remember the name of an event, goal, etc to access information about it since they have to enter it verbatim. (2)

<p align="center">
  <img src="../Images/diseases-and-conditions.PNG" alt="Diseases and conditions page" width="500px"/>
</p>

> *Recommendation: Provide some conditions or diseases that are often treated at Mayo Clinic. Also guide users to the symptom checker, where they can select from a list of symptoms and generate predicted diseases and conditions associated with those symptoms. In general, Mayo Clinic should better emphasize their symptom checker feature because it can be a great resource for those concerned with their health, like many seniors. (However, emphasize that it is necessary to check with a healthcare provider.)*

#### 7. Flexibility and Efficiency of Use
* The accessibility of the navigation bar can be a pain point to some viewers. It is relatively small and overshadowed by the large photos and graphics. Users must scroll all the way to the top to utilize it, as the website doesn’t make use of the “floating/sticky” feature typically incorporated in most websites. Additionally, this website doesn’t feature  a “scroll to top” button, which makes accessing the bar even more difficult. (1)

![Homepage of Mayo Clinic showing search box](../Images/homepage.PNG)

> *Recommendation: Create a separate button for searching that includes the magnifying glass so that the user easily recognizes that it can be clicked to Search.*

* Another pain point on the site is the lack of organization for the news feed. The “NEWS” tab leads users to a page with 8 articles, the top 2 of which have misaligned thumbnails. While there appear to be more pages of news/articles, the site requires you to step through the pages one by one using arrows. However, the site neither shows how many pages there are in total, nor does it allow you to easily jump between pages. If a user was on page 10 of the News feed and wanted to go back to the first page, they would have to click the back arrow 9 times. This pain point goes against Nielsen heuristic of flexibility and efficiency of use. (3)
![Symptom Checker Step 1 Capture](../Images/symptom-checker-step-1.PNG)

> *Recommendation: Keep the list so that users can just recognize and click on recommendations, but implement a search feature at the top so that users can have the option to efficiently find the symptom they are experiencing. Also, group the symptoms into different categories to help users find the symptom they are looking for more easily.*

* Under Billing, clicking the name of a category doesn't display the drop-down menu, but rather takes you to another page, which can be disorienting. The user must click the + sign to the right of the name to get the drop-down menu, which also requires dexterity and is therefore less accessible for seniors. (3)

> *Recommendation: Make it possible to access the drop-down by clicking the name of the category.*

#### 8. Aesthetic and Minimalist Design
* This website features additional graphics and information not relevant to the general topic. Examples of this include the home page, event pages, the news tab, etc. Although aesthetically pleasing in some instances, many of the graphics take attention away from the pertinent information and are a bit overwhelming for someone simply trying to get relevant info (3)

<p align="center">
  <img src="../Images/nav-care-at-mayo-clinic.PNG" alt="Navigation menu (Care at Mayo Clinic)" width="250px"/>
  <img src="../Images/nav-research.PNG" alt="Navigation menu (Care at Mayo Clinic)" width="250px"/>
</p>

> *Recommendation: Show only what is necessary in the navigation menu, and make sure the links are relevant to each category.*

* The billing and payments page has a very cluttered and unappealing design, placing a lot of cognitive strain on the user. (3)

![Billing and payments page](../Images/billing-and-payments.PNG)

> *Recommendation: Clean up the page by putting more spacing between the words, using better hierarchy to organize the information, listing items out in bullet points rather than in paragraph form, and using more relevant and high-quality images for each category.*

* Lastly, the font size on the homepage navigation (and in other random locations throughout the website is small and faint, making it inaccessible for individuals with visual impairments. (3)

> *Recommendation: Increase font sizes and increase contrast of the fonts (in this case, make them darker) to make them readable for seniors and other visually impaired individuals. Create a design guideline to ensure that all font sizes and styles are consistent throughout the website.*

#### 9. Help Users Recognize, Diagnose, and Recover From Errors
* FIGURE THIS OUT (2)

![After clicking Yes in the modal window box](../Images/clicked-yes.PNG)

> *Recommendation: Immediately explain why they can't make an appointment for COVID-19 vaccines at the time. Make sure the message is visible (e.g. in red and/or bold).*

#### 10. Help and Documentation
* This website doesn’t feature a help page or FAQ, only a search bar. I believe a help page or FAQ section would be extremely beneficial to all who view the website. Furthermore, the added features would help mitigate other issues, such as the search bar, as most of the information on this site is not easily accessible to a first time viewer. (3)

<p align="center">
  <img src="../Images/appointment-faq.PNG" alt="Appointment FAQ page" width="500px"/>
</p>

> *Recommendation: Hide the text under each question to make it easy for users to scan through the possible questions and choose only content they are interested in. Organize the questions in a logical way. Include a downward arrow next to each question to show that information about that question can be found if they click each title. Use bullet points and numbered lists whenever appropriate.*

### Overall Assessment

The Mayo Clinic website is very large and contains a lot of information, so the main usability issues involve organizing the content and navigation in a way that is understandable for users, especially in terms of consistency & standards, flexibility & efficiency of use, and aesthetics & minimalist design. From an accessibility standpoint, they need to increase their font sizes and contrast between text and background, especially in the main navigation menu but also in other areas of their website. 



## Website 2: [Yale University Art School](https://www.art.yale.edu/)

### About
Yale University is a private Ivy League Research institution and one of the most distinguished universities in the world. It has upheld this excellence since its establishment in 1701. Contrary to popular belief, Yale is actually best known for their excellent drama, music, and art programs. According to [usnews.com](https://www.usnews.com/best-colleges/yale-university-1426#:~:text=Yale%20University%2C%20located%20in%20New,and%20the%20Yale%20Dramatic%20Association), Yale ranks 2nd in Best Fine Arts Programs (tie), 2nd in Graphic Design, 1st in Painting / Drawing, 2nd in Sculpture (tie), and 1st in Photography in the United States. 

The [Yale School of Art website](https://www.art.yale.edu/) is the official website of the university’s graduate art program..It functions as a wiki; all school of art grad students, faculty, staff, and alums have the ability to change most of this site’s content (with some exceptions); and to add new content and pages. This can be particularly problematic. My goal is to make their website much more usable and accessible for all who view the site.

### Heuristic Evaluation

#### 1. Visibility of System Status
* Yale’s School of Art website unfortunately displays inconsistent feedback indicators for user action, perhaps as a symptom of its mish-mash of creators. On the site, the user hovering their cursor over certain links results in a feedback indicator of some kind; however, not only are the indicators inconsistent with one another, some links lack feedback indicators altogether. For example, in some cases, clickable links turn blue when the user navigates their cursor over them; in other cases, hovering the cursor over calendar events highlights and shakes the event. In both of these instances, the feedback provided leads the user to believe that clinking on the link or even would lead to a subpage on the site or to a different site altogether. In addition, some links are denoted with two arrows “>>” and some are denoted with just one “>”. Certainly, there is room for improvement in standardizing the feedback so as to ensure the user is clear about what the indicators mean. The potential user confusion due to inconsistency is only further compounded by the fact that not all links on the site have appropriate feedback for user action. Some links do not highlight or turn blue when the user hovers their cursor over it, potentially leading to issues with users not knowing that interacting with that link would potentially lead them to a subpage or different site -- they don’t appear to be “clickable” links. (3)

<p align="center">
  <img src="../Images/nav-services.PNG" alt="Navigation Menu, Services" width="350px"/>
</p>

> *Recommendation: Make sure that there is some kind of feedback (e.g. color change) when the cursor hovers over each menu item.*

#### 2. Match Between System and the Real World
*  The home page and many others use acronyms that first-time visitors might be unfamiliar with. For example, the acronym “SOA” is featured largely on the menu, but does not provide any insight on what those letters stand for. (1)

<p align="center">
  <img src="../Images/community-health-center-icons.PNG" alt="Community Health Center icons"/>
</p>

*Recommendation: “use words, phrases, and concepts familiar to the user, rather than internal jargon” (Nielsen Norman Group). (see examples [here](https://thenounproject.com/term/mental-health/3306335/) and [here](https://thenounproject.com/search/?q=medical&i=2468231)). Make sure icon styles are consistent as well.*

#### 3. User Control and Freedom
* Does not promote user control and freedom to back out of processes -- for example, when selecting “Editor Details” within the Community Bulletin Board space, the “Editor Details” box enlarges and changes to reflect the respective editors’ names and note who has editor access. However, there is no clear way to exit that change: no cancel, undo, or “X” button to return to the original formatting. This is especially problematic when the enlarged size of the box containing the editors’ names covers up information that was previously readable. One can exit this interaction by clicking outside of the box, but this revert function is not clearly labeled and discoverable.

> *Recommendation: Test users to see what the right timing for carousels would be. There should be enough time for users to read the text and process the information on each image. Use bigger arrows so that users can easily click them, and make sure the carousel is responsive to clicks. Add a visual indicator to show where the user is in the image gallery.*

#### 4. Consistency and Standards
* There is no proper organization of the elements on the website. They are clustered together with no order of hierarchy and importance. (3)

<p align="center">
  <img src="../Images/nav-bar.PNG" alt="Top Navigation Menu"/>
</p>

> *Recommendation: Reorganize the top navigation so that it complies with standards. For example, Hours & Locations can go under "About", Gala 2020 does not need to be displayed, and Vita 2021 should be kept under services (and should be renamed Free Tax Prep or something recognizable, since not everyone will know what VITA is).*

* The inconsistent use of colors, fade effects, borders, and font styles (uppercase, lowercase, italicized, bold, underlined, and regular font) is distracting to say the very least. It makes the website practically unusable. (3)

> *Recommendation: Reorganize the top navigation so that it complies with standards. For example, Hours & Locations can go under "About", Gala 2020 does not need to be displayed, and Vita 2021 should be kept under services (and should be renamed Free Tax Prep or something recognizable, since not everyone will know what VITA is).*

* Inconsistent acronym usage “SoA in the world Calendar” in one place and right below it is “School of Arts in the world Calendar.” 

> *Recommendation: Reorganize the top navigation so that it complies with standards. For example, Hours & Locations can go under "About", Gala 2020 does not need to be displayed, and Vita 2021 should be kept under services (and should be renamed Free Tax Prep or something recognizable, since not everyone will know what VITA is).*

#### 5. Error Prevention
* Website crashed often when I was navigating through it. "The server encountered an internal error or misconfiguration and was unable to complete your request. Please contact the server administrator, johannes.deyoung@yale.edu and inform them of the time the error occurred, and anything you might have done that may have caused the error. More information about this error may be available in the server error log." (3)

<p align="center">
  <img src="../Images/behavioral-health-contact.PNG" alt="Contact information for Behavioral Health" width="550px"/>
  
  <img src="../Images/dental-clinic-contact.PNG" alt="Contact information for Dental Clinic" width="550px"/>
</p>

> *Recommendation: Put the tabs above the content so that users know what information is relevant to which department. Put the contact information in a consistent and easy-to-find location for each tap. Alternatively, direct users to a contact page where they can easily find where they should contact.*

#### 6. Recognition Rather Than Recall
* NEED TO FIGURE OUT (2)

<p align="center">
  <img src="../Images/nav-services.PNG" alt="Navigation Menu, Services" width="350px"/>
</p>

> *Recommendation: Connect the dropdown box with the menu item title to show that the dropdown is under that header.*

#### 7. Flexibility and Efficiency of Use
* The navigation bar is hidden as a first-time user on the page may not easily locate it for easy navigation through the various sections of the website. (2)

> *Recommendation: Implement a search function to allow users another option to efficiently navigate through the website.*

* The user experience of the community bulletin board can be better worked on. The community board should be well simplified so it does not overwhelm the user and can also carry the same experience as a real board. (3)

<p align="center">
  <img src="../Images/csc-homepage.PNG" alt="CSC homepage"/>
</p>


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
* This website doesn’t feature a help page, FAQ, search bar, or any feature that provides additional help to the user. I believe all these features would be extremely beneficial to all who view the website. Furthermore, these added features would help mitigate other issues, such as searching for information in the atrociously organized and designed website. Most of the information on this site is not easily accessible to a first time viewer. (3)

* A lot of information tends to be displayed via images and brochures, but it is difficult to find them. (3)

> *Recommendation: Consolidate important general information on one page so that users are not completely confused. Provide a link to the contact page instead of randomly displaying the phone number and email. Provide more guidance to users on each page; there are many different departments, phone numbers, and locations. For example, who, where, and when exactly should a person contact if they are a new patient?*

### Overall Assessment

A lot of work needs to be done in many areas, but the areas to focus on first are probably flexibility & efficiency of use and aesthetics & minimalist design. Their health resources are invaluable to many low-income, immigrant families and their seniors, so being able to access that information easily should be prioritized. Also, an important feature to fix first is the visibility of the language switch, since many of their users may be Chinese monolinguals. The website is very harsh to look at in general, making it very difficult to use and makes CSC look unreliable. An update on aesthetics should therefore be one of their next steps.


