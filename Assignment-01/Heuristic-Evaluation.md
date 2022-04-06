# Making Music Learning Accessible to Everyone
## Assignment #1: Heuristic Evaluation
**Vivian Nguyen** | _Digital Humanities 110 - User Interface and Design_ | Spring 2022

### Project Description
> Many older adults believe that mastering a new musical instrument has little reputation for adults. Similar to learning a foreign language, learning an instrument is commonly seen as something that must be embedded during the formative (younger) years, otherwise the learner will be hopelessly behind, if not simply hopeless. It is believed that learning becomes much harder past the developmental stage of growth, so many individuals feel disheartened to start learning. As a child, I took a year of piano lessons, yet it was too costly for me to continue, coming from a disadvantaged background.

Now that I am an adult, with desires to continue the piano education I once had, I want to help others who find themselves wanting to learn an instrument past their formative years, and especially those who come from impoverished backgrounds and cannot afford traditional music teaching. I would like to create a free of charge online music school (conceptually in the form of a non-profit), that ideally contains original lesson plans (like Khan Academy), with regards to people of all ages and backgrounds.

### Severity Ratings for Usability Problems
| Rating | Importance |
| --- | --- |
| 1 | Cosmetic problem only: need not be fixed unless extra time is available on project |
| 2 | Minor usability problem: fixing this should be given low priority |
| 3 | Major usability problem: important to fix, so should be given high priority |

Severity ratings from the <a href="https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/">Nielsen Norman Group.</a>

