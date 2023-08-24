Of course! Let's design an exercise focused on using the different locators available in Selenium. 

### Exercise:

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

