# RiseAtSeven - Premium Agency Portfolio

A high-end, interactive agency portfolio website built with Next.js, GSAP, and Framer Motion. This project features sophisticated animations, modern UI components, and a focus on premium user experience.

## 🚀 Technologies Used

- **Framework**: [Next.js 15+](https://nextjs.org/) (App Router)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **Animations**: 
  - [GSAP](https://greensock.com/gsap/) (ScrollTrigger, Timelines)
  - [Framer Motion](https://www.framer.com/motion/) (Submenu transitions, Image crossfades)
- **Components**:
  - [Swiper.js](https://swiperjs.com/) (Mobile carousels, Infinite loops)
  - [Lenis](https://github.com/darkroomengineering/lenis) (Smooth scrolling)

## ✨ Key Features

### 1. Advanced Desktop Navigation
- **Dynamic Submenus**: 2-column layout with real-time image previews that change on hover.
- **Sliding Pill Background**: A white background that follows the cursor across nav items, pinning itself to active selections.
- **Micro-interactions**: Slide-up text reveal effects and hover-triggered badges.

### 2. Interactive Hero Section
- **Dynamic Title Animation**: A "push" interaction where an expanding image dynamically shifts title words apart in a flex layout.
- **Responsive Branding**: Integrated award badges and high-resolution agency showreel images.

### 3. Custom Interactive Elements
- **Legacy Section**: Desktop-pinned stacked card animation synchronized with a mobile-friendly Swiper.
- **What's New Grid**: 3-column interactive grid with custom cursor tracking and "blurred eclipse" hover effects.
- **Kinetic CTA**: A scroll-scrubbed kinetic typography section where text follows a sophisticated enter-drop-exit path.

### 4. Custom Cursor System
- **Context-Aware Cursor**: Changes behavior based on the hovered section (e.g., "blur" effect on grid images).
- **Smooth Tracking**: Built with GSAP for lag-free movement.

### 5. Premium Footer
- Responsive 4-column layout featuring newsletter integration, social badges, and large bottom-anchored branding.

## 🛠️ Local Setup

Follow these steps to get the project running on your local machine:

### 1. Clone the Repository
```bash
git clone [your-repo-url]
cd RiseAtSeven
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run the Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📁 Project Structure

- `src/app/`: Next.js App Router pages and global styles.
- `src/components/`: Reusable React components (Navbar, Hero, Footer, etc.).
- `src/components/ui/`: Atomic UI elements (Buttons, Inputs).
- `public/`: Static assets (Images, Fonts, Icons).

## 💡 Notes

- **Animations**: Heavy use of `gsap.context()` ensures that animations are properly cleaned up on component unmount, preventing memory leaks.
- **Performance**: High-resolution images are optimized via Next.js `<Image />` or strategic CSS loading.
- **Responsiveness**: Strictly follows a "Mobile-First" approach, with specific desktop enhancements for high-end displays.

---

Built with ❤️ for **RiseAtSeven**.
