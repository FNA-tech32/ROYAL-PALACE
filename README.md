# Royal Palace Hotel & Resorts 🏨✨

A luxury hotel and resort web application featuring front-of-house booking, dynamic room showcases, guest portal management, and a complete offline management console.

---

## 🌟 Overview & Architecture

**Royal Palace Hotel & Resorts** is a lightweight, high-performance web application built with **HTML5, Vanilla CSS3, and Pure Vanilla JavaScript**. It operates seamlessly without requiring any external build tooling, server runtimes, or Node.js dependencies.

### 🏛️ Core Technology Stack
- **Structure**: Semantic HTML5 (W3C validated).
- **Styling**: Vanilla CSS3 with CSS variables (tokens), CSS Grid, and Flexbox for responsive layouts across all device viewports (mobile, tablet, desktop).
- **Interactivity**: Pure Vanilla JavaScript with localized browser `localStorage` state management for bookings, accounts, and hotel configuration.
- **Typography**: Google Fonts (*Playfair Display* for luxury serif headings, *Inter* for clean UI sans-serif).
- **Icons**: Inline SVG vector graphics & Lordicon animated candidates.

---

## 📱 Contact & Brand Identity

- **Brand Name**: Royal Palace Hotel & Resorts
- **Brand Mark**: `RP`
- **Phone Number**: `9876543210`
- **WhatsApp**: `9876543210` (`https://wa.me/9876543210`)
- **Email Address**: `example@gmail.com`
- **Location**: 12 Adetokunbo Ademola Street, Victoria Island, Lagos, Nigeria

---

## 🗂️ Application Structure & Pages

### 🌐 Public Guest Website
| Page | File | Description |
|---|---|---|
| **Home** | [`index.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/index.html) | Hero showcase, quick booking widget, featured luxury suites, hotel amenities, testimonials, location map, and newsletter. |
| **Rooms & Suites** | [`rooms.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/rooms.html) | Full catalog of accommodations with real-time filters (capacity, price, room type). |
| **Room Details** | [`room-details.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/room-details.html) | High-definition room views, detailed amenity breakdowns, policies, and direct booking CTA. |
| **Booking Engine** | [`booking.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/booking.html) | Multi-step interactive reservation system with dates, room selection, guest data, and payment breakdown. |
| **Confirmation** | [`confirmation.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/confirmation.html) | Digital booking receipt with reservation reference number and instant WhatsApp confirmation link. |
| **Amenities** | [`amenities.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/amenities.html) | Comprehensive list of resort amenities (infinity pool, spa, fine dining, fitness center, conference halls). |
| **Special Offers** | [`offers.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/offers.html) | Curated packages, seasonal discounts, weekend getaways, and VIP specials. |
| **Gallery** | [`gallery.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/gallery.html) | Filterable photo gallery showcasing interiors, dining, events, and grounds. |
| **About Us** | [`about.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/about.html) | Hotel history, hospitality values, leadership message, and key statistics. |
| **Contact** | [`contact.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/contact.html) | Interactive contact form with direct WhatsApp redirection, 24/7 call buttons, and embedded location map. |

### 👤 Guest Authentication & Portal
| Page | File | Description |
|---|---|---|
| **Guest Login** | [`guest-login.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/guest-login.html) | Dedicated guest portal authentication with quick demo sign-in (`example@gmail.com` / `guest123`). |
| **Guest Register** | [`guest-register.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/guest-register.html) | Guest account registration with client-side validation. |
| **Guest Dashboard** | [`guest-dashboard.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/guest-dashboard.html) | View upcoming stays, past reservation history, booking status, and profile details. |
| **Booking Access** | [`guest-booking-access.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/guest-booking-access.html) | Instant reservation lookup by booking reference code without logging in. |

### 🛠️ Hotel Management Console (`manage/`)
| Page | File | Description |
|---|---|---|
| **Staff Login** | [`manage/login.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/manage/login.html) | Secure authentication for Admin & Front-Desk Staff (`admin@example.com` / `manager@example.com`). |
| **Staff Register** | [`manage/register.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/manage/register.html) | Staff onboarding and account creation portal. |
| **Admin Console** | [`manage/console.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/manage/console.html) | Complete administrative dashboard: live KPI metrics, active bookings table, admission requests, transaction logs, room overrides, and role permissions. |

---

## 📱 Full Responsive Design Audit

The website is engineered for seamless cross-device performance:
- **Mobile Viewports (320px – 480px)**:
  - Collapsible off-canvas slide drawer navigation with safe-area bottom padding.
  - Form grids stack to single-column layouts for touch friendliness.
  - Tables adapt into mobile-friendly stacked cards (`manage.css`).
  - Zero horizontal micro-scroll with `overflow-x: hidden; max-width: 100%;` applied on `html` and `body`.
- **Tablet Viewports (640px – 960px)**:
  - Fluid 2-column grid transitions for rooms, amenities, and search filters.
  - Hamburger menu navigation with backdrop blur overlay.
- **Desktop Viewports (1024px – 1440px+)**:
  - Full luxury horizontal navigation bar with direct booking CTA button.
  - Multi-column grids for galleries, room lists, and admin dashboard KPI cards.

---

## 🚀 How to Run Locally

Because this application relies on standard web technologies:
1. Double-click any `.html` file (e.g. [`index.html`](file:///c:/Projects/GitHubRepos/Royal-Stay-Guest-Hotel-and-Resorts/index.html)) to open it in any modern browser (Chrome, Edge, Firefox, Safari).
2. Alternatively, run any local HTTP server:
   ```powershell
   # Python built-in server
   python -m http.server 8000
   ```
   Open `http://localhost:8000` in your web browser.
