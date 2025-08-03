# 🏡 Property Detail Page – Next.js + Tailwind CSS

A responsive, modern property detail page for real estate or listing applications, built using **Next.js**, **Tailwind CSS**, and **TypeScript**. This project showcases a dynamic and interactive interface with reusable components, dynamic routing, booking functionality, and user reviews.

---

## 🚀 Features

- 🌐 **Dynamic Routing** with `[id].tsx` pages for each property
- 🧱 **Modular & Reusable Components** (PropertyDetail, BookingSection, ReviewSection)
- 🎯 **Fully Responsive UI** using Tailwind’s mobile-first utility classes
- 🛏️ **Detailed Property Info**: Images, location, amenities, descriptions
- 📅 **Interactive Booking Section** with date pickers and price calculation
- 🌟 **User Review Section** with avatars, ratings, and feedback cards
- 📦 **TypeScript Support** with proper data typing for props

---

## 📸 Screenshots

<img width="583" height="564" alt="image" src="https://github.com/user-attachments/assets/a5c3d3ad-8ad2-4f65-9858-d1107a036305" />

---

## 🧠 Learning Objectives

- Implement dynamic routing using Next.js
- Create reusable and typed React components
- Apply responsive layout principles with Tailwind CSS
- Manage props and local component state efficiently
- Organize property data in an intuitive user interface
- Follow best practices for structure, styling, and performance

---

## 🏗️ Project Structure
```
/components
├── PropertyDetail.tsx
├── BookingSection.tsx
└── ReviewSection.tsx

/pages
├── index.tsx
└── property/[id].tsx

/data
└── propertyListings.ts

/types
└── property.d.ts
```
---

## 🔧 Getting Started

### Prerequisites

- Node.js ≥ 16.x
- npm or yarn
- Git (optional)

### Installation

```
git clone https://github.com/your-username/alx-listing-app-01.git
cd alx-listing-app-01
npm install

Run in Development Mode
npm run dev
Then open: http://localhost:3000

Sample Property Route
http://localhost:3000/property/Modern Villa with Pool
Adjust the URL based on the available property name or id in your data.
```

## 📁 Sample Data (Static)

Located in: /data/propertyListings.ts

You can mock multiple property entries here to simulate a real estate listing experience.

## 📐 Best Practices Followed
- Component separation using Single Responsibility Principle
- Strict TypeScript typing for props and property data
- Consistent mobile-first styling with Tailwind
- Modular and scalable folder structure
- Performance optimizations like lazy image loading and efficient state management

## 🛠️ Technologies Used
- Tech	Description
- Next.js	React framework for SSR/SSG
- Tailwind CSS	Utility-first styling
- TypeScript	Static type checking
- React Icons	For amenities & UI visuals
- Day.js	Date manipulation (if included)

## ✅ Future Enhancements
- Add real backend integration or CMS (e.g., Sanity, Contentful)
- Authentication & User profile management
- Map integration for property locations
- Booking logic with payment gateway

## 📜 License
This project is open-source and available under the MIT License.

## ✨ Acknowledgements
Inspired by modern real estate UIs like Airbnb, Lodgify, and Booking.com — combining simplicity with functionality for an elegant experience.

## 💬 Feedback & Contributions
Feel free to fork the repo, suggest features, or open pull requests.
Have questions or suggestions? Reach out via GitHub Issues.

>“Design is not just what it looks like and feels like. Design is how it works.” – Steve Jobs
