# Solar Consulting Website - Development Notes

This README is for internal development purposes only. It documents our progress on the Solar Consulting website and outlines the next steps we need to take.

## Current Status

We have established a basic website structure with the following:

* **Homepage (`index.html`):** Includes a hero section, embedded solar potential tool (iframe), benefits section, contact CTA, and signup form.
* **Solar Basics (`solar-basics.html`):** A placeholder page for solar energy information.
* **Contact Us (`contact.html`):** A placeholder page for contact information and a form.
* **CSS (`style.css`):** Basic styling applied to the website.
* **JavaScript (`script.js`):** Currently empty.
* **Embedded Solar Potential Tool:** The tool from Cloud Run is embedded in the homepage using an iframe.
* **Signup Form:** A basic signup form has been added to the `index.html`.

The website is functional and viewable in a browser, but it is missing key content and visual elements.

## Outstanding Tasks

Here's a prioritized list of what we need to work on next:

1. **Visual Assets:**
    * **Hero Image:** Find or create a suitable hero image for the `#hero` section of `index.html`. Update the `style.css` file with the correct image path.
    * **SVG Icons:** Find or create SVG icons for the "Reduce Energy Costs," "Help the Environment," and "Increase Home Value" benefits. Update the `index.html` file with the correct icon paths.

2. **Content Creation:**
    * **Solar Basics Page:** Populate `solar-basics.html` with detailed information about solar energy.
    * **Contact Us Page:** Add a functional contact form to `contact.html`.

3. **Form Handling:**
    * Implement a way to handle form submissions from the contact form and signup form. This will likely require a backend service or serverless function. The current forms have `action="/signup"` which is a placeholder.

4. **Refine Styling:**
    * Adjust the padding of the `#hero` section in `style.css` to achieve the desired height.
    * Further refine the website's styling to improve its visual appeal.

## File Notes

* **`index.html`:** The main file. Check for image and icon paths after adding assets. The signup form is located here.
* **`style.css`:** Make all styling adjustments here. Remember to test responsiveness using browser developer tools.
* **`script.js`:** We will keep this file empty until we need to add specific interactive elements.

## Testing

* To view the website locally, use the following command in the terminal: `python3 -m http.server` then navigate to `http://localhost:8000` in your browser.

## Branching Strategy

* We are currently working in a separate branch called "improvements" (or whatever the current development branch is named).
* Before making significant changes, create a new branch from the "improvements" branch to isolate your work.
* When changes are complete, merge the branch after review.

## Next Steps

1. Prioritize finding or creating the hero image and SVG icons. This will greatly improve the visual appeal of the homepage.
2. Begin populating the `solar-basics.html` page with content.
3. Let's discuss the best approach for handling form submissions.

## Important Reminders

* Always test your changes thoroughly in the browser.
* Commit your changes frequently with descriptive commit messages.
* Communicate any challenges or questions you have.