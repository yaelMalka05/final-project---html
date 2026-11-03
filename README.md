# Fairytale – Fashion Store Website

A multi-page front-end website for an online fashion store, built as a first-year university project using HTML and CSS only.

## Pages
- Home
- Clothing: casual and elegant collections
- Shoes
- About us (with video)
- Contact, Delivery, Privacy
- Profile, Likes, Menu
- Payment flow: order form and rating page

## Technologies
- HTML5
- CSS3

## How to run
1. Download or clone the repository.
2. Open `html/home.html` in a browser.

## Project structure
- `html/` – all site pages
- `css/` – stylesheets, one per page
- `picture/` – images and video clips

## Author
[השם שלך]

(Known issues, for future improvement:
- `page2.html` and `page7.html` are empty drafts: all their content is commented out, and `page2.css` / `page7.css` are almost empty.
- Many pages contain large blocks of commented-out code.
- In the payment form (`pay.html`) each payment method radio button has a different `name`, so several methods can be selected at once. The same issue exists in the rating radios in `payment.html`.
- The email and date fields in the forms are not required, and the forms are not connected to a server. The `action` of the form in `profile.html` is empty.
- There is no JavaScript, so the cart, likes and menu are separate static pages rather than working features.
- Two links have an empty `href`, and some references to `page9.html` remain in comments.
- About 34 of the 134 images and videos are not used by any page.
- Image and video file names are random hashes, some with spaces or "(2)" in the name, and several images are about 2MB each, which slows page loading.
- Some images may be missing `alt` text, which affects accessibility.)
