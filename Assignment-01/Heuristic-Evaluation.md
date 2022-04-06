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

Severity ratings from the [Nielsen Norman Group](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/).

## Website 1: [Lessonface](https://www.lessonface.com/)
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

## Website 2: [Blue Bear School of Music](https://bluebearmusic.org/)

Blue Bear is a nonprofit organization from San Francisco Bay Area that strives to bring the power of music to underserved communities all across the San Francisco Bay Area. Through donor support, they offer free and low-cost programs in many wonderful local schools, community centers, churches and family shelters.

### Why?

I chose Blue Bear School of Music because it is a nonprofit, so the organization naturally has the same goal as me for my project idea. Although I don't foresee my project working with an actual nonprofit, I still think there are parallels between this organization and my proposed project. There is a lot of room for improvement for Blue Bear's website, design-wise, and I would like to comment on it.

### Overall Evaluation

At first glance, the website has a hero section with a slideshow of images and videos from the organization, but upon further inspection, there are many design choices that can be improved. On the surface, there are many issues of color contrast, textual hierarchy, website organization, and button styles, to start. I will elaborate more on my findings below.

### 01.  Visibility of System Status

**Problem: Unclickable images as site content** (Rating: 3)

![image](https://user-images.githubusercontent.com/69706820/161961292-1732c409-0bc1-439f-a15a-9ed2267a6503.png)

In the 50th anniversary page, the content consists of images with textual content. Users would try to click on the images to enlarge them to read the text, and wait for them to load, but then realize that they are unable to.

> **Solution:** Have the content actually embedded in the page (for accessibility and screen reader reasons as well).

### 02.  Match Between System and the Real World

**Problem: Cart button with no backend connection** (Rating: 3)

![image](https://user-images.githubusercontent.com/69706820/161961366-67c044a2-b0d6-40fe-b5ac-bb1ad77849c7.png)

A user would normally see this cart icon in a shopping website. This button is not apparent in all pages, but it is apparent in some. This will heavily confuse the user into thinking that you can shop on this website.

> **Solution:** Remove cart icon from all pages that include it.

### 03.  User Control and Freedom

**Problem: Not enough specific filtering** (Rating: 2)

![image](https://user-images.githubusercontent.com/69706820/161961414-7fb1c9f2-0fdc-4820-8fea-1ceb27ff472b.png)

When scheduling a lesson, you can only filter by instrument and instructors. Howevers, the instructor filter includes all instructors, despite the instrument you choose. You cannot filter by dates and times, and other important things to note.

> **Solution**: Add more filter options and fix instructor filter bug.

### 04.  Consistency and Standards

**Problem: Inconsistent button types** (Rating: 3)

![image](https://user-images.githubusercontent.com/69706820/161961545-d6d9174f-e4e9-4ba1-a03c-35ad8bdc9b18.png)
![image](https://user-images.githubusercontent.com/69706820/161961559-ea3cb37a-368f-42bf-8f3d-2811aa7810b8.png)
![image](https://user-images.githubusercontent.com/69706820/161961569-e471d055-8bc8-49af-9a00-67605996c3ba.png)
![image](https://user-images.githubusercontent.com/69706820/161961583-ba4fae3d-5cc3-42f8-b8b4-93db7eb97879.png)

The website uses the standard button class for buttons, but also uses hyperlinking as buttons when some content can be organized into buttons. It is inconsistent and leads to messy and confusing design to navigate.

> **Solution:** Stick with one button design, use less hyperlinks.

### 05.  Error Prevention

**Problem: Not having hyperlinks in expected areas** (Rating: 2)

![image](https://user-images.githubusercontent.com/69706820/161965950-efc6cd56-a407-49b1-a107-12d9f0ba50ed.png)

Because the user would see hyperlinks styled like this, they may subconsciously try clicking on the non-hyperlinked text thinking that they are uniform hyperlinks. This inconsistent design is prone to error and confusion by the user.

> **Solution:** Remove unnecessary hyperlinks around the website.

### 06.  Recognition Rather than Recall

**Problem: Easily lost when trying to schedule a lesson** (Rating: 2)

![image](https://user-images.githubusercontent.com/69706820/161965979-e377c0d6-2aa9-42ff-ad6f-b2648b4c2a6b.png)

There are many steps and layers to scheduling a lesson. First, you have to find a service/location you prefer. Then, you have to scroll down to find the “Schedule a Lesson” tab. After scrolling through this website a few times, I forgot how to schedule a lesson. This would be concerning if the user was older with the tendency to forget.

> **Solution:** Make the user more simple. Remove extra steps.

### 07.  Flexibility and Efficiency of Use

The main purpose of this website is to find a class. I find it great that they add the button to begin the process of finding a class with a unique border in the navigation bar (that stays constant on the top of the page). It is a shortcut, compared to going through the navigation tabs.

![image](https://user-images.githubusercontent.com/69706820/161966004-47bba47d-b919-4702-8d79-40b0b4469896.png)

### 08. Aesthetic and Minimalist design

**Problem: Issues with design and information hierarchy** (Rating: 3)

![image](https://user-images.githubusercontent.com/69706820/161961720-cdb1e1da-6f51-4460-af93-6c9a81fe7320.png)

No call-to-action button or subheadings on Hero section. A CTA button at the top of the page would have users more interested from the start of their user journey.

![image](https://user-images.githubusercontent.com/69706820/161961759-7e85afb1-e997-4692-bbdf-abd0230285cb.png)

On the contact page, they put the contact information on the Title/H1 header section, which is highly advised against. It should be in the body, as most people would expect information to be.

![image](https://user-images.githubusercontent.com/69706820/161961802-9b7ee6cf-74db-4967-89bd-db2ee454a5d0.png)

Right underneath the hero section of the landing page, we see a quote from Jack Black. Users would typically expect to see information about the service before quotes and testimonials on the landing page. Underneath the quote, we see information on “IN PERSON,” “ONLINE,” and “ON DEMAND” lessons in bullet points and hyperlinks, which is not very clear presentation design and hierarchy-wise.

> **Solution**: Come up with a design that separates these sections into columns, reorder most important information first.

### 0****9.  Help Users Recognize, Diagnose, and Recover from Errors****

**Problem: Instructor filter bug leads to confusion** (Rating: 3)

![image](https://user-images.githubusercontent.com/69706820/161963598-124da5e7-1341-4c9b-9eb2-88bc44a6b674.png)

This is the message you get when you search a **specific instrument** and **teacher** together. Instead of telling you that this teacher **does not** teach this instrument, it tells you that there are no lessons for this combination (which isn’t wrong, but doesn’t tell you that it is an error).

> **Solution:** Have the teachers filtered out to only eligible teachers after you choose the instrument.
> 

### ****10.  Help and Documentation****

**Problem: No help button or documentation** (Rating: 2)

Users are left to navigate this website without help, especially for a website with a lot of dense content, it would be very overwhelming for the user.

> **Solution:** Add a “help” button on the bottom corner of the website. Maybe have live chat.
