# Javascript Form
In this example, a button and form have been added under the list. When the user clicks on the button to add a new item, the form will come into view. The form lets users add a new item to the list with a single text input and a submit button. The new item button is hidden when the form is in view. When the user presses the submit button, the new item is added to the bottom of the list. The form is also hidden and the new item button is shown again.

## Components that make the app run

* New jQuery objects are created to hold the new item button, the form to add new items, and the add button. These are cached in variables.
* When the page loads, the CSS hides the new item button and shows the form. So jQuery methods show the new item button and hide the form.
* If a user clicks on the new item button the button element whose id attribute has a value of showForm, the new item button is hidden and the form is shown.

## How to run the app locally
* In your terminal
```
git clone https://github.com/bostonhuman/javascript-form
```
* Open `form.html` to run the app. 
