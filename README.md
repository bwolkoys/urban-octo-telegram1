# 01 HTML, CSS, for an SEO Page

## Your Task

**Refactoring** existing code (improving it without changing what it does) to meet a certain set of standards or to implement a new technology is a common task for front-end and junior developers. For this particular Challenge, a marketing agency has hired you to refactor an existing site to make it more accessible. 

> **Important**: When working with someone else's code, you should adhere to the **Scout Rule**&mdash;always leave the code a little cleaner than when you found it.

An increasingly important consideration for businesses, web **accessibility** ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards. Accessibility is good for business&mdash;for one thing, accessible sites rank higher in search engines like Google. It also helps companies avoid litigation, which might arise if people with disabilities can't access a website.

Accessibility can include complex requirements, but your tech lead has given you a small list of specific criteria for this project. These criteria are documented in the Acceptance Criteria section.

To impress clients, you should always exceed expectations and improve the codebase for long-term sustainability. For example, check that all links are functioning correctly. You can also increase the efficiency of the CSS by consolidating the selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

Are you ready to begin? Here are this week's Challenge requirements.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository, with a unique name and a README that describes the project.

---
© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.  

## Screenshots

![Screenshot 2024-06-28 at 1 55 03 PM] (<Screenshot 2024-06-28 at 1.55.03 PM-1.png>)

In this screenshot, I changes the title to "SEO Basics" (line 7) to represent the page better.
I also removed <div> and put <nav> to help read the code better. (line 13 and 25)

![Screenshot 2024-06-28 at 1:58:03 PM](<Screenshot 2024-06-28 at 1.58.03 PM.png>)

In this screenshot, I took out the <div> and put <section> (semantic elements) (line 30, 36, 38, 44, 46, 52). 
For search engine optimization, 
I changed "class" to "id" so that the ancor would work on the screen (line 30). I also added alt="descritpions of the images 
and icons" for accessability purposes (line 31, 39, 47)

![Screenshot 2024-06-28 at 2:01:00 PM](<Screenshot 2024-06-28 at 2.01.00 PM.png>)

In this screenshot, I took out <div> and put <aside> (semantic elements) to better read the page (line 56, 62, 63, 69, 70, 76), 
I added alt="" to describe the icons (line 58, 65, 72). At the bottom I changed the footer h2 to h4 so it is in a logical 
structure (line 79).