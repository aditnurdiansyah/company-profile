# Company Profile Website

## Project Overview

This project is a **Company Profile Website** built using HTML and CSS. The website is designed to introduce a company/brand, present its services and product catalog, showcase portfolio items, and provide contact and social media information in a simple and responsive layout.

The project focuses on applying fundamental frontend development practices such as semantic HTML structure, CSS Flexbox, responsive media queries, reusable CSS variables, smooth navigation, external icon integration, WhatsApp contact links, and embedded Google Maps.

## 🔗 [Online Version](https://company-profile-af-it.vercel.app)

## Project Features

- **Company Profile**
  Presents the company/brand introduction through an About section with supporting images and descriptions.

- **Hero Section**
  Provides a prominent introduction to the brand with a call-to-action button that directs visitors to WhatsApp for collaboration or inquiries.

- **Services Section**
  Displays the main service/value highlights using icons and descriptive content.

- **Product Catalog**
  Shows available products in a responsive grid layout, including product images, descriptions, prices, and direct WhatsApp contact buttons.

- **Portfolio Section**
  Displays portfolio/work images in a responsive gallery with hover effects.

- **Contact Section**
  Provides the company's location through an embedded Google Maps view and links to social media platforms.

- **Responsive Navigation**
  Uses a sticky navigation bar with a hamburger menu for tablet and smartphone screen sizes.

- **Responsive Layout**
  Uses CSS Flexbox and media queries to adapt the layout for desktop, tablet, and smartphone devices.

- **CSS Variables**
  Uses CSS custom properties for the main color palette, making the design easier to maintain and customize.

- **External Icons**
  Uses Ionicons for interface and social media icons.

- **WhatsApp Integration**
  Product and collaboration buttons use WhatsApp links so visitors can contact the company directly.

## Technologies Used

- **HTML5** — Website structure and content
- **CSS3** — Styling, layout, animations, and responsive design
- **Flexbox** — Page and component layout
- **CSS Media Queries** — Responsive behavior
- **CSS Custom Properties** — Color and theme variables
- **Ionicons** — Interface and social media icons
- **Google Maps Embed** — Location display
- **WhatsApp Link** — Direct customer communication

## Project Structure

```text
company-profile/
├── image/
│   ├── about_1.png
│   ├── about_2.png
│   ├── catalog_1.jpeg
│   ├── catalog_2.jpeg
│   ├── catalog_3.jpeg
│   ├── catalog_4.jpeg
│   ├── catalog_5.jpeg
│   ├── catalog_6.jpeg
│   ├── catalog_7.jpeg
│   ├── catalog_8.jpeg
│   ├── hero_image.png
│   ├── portfolio_1.jpeg
│   ├── portfolio_2.jpeg
│   ├── portfolio_3.jpeg
│   ├── portfolio_4.jpeg
│   ├── portfolio_5.jpeg
│   ├── portfolio_6.jpeg
│   ├── portfolio_7.jpeg
│   └── portfolio_8.jpeg
├── index.html
├── style.css
└── README.md
```

## Website Sections

### 1. Home

The Home section introduces **AF it** through a hero banner and provides a WhatsApp call-to-action for visitors who want to collaborate or make an inquiry.

### 2. About

The About section contains company introduction content supported by two images. It is structured using a two-column layout on larger screens and changes to a vertical layout on smaller devices.

### 3. Services

The Services section highlights four key values:

- Quality
- Design
- Creativity
- Communication

Each item uses an Ionicons icon and a short description.

### 4. Catalog

The Catalog section presents eight product items. Each catalog item contains:

- Product image
- Product name
- Product description
- Product price
- WhatsApp contact button

The catalog is displayed using a responsive Flexbox grid.

### 5. Portfolio

The Portfolio section contains eight portfolio images. Images include a hover animation that slightly enlarges and changes their opacity when the user moves the cursor over them.

### 6. Contact

The Contact section provides:

- Embedded Google Maps location
- LinkedIn link
- Facebook link
- Instagram link

