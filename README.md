# Project: Star Wars & Product Showcase Experience

A highly interactive, cinematic web experience built with Next.js, GSAP, and Tailwind CSS.

## 🚀 Features Implemented

### 1. Cinematic Opening Sequence
- **Star Wars Crawl**: A classic 3D scrolling text intro using CSS 3D transforms and GSAP.
  - **Dynamic Starfield**: A canvas-based background with moving stars that fly past the viewer.
  - **Receding Effect**: Text correctly fades and shrinks into the distance (Z-axis animation).
  - **Sequencing**: Automatically triggers after the initial "Coming Soon" brand reveal.

### 2. Horizontal Product Showcase
- **Scroll-Driven Navigation**: A horizontal scroll section that activates naturally as the user scrolls down.
- **Parallax Depth**: Product images move slightly against the scroll direction to create a 3D depth effect.
- **Portrait Design**: 6 high-quality, portrait-oriented images from Unsplash.
- **Interactive Styling**:
  - Black & White default state.
  - Full color reveal on hover.
  - Scale animations for a premium feel.

### 3. Email Signup Section
- **Sleek Dark Theme**: A "Join the Resistance" newsletter signup form.
- **Visual Polish**: Ambient glow effects and minimal input styling.
- **Placement**: Integrated seamlessly after the product scroll and before the footer.

### 4. Global Visual Polish
- **Custom Cursor**: A cinematic custom cursor with a trailing follower and hover states for interactive elements.
- **Sound Design (Visual)**: Grainy noise overlay for a filmic texture.
- **Responsive Layout**: Optimized for different screen sizes (though primarily designed for desktop impact).
- **Footer**: A clean "End of Transmission" footer to conclude the experience.

## 🛠️ Tech Stack
- **Framework**: Next.js 15 (App Router)
- **Styling**: Tailwind CSS v4
- **Animation**: GSAP (GreenSock Animation Platform) + ScrollTrigger
- **Language**: TypeScript

## 📦 Project Structure
- `app/page.tsx`: Main entry point orchestrating the entire GSAP timeline.
- `app/components/`:
  - `StarWarsCrawl.tsx`: The 3D text scroll component.
  - `Starfield.tsx`: Canvas star animation.
  - `ProductScroll.tsx`: Horizontal scroll section with parallax.
  - `EmailSignup.tsx`: Newsletter form.
  - `CustomCursor.tsx`: Interactive cursor.

## 🏃‍♂️ How to Run
1. Install dependencies:
   ```bash
   npm install
   ```
2. Run the development server:
   ```bash
   npm run dev
   ```
3. Open [http://localhost:3000](http://localhost:3000) in your browser.
# kaiknot-rw
