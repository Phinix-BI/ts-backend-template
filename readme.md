# 🚀 TypeScript Backend Template

A clean and scalable starter template for building Node.js backend applications using TypeScript. This setup includes Express, environment management, auto-reload during development, and a well-organized folder structure.

---

## 📁 Project Structure

typescript-backend-template/
├── src/ # TypeScript source files
│ └── index.ts # Entry point
├── dist/ # Compiled JavaScript (auto-generated)
├── .env # Environment variables (should be kept secret)
├── .env.example # Example environment file
├── .gitignore
├── nodemon.json
├── package.json
├── tsconfig.json
└── README.md


---

## 🧰 Tech Stack

- **Node.js** with **Express**
- **TypeScript**
- **Nodemon** + **tsc --watch** for live development
- **dotenv** for environment configuration
- **Pre-configured scripts** for build, dev, and production

---

## 🛠️ Installation
🔨 Scripts
Command	Description
npm run build	Compiles TypeScript into dist/ folder
npm start	Runs the compiled app from dist/
npm run watch	Watch and compile TypeScript on changes
npm run dev	Live reload with tsc + nodemon

🧠 npm run dev = Runs tsc --watch and nodemon dist/index.js concurrently

```bash
git clone https://github.com/Phinix-BI/ts-backend-template.git
cd typescript-backend-template
npm install
```

⚙️ Environment Setup

Create a .env file in the root directory and define your environment variables:

``` bash
PORT=3000
```

Or copy the example:

``` bash
cp .env.example .env
```

🔨 Scripts
Command	Description

```bash
npm run build	Compiles TypeScript into dist/ folder
npm start	Runs the compiled app from dist/
npm run watch	Watch and compile TypeScript on changes
npm run dev	Live reload with tsc + nodemon
```
``` bash
🧠 npm run dev = Runs tsc --watch and nodemon dist/index.js concurrently
```

