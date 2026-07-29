# Portfolio — Rayane Cathelin

Site portfolio personnel présentant mon parcours (BUT Informatique, parcours DACS) ainsi que mes projets : stage en développement web, infrastructures systèmes/réseau, automatisation IaC et applications diverses.

Site statique en HTML/CSS/JS vanilla, sans build ni dépendances.

## Structure du dépôt

```
.
├── index.html          # Page d'accueil
├── pages/               # Pages détaillées de chaque projet
├── assets/
│   ├── css/             # Feuille de style
│   ├── img/              # Images et captures d'écran
│   └── docs/             # CV et documents téléchargeables (PDF)
└── README.md
```

## Aperçu des projets présentés

- **Stage Izydesk** — développement e-commerce en React/Next.js
- **Client Borg Backup** — application graphique de sauvegarde
- **Nuit de l'Info 2024** — jeu web, victoire au défi national
- **Automatisation IaC** — déploiement Docker avec Terraform/Ansible
- **Infrastructure SSO** — Authentik, OpenLDAP, Traefik, Cloudflare Tunnel
- **Vote électronique** — chiffrement ElGamal, client-serveur JavaFX
- **Site e-commerce PHP** — architecture MVC

## Lancer le site en local

Aucune dépendance requise, il suffit d'ouvrir `index.html` dans un navigateur, ou de servir le dossier avec un serveur statique, par exemple :

```bash
python3 -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.
