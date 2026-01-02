# ♟️ Chess Quest - Project Structure

## 🏗️ Directory Layout

```
chess-quest/
├── 📁 backend/
│   ├── 📁 src/
│   │   ├── 📁 chess/
│   │   │   ├── game.ts
│   │   │   ├── engine.ts
│   │   │   └── validator.ts
│   │   ├── 📁 auth/
│   │   │   ├── auth.service.ts
│   │   │   └── middleware.ts
│   │   ├── 📁 rewards/
│   │   │   ├── achievement.service.ts
│   │   │   └── quest.service.ts
│   │   ├── 📁 tournaments/
│   │   │   ├── bracket.ts
│   │   │   └── manager.ts
│   │   ├── 📁 sockets/
│   │   │   ├── game.socket.ts
│   │   │   └── chat.socket.ts
│   │   └── server.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── Dockerfile
├── 📁 frontend/
│   ├── 📁 src/
│   │   ├── 📁 components/
│   │   │   ├── ChessBoard.tsx
│   │   │   ├── RewardNotification.tsx
│   │   │   └── TournamentBracket.tsx
│   │   ├── 📁 pages/
│   │   │   ├── HomePage.tsx
│   │   │   ├── GamePage.tsx
│   │   │   └── ProfilePage.tsx
│   │   ├── 📁 services/
│   │   │   ├── api.ts
│   │   │   └── socket.ts
│   │   ├── 📁 stores/
│   │   │   └── gameStore.ts
│   │   ├── 📁 types/
│   │   │   └── chess.types.ts
│   │   ├── App.tsx
│   │   └── index.tsx
│   ├── package.json
│   ├── tailwind.config.js
│   └── tsconfig.json
├── 📁 mobile/
│   ├── 📁 src/
│   ├── App.js
│   └── package.json
├── 📁 docker/
│   ├── docker-compose.yml
│   └── nginx.conf
├── 📁 docs/
│   ├── API.md
│   └── SETUP.md
├── .gitignore
├── README.md
├── package.json
└── LICENSE
```

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/chess-quest.git
cd chess-quest

# Install dependencies
npm install

# Start development
npm run dev
```

## 📦 Workspace Setup
This project uses npm workspaces for monorepo management.