## Website 1: <a href="https://www.lessonface.com/">Lessonface</a>
Lessonface, founded in 2013, is a Public Benefit Company whose purpose is to connect students with great teachers for live online music, language, and arts lessons. Their mission is to help students achieve their self-enrichment goals while treating teachers equitably. Lessonface is COPPA (Children's Online Privacy Protection Act) compliant and designed for all ages.

### Why Lessonface?
I chose Lessonface as a competitor application because this website displayed many features I envision to include. These include the feature to personally match with a suitable teacher, reviews, and individual pages for teachers with information. However, I would like to focus only on instrument learning, and emphasize more on the idea that everyone is welcome to learn instruments. I would like to use Lessonface as inspiration and to help me decide what to build upon.

### Overall Evaluation
At first visit, the visitor is well aware that the branding for Lessonface is really refined, and the website does not look like a website builder template like many other websites of this nature. However, aspects that strike me immediately are the circles of videos on top of a royal blue background on the hero section of the landing page. It is extremely cluttering to be the first thing you see when you visit, and hinders your intake of information (text), especially when the videos are rather bright and the white text lies on top of them. Right below, the categorization of “Music” and “Language and Arts” lessons are also very cluttered, with both types of lessons being on the same row. I think this website can be improved in design, content structuring, and filtering.

### 01.  Visibility of System Status

**Problem: Blank white screen** (Rating: 1)

When loading the website, even though the favicon (small icon on top of the browser tab) is fully loaded, the page shows a white screen before the entire page appears before me. A loaded favicon signifies a page that has loaded all of its assets, and to regular internet users, they would expect to see a loaded page. Even after the buffering animation is gone, the page is still blank for a bit, which causes confusion to users.

![image](https://user-images.githubusercontent.com/69706820/161941462-e8ad1ca0-c3e4-44d3-aba1-07a73ec6ef1e.png)

> **Solution:** Have a loading/buffering animation load in on the page, instead of a blank screen.

### 02.  Match Between System and the Real World

**Problem: Use of magnet imagery** (Rating: 1)

![image](https://user-images.githubusercontent.com/69706820/161943659-53af97ca-06e3-433b-b0a0-241481f17f6e.png)

Although it might seem obvious that the magnet is supposed to refer to “matching” the student with the teacher, I was confused by the magnet imagery as it is a single magnet without the other magnet. It is a very specific use of a magnet icon that people might not be used to seeing to refer to pairing people together.

> **Solution:** Remove or replace with a more recognizable icon.

### 03.  User Control and Freedom

**Problem: Cannot remove category when searching music lessons** (Rating: 2)

![image](https://user-images.githubusercontent.com/69706820/161946075-abd5336a-304a-4e64-9219-f05be34074d2.png)

The category filter is designed like a multi-select, with the design of the “X” on the category chosen. However, it is a single-select and you cannot search multiple instruments at once, or remove the category to search all instruments at once.

> **Solution**: Make it a multi-select filter to enhance user freedom.

### 04.  Consistency and Standards

**Problem #1: Not actually a button** (Rating: 3)

![image](https://user-images.githubusercontent.com/69706820/161935383-02ed66c7-a05a-4c2c-b912-2bdc22d240f9.png)

The phone number to contact the establishment is on the top right “navigation bar” (or what is intended to be a navigation bar, but does not include the actual navigation links—will be elaborated upon). However, it appears to the user as a button as that is the **web standard**, but when pressed, it does not lead to any page. Users may wait for a couple seconds expecting a page to load, but in actuality, it is just information placed in a button design.

> **Solution #1:** Replace phone number and make it a “Contact” button that leads to a page with contact information that includes the phone number, or move the phone number to the footer, or link it to a "tel" so that the user can call the number.

**Problem #2: Hamburger menu used on desktop/wide screen** (Rating: 3)

![image](https://user-images.githubusercontent.com/69706820/161936016-2f3b50eb-dc2e-4a1f-b9ed-f26e6175fd98.png)
![image](https://user-images.githubusercontent.com/69706820/161936098-70514308-1ea4-48b0-b7bf-350e2c42efc1.png)

In standard web design, a hamburger menu as the main way of navigation for desktop design is rare. If Lessonface is advertising for students of all ages, an older user would likely not know to click on the icon to find more pages. Additionally, the hamburger menu hides two levels of links. You would have to click on “more” to find more important pages.

> **Solution #2**: Use the navigation bar for desktop to lay out all of the options, and hamburger only for mobile on responsive web design.

**Problem #3: Inconsistent language. “Register” vs. “Sign up”** (Rating: 2)

![image](https://user-images.githubusercontent.com/69706820/161938817-995e8a6e-8647-4712-9eee-44deea722934.png)
![image](https://user-images.githubusercontent.com/69706820/161938900-43afd6bd-5a00-44a3-8859-b42a750a4a12.png)

Quoted from the NN group, "Users should not have to wonder whether different words, situations, or actions mean the same thing.” “Register” and “SIGN UP” would typically mean the same thing, but for usability, there should be no room for doubt.

> **Solution #3:** Stick with “Sign Up,” which is more commonly used adjacent to “Log In.”

### 05.  Error Prevention

**Problem: It is easy to get lost** (Rating: 2)

![image](https://user-images.githubusercontent.com/69706820/161950108-5bf41bbf-d392-4fec-96ce-775ca1078c9c.png)

Under the hero section, are two large categories: music and language+arts. In between, it shows subcategories of the music section by default. If you click on the language+arts category, the middle section changes. However, it is hard to realize that, with the layout, so most users probably will miss the fact that they can click on the other section.

> **Solution:** Put subcategories underneath the large categories.
> 
### 06.  Recognition Rather than Recall

**Problem: Important links under nested menu** (Rating: 3)

![image](https://user-images.githubusercontent.com/69706820/161950178-f956428b-4bda-47d8-9bf5-04378bd2f7f4.png)

New users will have to search harder to learn more about Lessonface, as information on the company and how it works is “the least important” in this information hierarchy.

> **Solution:** Put all of this information in the navigation bar, laid out.

### 07.  Flexibility and Efficiency of Use

**Problem: Booking session with teacher requires three steps** (Rating: 1)

When you click “book” with a teacher, you are led to another page where you have to press that button again, which wastes time.

> **Solution:** Have a shortcut button lead towards the destination faster.

### 08. Aesthetic and Minimalist design

**Problem: Cluttered hero section** (Rating: 2)

![image](https://user-images.githubusercontent.com/69706820/161950278-9d344d35-a78e-442c-bff0-48f4457500a2.png)

Immediately, when you enter the website, you are seeing too much. The videos on top of a blue background is rather jarring to meet with, and the lighter colored videos, at times, can interfere with the readability of the hero text.

> **Solution**: Remove videos, or have one video displayed at a time at the side.

### 09.  Help Users Recognize, Diagnose, and Recover from Errors

**Problem: No error message when typing invalid input** (Rating: 2)

![image](https://user-images.githubusercontent.com/69706820/161950349-6fa32489-706d-4279-901b-dc32e0ec2a9f.png)

This search bar only shows results when your input matches what they have in the database, but if you type something that doesn’t match anything, nothing tells you that.

> **Solution:** Add a message saying “Does not match any results.”

### 10.  Help and Documentation

**Problem: No onboarding** (Rating: 1)

There are no guides on the process on finding a teacher and booking the lessons.

> **Solution:** Add an onboarding for new users.
