# Horiseon Code Refactor

## Description 

For this project, I was tasked to research accessibility standards and apply necessary or desired changes to the Horiseon website to better meet those standards, both to provide accessibilty to customers as well as to improve search engine optimization (SEO).

While completing the above work, I could also take the opportunity to follow the "Scout Rule" and make the code cleaner or better organized than when I found it.

I researched accessiblity standards and learned that one key accessibilty concern is text descriptions for any images displayed on the web page. Complete and expressive descriptions are preferred, and I added these descriptions in alt text for all page images. I found that the web page includes a background image inserted via CSS, which does not allow for standard alt text. Instead, together with the class id I had to add the attribute role="img", as well as an ARIA label, short for Accessible Rich Internet Applications. With this technique, assistive technologies, such as screen readers, can be provided with additional information about the purpose of HTML elements so tagged.

Other page updates involved clean-up and organization of the HTML and CSS code. I fixed a broken navigation link, reordered CSS items to match the HTML, and consolidated various CSS selectors. I also added detailed comments to both the HTML and CSS files to clarify functionality.

Notably, I learned that there are multiple ways to structure CSS tagging. Class IDs, elements such as "main" and "aside", and combinations of both can direct formatting of various components in the web page. I chose to add semantic elements and then remove superfluous Class IDs, but it is possible that one way or another might be the preferred standard for different developers or companies.

I deployed the application on [GitHub](https://github.com/) [Pages](https://pages.github.com/), and it can be found [here](https://d-a-v-i-d-w-r-i-g-h-t.github.io/horiseon-refactor/).


## Installation

N/A


## Usage 

Provide instructions and examples for use. Include screenshots as needed. 

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

```md
![alt text](assets/images/screenshot.png)
```


## Credits

I learned about semantic elements from the [Semrush Blog](https://www.semrush.com/blog/), [Semantic HTML: What It Is and How to Use It Correctly](https://www.semrush.com/blog/semantic-html5-guide/).

I learned about image descriptions from [Perkins School for the Blind](https://www.perkins.org/), [How to Write Alt Text and Image Descriptions for the visually impaired](https://www.perkins.org/resource/how-write-alt-text-and-image-descriptions-visually-impaired/?gclid=Cj0KCQjw06-oBhC6ARIsAGuzdw2Q3-ZpaKBjylgurELGWHtC1TeAx5Q_9LhN32vlC5OewXqIoyc9_VoaAggvEALw_wcB).

I learned about adding alternate text to a CSS-inserted background image from [CanAdapt](https://www.davidmacd.com/), [Alternate text for background images](https://www.davidmacd.com/blog/alternate-text-for-css-background-images.html).


## License

The last section of a good README is a license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, use [https://choosealicense.com/](https://choosealicense.com/)


---

🏆 The sections listed above are the minimum for a good README, but your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)

Badges aren't _necessary_, per se, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.

## Features

If your project has a lot of features, consider adding a heading called "Features" and listing them there.

## Contributing

If you created an application or package and would like other developers to contribute it, you will want to add guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own.

## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them.

---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.