# Task Manager

Aplikasi Task Manager yang dibangun dengan Next.js, TypeScript, dan Tailwind CSS. Aplikasi ini memungkinkan pengguna untuk mengelola task dengan fitur CRUD lengkap dan penyimpanan lokal menggunakan localStorage.

## 🚀 Fitur

- ✅ **CRUD Operations**: Create, Read, Update, Delete tasks
- 💾 **Local Storage**: Data tersimpan permanen di browser
- 📱 **Responsive Design**: Bekerja di desktop dan mobile
- 🎨 **Modern UI**: Menggunakan shadcn/ui dan Tailwind CSS
- 🔍 **Form Validation**: Validasi input dengan error handling
- 📊 **Task Statistics**: Dashboard dengan statistik task
- 🏷️ **Priority & Status**: Sistem prioritas dan status dengan color coding
- ⚡ **Real-time Updates**: Update otomatis tanpa refresh
- 🔄 **CI/CD Pipeline**: Automated testing dan deployment

## 🛠️ Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Icons**: Lucide React
- **Storage**: localStorage
- **CI/CD**: GitHub Actions

## 📦 Installation

### Prerequisites
- Node.js 18.x atau lebih tinggi
- npm atau yarn

### Setup Project

1. **Clone repository**
\`\`\`bash
git clone https://github.com/username/task-manager.git
cd task-manager
\`\`\`

2. **Install dependencies**
\`\`\`bash
npm install
\`\`\`

3. **Setup shadcn/ui**
\`\`\`bash
npx shadcn@latest init
npx shadcn@latest add card button input label textarea select badge
\`\`\`

4. **Run development server**
\`\`\`bash
npm run dev
\`\`\`

5. **Open browser**
\`\`\`
http://localhost:3000
\`\`\`

## 🏗️ Project Structure

\`\`\`
task-manager/
├── .github/
│   └── workflows/
│       └── ci.yml
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── ui/
│   ├── task-form.tsx
│   └── task-form-demo.tsx
├── lib/
│   └── utils.ts
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── README.md
\`\`\`

## 💻 Usage

### Menambah Task Baru
1. Klik tombol "Add New Task"
2. Isi form dengan informasi task
3. Pilih priority dan status
4. Klik "Add Task"

### Mengedit Task
1. Klik icon edit (✏️) pada task card
2. Ubah informasi yang diperlukan
3. Klik "Save Changes"

### Menghapus Task
1. Klik icon delete (🗑️) pada task card
2. Konfirmasi penghapusan

### Fitur Storage
- Data otomatis tersimpan di localStorage
- Klik "Clear All" untuk menghapus semua data
- Klik "Reset Default" untuk kembali ke data default

## 🚀 Deployment

### Manual Deployment

1. **Build project**
\`\`\`bash
npm run build
\`\`\`

2. **Start production server**
\`\`\`bash
npm start
\`\`\`

### Automatic Deployment (CI/CD)

Project ini menggunakan GitHub Actions untuk CI/CD:

1. **Push ke branch main** akan trigger deployment otomatis
2. **Pull request** akan menjalankan tests dan build
3. **Deploy ke Vercel** secara otomatis setelah tests berhasil

### Environment Variables (untuk deployment)

Buat secrets di GitHub repository:

\`\`\`env
VERCEL_TOKEN=your_vercel_token
VERCEL_ORG_ID=your_org_id
VERCEL_PROJECT_ID=your_project_id
\`\`\`

## 🧪 Testing

\`\`\`bash
# Run tests
npm run test

# Run build
npm run build

# Run linting
npm run lint
\`\`\`

## 🤝 Contributing

1. Fork repository
2. Create feature branch (\`git checkout -b feature/amazing-feature\`)
3. Commit changes (\`git commit -m 'Add amazing feature'\`)
4. Push to branch (\`git push origin feature/amazing-feature\`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - React framework
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [shadcn/ui](https://ui.shadcn.com/) - UI components
- [Lucide React](https://lucide.dev/) - Icons
- [Vercel](https://vercel.com/) - Deployment platform

---

**Happy Coding! 🎉**
