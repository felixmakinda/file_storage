# 📁 File Storage Web Application

A modern, fast, and secure file storage web application built with **Next.js** and **Convex**. Easily upload, manage, and access your files from anywhere!

---

## 🚀 Features

- 🌐 Built with **Next.js** for fast, SEO-friendly frontend
- ⚡ Real-time data handling powered by **Convex**
- 📂 File upload and management system
- 🔐 Secure file storage and access
- 🔎 File preview & download functionality
- 🗑️ File deletion & management dashboard
- 🧑‍💻 Clean, minimal UI
- 🌍 Fully responsive (mobile & desktop)

---

## 🛠️ Tech Stack

- **Frontend:** Next.js
- **Backend / Database:** Convex
- **Storage:** Configurable (Local / Cloud storage - e.g., AWS S3, Firebase, etc.)
- **Authentication:** Optional (NextAuth / Clerk / Custom)

---

## 📦 Installation

### Clone the Repository

```bash
git clone https://github.com/felixmakinda/file_storage.git
cd file_storage
```

### Install Dependencies

```bash
npm install
# or
yarn install
```

### Set up Convex

1. Create a [Convex](https://dashboard.convex.dev/) project.
2. Get your **deployment URL** and **admin key**.
3. Update `.env.local` with:

```bash
NEXT_PUBLIC_CONVEX_URL=your_convex_deployment_url
CONVEX_ADMIN_KEY=your_convex_admin_key
```

### (Optional) Configure Storage Provider

- Add necessary credentials to `.env.local`.
- Adjust storage logic in `/lib/storage.ts` or `/utils/`.

---

## 🏃‍♂️ Run Locally

```bash
npm run dev
# or
yarn dev
```

Visit: `http://localhost:3000`

---

## 🚧 Folder Structure

```
├── convex/          # Convex functions (queries, mutations)
├── lib/             # Utility functions (e.g., storage logic)
├── pages/           # Next.js pages
├── components/      # Reusable React components
├── public/          # Static assets
├── styles/          # CSS/SCSS files
├── .env.local       # Environment variables
├── README.md
└── ...
```

---

## 🌐 Deployment

You can deploy easily to:

- **Vercel** (Recommended for Next.js)
- **Netlify**, **Render**, or others (ensure Convex & storage configs are set)

---

## 🙌 Contributing

Feel free to fork the project, open issues, or submit pull requests.

```bash
# To contribute:
1. Fork the repo
2. Create a new branch (git checkout -b feature/your-feature)
3. Commit changes
4. Push to your fork
5. Open a PR
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 📬 Contact

- Created by **Felix Makinda**
- Questions? DM me or open an issue!
