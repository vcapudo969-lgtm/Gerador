# Task: Gerador de Keys Implementation

## Plan
- [x] Database Setup
  - [x] Initialize Supabase `supabase_init`
  - [x] Create tables: `profiles`, `login_versions`, `validity_options`, `generated_keys`, `transactions`, `complaints`, `api_keys`
  - [x] Seed data for `login_versions` and `validity_options`
- [x] Auth & Layout
  - [x] Configure `AuthContext.tsx` and `RouteGuard.tsx`
  - [x] Update `index.css` and `tailwind.config.js` for the dark theme
  - [x] Create `Sidebar` and `DashboardLayout` components
- [x] Pages Implementation
  - [x] Login Page
  - [x] Dashboard Page (Principal)
  - [x] Generate Keys Page (Keys)
  - [x] Manage Keys Page (Keys)
  - [x] API Keys & Docs Page (API)
  - [x] Wallet & Transfer Page (Carteira)
  - [x] Profile, Affiliate, Complaints Pages (Perfil)
- [x] Bot API Integration
  - [x] Create `bot-api` Edge Function
  - [x] Create `generate-bot-key-external` Edge Function (Simplified for bots)
  - [x] Add API Key management in Profile
  - [x] Create Admin API management page (`/admin/apis`)
  - [x] Update Documentation with Bot examples and command mapping
- [x] Final Polish
  - [x] Linting and bug fixes
  - [x] Image replacement with `image_search`

## Notes
- Theme: Dark background, purple/green accents.
- Language: Portuguese UI, English code comments.
- Must use Supabase for everything.
- Bot API deployed and functional at /functions/v1/bot-api
