# Workers Listing App - Assignment

**Author:** Abhay Jangir  
**Branch:** `assignment/abhay-jangir` 

---

## Features Implemented

1. **Responsive Cards Layout**
   - Corrected grid layout for desktop, tablet, and mobile.
   - Modern card design with shadow, rounded corners, hover effects, and service badges.

2. **Sticky Navbar**
   - Fully responsive top navigation bar that remains visible while scrolling.

3. **Filters and Pagination**
   - Filter workers by service type and maximum price/day.
   - Pagination with 9 workers per page.
   - Filters and pagination work seamlessly together.

4. **API Integration**
   - Worker data served via `/api/workers` route.
   - Frontend fetches data using SWR with caching, loading skeletons, and error handling.
   - Original JSON import logic is commented out for reference.

5. **Performance Optimizations**
   - Lazy loading for images (Next.js Image component).
   - Memoization for filtered and paginated workers.
   - Skeleton loading screens while data fetches.
   - Clean and maintainable code with proper TypeScript types.

---

## Technologies Used

- **Frontend:** Next.js 13 (App Router), React, TypeScript  
- **Styling:** Tailwind CSS  
- **API & Data:** Next.js API Routes, SWR for data fetching and caching  
- **Deployment:** GitHub Pages / Vercel (optional)

---

## Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/abhayjangir/assignment-abhay-jangir.git
