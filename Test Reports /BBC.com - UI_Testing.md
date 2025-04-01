## Description: Accessibility assessment of BBC.com using automated and manual testing tools. Various aspects such as keyboard navigation, color contrast, screen reader support, interactive elements, and form validation are evaluated.

Accessibility Testing



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


**BBC003**:  Verify all links  work as expected

Description: All links should direct the user to the correct part of the website.


Steps to Reproduce:

a. Open website

b. Click all Navigation Bar

c. click several news

d. go to the footer and click all links

**Expected Behavior**: All links opened work as they should, no error found.

**Actual Behavior**: Links work as expected.

## Status:
Approved


**BBC004** : Website translate to the language 

Description: The website performs a well traslation.

Steps to reproduce:

a. Open the website.

b. Scroll to the footer of the page.

c. Change the language.

d. Navigate through the website.

**Expected Behavior**: The website should fully translate into the selected language without any sections remaining in another language.

**Actual Behavior**: In the Korean language the articule "https://www.bbc.com/korean/institutional-49283197" the articule is in english. 

![image](https://github.com/user-attachments/assets/a770b70b-4bae-4122-8624-44cfb9134c96)


The "Do Not Sell My Information" link in the footer is still in English and redirects the user to the homepage instead of the intended article.

![image](https://github.com/user-attachments/assets/13180e82-fa51-455d-9a4a-29e88c5726ff)


## Status:
Failed 





