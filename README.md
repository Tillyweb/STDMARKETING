# 🦷 STD Dental Marketing — Advanced Partner Portal

A visually stunning, high-end single-page web application featuring custom **cyber-purple glassmorphic aesthetics**, interactive background bubble animations, and an intelligent **AI Marketing Suggestion Engine** backed by Google Gemini API.

This application is designed specifically for **ห.จ.ก S.T.D. DENTALLAB จำกัด** to streamline client clinic databases, track dispatching/delivery note status, and leverage generative AI to provide cutting-edge regional business advice.

👉 **Live Demo / Deployment Ready**: Simply host `index.html` on any static provider (GitHub Pages, Netlify, Vercel).

---

## 🎨 Design System & Aesthetics

This portal replaces standard minimum viable product designs with high-fidelity, premium SaaS aesthetics:
*   **Ambient Neon Backdrops**: Blurry, slow-drifting neon gradient orbs orbiting in the background to add immense visual depth.
*   **Frosted Glass Framework**: Glass panels (`backdrop-filter: blur(24px)`) with semi-transparent borders and subtle lavender shadows.
*   **Interactive Particle Bubbles**: Custom-coded floating bubble particles that float up from the bottom of the screen. Hovering over them scales them up, and **clicking them pops them with a cute fluid particle splash animation**.
*   **Polished Skeletons & Modals**: Smooth gradient-pulse skeletons while loading database entries and slide-out drawers (`request-drawer`, `settings-drawer`) instead of disruptive full-screen redirections.
*   **Print-ready Delivery Note**: High-contrast, beautifully styled A4 physical dispatch voucher featuring warning terms, signature lines, stamp highlights, and a **scannable mock barcode**. All navigation links and buttons automatically hide when printing.

---

## ⚡ Technical Features

1.  **Dual Role Privilege System**:
    *   **Admin** (Access Code: `8956`): Full CRUD permissions, deleting requests, and AI analytics triggers.
    *   **Staff** (Access Code: `std497`): Read and add permissions, with standard updates routed through an Admin Approval queue.
2.  **Settings Panel & API Key Management**:
    *   Sleek settings slide-out panel allowing users to input and securely save their own **Gemini API key** in browser `localStorage`.
3.  **Simulated AI Analytics Fallback**:
    *   If no Gemini API key is provided, the AI Marketing button will dynamically read the active Chart.js monthly data, calculate cumulative values, and generate **three highly detailed, professional regional marketing suggestions in Thai** (rendered in formatted Markdown inside an interactive modal).
    *   If a Gemini API key is set, it will make direct calls to the live `gemini-2.5-flash` model.
4.  **Google Sheets Integration**: Standardized JSONP data fetching/writing to provide instant CRUD integration.

---

## 🚀 Getting Started

### Local Setup
Since this app is a fully static standalone single-page application with CDNs, there are no dependencies to install!
1. Clone this repository:
   ```bash
   git clone https://github.com/Tillyweb/STDMARKETING.git
   ```
2. Double-click `index.html` to open and run it immediately in any modern web browser.

### Hosting
You can deploy this page in 30 seconds to **GitHub Pages**:
1. Go to your repository settings on GitHub.
2. Under the **Pages** tab, select **Deploy from a branch** and set the source branch to `main` (folder `/root`).
3. Click Save, and your app will be live globally!

---

ห.จ.ก S.T.D. DENTALLAB จำกัด © 2026. Designed with Advanced Agentic Coding.
