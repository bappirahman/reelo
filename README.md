# Re## ✨ Features

- 📱 **9:16 Vertical Video Platform**: Share videos exclusively in 9:16 aspect ratio for optimal mobile viewing
- � **Modern Video Experience**: Seamless video browsing and discovery interface
- �🎬 **Video Upload & Streaming**: Upload, process, and stream vertical videos seamlessly
- 👥 **User Profiles**: Create profiles to showcase your vertical video content
- 💾 **MongoDB Database**: Robust data storage with Mongoose ODM
- 🚀 **Next.js 15**: Latest React framework with App Router
- 🎨 **Tailwind CSS**: Modern, responsive UI design optimized for vertical content
- ⚡ **Turbopack**: Lightning-fast development buildsmodern video sharing platform built with Next.js for sharing vertical videos in 9:16 aspect ratio, optimized for mobile-first viewing experiences.

## ✨ Features

- 📱 **9:16 Vertical Video Platform**: Share videos exclusively in 9:16 aspect ratio for optimal mobile viewing

- 🎬 **Video Upload & Streaming**: Upload, process, and stream vertical videos seamlessly
- � **User Profiles**: Create profiles to showcase your vertical video content
- 💾 **MongoDB Database**: Robust data storage with Mongoose ODM
- 🚀 **Next.js 15**: Latest React framework with App Router
- 🎨 **Tailwind CSS**: Modern, responsive UI design optimized for vertical content
- ⚡ **Turbopack**: Lightning-fast development builds
- 🔍 **TypeScript**: Type-safe development experience
- 📝 **ESLint**: Code quality and consistency
- 🪝 **Husky**: Pre-commit hooks for code quality

## 🛠️ Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS 4 (optimized for vertical video layouts)
- **Database**: MongoDB with Mongoose
- **Video Format**: Exclusively 9:16 aspect ratio vertical videos
- **Package Manager**: pnpm
- **Code Quality**: ESLint, Husky
- **Development**: Turbopack for fast builds

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- pnpm (recommended) or npm
- MongoDB database (local or MongoDB Atlas)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/bappirahman/reelo.git
   cd reelo
   ```

2. **Install dependencies**

   ```bash
   pnpm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory:

   ```env
   MONGO_URI=your_mongodb_connection_string
   ```

4. **Run the development server**

   ```bash
   pnpm dev
   ```

5. **Open your browser**

   Navigate to [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

- `pnpm dev` - Start development server with Turbopack
- `pnpm build` - Build the application for production
- `pnpm start` - Start the production server
- `pnpm lint` - Run ESLint for code quality checks
- `pnpm build:check` - Type-check without generating files

## 📁 Project Structure

```
reelo/
├── app/                 # Next.js App Router
│   ├── globals.css     # Global styles
│   ├── layout.tsx      # Root layout
│   └── page.tsx        # Home page
├── lib/                # Utility functions
│   └── db.ts          # Database connection
├── public/            # Static assets
├── types.d.ts         # Global type definitions
├── package.json       # Dependencies and scripts
└── README.md          # Project documentation
```

## 🔧 Configuration

### Database Connection

The application uses a singleton pattern for MongoDB connections to prevent connection issues during development:

```typescript
// lib/db.ts
export async function connectToDatabase() {
  // Cached connection logic for optimal performance
}
```

### TypeScript Configuration

Global types are defined in `types.d.ts` for the mongoose connection caching pattern.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License.

## 👤 Author

**Bappi Rahman**

- GitHub: [@bappirahman](https://github.com/bappirahman)

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- MongoDB team for the excellent database solution
- Vercel for hosting and deployment platform
- The open-source community for continuous inspiration
