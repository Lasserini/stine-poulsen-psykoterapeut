# Testing

## 1. Code Validation
The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.
-   [W3C Markup Validator](https://validator.w3.org/#validate_by_input)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

### 1.1 CSS Validation
The test was succesfull and did not report any issues.<br>
<img src="https://github.com/Lasserini/stine-poulsen-psykoterapeut/blob/master/validation/css_validation.png">

### 1.2 HTML Validation
The first attempt at HTML Validation gave a long list of various items that wasn't allowed in span containers, those containers were changed to divs. Some fixes to the contact formular were also required. Below is the result of the 2nd pass through the tests.
#### Index Page
<img src="https://github.com/Lasserini/stine-poulsen-psykoterapeut/blob/master/validation/html_validation.png"><br>

#### Individual Therapy Page
<img src="https://github.com/Lasserini/stine-poulsen-psykoterapeut/blob/master/validation/html_validation.png"><br>

#### Couples Therapy Page
<img src="https://github.com/Lasserini/stine-poulsen-psykoterapeut/blob/master/validation/html_validation.png"><br>

#### About Me Page
  -> P error to fix.

#### Price Page
<img src="https://github.com/Lasserini/stine-poulsen-psykoterapeut/blob/master/validation/html_validation.png"><br>

#### Contact Page
<img src="https://github.com/Lasserini/stine-poulsen-psykoterapeut/blob/master/validation/html_validation.png"><br>


## 2. Responsiveness
To test responsiveness across various devices & screensizes, I used [Responsive Design Checkcer](https://www.responsivedesignchecker.com/), a 15`` laptop & a OnePlus 6T mobile phone.

Viewport | iPhone 5/5s<br>320x568 | Galaxy S5/S6/S/<br>360*640 | OnePlus 6T<br>412x892 | Ipad Mini<br>768x1012 | Ipad Pro<br>1366x1024 | Desktop 1024px | Desktop 1440px
--- | --- | --- | --- | --- | --- | --- | --- |
Site responsive<br>below 801px  | Ok | Good| Good | Good | n/a | n/a | n/a
Site responsive<br>above 800px | n/a | n/a | n/a | n/a | Good | Good | Good
Links functionality  | Good | Good | Good | Good | Good | Good | Good
Navigation Menu  | Minor<br>Issue | Good | Good | Good | Good | Good | Good
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
### 5.1 Returning Customer
- **Goal** Visiting the site for easy access to contact information.
- **User Story:** <br>
  
### 5.2 Referred Client
- **Goal** Visiting the site on the basis of a recommendation, needs easy path to information about the specific therapy they are looking for.
- **User Story:** <br>

### 5.3 First Time Visitor - Potential client looking for a Psychotherapist
- **Goal** Potential client with no previous knowledge of the Psychotherapist. Need access to information about specific therapy forms, but also more in-depth about the Psychotherapist.
- **User Story:** <br>

## 5. Known Bugs
- On devices with a viewport height below 600px there is an issue with the dropdown navigation menu. The menu is locked in place & doesn't scale, which causes an issue on the very smallest of phones. The fix will probably involve slightly reducing the space each list item in the menu occupy. Alternately a fix could involve scaling the menu size in accordance to viewport height, or a media query to address the problematic screen sizes.