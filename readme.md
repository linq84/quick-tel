# Quick Tel Redirect

A web page developed with the primary functionality of guiding users to make a phone call by clicking a button or automatically on loading the url. The button's click event is tied to a JavaScript function, `callPhoneNumber()`, which handles the redirection.

The function `window.location.replace()` prevents the original page from staying in the session history, thereby avoiding potential redirect loops when the back button is pressed.

The styling is minimized to make the page load faster and render more efficiently.

The final product is a sleek and efficient web page that allows users to initiate a phone call with a simple click of a button or timeout on the redirect.

# Use case

- I chose to map mine to a '.tel' domain as a hack on the word telephone. You could choose to use your own subdomain like 'call.example.com'.
- Use the link/domain across multiple locations and only need to update the one redirect.
- Extend it further by using geo tracking to redirect users to different geo numbers
