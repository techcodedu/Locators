
### Exercise 1:

**Objective**: Create a program to interact with the following HTML page and demonstrate the usage of various locators:

**HTML**:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Locator Exercise</title>
</head>
<body>

<div class="container">
    <h3>Locator Exercise</h3>

    <a href="#" id="nav-link">Navigation Link</a>
    <input type="text" name="search" placeholder="Search here">
    <p class="description">This is a sample description.</p>
    <button>Submit</button>
    <a href="#">Another Link</a>
</div>

</body>
</html>
```

**Tasks**:
1. Locate the link with ID and click it.
2. Locate the input field by its name and enter the text "Selenium Test".
3. Retrieve and print the text from the `p` tag with class "description".
4. Locate the button by its tag name and click it.
5. Locate the second link using link text and click it.

### Instructions:

1. Initialize the WebDriver and navigate to the provided HTML page.
2. Perform the tasks using the appropriate locators as mentioned.
3. Close the WebDriver after all tasks are completed.


### Exercise 2:

# Google Locator Exercise

This exercise demonstrates the usage of different locators in Selenium WebDriver to interact with Google's homepage.

## Tasks

1. Navigate to `https://www.google.com/`.
2. Locate the Google search box by its `name` attribute and enter "selenium".
3. Find the Google "Search" button using its `name` attribute and click it.
4. Retrieve and print the text of the first search result using its `tag name`.
5. Click on the "Images" link above the search results using `link text`.
6. Locate the Google Apps (grid) icon near the top right corner using its `class name` and click it.
7. Locate the "YouTube" link inside the Google Apps dropdown using `partial link text` and print the URL (without clicking).
8. Use an `XPath` expression to find the "Sign In" button at the top right and click it (if available).
9. Locate the "Email or phone" input field on the Sign In page using `CSS selector` and enter "example@gmail.com".

## Prerequisites

1. Install [ChromeDriver](https://sites.google.com/chromium.org/driver/) and make sure its path is set correctly in the code.
2. Java development environment set up.



