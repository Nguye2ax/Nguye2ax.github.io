---
header-includes:
  - \usepackage{graphicx}
  - \usepackage[margin=1in]{geometry}
---

# Individual Project 1 - Professional Profile Website

**WAPH - Web Application Programming and Hacking**  
**Instructor:** Dr. Phu Phung  

## Student Information

**Name:** Alex Nguyen  
**Email:** nguye2ax@mail.uc.edu  
**GitHub Username:** Nguye2ax  

\begin{center}
\includegraphics[width=0.30\linewidth]{headshot.png}

\textbf{Alex Nguyen Headshot}
\end{center}

\clearpage

# Individual Project 1 - Professional Profile Website

## Overview

For Individual Project 1, I created a professional profile website using GitHub Pages. The main goal of this project was to take what I learned from Lab 2 and use it to make a front-end website that can be looked at online.

My website has a main profile page called `index.html` and a separate WAPH course page called `waph.html`. The profile page includes my name, headshot, email, background, education, skills, project experience, JavaScript features, API integration, a page tracker, and a cookie message that remembers the visitor.

This project got me to understand how front-end web development works when it's not just running on my VM, but published online. I was able to connect HTML, CSS, JavaScript, Bootstrap, jQuery, Vue.js, public APIs, cookies, localStorage, and GitHub Pages together into one working website.

Published website URL:  
https://Nguye2ax.github.io

WAPH course page URL:  
https://Nguye2ax.github.io/waph.html

Project source code:  
https://github.com/Nguye2ax/Nguye2ax.github.io

\clearpage

# General Requirements

## Professional Profile Website

For the general requirement, I created a professional profile website on GitHub Pages. My homepage includes my name, headshot, email, background, education, skills, and experience/projects.

The homepage is basically my simple professional profile page. It gives a quick overview of who I am, what I am studying, what skills I am building, and what kind of technical areas I am interested in.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-top.png}

\textbf{Figure 1: Homepage Top Section}
\end{center}

## About Me and Education

The About Me section explains my background as an Electrical Engineering student. I also mention that I am interested in MEP design, engineering problem solving, leadership, technology, web application programming, and security.

The Education section explains that I am studying Electrical Engineering and currently taking Web Application Programming and Hacking. This connects my professional profile to the course work.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-about-education.png}

\textbf{Figure 2: About Me and Education Sections}
\end{center}

## Skills and Experience

The Skills section includes skills that connect to my engineering background and what I have learned so far in WAPH. I included Git and GitHub, MEP design basics, problem solving, teamwork and leadership, Linux and Ubuntu basics, HTML, CSS, JavaScript, PHP basics, and web application security basics.

The Experience and Projects section explains that I have worked on course labs, front-end webpages, GitHub Pages deployment, and web security practice. I also connected it back to MEP design and engineering projects because those are things I am interested in outside of just web programming.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-skills.png}

\textbf{Figure 3: Skills Section}
\end{center}

## WAPH Course Page Link

I also created a second HTML page called `waph.html` to introduce the Web Application Programming and Hacking course and related hands-on projects.

The homepage includes a button that links to the WAPH course page. This satisfies the requirement to create a new page for the course information.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/waph-page3.png}

\textbf{Figure 4: Link to WAPH Course Page and Project Links}
\end{center}

\clearpage

# WAPH Course Page

The `waph.html` page gives an overview of the course, labs, hackathons, and Individual Project 1. It includes information about Lab 0, Lab 1, Lab 2, Hackathon 1, and the project itself.

This page helps separate my professional profile from the course work. The homepage is focused on me as a student and professional info, while the WAPH page explains what I have been learning in the course.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/waph-page.png}

\textbf{Figure 5: WAPH Course Page Top Section}
\end{center}

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/waph-page2.png}

\textbf{Figure 6: WAPH Course Page Labs and Hackathon Sections}
\end{center}

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/waph-page3.png}

\textbf{Figure 7: WAPH Course Page Project Links and Progress}
\end{center}

\clearpage

# Non-Technical Requirements

## Bootstrap Styling

For the styling requirement, I used Bootstrap as the open-source CSS framework. Bootstrap helped make the page cleaner and easier to organize. I used Bootstrap buttons, containers, and general layout styling.

I also added my own internal CSS for the page background, profile image, section boxes, API image, clock design, and layout spacing. This made the website look more organized and easier to read.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-top.png}

\textbf{Figure 8: Bootstrap Layout and Page Design}
\end{center}

## Page Tracker

For the page tracker requirement, I added a local page tracker using JavaScript `localStorage`. The tracker counts how many times the page has been visited on the same browser.

I used `localStorage` because it made the tracker feel more accurate for my own page. Instead of using a random outside counter that already had a high number, the local tracker starts from the browser and increases when the page is visited again.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-page-tracker.png}

\textbf{Figure 9: Local Page Tracker First Example}
\end{center}

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-page-tracker2.png}

\textbf{Figure 10: Local Page Tracker Updating After Another Visit}
\end{center}

\clearpage

# Technical Requirements

## JavaScript Features

For the JavaScript requirements, I added multiple JavaScript features to the homepage. I added a show/hide email button, a digital clock, an analog clock, a local page tracker, and a Vue.js motivation button.

The show/hide email feature lets the user reveal or hide my email address. The digital and analog clocks update every second. The page tracker uses `localStorage` to count page visits. The Vue.js feature changes the message when the user clicks the motivation button.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-clock.png}

\textbf{Figure 11: JavaScript Digital and Analog Clock Feature}
\end{center}

