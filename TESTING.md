# Testing

## 1. Code Validation
The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.
-   [W3C Markup Validator](https://validator.w3.org/#validate_by_input)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

### 1.1 CSS Validation
The test was succesfull and did not report any issues.<br>
-> Insert fullsize screenshot of test result

### 1.2 HTML Validation
The first attempt at HTML Validation gave a long list of various items that wasn't allowed in span containers, those containers were changed to divs. Some fixes to the contact formular were also required. Below is the result of the 2nd pass through the tests.
#### Index Page
-> Insert fullsize screenshot of test result

#### Individual Therapy Page
-> Insert fullsize screenshot of test result

#### Couples Therapy Page
-> Insert fullsize screenshot of test result

#### About Me Page
-> Insert fullsize screenshot of test result

#### Price Page
-> Insert fullsize screenshot of test result

#### Contact Page
 -> Insert fullsize screenshot of test result


## 2. Responsiveness
To test responsiveness across various devices & screensizes, I used [Responsive Design Checkcer](https://www.responsivedesignchecker.com/), a 15`` laptop & a OnePlus 6T mobile phone.

Viewport | iPhone 5/5s<br>320x568 | Galaxy S5/S6/S/<br>360*640 | OnePlus 6T<br>412x892 | Ipad Mini<br>768x1012 | Ipad Pro<br>1366x1024 | Desktop 1024px | Desktop 1440px
--- | --- | --- | --- | --- | --- | --- | --- |
Site responsive<br>below 801px  | Good | Good| Good | Good | n/a | n/a | n/a
Site responsive<br>above 800px | n/a | n/a | n/a | n/a | Good | Good | Good
Links functionality  | Good | Good | Good | Good | Good | Good | Good
Navigation Menu  | Good | Good | Good | Good | Good | Good | Good
Images | Good | Good | Good | Good | Good | Good | Good
Renders as expected | Good | Good | Good | Good | Good | Good | Good


## 3. Browser Compatability
Browser -> | Chrome | Firefox | Edge | Safari | Opera | IE
--- | --- | --- | --- | --- | --- | --- |
Appearance  | Good | Good | Good | ? | Good | Good
Responsiveness | Good | Good | Good | ? | Good | Good
Functionality | Good | Good | Good | ? | Good | Good

## 4. Contrast Testing
A test of colour contrast to ensure accessibility.
-   [WebAim Contrast Checkter](https://webaim.org/resources/contrastchecker/)

Black text (#3A3A3A) on white background (#FFFFFF).
- Passes all tests.

Black text (#252525) on white background (#FFFFFF).
- Passes all tests.

White text (#FFFFFF) on green background (#0f352d).
- Passes all tests.

White text (#FFFFFF) in footer on brown background (#35251a).
- Passes all tests.

Black text (#252525) on grey background (#CCCCCC).
- Passes all tests.

Green icon and hovor effect (#159D15) on dark green background (#0F352D)
- Passes tests for Graphical Objects & User Interface Components.
- It fails the test for normal text & some large text. But the website only utilize the colors together for icons and UI effects.

## 5. Testing User Stories from User Experience (UX) Section


## 5. Known Bugs
- On devices with a viewport height below 600px there is an issue with the dropdown navigation menu. The menu is locked in place & doesn't scale, which causes an issue on the very smallest of phones. Bugfix: Applied a change that makes the menu list items scale with viewport height.
- There was a validation issue on the about me page. The problem was identified as headings being used inside a paragraph. Bugfix: A restructuring of the content box fixed the issue.