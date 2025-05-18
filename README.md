# Trackit-Saveetha

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Available-brightgreen)](https://lafdavns.site/)

**Trackit-Saveetha** is a modern web application designed to streamline item tracking and inventory management for Saveetha University. Built with a focus on performance, scalability, and user experience, this project leverages cutting-edge technologies to deliver a seamless solution for managing institutional assets.

---

## 🚀 Features

- **Real-Time Inventory Tracking**: Monitor and manage items across various departments with up-to-date information.
- **User Authentication**: Secure login and access control using Supabase authentication services.
- **Responsive Design**: Optimized for desktops, tablets, and mobile devices to ensure accessibility on all platforms.
- **Interactive Dashboard**: Visualize inventory data with intuitive charts and tables.
- **Search and Filter**: Quickly locate items using dynamic search and filtering options.
- **Role-Based Access Control**: Differentiate user permissions for administrators, staff, and other roles.

---

## 🛠️ Tech Stack

- **Frontend**: [React](https://reactjs.org/), [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Backend & Auth**: [Supabase](https://supabase.io/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Package Manager**: [Bun](https://bun.sh/)

---

## 📦 Project Structure

```
├── public/                 # Static assets
├── src/                    # Source code
│   ├── components/         # Reusable UI components
│   ├── pages/              # Application pages
│   ├── services/           # API calls and services
│   └── utils/              # Utility functions
├── supabase/               # Supabase configuration and SQL scripts
├── .gitignore              # Git ignore rules
├── package.json            # Project metadata and dependencies
├── tailwind.config.ts      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
└── vite.config.ts          # Vite build configuration
```

---

## ⚙️ Getting Started

Follow these steps to set up the project locally:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Aadithya2201/Trackit-Saveetha.git
   cd Trackit-Saveetha
   ```

2. **Install dependencies**:

   ```bash
   bun install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the root directory and add your Supabase credentials:

   ```env
   VITE_SUPABASE_URL=your-supabase-url
   VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
   ```

4. **Run the development server**:

   ```bash
   bun dev
   ```

   The application will be available at `http://localhost:3000`.

---

## 🌐 Live Demo

Experience the application live:

👉 [https://lafdavns.site/](https://lafdavns.site/)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [Supabase](https://supabase.io/) for providing an open-source backend solution.
- [Tailwind CSS](https://tailwindcss.com/) for utility-first CSS framework.
- [Vite](https://vitejs.dev/) for fast and efficient build tooling.
