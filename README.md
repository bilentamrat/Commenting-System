# Commenting-System

Displays an image and adds a comment form. The comment form includes:
     a. A name, email address, and large body input
     b. A checkbox to agree to have the comment posted
     c. A submit button
All three comment fields are required and valid before being submitted. When submitted, it displays using a reusable comment component, that also includes the time and date the comment was submitted. Comments are also managed by a state manager; whenever a new comment is added, it triggers the state manager that then updates the displayed comments on the site. Comments are displayed in the order that they were submitted
