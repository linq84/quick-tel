# Quick Tel Redirect

A web page was developed with the primary functionality of guiding users to make a phone call by clicking a button or automatically on loading the url. The button's click event is tied to a JavaScript function, `callPhoneNumber()`, which handles the redirection.

The function `window.location.replace()` prevents the original page from staying in the session history, thereby avoiding potential redirect loops when the back button is pressed.

The styling is minimized to make the page load faster and render more efficiently.

The final product is a sleek and efficient web page that allows users to initiate a phone call with a simple click of a button or timeout on the redirect.
