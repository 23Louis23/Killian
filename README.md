# Killian Training App

App de suivi pour le cycle **Renfo** de Killian (4 semaines, 3 séances par semaine : Push / Pull / Legs). Elle utilise la **même base de données Supabase** que les apps de Jox, Loan, Fifi, Manon, Lucie & Yo et Suzy — pas besoin de recréer un compte ou un projet.

## Particularité par rapport aux autres apps

Thème aux couleurs de l'OM (bleu ciel sur fond marine) plutôt que le thème habituel — un petit clin d'œil pour Killian.

## 1. Base de données

✅ Déjà faite — cette app utilise le même projet Supabase que les autres, avec la colonne `athlete` ("Killian") qui sépare ses données de celles des autres athlètes.

## 2. Configurer l'appli

✅ Déjà fait — `index.html` contient l'URL et la clé Supabase (les mêmes que pour les autres), et un code d'accès (`6710` par défaut, modifiable en cherchant `APP_PIN` dans le fichier).

## 3. Déployer sur Vercel (gratuit) — sans rien installer

Même procédure que pour les autres athlètes :

1. Crée un nouveau repo GitHub (ex: `killian-training-app`).
2. Upload les 2 fichiers (`index.html`, `README.md`) via "uploading an existing file" sur la page du repo.
3. Va sur [vercel.com/new](https://vercel.com/new), importe ce nouveau repo, déploie avec les réglages par défaut.
4. Récupère l'URL propre du projet (ex: `https://killian-training-app.vercel.app`, pas l'URL avec un hash aléatoire) dans la section "Domains" du projet.

## 4. Utilisation

Envoie l'URL + le code `6710` à Killian. Chaque séance permet de renseigner les charges (2 cases pour le superset de Push, 3 cases pour le drop set de Pull), le Hooper du jour (sommeil/fatigue/stress/courbatures), une note sur les abdos et une note générale de séance. L'onglet Historique affiche l'évolution du score Hooper, et le Tableau de bord l'évolution des charges par exercice.
