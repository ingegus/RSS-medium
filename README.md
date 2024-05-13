[![es](https://img.shields.io/badge/Readme%20in-spanish-red)](https://github.com/ingegus/RSS-medium/blob/main/README.es.md)
# RSS-medium
Rss reader for profiles with posts on Medium. It presents the posts through cards that are in a carousel. Uses Bootsrap, CSS and JQuery.

## How to use it

To perform the correct implementation it is only necessary to insert the bootstrap and JQuery libraries in the index.html file.

Then link the rss.js file, which contains the variables for the total number of posts to publish (numPostsToShow) and the user (mediumUrl).
<code>
    const mediumUrl = 'https://pipimarquez.medium.com'; // URL de Medium
    const numPostsToShow = 4; // Número de posts a mostrar
</code>
On the other hand, it uses the site https://rss2json.com to convert the Medium feed to a Json file in order to perform the extraction process.

### Features.

* Allows you to indicate how many posts you want to publish
* In case of less than 3 posts, it hides the navigation buttons.
* Buttons with accessible colors for easy reading.
* In case the post does not have an image, it loads a generic image, the Medium logo.

### Example site
You can see the final operation by going to https://ingegus.dev/RSS-medium/
