# The Good Food Restaurant Website

A five-page website for The Good Food Restaurant, a family-run restaurant at 12 Main Street, Freetown, Sierra Leone. Customers can see the menu and prices in Leones, learn about the restaurant, find contact details, and order food online for delivery or pickup.

Built with HTML, CSS and a small amount of JavaScript. No frameworks or installation needed.

## How to open the website

1. Unzip `good-food-website.zip`.
2. Open the `good-food-website` folder.
3. Double-click `index.htm` to open it in a web browser (Chrome, Edge, Firefox or Safari).

Keep all the files and the `images` folder together in the same folder, or the pictures and styles will not load.

## Files

```
good-food-website/
├── index.htm      Home page
├── about.htm      About Us page
├── menu.htm       Our Menu page
├── contact.htm    Contact Us page
├── order.htm      Menu & Online Ordering page (major feature)
├── style.css      Styles for all five pages
├── README.md      This file
└── images/
    ├── hero.jpg                 Home page main photo
    ├── about-team.jpg           About Us team photo
    ├── jollof-rice.jpg          Popular Dishes (Home)
    ├── grilled-chicken.jpg      Popular Dishes (Home)
    ├── fish-chips.jpg           Popular Dishes (Home)
    ├── beef-stew.jpg            Popular Dishes (Home) and ordering list
    ├── jollof-rice-sq.jpg       Ordering list
    ├── grilled-chicken-sq.jpg   Ordering list
    ├── fish-chips-sq.jpg        Ordering list
    └── chicken-wings-sq.jpg     Ordering list
```

## Pages

**Home (index.htm)**
Welcome heading, main photo, a quick search (food type, price range, text search), four Popular Dishes with prices and "Order Now" buttons, and a lunch deal banner.

**About Us (about.htm)**
Our Story with a team photo, Our Mission, and four values: Fresh Ingredients, Quality Service, Customer Focus and Community.

**Our Menu (menu.htm)**
Five categories (Starters, Main Courses, Seafood, Drinks, Desserts), each with three dishes and prices. Each "View Items" button opens the ordering page filtered to that category.

**Contact Us (contact.htm)**
A message form (Full Name, Email, Subject, Message) that checks the required fields before sending. Contact information: address, phone numbers, email, opening hours and social media links. A map of Freetown.

**Menu & Online Ordering (order.htm)**
The major feature of the website:
- Filter dishes by category, price range or search text
- Choose a quantity with the − and + buttons
- Add dishes to the cart and remove them
- Choose delivery (Le 15,000) or pickup (free)
- See the subtotal, delivery cost and total update automatically
- Press "Proceed to Checkout" to see an order confirmation with an order number

## How the pages connect

| From | Button or link | Goes to |
|---|---|---|
| Every page | Top menu (Home, About, Menu, Contact, Order Online) | That page |
| Every page | Search icon | Ordering page, with the cursor in the search box |
| Home | View Menu / View all dishes | Our Menu |
| Home | Find food (quick search) | Ordering page with the chosen filters |
| Home | Order Now on a dish | Ordering page with that dish in the cart |
| Our Menu | View Items | Ordering page filtered to that category |

## Design

- **Colours:** charcoal (#1E1B16) and gold (#F4B400), with white and pale gold backgrounds
- **Fonts (Google Fonts):** Kaushan Script for the logo and highlights, Bree Serif for headings, Nunito Sans for body text
- **Mobile friendly:** on small screens the layout becomes one column and the top menu turns into a ☰ button

## Notes

- Google Fonts and the map need an internet connection. Without internet the site still works, using backup fonts, and the map area stays blank.
- The ordering and contact form are a front-end demonstration. No real orders or messages are sent, because the website has no server or database.
- To change a photo, replace the file in the `images` folder with a new one that has the same file name.
- To change a dish or price on the ordering page, edit the `MENU` list in the script near the bottom of `order.htm`. Prices on the Home and Our Menu pages are written in the HTML of those pages.

## Author

Assignment 1: Web Design, The Good Food Restaurant Website.
