# Ropafadzo Badza - Profile & Mini-Portfolio

## Project Description

This is my personal profile and mini-portfolio created for my Web Technologies course. The website introduces my background, skills and interests as a Computer Information Systems student.

## Technologies Used

* HTML5
* CSS3
* Git
* GitHub

## AI-Assisted Content

AI was used to help develop the About Me section of my portfolio.

The complete AI prompt, raw AI output, final edited version and reflection are documented in:

[View the AI Prompt Log](PROMPT_LOG.md)

## Accessibility

I checked my webpage for basic accessibility requirements. The profile image has meaningful alternative text, all contact form fields have associated labels, and the page uses a clear heading structure.

I also checked the contact form to ensure that the fields use appropriate HTML5 validation such as required fields, email validation and minimum input lengths.

### Peer Review Feedback

My peer reviewed my portfolio and identified two accessibility issues.

1. **Contact form labels:** One of the text input fields did not have an associated label. This could make it difficult for users, especially screen-reader users, to understand what information they were expected to enter.

2. **Profile image alternative text:** The profile image used the alternative text `"two friends"`, which did not clearly describe the image in the context of my portfolio.

My peer recommended adding labels to all form inputs and using more meaningful alternative text for the profile image.

### Accessibility Issue and Fix

I fixed the contact form by adding clear `<label>` elements for all form inputs and connecting each label to its corresponding input using matching `for` and `id` attributes.

I also changed the profile image alternative text to `"Portrait of Ropafadzo Badza"` to provide a more meaningful description.

These changes improved the accessibility of my portfolio and made the form and image easier to understand for users who rely on assistive technologies.

## Project Structure

* `index.html` - Main webpage
* `styles.css` - Styling for the webpage
* `PROMPT_LOG.md` - AI prompt, raw output, edited version and reflection
* `images/profile.jpeg` - Profile image

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Use the navigation menu to explore the different sections of the portfolio.

## Version Control

Git and GitHub were used to track the development of this portfolio. The project was developed through multiple incremental commits as features and improvements were added.
