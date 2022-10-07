Prerequis: Avoir Docker Descktop installé

Dans une console (terminal)
Pour Lancer: docker compose up

Pour arreter : Ctrl+c  /  docker compose down

Etape importante: 

Récuperer votre clef d'authentification Gravity pour les sessions de tests depuis Gravity et remplacer la clef existante dans le fichier situé a cet endroit:
- cypress_rwa/src/index.tsx


`GravityCollector.init({
  authKey: "05f42d54-dd12-400d-ad24-.....",
});`