# CampusNest

CampusNest is a comprehensive full-stack web platform designed specifically for UC Riverside students to explore, rate, and share housing options around campus. The platform aims to simplify the housing search process by creating a centralized, trusted community of UCR students sharing their housing experiences.

## 🎯 About The Project

CampusNest addresses the critical need for reliable student housing information at UCR by providing:
- A secure, UCR student-exclusive platform using OAuth 2.0 authentication
- Verified student reviews and ratings of local housing options
- Detailed housing listings with comprehensive information
- A user-friendly interface for posting and discovering housing opportunities

## 🚀 Features

- Secure UCR student authentication via OAuth 2.0
- Modern and responsive UI built with Next.js 14
- Student-verified housing reviews and ratings
- Housing listing creation and management
- Firebase integration for backend services
- Styling with Tailwind CSS and Bootstrap
- Smooth animations with Framer Motion
- Component-based architecture
- Robust development tooling

## 🛠️ Tech Stack

- **Frontend Framework:** Next.js 14, React 18
- **Styling:** Tailwind CSS, Bootstrap, React Bootstrap
- **Backend/Database:** Firebase
- **Animation:** Framer Motion
- **Icons:** Heroicons, React Icons
- **HTTP Client:** Axios
- **Development Tools:**
  - ESLint for code linting
  - Prettier for code formatting
  - Husky for git hooks
  - PostCSS for CSS processing

## 📦 Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn package manager
- Git

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd R-Group
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   - Create a `.env.local` file in the root directory
   - Add necessary environment variables (refer to `.env.example` if available)

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run format` - Format code with Prettier
- `npm run check` - Check code formatting
- `npm run eslint` - Run ESLint with specific extensions

## 🔧 Project Structure

```
R-Group/
├── src/
│   ├── app/          # Next.js app directory
│   ├── components/   # Reusable React components
│   ├── data/        # Static data and configurations
│   ├── public/      # Static assets
│   └── utils/       # Utility functions
├── public/          # Public assets
└── [Configuration files]
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the terms of the license included with this repository.

## 👥 Contributors

See [Contributors.jsx](./Contributors.jsx) for a list of project contributors.

---

Made with ❤️ by the R-Group team