## Digital and Analog Clock

The digital clock displays the current date and time as text. The analog clock uses JavaScript to rotate the hour, minute, and second hands based on the current time.

This part helped me understand how JavaScript can update page content repeatedly using `setInterval()`. It also helped me see how JavaScript can control CSS styles, because the analog clock hands move by changing their rotation.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-clock.png}

\textbf{Figure 12: Clock at One Time}
\end{center}

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-clock2.png}

\textbf{Figure 13: Clock Updating at a Different Time}
\end{center}

## jQuery

I used jQuery for some parts of the website, including updating text on the page and working with the Joke API. jQuery made the code shorter and easier to read compared to writing everything with plain JavaScript.

For example, the Joke API section uses jQuery to get a random joke and display it on the page. The joke can also update when the user clicks the button.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-jquery-feature1.png}

\textbf{Figure 14: Joke API Using jQuery - First Joke}
\end{center}

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-jquery-feature2.png}

\textbf{Figure 15: Joke API Using jQuery - New Joke}
\end{center}

\clearpage

## Vue.js

I used Vue.js as another open-source JavaScript framework/library. I added a small Vue.js section where the page starts with a message and changes the message when the user clicks a button.

This was a simple feature, but it helped me show that I used another JavaScript library besides jQuery. It also helped me understand that frameworks can control parts of the page in a different way than normal JavaScript.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-vue1.png}

\textbf{Figure 16: Vue.js Message Before Button Click}
\end{center}

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-vue2.png}

\textbf{Figure 17: Vue.js Message After Button Click}
\end{center}

# Public Web API Integration

## Joke API

For the first public API, I used the Joke API. The homepage gets a random joke from the public Joke API and displays it on the page. I also made it update every 1 minute.

There is a disclaimer because the joke content is generated by a third-party API, and I do not create or control the content.

API used:  
https://v2.jokeapi.dev/joke/Any?type=single

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-jquery-feature1.png}

\textbf{Figure 18: Joke API Demo First Result}
\end{center}

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-jquery-feature2.png}

\textbf{Figure 19: Joke API Demo Second Result}
\end{center}

## Dog Image API

For the second public API, I used the Dog CEO API. This API returns a random dog image, so it satisfies the requirement for a public API with a graphic/image.

The page loads a dog image when the site opens, and the user can also click a button to get a new dog image. Like the joke, there is a disclaimer because the image comes from a third-party public API.

API used:  
https://dog.ceo/api/breeds/image/random

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-dog-api1.png}

\textbf{Figure 20: Dog Image API First Result}
\end{center}

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-dog-api2.png}

\textbf{Figure 21: Dog Image API New Image Result}
\end{center}

\clearpage

# Cookies

For the cookie requirement, I used JavaScript cookies to remember the visitor. If the user visits the site for the first time, the page displays a welcome message. If the user visits again, the page displays a welcome back message and shows the last visit date and time.

This helped me understand how cookies can store small pieces of data in the browser and use that data later when the user returns.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/homepage-top.png}

\textbf{Figure 22: Cookie Last Visit Message on Homepage}
\end{center}

# Source Code and GitHub

The source code for the deployed website is stored in my GitHub repository. The main files are `index.html`, `waph.html`, `README.md`, `headshot.png`, and the `screenshots` folder.

I used Git to add, commit, and push my updates to GitHub. After pushing, the site was deployed through GitHub Pages.

Project source code:  
https://github.com/Nguye2ax/Nguye2ax.github.io

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/github-repo.png}

\textbf{Figure 23: GitHub Repository for Individual Project 1}
\end{center}

# Website Printed from Browser

One of the required deliverables is the deployed website printed from the browser as a PDF. I opened my published GitHub Pages website in the browser and used the browser print option to save it as a PDF.

\begin{center}
\includegraphics[width=0.62\linewidth]{screenshots/website-print-preview.png}

\textbf{Figure 24: Website Browser Print Preview}
\end{center}

\clearpage

# What I Learned

In this project, I learned how to turn a front-end webpage into a real deployed website using GitHub Pages. I also learned how to organize a professional profile website with different sections like About Me, Education, Skills, Projects, and Course Work.

I also learned more about JavaScript because I had to use it in different ways. I used JavaScript for the show/hide email button, the digital clock, the analog clock, cookies, localStorage page tracking, and API calls.

The API part helped me understand how a webpage can get live data from outside services. The Joke API returned text data, while the Dog API returned an image. This showed me that APIs can return different kinds of data, and the front-end code has to decide how to display that data.

The cookie and localStorage parts also helped me understand how browsers can remember information. Cookies were used to remember the last visit time, while localStorage was used to count page visits on the browser.

Overall, this project helped me connect a lot of what we learned in Lab 2 into one working website. It also helped me understand deployment better because the website is no longer only on my VM. It is published online through GitHub Pages.

# Report and Deliverables

For this project, I created the professional profile website, the WAPH course page, and the required front-end features. I also deployed the website to GitHub Pages and included the source code in my GitHub repository.

Published website URL:  
https://Nguye2ax.github.io

WAPH course page URL:  
https://Nguye2ax.github.io/waph.html

Project source code:  
https://github.com/Nguye2ax/Nguye2ax.github.io

The final submission includes three PDF deliverables:

1. Project report PDF  
2. Deployed website printed from the browser as a PDF  
3. Source code of the deployed website printed from the browser as a PDF  

# Submission

The final project report PDF was generated using Pandoc with the following command:

```bash
pandoc README.md -o nguye2ax-waph-project1.pdf
```
