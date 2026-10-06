# ⚡ Industry-Optimized Password Generator

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Web Crypto API](https://img.shields.io/badge/CSPRNG-Web_Crypto_API-success?style=for-the-badge)](#)

A zero-bloat, ultra-optimized cryptographic password generator built with strict performance standards and native Web Crypto APIs.

---

## 🎯 Design Principles

- **Zero Boilerplate Bloat**: No heavy external dependencies. Pure React state management with memoized character pools.
- **Cryptographic Security**: Uses `window.crypto.getRandomValues()` (CSPRNG) instead of insecure `Math.random()`.
- **Instant UI Feedback**: Sub-millisecond generation time with instant clipboard copy and entropy strength metering.
- **Responsive & Modern**: Styled with Tailwind CSS for clean layout on all viewports.

---

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Randomness Engine**: Native [Web Crypto API](https://developer.mozilla.org/en-US/docs/Web/API/Crypto/getRandomValues)

---

## 🚀 Running Locally

```bash
# 1. Clone repository
git clone https://github.com/Nikhil-Vzo/Industry-optimised-Password-generator.git
cd Industry-optimised-Password-generator

# 2. Install dependencies
npm install

# 3. Start dev server
npm run dev
```

---

## 👨‍💻 Author
[Nikhil Yadav](https://github.com/Nikhil-Vzo)
