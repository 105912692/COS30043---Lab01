# COS30043---Lab01

# COS30043 Interface Design and Development

# Lab 01

# Overview

In this lab you will set up your development environment, create a webpage using HTML and
CSS, and learn how to test your pages for accessibility compliance using tools.

# Part 1: Setting Up Your Development Environment

If you have not already done so, install Visual Studio Code from https://code.visualstudio.com/.
Install the following recommended extensions:

- Live Server
Live Server can launch a local development server with live reload. If you right-click an HTML file
and select “Open with Live Server,” you can preview your page in the browser.

# Part 2: Create a Webpage

Create a single webpage using HTML and CSS to refresh what you learned before. You may also
incorporate other techniques you know (e.g. JavaScript), but HTML and CSS are the minimum
requirement.
Your page must include the following elements:

- A logo.
- A page title.
- A navigation bar with links.
- A footer with relevant information (e.g. copyright, contact details).
- The main body of the page must include at least: a paragraph, an image, a table, and a list.
- Use appropriate styles.
Preview your page using VS Code Live Server. Continue refining it until you are satisfied with the
layout and content.

# Part 3: Accessibility Testing with Lighthouse

Lighthouse is an open-source auditing tool built into Google Chrome’s DevTools. It evaluates
web pages for performance, accessibility, best practices, and SEO, and provides actionable
recommendations for improvement.

2. Open your webpage in Google Chrome using Live Server.
3. Open Chrome DevTools (right-click the page and select "Inspect").
4. Navigate to the "Lighthouse" tab in DevTools.
5. Under "Categories", ensure "Accessibility" is selected (you may deselect others to speed up
    the audit).
6. Click "Analyze page load" to generate the report.


7. Review the accessibility score and the list of issues found.
8. Address the issues in your HTML/CSS, save, and re-run the audit until the score improves.

# Part 4: Accessibility Testing with AChecker

AChecker is a web-based accessibility evaluation tool that checks HTML content against
accessibility standards such as WCAG 2.0.

1. Go to https://achecker.achecks.ca/checker/index.php.
2. Select "HTML File Upload" and choose the attached “formtask.html”.
3. Expand the "Options" section and select "WCAG 2.0 (Level AA)".
4. Click "Check It".
The Accessibility Review will categorise issues into three types:
- **Known Problems:** Definite accessibility barriers that must be fixed.
- **Likely Problems:** Issues that are very probably barriers and should be reviewed.
- **Potential Problems:** Items that may be barriers depending on context; review is
    recommended.
Review the Known Problems and fix them. Re-test your page after each round of fixes until
there are no Known Problems remaining.

# Submission

Submit your work to Canvas, including your website source code, a screenshot of the Lighthouse
accessibility score, the fixed formtask.html, and an AChecker report.

Show your work to your tutor during the lab session to get marked off. This lab is assessed in
Week 1 and Week 2 only. If you cannot attend, please provide supporting documentation (e.g. a
medical certificate) to request an extension.

Your tutor will review your work and ask you questions to assess your understanding. Marks are
based on the quality of your work and your ability to explain your work.

- Up to 2 marks: limited or no understanding demonstrated.
- Up to 4 marks: reasonable understanding demonstrated.
- Up to 6 marks: strong and clear understanding demonstrated.


