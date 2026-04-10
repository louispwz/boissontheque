# boissontheque
An application allowing the tracking and grading of drinks

## 🎙️ Mode Podcast

Activez le **Mode Podcast** dans les paramètres des comptes pour accéder à l'onglet Podcast.

### Fonctionnalités :
- **Créer des questions** : Ajoutez des questions pour animer vos soirées au bar
- **Tirage au sort** : Sélectionnez une question aléatoirement
- **Voir toutes les questions** : Gérez votre liste de questions

## 🚀 Déploiement sur Vercel

1. **Créez un compte Vercel** : https://vercel.com
2. **Importez votre dépôt GitHub** dans Vercel
3. **Vercel détectera automatiquement** la configuration et déploiera

**Votre clé Supabase est maintenant cachée** dans la fonction serverless `/api/supabase.js`

## 🔧 Configuration

- Modifiez les clés Supabase dans `/api/supabase.js` si nécessaire
- Les appels à Supabase passent maintenant par votre backend Vercel
