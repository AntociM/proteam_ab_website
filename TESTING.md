# Testing and Validation

## Code validation
The HTML and CSS code were tested before each commit using [W3C HTML Validator](#https://validator.w3.org/) and [W3C CSS Validator](#https://jigsaw.w3.org/css-validator/).
A few bugs have been found during the development process, which in turn were corrected.

### HTML Results
![](https://github.com/AntociM/proteam_ab_website/blob/main/docs/images/w3c_html_validate.jpg)

### CSS Results
![](https://github.com/AntociM/proteam_ab_website/blob/main/docs/images/w3c_css_validator.jpg)


## Responsiveness
The responsiveness was tested using three different tools:
- Chrome Developer Tools
- http://ami.responsivedesign.is/#
- https://www.responsivedesignchecker.com/

From which Chrome Developer Tools proved to be the most efficient, as it provided a wide range of device emulations. 

## Compatibility
The website was tested on Chrome, Edge, Mozilla Firefox. the functionality and appereance remains unchanged between these three on any device size. Even though the website was 
written using fundamental HTML and CSS, it does not guarantee compatibility on other browsers.

## Lighthouse
This [tool](#https://developers.google.com/web/tools/lighthouse) was used to test the performance and accesibility. It provided quick useful feedback regarding the image sizes
that were causing a slowdown. Here are the final results:
![](https://github.com/AntociM/proteam_ab_website/blob/main/docs/images/lighthouse.jpg)


## Known issues
1. On Iphone 5/SE, the text on service page does not scale down as it should, and it becomes a hard to read.
2. The `textarea` in the comment section doesn't not scale well, and it becomes way to short compared to the others froms. Visible on mobile devises.
3. When clicking on the navigation bar, the view does not jump at the beggining of the section and some test will end up getting cut off.


