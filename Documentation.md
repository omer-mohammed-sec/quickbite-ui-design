# QuickBite – Full Project Documentation

**Course:** E-Commerce and Web Application  
**Assignment:** Group Assignment II – UI/UX Design Using Figma  
**University:** UNILAK  

---

## 1. Problem Statement

### What problem does the application solve?
Many people in Kigali, Rwanda find it difficult to order food from restaurants without physically going there. Existing solutions are either unavailable locally, confusing to use, or don't support local restaurants and payment methods. **QuickBite** solves this by providing a simple, fast, and locally-tailored food delivery experience.

### Who are the target users?
- Students and working professionals in Kigali (ages 18–40)
- People with busy schedules who cannot cook or go out
- Restaurants that want to expand their customer reach digitally

### Why is the system important?
- Saves users time and effort
- Helps local restaurants grow digitally
- Promotes Rwanda's growing digital economy
- Provides a convenient, reliable, and affordable delivery option

---

## 2. User Persona

### Persona: Alice Mutoni

| Attribute | Details |
|-----------|---------|
| **Name** | Alice Mutoni |
| **Age** | 24 |
| **Occupation** | University Student, UNILAK |
| **Location** | Gasabo, Kigali |
| **Tech Usage** | Smartphone daily, comfortable with apps |

**Goals:**
- Order food quickly between classes without leaving campus
- Discover new restaurants near her location
- Pay easily using Mobile Money (MTN/Airtel)

**Challenges / Frustrations:**
- Current food options require phone calls and long waits
- No visibility into delivery time or order status
- Unclear pricing and hidden delivery fees

**Quote:** *"I just want to order food in under 2 minutes and know exactly when it arrives."*

---

## 3. User Flow

The sequence of steps a user follows in the app:

Splash Screen
    │
    ▼
Login / Register
    │
    ▼
Home Page  ──────────────────────────────► Profile Page
    │                                           │
    ▼                                     (Edit profile,
Restaurant Page                            order history,
    │                                      addresses)
    ▼
Food Item Detail
    │
    ▼
Cart (Add / Remove Items)
    │
    ▼
Checkout (Address + Payment)
    │
    ▼
Order Confirmation
    │
    ▼
Order Tracking (Live Status)

**Explanation:** The user opens the app and is greeted by the splash screen, then directed to log in. Once on the home page, they can browse categories, tap a restaurant, select food items, adjust quantities, and proceed through checkout. After payment, a confirmation screen shows estimated delivery time and live order tracking.

---

## 4. Wireframes (Low-Fidelity)

4 screens were designed as low-fidelity wireframes focusing on structure and layout:

| Screen | Description |
|--------|-------------|
| **Screen 1 – Login/Register** | Email/password fields, login button, register link |
| **Screen 2 – Home Page** | Search bar, category pills, featured restaurant cards, bottom nav |
| **Screen 3 – Restaurant/Product Page** | Restaurant banner, info, menu items with Add buttons |
| **Screen 4 – Profile Page** | Avatar, user info, settings menu (Orders, Addresses, Payments) |

> See `/wireframes/` folder for exported images.



## 5. High-Fidelity UI Design

6 polished screens designed with full color, typography, icons, and spacing:

| Screen | Description |
|--------|-------------|
| **01 – Splash** | Branded orange screen with logo and "Get Started" CTA |
| **02 – Login** | Gradient top card, form fields, social login options |
| **03 – Home** | Promo banner, category icons, restaurant cards, bottom nav |
| **04 – Food Detail** | Item image, reviews, size selector, quantity, add to cart |
| **05 – Cart & Checkout** | Item list with qty controls, order summary, promo code |
| **06 – Order Confirmed** | Green success screen, order details, 4-step status tracker |

### Design System

**Color Palette:**
- Primary: `#FF5919` (Orange) — brand identity, CTAs
- Secondary: `#21B86A` (Green) — success states, open status
- Background: `#F9F9F9` — clean off-white
- Dark Text: `#1A1A1F`
- Muted Text: `#73737A`
- Card White: `#FFFFFF`

**Typography:** Inter (Google Font)
- Headings: Inter Bold 20–36px
- Body: Inter Regular 13–15px
- Labels: Inter Medium 11–13px

**Spacing:** 8px grid system, 20px horizontal padding, 16px card radius

---

## 6. Features Implemented

- ✅ User authentication (Login / Register)
- ✅ Location display
- ✅ Category browsing
- ✅ Promotional banner
- ✅ Restaurant listing with ratings and delivery times
- ✅ Food item detail with size selection and quantity control
- ✅ Cart management with order summary
- ✅ Promo code input
- ✅ Order confirmation screen
- ✅ 4-step order status tracker
- ✅ User profile with settings menu

---

## 7. Accessibility Considerations

| Consideration | How It Was Applied |
|--------------|-------------------|
| **Font Sizes** | Minimum 11px labels, 14px+ for body text |
| **Color Contrast** | White text on orange (#FF5919) passes WCAG AA ratio |
| **Touch Targets** | All buttons ≥ 48px height for easy tapping |
| **Clear Navigation** | Persistent bottom nav bar with icons + labels |
| **Status Feedback** | Success/error states use both color AND icons |
| **Consistent Layout** | Same header, nav, and card patterns across all screens |
| **Readable Hierarchy** | Clear H1 → body → label size distinction per screen |

---

## 8. Challenges Faced

1. **Maintaining consistency** across 10 screens (wireframes + HiFi) — solved by defining a color and typography system upfront.
2. **Balancing simplicity with detail** in wireframes — kept placeholders clear without over-designing.
3. **Prototype connections** — ensuring all navigation arrows in Figma connect correctly required careful labeling.
4. **Local context** — adapting the design for Kigali users (currency in RWF, familiar restaurant types) added thoughtfulness to the UX.

---

## 9. Conclusion

QuickBite demonstrates how UI/UX design principles can be applied to create a user-centered food delivery experience tailored to the local Kigali market. Through systematic wireframing, a consistent high-fidelity design system, and an intuitive user flow, the prototype achieves the goal of being simple, fast, and accessible. The design follows modern mobile UI practices and is ready to serve as a foundation for real development.

---

*"Every successful application starts with understanding users and designing experiences that solve real problems."*