This section helps visitors find the company location and connect through social media.

### 7. Footer

The footer contains:

- Company/brand information
- Community navigation
- Service links
- Contact information
- Copyright information
- Social media icons

## Responsive Design

The website includes responsive breakpoints for tablet and smartphone devices.

### Desktop

The main sections use multi-column layouts to make efficient use of available screen space.

### Tablet

At screen widths up to `768px`:

- Navigation changes to a hamburger menu.
- About content becomes vertically arranged.
- Services use two columns.
- Catalog uses two columns.
- Portfolio uses two columns.
- Contact content becomes vertically arranged.
- Footer columns are reduced.

### Smartphone

At screen widths up to `481px`:

- Services use one column.
- Catalog uses one column.
- Portfolio uses one column.
- Contact content remains vertically arranged.
- Footer sections use one column.

## Color Scheme

The website uses CSS custom properties to define its main color palette:

```css
:root {
    --peach: #ffdab9;
    --dark: #2f4f4f;
    --cyan: #e0ffff;
    --brown: #3e2723;
    --green: #25d366;
}
```

Using CSS variables makes it easier to change the visual identity of the website without modifying every individual CSS rule.

## How to Run

No build tools or package installation are required.

### 1. Clone the Repository

```bash
git clone https://github.com/aditnurdiansyah/company-profile.git
```

### 2. Navigate to the Project

```bash
cd company-profile
```

### 3. Open the Website

Open `index.html` directly in a modern web browser.

Alternatively, use a local development server such as the **Live Server** extension in Visual Studio Code.

## External Resources

The project uses several external services/resources:

- **Ionicons** for interface and social media icons.
- **Google Maps Embed** for displaying the company location.
- **WhatsApp** links for direct communication.

An internet connection may be required for these external resources to load correctly.

## Customization

The website can be customized by modifying:

- Company/brand name
- About section content
- Service descriptions
- Product catalog information
- Product prices
- Portfolio images
- Contact information
- Social media URLs
- Google Maps location
- WhatsApp number and message
- Color variables in `style.css`

### Changing the Main Colors

Edit the variables inside `style.css`:

```css
:root {
    --peach: #ffdab9;
    --dark: #2f4f4f;
    --cyan: #e0ffff;
    --brown: #3e2723;
    --green: #25d366;
}
```

### Adding or Replacing Images

Place new images inside the `image/` directory and update the corresponding `src` attributes in `index.html`.

## Current Implementation Notes

The current project is intentionally focused on fundamental HTML and CSS implementation. It does **not** currently include:

- A separate JavaScript file
- A database or backend
- A server-side contact form
- SEO-specific meta tags
- Open Graph metadata
- A dedicated favicon configuration
- A dark mode implementation
- A multi-page navigation structure

These features can be added in future development iterations as the project evolves.

## Future Improvements

Potential improvements include:

- Adding complete SEO metadata.
- Adding Open Graph and Twitter Card metadata.
- Adding a favicon and brand assets.
- Implementing dark mode with CSS variables.
- Adding JavaScript-based interactive components.
- Improving accessibility with more descriptive `alt` attributes and semantic elements.
- Creating dedicated pages for products, services, and portfolio items.
- Connecting the contact section to a backend or form service.
- Adding product filtering or categorization.
- Improving form and navigation accessibility.
- Adding performance optimization for images and external resources.

## Conclusion

This Company Profile Website provides a practical foundation for presenting a company's identity, services, products, portfolio, and contact information through a responsive web interface.

By building the project with HTML5 and CSS3, the project demonstrates essential frontend development concepts including semantic page organization, Flexbox layouts, CSS variables, responsive design, hover interactions, external service integration, and mobile-friendly navigation.

The project can serve as a foundation for further development into a more complete company website with JavaScript functionality, backend integration, improved accessibility, SEO optimization, and additional interactive features.

## Repository

This project is available on GitHub:

https://github.com/aditnurdiansyah/company-profile
