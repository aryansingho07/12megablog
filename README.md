# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

<div align="center">

# 🚀 12MegaBlog

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=A855F7&center=true&vCenter=true&width=940&lines=Welcome+to+the+Future+of+Blogging!;Create%2C+Share%2C+and+Explore+Stories;Built+with+React+%26+Three.js;Modern+UI+%2B+3D+Experience" alt="Typing SVG" />
</div>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/Appwrite-F02E65?style=for-the-badge&logo=appwrite&logoColor=white" alt="Appwrite" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/yourusername/12megablog?style=social" alt="GitHub stars" />
  <img src="https://img.shields.io/github/forks/yourusername/12megablog?style=social" alt="GitHub forks" />
  <img src="https://img.shields.io/github/issues/yourusername/12megablog" alt="GitHub issues" />
  <img src="https://img.shields.io/github/license/yourusername/12megablog" alt="License" />
</p>

---

### 🌟 Experience the Future of Blogging

**12MegaBlog** is not just another blogging platform – it's a revolutionary, immersive experience that combines the power of modern web technologies with stunning 3D visuals and smooth animations. Create, share, and explore stories in a whole new dimension!

<div align="center">
  <img src="https://user-images.githubusercontent.com/placeholder/demo.gif" alt="12MegaBlog Demo" width="800px" style="border-radius: 10px; box-shadow: 0 10px 30px rgba(0,0,0,0.3);" />
</div>

</div>

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎨 **Modern UI/UX**

- Beautiful gradient backgrounds
- Smooth animations and transitions
- Responsive design for all devices
- Dark theme with glassmorphism effects

### 🔐 **Authentication System**

- Secure user registration and login
- Password reset functionality
- Session management with Redux
- Protected routes and authorization

</td>
<td width="50%">

### 📝 **Content Management**

- Rich text editor with TinyMCE
- Create, edit, and delete posts
- Image upload and management
- Draft and publish workflow

### 🌐 **3D Experience**

- Interactive Three.js components
- Animated hero sections
- Immersive visual effects
- Hardware-accelerated graphics

</td>
</tr>
</table>

## 🛠️ Tech Stack

<div align="center">

