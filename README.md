# airbnb-clone-project

A full-stack clone of the popular accommodation booking platform, AirBnB. This project simulates a real-world web application where users can browse properties, view detailed listings, and complete bookings.

### Project Goals
- Build a responsive, user-friendly booking platform
- Apply UI/UX best practices using Figma designs
- Collaborate using Git and version control workflows
- Practice real-world software development in a team environment

### Tech Stack
- **Frontend:** HTML, CSS, JavaScript (React)
- **Design:** Figma (UI/UX Design)
- **Version Control:** Git & GitHub

### Project Structure (To Be Developed)
- Component-based frontend structure
- Reusable UI components (Navbar, PropertyCard, Footer, etc.)
- Responsive and accessible design


## UI/UX Design Planning

### Design Goals
- Create an intuitive and seamless booking flow
- Maintain visual consistency across all pages
- Ensure fast loading times and performance optimization
- Prioritize mobile responsiveness (mobile-first approach)

### Key Features to Implement
- **Property Search & Filtering:** Users can search listings and apply filters (e.g., location, price, rating)
- **Detailed Property View:** Display full property information with images and booking form
- **Secure Checkout Process:** Allow users to complete bookings with confirmation feedback
- **User Authentication:** Enable sign-in/sign-up functionality (planned for future)

### Primary Pages

| Page                  | Description                                                                 |
|------------------------|------------------------------------------------------------------------------|
| **Property Listing View** | Grid layout displaying available properties with filtering options          |
| **Listing Detailed View** | In-depth information on selected property, including gallery and booking form |
| **Simple Checkout View**  | Streamlined checkout page with payment form and confirmation details         |

### Importance of a User-Friendly Design
A user-friendly booking system reduces friction in the user journey, leading to higher conversion rates and customer satisfaction. Clear navigation, fast-loading pages, responsive design, and an intuitive interface help users easily search, explore, and book accommodations without confusion or frustration. Accessibility and consistency are key pillars of the user experience.

#### Color Styles
- **Primary Color:** `#FF5A5F`
- **Secondary Color:** `#008489`
- **Background Color:** `#FFFFFF`
- **Primary Text Color:** `#222222`
- **Secondary Text Color:** `#717171`

#### Typography
- **Primary Font Family:** Circular
- **Font Weights:**
  - **Headings:** Bold (700)
  - **Body:** Medium (500), Book (400)
- **Font Sizes:**
  - Headings: 24px – 32px
  - Body Text: 16px
  - Secondary Text: 14px

#### Impoertance of identifying design properties of a mock up design
Understanding the color styles and typography used in a Figma mockup is critical for maintaining **visual consistency** across the app. It ensures the final product accurately reflects the design vision and improves **user experience**, **readability**, and **brand identity**. Using the exact fonts, colors, and spacing enhances the **professional look** of the site and builds user trust.


## Project Roles and Responsibilities

| **Role**              | **Responsibilities**                                                                                      |
|------------------------|------------------------------------------------------------------------------------------------------------|
| **Project Manager**    | Oversees the project timeline, assigns tasks, facilitates communication, and ensures on-time delivery.    |
| **Frontend Developers**| Build the UI components based on Figma designs, ensure responsive layouts, and integrate frontend logic.   |
| **Backend Developers** | Develop APIs, manage the database, and implement business logic to power the frontend experience.          |
| **Designers**          | Create wireframes and mockups in Figma, maintain the design system, and ensure user-friendly UX.           |
| **QA/Testers**         | Write test cases, identify bugs, perform functional and regression testing, and ensure the app meets standards. |
| **DevOps Engineers**   | Set up CI/CD pipelines, manage deployment infrastructure, and monitor the production environment.           |
| **Product Owner**      | Defines the product vision and requirements, prioritizes features, and represents stakeholder interests.   |
| **Scrum Master**       | Facilitates agile ceremonies (standups, sprint reviews), removes blockers, and encourages team collaboration. |

Each role is crucial to the project’s success, ensuring that the product is not only functional but also user-centered, well-tested, and delivered efficiently.


## UI Component Patterns

### Navbar
- Includes logo, search bar, and user navigation
- Mobile-responsive with a collapsible menu
- Appears on all major pages

### Property Card
- Displays property image, name, price, rating, and location
- May include a “favorite” (heart) button
- Used in grid/list view on the property listing page

### Footer
- Contains site navigation links (About, Terms, Privacy)
- Displays social media icons
- Includes copyright

### Additional (Future) Components
- **Search Filters:** Dropdowns, checkboxes, and sliders for filtering results
- **Booking Form:** Collects user info and handles booking confirmation
- **Image Gallery:** Scrollable image viewer for property pages
- **Authentication Modals:** Login/Signup forms
