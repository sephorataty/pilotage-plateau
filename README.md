# Pilotage plateau

Tableau de bord de production des conseillers (segments, semaines, classement, évolution individuelle, rapport Excel/PDF).

- **Tableau de bord** : `index.html` — accès protégé par code ; les données (`data.enc.json`) sont chiffrées (AES-256-GCM, clé dérivée du code par PBKDF2).
- **Mise à jour mensuelle** : ouvrir `admin.html`, déposer l'export Excel, saisir le code, générer `data.enc.json`, puis le téléverser ici en remplacement de l'ancien (Add file → Upload files → Commit changes).

Aucune donnée en clair n'est stockée dans ce dépôt.
