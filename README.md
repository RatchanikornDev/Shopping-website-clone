# Shopping Website Clone

https://shopping-website-clone-gilt.vercel.app/

This is a clone of a shopping website, built using Astro for the frontend and various web technologies. It showcases an e-commerce platform with features like product listings, category navigation, and more.

## Features

- **Responsive Design**: The website is fully responsive and looks great on both mobile and desktop devices.
- **Product Listings**: Display of various products with details like name, price, ratings, and images.
- **Category Navigation**: Includes navigation for different categories such as "Shop", "On Sale", and "New Arrivals".
- **Interactive Elements**: Includes buttons, search bar, and pop-ups for a smooth user experience.

## Technologies Used

- **Astro**: A modern static site generator that compiles and optimizes your components.
- **HTML5**: For basic page structure.
- **CSS3**: For styling the page and ensuring a visually appealing design.
- **Tailwind CSS**: Used for utility-first CSS to quickly style components and pages.

## Components

### `ProductItems.astro`
This component is responsible for rendering product details like name, price, rating, and image for each product on the site.

```astro
---
import ProductItems from "../components/ProductItems.astro";
---

<ul class="grid grid-cols-2 lg:grid-cols-4 gap-4 mt-14">
  <ProductItems
    name="T-SHIRT WITH TAPE DETAILS"
    price="120"
    star="4.8"
    image="/assets/T-shirt.png"
  />
  <ProductItems
    name="SKINNY FIT JEANS"
    price="99.99"
    star="5"
    sale={{ percentage: 20, price: 79.99 }}
    image="/assets/jeans.png"
  />
  <ProductItems
    name="CHECKERED SHIRT"
    price="180"
    star="3.8"
    image="/assets/T-shirt2.png"
  />
  <ProductItems
    name="SLEEVE STRIPED T-SHIRT"
    price="99.99"
    star="4"
    image="/assets/T-shirt3.png"
  />
</ul>

A clone of an online shopping website featuring a clean, modern design with a focus on easy navigation, product discovery, and an engaging shopping experience.

Features
	•	Sign Up Promotion: Sign up to get a 20% discount on your first order.
	•	Navigation Bar: A responsive navigation bar with links to categories like “Shop,” “On Sale,” “New Arrivals,” and “Brands.”
	•	Search Bar: Users can search for products with a prominent search bar.
	•	Product Listings: Displaying product items such as T-shirts, jeans, and more. Each product includes details such as price, ratings, and discount information.
	•	New Arrivals Section: A dedicated section to showcase new product arrivals.
	•	Dress Styles: Browse by various dress styles like Casual, Formal, Party, and Gym.
	•	Happy Customers: Testimonials section with customer reviews.
	•	Responsive Design: The layout adapts to different screen sizes, from mobile to desktop.

Setup

To run this project locally:
	1.	Clone the repository:
git clone https://github.com/yourusername/shopping-website-clone.git

	2.	Install dependencies:
cd shopping-website-clone
npm install

	3.	Start the local server:
npm start

	4.	Open your browser and go to http://localhost:3000 to view the site.

File Structure
	•	src/components/ProductItems.astro: Component for rendering product items with details like name, price, star rating, and image.
	•	assets/: Contains images used throughout the site, including logos, product images, and promotional banners.

Technologies Used
	•	Astro: A static site generator for faster performance and optimized page loads.
	•	Tailwind CSS: A utility-first CSS framework for creating responsive and customizable designs.
	•	SVG Icons: Used for various interactive and decorative elements, such as the close button and the search icon.

Customization

Feel free to replace images in the assets folder to match your branding. You can also adjust the content of the ProductItems component to showcase different products.

License

This project is open-source and available under the MIT License.
