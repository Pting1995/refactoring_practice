# Refactoring Project

![Horiseon](assets/images/Horiseon.png)

Nothing changed from the user's perspective. A more descriptive title was added. Nondescriptive divs were renamed into nav, section, and article. Redundant elements in style.ccs were consolidated to make future changes easier. Elements were reorganized in style.ccs by when they are used in the html. Removed an unused footer h2 element and added comments to make finding parts of the page easier. Alt attributes were added to images. These changes were made for ease of use for the future of the website.

## Examples of changes

div changes:
``` 
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
```
*div tag was changed into nav tag*

element consolidation:
```
.search-engine-optimization img,
.online-reputation-management img,
.social-media-marketing img {
    max-height: 200px;
}
```
*three separate elements were simplified*

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Deployed Link

* [See Live Site](https://github.com/Pting1995/refactoring_project)

## Authors

* Peter Ting

- [Link to Github](https://github.com/Pting1995)
- [Link to LinkedIn](https://www.linkedin.com/in/pting002/)

## License

This project is licensed under the MIT License 

## Acknowledgments

* Thank you to UC Berkeley's Extension Bootcamp for giving me the opportunity to work on this project!