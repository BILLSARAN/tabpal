# 🎸 TabPal

> Guitar chord & tab app with AI-powered recommendations

## What is TabPal?

TabPal is a web application for guitarists that provides:

- 🎵 **Song Database** — Chords & tabs for popular songs (English + Greek)
- 🎸 **Interactive Chord Diagrams** — SVG fretboard visuals with finger positions
- 🔄 **Transpose & Capo** — Change keys instantly, get capo suggestions
- 🤖 **AI Assistant** — Find similar songs, understand music theory
- 🎧 **Spotify Integration** — Auto-enrichment with key, tempo, mood data
- 📥 **Download** — Export to PDF & ChordPro format
- 🌐 **Bilingual** — English & Greek interface

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React + TypeScript + Tailwind CSS |
| Backend | Node.js + Express + TypeScript |
| Database | PostgreSQL + Prisma ORM |
| AI | Gemini API |
| External | Spotify Web API |

## Project Structure

```
tabpal/
├── frontend/          # React + TypeScript app
├── backend/           # Express API server
├── shared/            # Shared types & music utilities
├── database/          # Prisma schema, migrations, seed data
├── docs/              # Documentation
└── .github/           # CI/CD workflows
```

## Getting Started

> 🚧 Under construction — setup instructions coming soon!

### Prerequisites

- Node.js 18+
- pnpm
- PostgreSQL 15+
- Spotify Developer account (for enrichment features)
- Gemini API key (for AI features)

### Installation

```bash
# Clone the repo
git clone https://github.com/BILLSARAN/tabpal.git
cd tabpal

# Install dependencies
pnpm install

# Setup environment variables
cp .env.example .env

# Start development
pnpm dev
```

## Contributing

Contributions are welcome! Please read our contributing guidelines (coming soon).

## License

[MIT](LICENSE)
