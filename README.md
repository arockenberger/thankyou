# Thank-You-Note Generator for the Carpentry@UiO Community

This is my gift to the awesome instructors, helpers, and the library staff that make the Carpentry@UiO community what it is!

## How To…?

Click on the link (https://arockenberger.github.io/thankyou/), and you will land on a website. Here, click on the big red button "Thank You!", sit back and feel good about yourself!

*Tested with ChromeBrowser Version 78.0.3904.108 on a MacBookAir with macOS Mojave 10.14.6. Fonts don't render correctly and quotes are not centered on sticky note image when using a smartphone.*

## About

This repository contains the following three files that are important to run the scripts:

* [index.html](index.html)
  * *HTML-code, containing style information*
* [javascript.js](javascript.js)
  * *Javascript file containing the quotes from the sticky notes and a script for generating quotes randomly. The script also contains style information.*
* [yellow-sticky_800px.png](yellow-sticky_800px.png)
  * *Image file of a sticky note, serves as a background image.*

The other files in the repository are not necessary for functionality, but might be useful for testing and as a source for alternative images etc.

### TO-DO

* The style information in the HTML-header and in the Javascript function should be transferred to a CSS file style.css
* The quotes in (javascript.js) should be transferred to a text file and the Javascript file should be modified accordingly. The idea is to continuously add the positive sticky note feedback to a quotes.txt file from which the Javascript fetches the contents
* Overall design of the final product: I am not a designer, but I would like this ThankYou! to become as visually pleasing as possible. Feel free to come up with a dashing design!


### Acknowledgements

* I basically used every help I could get with HTML, CSS, and Javascript. I made extensive use of the [W3Schools](https://www.w3schools.com/default.asp) explanations and examples and shamelessly copied and edited examples I found on [StackOverflow](https://stackoverflow.com/questions) by googling hard and made them fit my needs. I owe thanks to [@jaknil](https://github.com/jaknil) for helping me debugging the Javascript (turns out you cannot have quotation marks within quotation marks…) and encouraging me to finish the project. The running versions of the [HTML](index.html) and the [Javascript](javascript.js) were finished at [BitRaf](https://bitraf.no/) on Dec 7, 2019.

## License information

The code in this repository is licensed under a [GNU General Public License v3.0](LICENSE.txt)

The images in this repository are licensed under a CC-BY-NC 4.0 [Creative Commons Attributes Non-Commercial International License](https://creativecommons.org/licenses/by-nc/4.0/), which means they are allowed for private use. I consider this product "private use". If you, however, want to fork or clone this repository and built upon it and eventually do commercial stuff with it, you MUST NOT use the images. Please check the [imagelog.md](imagelog.md) for License information and sources for all images.
