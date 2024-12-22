# **ShopHoria**

ShopHoria is a modern and feature-rich e-commerce platform designed to deliver a seamless shopping experience. With a modular component architecture, state management using Redux, and a responsive layout built with Tailwind CSS, it offers robust functionality for both end-users and administrators.
 
---

## **Table of Contents**

1. [Overview](#overview)
2. [Key Features](#key-features)
3. [Tech Stack](#tech-stack)
4. [Folder and Component Structure](#folder-and-component-structure)
5. [Installation and Setup](#installation-and-setup)
6. [Usage](#usage)
7. [Screenshots](#screenshots)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

---

## **Overview**

ShopHoria is a full-stack e-commerce application built with React.js and Tailwind CSS. It follows a well-organized component structure, making the codebase scalable and maintainable. Features like product browsing, cart management, user authentication, and seamless checkout provide a smooth and intuitive shopping experience.

---

## **Key Features**

### **Frontend**
- Modular **React components** for easy customization and scalability.
- **Responsive design** using Tailwind CSS for mobile, tablet, and desktop views.
- Dynamic product lists, banners, and promotional offers.
- Pagination and navigation using Breadcrumbs.

### **State Management**
- Managed global state using **Redux Toolkit** for a predictable data flow.
- Modular `orebiSlice` for managing cart, products, and user interactions.

### **Page-Specific Features**
- **Home**: Displays banners, best sellers, and special offers.
- **Shop**: Categorized product listings with filters and side navigation.
- **Product Details**: Detailed view of individual products.
- **Cart**: Manage items, quantities, and total price.
- **Account**: User registration and login.

---

## **Tech Stack**

- **Frontend**:
  - React.js
  - Tailwind CSS
  - Redux Toolkit

- **Build Tools**:
  - PostCSS
  - Webpack

---

## **Folder and Component Structure**

### **Folder Hierarchy**
```
src/
├── components/                # Core reusable components
│   ├── Banner/                # Banner and sub-components
│   │   ├── Banner.js
│   │   └── BannerBottom.js
│   ├── designLayouts/         # Layout and design utilities
│   │   ├── buttons/
│   │   │   └── ShopNow.js
│   │   ├── Flex.js
│   │   ├── Image.js
│   │   ├── List.js
│   │   └── ListItem.js
│   ├── home/                  # Home page-specific components
│   │   ├── BestSellers/
│   │   │   └── BestSellers.js
│   │   ├── NewArrivals.js
│   │   └── Sale.js
│   ├── Products/              # Reusable product-related components
│   │   ├── Badge.js
│   │   ├── Heading.js
│   │   └── Product.js
│   ├── SpecialOffers/
│   │   └── SpecialOffers.js
│   ├── YearProduct.js
│   └── Footer/
│       ├── Footer.js
│       └── FooterBottom.js
├── constants/                 # Static constants and styles
│   ├── index.js
│   └── style.css
├── pageProps/                 # Components for product and shop-related pages
│   ├── productDetails/
│   │   ├── ProductInfo.js
│   │   └── ProductsOnSale.js
│   ├── shopPage/
│   │   ├── Breadcrumbs.js
│   │   ├── Pagination.js
│   │   └── ShopSideNav.js
│   └── SpecialCase.js
├── pages/                     # Application pages
│   ├── About.js
│   ├── Account/
│   │   ├── SignIn.js
│   │   └── SignUp.js
│   ├── Cart/
│   │   ├── Cart.js
│   │   └── ItemCard.js
│   ├── Contact.js
│   ├── Home.js
│   ├── Journal.js
│   ├── Offer.js
│   ├── Payment.js
│   ├── ProductDetails.js
│   └── Shop.js
├── redux/                     # Redux store and slices
│   ├── orebiSlice.js
│   └── store.js
├── App.js                     # Main application file
├── index.js                   # React entry point
├── index.css                  # Global CSS file
├── tailwind.config.js         # Tailwind CSS configuration
└── package.json               # Dependencies and scripts
```

### **Notable Components**
1. **Banner**
   - Dynamic promotional banners (`Banner.js`, `BannerBottom.js`).
2. **Home**
   - Best sellers (`BestSellers.js`), New arrivals (`NewArrivals.js`), and special offers.
3. **Products**
   - `Product.js`, `Badge.js`, and `Heading.js` for product showcases.
4. **Footer**
   - Organized footer sections with `Footer.js`, `FooterBottom.js`, and `FooterListTitle.js`.

---

## **Installation and Setup**

### **Prerequisites**
- Node.js installed on your system
- npm or yarn as a package manager

### **Steps**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/umar-7w4/ShopHoria.git
   cd ShopHoria
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm start
   ```

4. **Access the application**:
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## **Usage**

- **Homepage**: View featured products, banners, and promotional sections.
- **Shop Page**: Browse products with filters and navigation.
- **Product Details**: View detailed information about products.
- **Cart**: Add, remove, and manage items in your shopping cart.
- **User Account**: Register, log in, and manage account details.
  
---

## **Contributing**

Contributions are welcome! Please follow the steps below to contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push your branch:
   ```bash
   git push origin feature/new-feature
   ```
5. Open a pull request.

---

## **License**

@ Copyright 2024 | ShopHoria | All Rights Reserved 


---

## **Contact**

- **Author**: Umar Mohammad
- **GitHub**: [umar-7w4](https://github.com/umar-7w4)
- **LinkedIn**: [Profile](https://linkedin.com/in/umarmhd)
