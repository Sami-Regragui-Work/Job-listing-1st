# 🚀 Job Listings Management Platform

A modern and interactive job listings management platform built with Vanilla JavaScript, offering a complete user experience with form validation, advanced search, favorites system, and data persistence.

## 📋 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Demo](#demo)
- [Installation](#installation)
- [Performance Criteria](#performance-criteria)

## 🎯 Overview

This platform provides a complete solution for managing job listings, allowing users to view, filter, add, and manage job opportunities. The application stands out with its intuitive interface, responsiveness, and ability to persist data locally.

### Key Benefits

- **🎨 Modern UI**: Responsive design using CSS3 Grid/Flexbox for mobile and desktop
- **⚡ Optimal Performance**: Dynamic updates without full page reloads
- **💾 Data Persistence**: Automatic saving to localStorage for a continuous experience
- **🔍 Smart Search**: Real-time filtering by keywords, skills, and multiple criteria
- **✅ Robust Validation**: Form validation with instant feedback and contextual error messages
- **♥️ Favorites System**: Personalized favorites management with dynamic counters

## 🛠 Key Features

### 1. User Profile Management
- Create and edit a profile (name, desired role)
- Add/remove skills via an interactive interface
- Real-time field validation
- Automatic saving of preferences

### 2. Full CRUD Operations
- **Create**: Add new job listings via a modal form
- **Read**: Display listings as responsive cards
- **Update**: Edit existing listings with pre-filled data
- **Delete**: Remove listings with confirmation and instant update

### 3. Advanced Search and Filtering
- Text search across positions, companies, and descriptions
- Multiple filters by skills, contract type, location
- Combine filters for precise results
- Dynamic display of active filter tags
- Real-time results counter

### 4. Favorites System
- Interactive favorite button on each listing
- Dedicated tab to view favorite listings
- Favorites counter in navigation
- Persistence of favorites via localStorage

### 5. Form Validation
- Native HTML5 validation enhanced with JavaScript
- Contextual and accessible error messages (ARIA)
- Immediate visual feedback while typing
- Prevention of submitting incomplete data

### 6. Interactive Event Handling
- Tab navigation (My Profile / My Favorites / Manage Listings)
- Modals for listing details and management forms
- Smooth interactions with transition animations
- "Clear" button to reset filters

## 💻 Technologies Used

- **Vanilla JavaScript**: Modular and functional architecture without frameworks
- **HTML5**: Semantic structure with ARIA attributes for accessibility
- **CSS3**: Grid/Flexbox layouts, custom properties, and animations
- **LocalStorage API**: Persistence for user profile, favorites, and listings
- **JSON**: Structured data format for job listings
- **Google Fonts**: Modern typography with League Spartan

## 📁 Project Structure

```
📦 job-platform
├── 📂 assets/
│   ├── 📂 data/
│   │   └── 📄 data.json          # JSON database of listings (id, company, position, skills, etc.)
│   ├── 📄 starter.js             # Main JavaScript script (business logic, CRUD, filters)
│   └── 📄 style.css              # Full stylesheet (layout, components, animations)
├── 📄 index.html                 # Main HTML structure with tabs and modals
└── 📄 README.md                  # Project documentation
```

### File Descriptions

- **`data.json`**: Contains an array of objects representing job listings. Each listing includes:
    - `id`: Unique identifier
    - `company`: Company name
    - `logo`: Logo URL (dynamically generated via DiceBear API)
    - `position`: Job title
    - `role`: Category (Backend, Frontend, DevOps, etc.)
    - `level`: Experience level (Junior, Midweight, Senior)
    - `contract`: Contract type (Full-time, Freelance, etc.)
    - `location`: Geographic location
    - `skills`: Array of required skills
    - `description`: Detailed job description
    - `new` / `featured`: Flags for visual badges

- **`starter.js`**: Contains all application logic organized in functional modules:
    - Loading and parsing JSON data
    - User profile management
    - CRUD operations on listings
    - Search and filtering system
    - Favorites and localStorage management
    - Form validation
    - Modal control and tab navigation

- **`style.css`**: Complete stylesheet including:
    - CSS variables for a consistent theme
    - Responsive layouts (Grid/Flexbox)
    - Reusable components (cards, buttons, forms)
    - Animations and smooth transitions
    - Interactive states (hover, focus, active)

- **`index.html`**: Semantic HTML structure with:
    - Tab system for navigation (Profile / Favorites / Manage)
    - Filter bar with search and tags
    - Containers for dynamic listing display
    - Two modals (listing details / manage listing)
    - Forms with validation and accessibility

## 🎬 Demo

The application is hosted on GitHub Pages and accessible via the following link:  
**[🔗 View the live demo](https://sami-regragui-work.github.io/job-platform/)**

### Screenshots

#### My Profile
![My Profile Screenshot](/assets/images/mon-profile-scsh.png)

#### Favorites Tab
![Favorites Tab Screenshot](/assets/images/mes-favories-scsh.png)

#### Manage Listings Tab
![Manage Listings Tab Screenshot](/assets/images/gerer-les-offres-scsh.png)

##### Add Listing Form
![Add Listing Form Screenshot](/assets/images/ajouter-une-nouvelle-offre-scsh.png)


## 🚀 Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local server for testing (optional: Live Server, Python HTTP server)

### Installation Steps

1. **Clone the repository**
     ```bash
     git clone https://github.com/your-username/job-platform.git
     cd job-platform
     ```

2. **Open the project**
     - Option 1: Double-click `index.html`
     - Option 2: Use Live Server (VSCode extension)

3. **Get started**
     - Fill your profile in the "My Profile" tab
     - Browse available listings
     - Use filters and search
     - Add listings to favorites
     - Create new listings via "Manage Listings"

## ✅ Performance Criteria

The application meets the following performance criteria:

- ✅ **Intuitive Interface**: Clear tab navigation with immediate visual feedback
- ✅ **Effective Validation**: Strict data integrity checks with contextual error messages
- ✅ **Dynamic Without Refresh**: All interactions handled via DOM manipulation (SPA-like behavior)
- ✅ **Complete Listings Management**: 100% functional CRUD with intuitive modals
- ✅ **Operational Search and Filtering**: Real-time result updates with counters
- ✅ **Reliable Persistence**: localStorage for profile, favorites, and custom listings

## 🎓 Implemented User Stories

### Form Management
- ✅ Error messages shown for invalid profile data
- ✅ Prevention of submitting incomplete data

### Search and Filtering
- ✅ Keyword search in positions, companies, and descriptions
- ✅ Filtering by required skills with clickable tags
- ✅ Real-time results updates

### Listings Management
- ✅ Adding new listings via modal form
- ✅ Editing existing listings with pre-filled data
- ✅ Deleting listings with confirmation

### Favorites System
- ✅ Mark listings as favorites
- ✅ Favorites persist after closing the browser
- ✅ Dedicated tab to view all favorites

### User Profile
- ✅ Create and edit profile with skills
- ✅ Automatic profile saving

### User Experience
- ✅ Responsive interface on mobile and desktop
- ✅ Visual feedback on all interactions

## 🌟 Bonus Features

- **Advanced Regex**: Strict validation for URLs and specific formats
- **Transition Animations**: Smooth visual effects for modals and tabs
- **Dynamic Counters**: Real-time display of favorites and result counts
- **ARIA Accessibility**: Screen reader support with appropriate attributes

## 👨‍💻 Author

**Sami Regragui**  
Project completed as part of the YouCode Youssoufia training, supervised by Mr. Aymane Benhima

---

## 📄 License

This project is an educational project. Can be used for learning purposes without restrictions, or for commercial use with this readme included.

---

**Note**: This application uses Vanilla JavaScript without external frameworks, demonstrating mastery of core web development concepts (DOM manipulation, event handling, data persistence, form validation).