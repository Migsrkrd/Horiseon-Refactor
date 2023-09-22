# Horiseon-Refactor

## Technology Used
Git Link:   [https://git-scm.com/](https://git-scm.com/)
<br>

HTML Link:  [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
<br>

CSS Link:   [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
## Description

The Horiseon website received a various amount of adjustments within both it's HTML and CSS coding. The original code was developed to display the company website, endulging the viewer with it's subjects of search engine optimization, online reputation managemtn, social media marketing and more! Although the site was mostly functional, there were some issues needing to be adressed, such as the lack of semantic values with the HTML, lack of accessibility codes, logical HTML structures, a basic title, as well as issues with the documents sequence. While the site may seem fully functional on the outside, these mistakes are crucial for the experience of all types of people including fellow coders. 

The first step that was taken was to adjust the subjects of the HTML and alter them to become semantic values. The majority of the HTML was covered in div brackets. While they can serve its function properly, this does not help other coders to understand the layout of the document. In order to solve this problem, these were changed to semantic values of Header, Section, Article, Aside, Footer, etc. Now when future software engineers need to look at and understand the written HTML, the flow and documentation of the file can be easily comprehended.

Secondly, accessibility codes were added to all images and icons within the site. Accessibility is an extremely important aspect to a site. If these were not applied and left absent, then people who are in need of computer assistants, such as screen readers, would be unable to fully take in the infromation of the full website. In order to solve this issue, accessible descriptions were applied all images within both the HTML, and the CSS files.

Lastly, there were some mistakes within the HTML codes. For instance, not all headings were in sequential order. Now the website begins with a heading of div, and sequentially leads to the last used header, div, in the footer. Also, the title for the HTML was adjusted to more accurately describe the purpose of the document. Finally, the site navigation section was fixed in both the HTML and CSS. There are three links located in the navigation section of the HTML, however not all of them contained their correlating IDs that were located within the CSS file. This required a simple fix of applying the code ID to the missing slot. Now all three navigation links work as implied.

* Visit The Refactored Horiseon Website Here: [https://migsrkrd.github.io/Horiseon-Refactor/#search-engine-optimization](https://migsrkrd.github.io/Horiseon-Refactor/#search-engine-optimization)

## Table of Contents
* [Code Refactor Example](#code-refactor-example)
* [Usage](#usage)
* [Learning Points](#learning-points)
* [Author Info](#author-info)
* [Credits](#credits)

## Code Refactor Example
Below displays some of the issues stated in the description. The following contains inadequete values, missing IDs, and unordered headers.
<br>

```html
    </div>
    <div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
        <div class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
        <div class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" />
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </div>
    <div class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </div>
```


Now that we can see some of the mistakes in the initial set of HTML code, here are some of the changes made to solve these issues.
<br>

```html
    <aside>
        <article class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="lead generation image"/>
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </article>
        <article class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="Brand Awareness icon"/>
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </article>
        <article class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="Cost Management icon" />
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </article>
    </aside>
    <footer>
        <h4>Made with ❤️️ by Horiseon</h4>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>
```

## Usage
This is best used when cloning a repository through Github.

![Git-clone-copy-SSH](<images/Screenshot 2023-09-20 192728.png>)



Then the SSH key copy can be inserted into any file destination on your own device through your command line

![Git-Clone-Command-Line](<images/Screenshot 2023-09-20 192810.png>)



## Learning Points

There were many aspects of my current knowledge that started this project off. However much more was learned during many mistakes, accidents, and roadbloacks. For example: never commit until the current code is saved and tested to make sure your actions are correct in intention. Also, always be sure to check correlating CSS code with the HTML, as some changes you have made to the HTML may have an effect on the CSS. Lastly, always use semantic elements in order to better comprehend each purpose of the given code.

## Author Info
### Michael Reickerd
<br>

* [Github](https://github.com/Migsrkrd)
* [LinkedIn](https://www.linkedin.com/in/mikey-reickerd-1716a71a3/)

## Credits
* ### Jorge Castro
* ### Armand Araujo
* ### Ryan England
* W3 Scools: [https://www.w3schools.com/](https://www.w3schools.com/)
