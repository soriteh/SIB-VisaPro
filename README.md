# SIB-VisaPro

Application web responsive de gestion des demandes de visa pour SIB Services. Frontend React + Vite, devise FG, thème clair/sombre, tableau de bord, demandes, clients, paiements et export CSV.

## Démarrer
- Node.js 20+ et npm
- `npm install`
- Copier `.env.example` vers `.env.local` et renseigner les variables Supabase si nécessaire
- `npm run dev`

## Déploiement Vercel
Importer ce dépôt dans Vercel. Build: `npm run build`; Output: `dist`. Configurer `VITE_SUPABASE_URL` et `VITE_SUPABASE_ANON_KEY` si Supabase est utilisé.

## Important sécurité
Les données d'exemple sont fictives. Le schéma SQL fourni est une base initiale et doit être audité; ne pas y stocker de passeports réels avant d'avoir vérifié les règles RLS, les rôles et le stockage privé. Ne jamais publier la clé Supabase service_role.