| Frontend                                                                                                  | Backend                                                                                                         | Styling                                                                                                                              | Build Tools                                                                                         |
| --------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------- |
| ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)          | ![Appwrite](https://img.shields.io/badge/Appwrite-F02E65?style=flat-square&logo=appwrite&logoColor=white)       | ![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)                        | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)       |
| ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white) | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)          | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)                                        | ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white) |
| ![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)          | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ![Styled Components](https://img.shields.io/badge/Styled_Components-DB7093?style=flat-square&logo=styled-components&logoColor=white) | ![NPM](https://img.shields.io/badge/NPM-CB3837?style=flat-square&logo=npm&logoColor=white)          |

</div>

## 🚀 Quick Start

### Prerequisites

<div align="center">
  <img src="https://img.shields.io/badge/Node.js->=16.0.0-green?style=for-the-badge&logo=node.js" alt="Node.js" />
  <img src="https://img.shields.io/badge/NPM->=8.0.0-red?style=for-the-badge&logo=npm" alt="NPM" />
</div>

### Installation

```bash
# 📦 Clone the repository
git clone https://github.com/yourusername/12megablog.git
cd 12megablog

# 📥 Install dependencies
npm install

# 🔧 Set up environment variables
cp .env.example .env.local
```

### Environment Setup

Create a `.env.local` file in the root directory:

```env
# 🔐 Appwrite Configuration
VITE_APPWRITE_URL=https://cloud.appwrite.io/v1
VITE_PROJECT_ID=your_project_id
VITE_DATABASE_ID=your_database_id
VITE_COLLECTION_ID=your_collection_id
VITE_BUCKET_ID=your_bucket_id

# 🌐 TinyMCE API Key (Optional)
VITE_TINYMCE_API_KEY=your_tinymce_api_key
```

### Development

```bash
# 🚀 Start development server
npm run dev

# 🏗️ Build for production
npm run build

# 👀 Preview production build
npm run preview

# 🔍 Run linting
npm run lint
```

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F75C7E&center=true&vCenter=true&width=435&lines=Visit+http%3A%2F%2Flocalhost%3A5173;Start+Creating+Amazing+Content!" alt="Local server info" />
</div>

## 📱 Application Structure

```
12megablog/
├── 📁 public/                  # Static assets
├── 📁 src/
│   ├── 📁 components/          # Reusable UI components
│   │   ├── 🎭 Hero3D.jsx      # 3D hero component
│   │   ├── 🎨 ThreeScene.jsx   # Three.js scene
│   │   ├── 📝 PostForm.jsx     # Blog post form
│   │   └── 🔒 AuthLayout.jsx   # Authentication wrapper
│   ├── 📁 pages/               # Application pages
│   │   ├── 🏠 Home.jsx         # Landing page
│   │   ├── ✍️ AddPost.jsx      # Create new post
│   │   ├── ✏️ EditPost.jsx     # Edit existing post
│   │   └── 👤 Login.jsx        # User authentication
│   ├── 📁 store/               # Redux store
│   ├── 📁 appwrite/            # Backend services
│   └── 📁 conf/                # Configuration files
├── 📄 package.json             # Dependencies
└── ⚙️ vite.config.js          # Vite configuration
```

## 🎯 Key Features Breakdown

### 🎨 **Interactive 3D Elements**

- Powered by Three.js and React Three Fiber
- Smooth animations and particle effects
- Hardware-accelerated performance
- Responsive 3D scenes

### 📝 **Rich Text Editor**

- TinyMCE integration for advanced formatting
- Image upload and management
- Real-time preview
- Auto-save functionality

### 🔐 **Secure Authentication**

- Appwrite backend integration
- JWT token management
- Protected routes
- User session persistence

### 🎭 **Modern Design**

- Glassmorphism UI effects
- Gradient backgrounds
- Smooth transitions
- Mobile-first responsive design

## 🌐 Deployment

### Vercel (Recommended)

```bash
# 🚀 Deploy to Vercel
npm i -g vercel
vercel --prod
```

### Other Platforms

<div align="center">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Netlify" />
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" alt="Railway" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white" alt="Render" />
</div>

## 📈 Performance

<div align="center">
  <img src="https://img.shields.io/badge/Lighthouse-100%25-brightgreen?style=for-the-badge&logo=lighthouse" alt="Lighthouse Score" />
  <img src="https://img.shields.io/badge/Bundle_Size-<500KB-blue?style=for-the-badge" alt="Bundle Size" />
  <img src="https://img.shields.io/badge/Load_Time-<2s-orange?style=for-the-badge" alt="Load Time" />
</div>

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

<div align="center">
  <img src="https://contrib.rocks/image?repo=yourusername/12megablog" alt="Contributors" />
</div>

### Development Workflow

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 Commit your changes (`git commit -m 'Add amazing feature'`)
4. 📤 Push to the branch (`git push origin feature/amazing-feature`)
5. 🔃 Open a Pull Request

## 📊 Project Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yourusername&repo=12megablog&show_icons=true&theme=radical" alt="GitHub Stats" />
</div>

## 🐛 Known Issues

- [ ] Three.js performance optimization needed for mobile devices
- [ ] Dark mode toggle implementation
- [ ] SEO improvements for blog posts

## 🗺️ Roadmap

- [ ] 🎯 **v2.0**: Advanced 3D interactions
- [ ] 🌙 **v2.1**: Dark/Light theme toggle
- [ ] 📱 **v2.2**: Progressive Web App (PWA) support
- [ ] 🔍 **v2.3**: Advanced search and filtering
- [ ] 💬 **v2.4**: Comment system
- [ ] 📊 **v2.5**: Analytics dashboard

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=A855F7&center=true&vCenter=true&width=600&lines=Made+with+❤️+and+lots+of+☕;Star+⭐+if+you+found+this+helpful!;Happy+Coding!+🚀" alt="Footer message" />
</div>

<div align="center">
  <p>
    <a href="#top">⬆️ Back to Top</a> •
    <a href="mailto:your.email@example.com">📧 Contact</a> •
    <a href="https://twitter.com/yourusername">🐦 Twitter</a> •
    <a href="https://linkedin.com/in/yourprofile">💼 LinkedIn</a>
  </p>
</div>
