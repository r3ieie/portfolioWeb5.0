 # portfolioWeb5.0
 Ryzadelicious 🍕

Aesthetic, responsive portfolio-style website for Ryzadelicious, a
pizza shop. The site presents the shop, menu, story, contact
information, and a functional demo shopping cart in a single HTML page.

✨ Features

Responsive pizza shop landing page

Fixed navigation bar with working links:

Home

Menu

About

Contact

Aesthetic warm pizza-inspired design

Hero section with call-to-action buttons

Menu generated dynamically with JavaScript

9 pizza products with names, descriptions, prices, and emojis

Functional shopping cart

Add products to the cart

Increase/decrease item quantities

Automatic cart item count

Automatic order total in Philippine pesos (₱)

Demo checkout interaction

Contact form with demo submission interaction

Responsive layout for desktop, tablet, and mobile screens

🍕 Menu

The current menu includes:

Product                Price

Classic Margherita      ₱299
Pepperoni Party         ₱349
Four Cheese Dream       ₱379
Hawaiian Sunshine       ₱339
Bacon BBQ               ₱399
Garden Veggie           ₱329
Spicy Chicken           ₱389
Garlic Shrimp           ₱429
Truffle Mushroom        ₱449

🛠️ Technologies Used

HTML5 --- page structure and content

CSS3 --- styling, layout, responsive design, animations, and
visual effects

JavaScript --- dynamic products, shopping cart, quantity
controls, checkout, and contact-form interactions

No external frameworks or libraries are required.

📁 Project Structure

ryzadelicious/
└── ryza.html

The project is currently contained in one HTML file, including its CSS
and JavaScript.

🚀 How to Run

Download or copy ryza.html.

Open ryza.html in a modern web browser such as Chrome, Edge,
Firefox, or Safari.

Use the navigation menu to move between sections.

Browse the menu and use Add + to add pizzas to the cart.

Open the cart to adjust quantities or test the demo checkout.

Because the project is a standalone HTML file, no server or installation
is required for the current demo.

🛒 Shopping Cart

The cart is handled entirely in the browser using JavaScript.

Users can:

Add a pizza.

Add multiple quantities of the same pizza.

Increase or decrease quantities.

Remove an item by reducing its quantity to zero.

View the current total.

Test the checkout flow.

The checkout currently displays a demo confirmation message and does
not process real payments or create real orders.

📩 Contact Form

The contact form collects:

Name

Email address

Message

The current submission behavior is a demo. It displays a confirmation
message and resets the form, but it does not send information to a
backend or email service.

📱 Responsive Design

The layout adapts to smaller screens using CSS media queries. On mobile
devices:

Navigation links are hidden.

Main sections switch to a single-column layout where appropriate.

Product cards become easier to view vertically.

Typography and pizza artwork scale down for smaller screens.

🎨 Customization

You can customize the website by editing ryza.html.

Change colors

The main colors are defined in the CSS variables:

:root {
  --red: #c92b2b;
  --red2: #f0443e;
  --cream: #fff8ec;
  --gold: #f5b642;
  --ink: #24201d;
}

Add or edit pizzas

Products are stored in the JavaScript products array:

{
  name: "Classic Margherita",
  price: 299,
  emoji: "🍕",
  desc: "Tomato sauce, mozzarella, basil & olive oil."
}

Add another object to this array to create a new menu item.

⚠️ Demo Limitations

This is a front-end demonstration website. The following features are
not connected to real services:

Online payment processing

Real order submission

Database storage

Email delivery

Customer accounts

Real-time inventory

Delivery tracking

These can be added later with a backend, database, payment gateway, and
email/order service.

📄 License

This project is provided as a customizable demo website for
Ryzadelicious. Add your preferred license or usage terms before
publicly distributing the project.

Ryzadelicious --- Pizza Made Happy 🍕
