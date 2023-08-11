# Forms Accessibility
## Optimize for keyboard

Many people navigate forms with the [keyboard](https://app.uxcel.com/glossary/keyboards) alone — screen reader users, users with limited mobility who can't use the mouse, or power users like administrators who do a lot of data entry. Ensure that users can interact with all elements using keyboard only: form fields, [links](https://app.uxcel.com/glossary/links), [buttons](https://app.uxcel.com/glossary/buttons), [tooltips](https://app.uxcel.com/glossary/tooltips), etc.

Use focus indicators — outlines that show which element on a [web](https://app.uxcel.com/glossary/web) [page](https://app.uxcel.com/glossary/pages) is focused. They help users to keep track of where they are without getting lost. Most browsers have default focus indicators, although they often don't have enough contrast with the [background](https://app.uxcel.com/glossary/background), so you might want to create your own.

## Opt for a single-column layout

![Opt for a single-column layout Bad Practice](https://img.uxcel.com/practices/single-column-layout-1611654565119/b-1663842469258.jpg)

![Opt for a single-column layout Best Practice](https://img.uxcel.com/practices/single-column-layout-1611654565119/a-1663842469257.jpg)

Many [checkout](https://app.uxcel.com/glossary/checkout) [usability](https://app.uxcel.com/glossary/usability) studies confirm that multiple [columns](https://app.uxcel.com/glossary/columns) form layouts are more difficult for users to navigate. They lead users to skip fields where they actually have data to input, input data into the wrong fields, or abandon the form because of frustration. It gets exponentially difficult for users with disabilities.

To avoid that, use single-column layouts to keep visual momentum moving down the page. Exceptions to this rule are short, logical fields presented on the same [row](https://app.uxcel.com/glossary/rows) like City, [State](https://app.uxcel.com/glossary/states), and Zipcode.

## Define input boundaries

![[Attachments/ded8d77093bdf4f7948331e887c261bf_MD5.jpg]]

![[Attachments/47f7046dcd436e3245544618197622e3_MD5.jpg]]

Avoid the temptation to create clear form fields without clearly defined boundaries or outlines. While it may make the form look simpler and less cluttered, it may become difficult for people with cognitive disabilities and low vision to know the click target's [size](https://app.uxcel.com/glossary/size) and location. The outlines of the inputs should be visible so that users know the click target's size and location.

## Always keep labels outside of the input

![[Attachments/382019873405723ab1ec6faa6f532560_MD5.jpg]]

![[Attachments/3890dbe4ee5d1cdb1afbdaf2eaa5aea6_MD5.jpg]]

Instead of [placeholder](https://app.uxcel.com/glossary/placeholder) text, place labels, hints, and instructions outside the form field, and clearly indicate required information. There are several benefits to this:

-   Labels don't disappear when users enter [content](https://app.uxcel.com/glossary/content) into the field, and they can always check what they're supposed to input
-   Labels are more visible and contrasting than placeholder text, which is essential for low-vision users
-   Unlike placeholder text, screen readers can easily read labels. Just make sure that users can interact with all elements using the keyboard alone

## Ensure that labels are visible

![[Attachments/f78fc03fb6f5c4b9a5a7692a0683104e_MD5.jpg]]

![[Attachments/eb2d4fae15c629285bc544cacb202ac9_MD5.jpg]]

Nothing is more annoying than forms with tiny, barely visible labels. How do you know what information the form requires you to enter if you can't read what it asks?

That's why it's crucial to make field labels clearly visible and legible. To do that, avoid using a [font size](https://app.uxcel.com/glossary/font-size) smaller than 16px and keep a contrast ratio of at least 4.5:1.

## Use autocomplete for common information

![[Attachments/e99d2fc6bbb85a379438ba0eebc675c7_MD5.jpg]]

![[Attachments/b92761c70fffc35206c1c868c38e344e_MD5.jpg]]

It's tedious to enter information into the form, especially for users with disabilities that affect fine motor skills. Providing the option to use [autocomplete](https://app.uxcel.com/glossary/autofill) helps people fill in form fields more quickly, easily, and accurately.

Use autocomplete for common information that people have probably entered multiple times — name, [password](https://app.uxcel.com/glossary/password), address, phone number, or [email](https://app.uxcel.com/glossary/email).

## Use multiple cues for error states

![[Attachments/fd3d1cc5e9b7832b18e2e58246d9844b_MD5.jpg]]

![[Attachments/3682223e81e4fd9542d36deeed9eedeb_MD5.jpg]]

Have you ever tried submitting a form only to get an error that you missed a field, but you couldn't find which one? When this happens, it causes a lot of frustration.

It's crucial to provide evident and specific error states so that users don't overlook critical information. To make error states perceivable by different senses, use multiple cues simultaneously — [color](https://app.uxcel.com/glossary/color), [icons](https://app.uxcel.com/glossary/icons), bold [font](https://app.uxcel.com/glossary/fonts) weight, heavy border or outline, and helpful text.

## Associate error state with the input It corresponds to

![[Attachments/96663862704bb9b4c5fb018f3fe26412_MD5.jpg]]

![[Attachments/4d33b6a899d08cb93893d00de0731ece_MD5.jpg]]

To make the form accessible to assistive technology users, use the `aria-describedby` attribute. It associates one element with another — in this case, the field label with the error state.

When users go back through the form to fix errors, the screen reader will read the error right after the label without users' need to navigate around. It's also helpful for users who use a screen magnifier, as it shows only a portion of the entire screen at once, potentially leaving vital elements out of sight. Using the `aria-describedby` attribute ensures that users don't miss important information.

## Add an error summary

In addition to creating clear error states under inputs, add a [list](https://app.uxcel.com/glossary/lists) of all input errors below the form if the submission was unsuccessful. It helps assistive technology users understand all the issues present in the form. This is especially important for larger forms with many inputs. Ensure that each reported error also has a link to the corresponding field with invalid input.

Take the lesson quiz and assess your knowledge

Completing the interactive quiz is proven to help you learn faster and remember the information for longer.

## Key skills

## From Course

![[Attachments/f3c023691c442168a28be3e2ed4599b6_MD5.svg]]

Design Accessibility

## Share this lesson