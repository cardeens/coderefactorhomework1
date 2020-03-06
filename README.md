# Homework 1- Code Refactor
Homework Assignment 1, 3/5/2020: Code Refactor

## Description

The deliverable for this proejct is a homepage for Horiseon, which outlines the company's solutions and value adds. As an agency for Horiseon, our primary goal was to revamp the codebase to ensure it follows accessibilty standards so that their site is optimized for search engines, efficient, and sustainable. Our secondary goal was to update to the format and style of the webpage to be more appealing to the end user and better represent the Horiseon brand.

It was important to clean up the code base as there were some minor errors and inefficencies which could make the code unsustainable. For instance, there were orginally over 200 lines of code in the style.css file as there were multipe selectors and properties with the exact same formatting. By updating the HTML file to have identical tags where formatting was the same, we were able to consolidate the code in the CSS file and bring it to 134 lines. 

There were also several div tags which should use semantic HTML tags instead. By updating these, we created a more efficient code base that is easier to read and follows accessibility standards for screen-reading and other functions. We also made sure there were alt tags for all images to follow the same accessibility standards. We also added comments so that future users can easily navigate our HTML code.

Next, we made sure to correct any minor errors in the code. For instance, there was a missing ID tag in the HTML file for the SEO content section, thus making the SEO text in the navigation bar unclickable which was our expected outcome. There were also quotations missing around the Calibri font names in the CSS file, which could have created issues for users. We then removed any uneccessary tags such as an </img> tag at the end of the Cost Management image in the HTML file. 

Lastly, we updated the the formatting of the webpage to be more appealing and user-friendly. For instance, the 'seo' text in the title Hariseon was a different color but was almost impossible ot tell the difference, so we updated it to a different shade of blue that is within the companies brand guidlines. We also updated the margins in the aside so that the bottom was flush with the bottom of the main content. We reduced the height of the figure under the nav bar as it was so large that the content was below the fold on most screen sizes, which is a poor user experience. lastly, we updated the footer to match the branding of the header. 

## Installation

Now that you have access to the project repo, use the git clone command in your terminal to clone the resources onto your local device. Afterwards, open the direcory in your code editor to access the index.html and style.css files. 

## Usage

When navigating the project files, index.html is the application page, and style.css is your style sheet (which is linked to the html page). There is also an images folder with all the images used in the web page. 

## Tests

To test, open index.html in your browser. The expected outcome is the Horiseon homepage will open with the correct layout and styling outlined in the project files. 

