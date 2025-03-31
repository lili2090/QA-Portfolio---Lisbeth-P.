## Description: Accessibility assessment of BBC.com using automated and manual testing tools. Various aspects such as keyboard navigation, color contrast, screen reader support, interactive elements, and form validation are evaluated.

**BBC001**: Links Must Have Discernible Text
Description: Links on the website lack discernible text, which affects screen reader users and overall accessibility.

 Steps to Reproduce:


a. Navigate to the page (insert URL or section of the site).

b. Inspect the links.

**Expected Behavior**: All links should have clear, descriptive text that communicates the link’s purpose.
 **Actual Behavior**: Links are either missing text or have non-descriptive text (e.g., "click here").


**BBC002**: Images Must Have Alt Text
Description: Some images on the site do not have alt text, making it inaccessible for visually impaired users.

 Steps to Reproduce:

a. Navigate to the image (insert URL or section).

b. Inspect the image element for the presence of alt attributes.]

**Expected Behavior**: All images must have alt attributes describing the content or function of the image.
**Actual Behavior**: Certain images are missing alt text.

## Status:
Failed 
