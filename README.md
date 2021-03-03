# Horiseon accessibility update

>This was created to update the code base of the Horiseon marketing agency webpage to follow accessibility standards so that the site is optimised for search engines.

## Table of content

- [**Goals**](#goals)
- [Improving accessibility](#improving-accessibility)
- [Mock up](#mock-up)
- [Application Link](#application-link)


## Goals
The Marketing agencys goal of achieveing an accessible website meant having to meet certain criteria. These are as follow:
- The source code contain semantic HTML elements.
- The structure of the HTML elements follw a logical structure (indepent of styling and positioning).
- The image elements contain accessible alt attributes.
- The heading attributes fall in sequential order.
- The title element has a concise and descriptive title.

## Improving accessibility
As seen in the goals, for this site to meet the accessibility standards semantic code had to be implemented where it was missing. 

    <div id="search-engine-optimization">
        <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
        <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
    </div>

Code such as the above lacked semantic code to easily indicate what was the code meant, aswell as accessible alt attributes in the images. To fix this, semantic tags like < article > replaced div tags,

        <article id="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="journal on table with seo brainstorm" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </article>
making it easier for the code to be read, therefore helping with future maintainence. 

## Mock up
The following image shows the application's appearance and functionality.
![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](https://github.com/[subwayaintfresh]/[horiseon-accessibility-update]/blob/[assets]/subwayaintfresh.github.io_Homework-week-1_.png?raw=true)

>**Note:** All changes made in the HTML and CSS of the application hasn't affected the appearence, only the accessibility. 

## Application link
Link to the Horison deployed website: https://subwayaintfresh.github.io/horiseon-accessibility-update/
