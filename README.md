# Favorite Freeze

A glacier arcade for the Sui and Lofi community. Slide the yeti, catch the
favorite things, dodge the frost.

## Develop

    npm install
    npm run dev        # http://localhost:8080

## Build

    npm run build      # runs database migrations when DATABASE_URL is set
    npm run typecheck

## Database

Leaderboard and community favorites live in Postgres. Set `DATABASE_URL` to a
Supabase (or any Postgres) connection string. Without it the app falls back to
an in-process PGLite database for local development.

Schema: `migrations/0002_game.sql`.
