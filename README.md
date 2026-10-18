# 🧠 Claude Skills

Bienvenue dans **Claude Skills**, une collection de "Skills" (compétences), de prompts systèmes avancés et de workflows conçus pour transformer Claude (ou d'autres LLMs) en assistants ultra-spécialisés.

Chaque "skill" est pensé pour accomplir une tâche précise de bout en bout, en adoptant un rôle d'expert et en suivant une méthodologie rigoureuse.

## 📂 Organisation du dépôt

Pour que le dépôt reste clair et facile à naviguer, chaque compétence possède son propre dossier dans le répertoire `/skills`. Vous y trouverez une documentation dédiée et le prompt prêt à l'emploi.

```text
claude-skills/
├── README.md                  # Ce fichier (présentation globale)
└── skills/
    ├── droit-a-l-oubli/       # Dossier du skill
    │   └── README.md          # Documentation et prompt système du skill
    └── ...                    # Vos futurs skills
```

## 📋 Catalogue des Skills

Voici la liste des compétences actuellement disponibles dans ce dépôt :

| 🛡️ Nom du Skill | 📝 Description | 🔗 Lien |
| :--- | :--- | :--- |
| **Droit à l'Oubli (RGPD)** | Expert juridique accompagnant l'utilisateur de A à Z pour faire effacer ses données personnelles d'internet (déréférencement, source, CNIL). | [Voir le skill](./skills/droit-a-l-oubli/) |
| *(D'autres à venir)* | *Ajoutez ici la description de vos futurs skills...* | |

## 🚀 Comment utiliser ces skills ?

L'utilisation de ces compétences est très simple et ne nécessite aucune compétence en code :

1. Parcourez le catalogue ci-dessus et cliquez sur le lien du skill qui vous intéresse.
2. Dans la documentation du skill, repérez la section **"Le Prompt Système"**.
3. Copiez l'intégralité du texte de cette section.
4. Collez ce texte :
   - Dans les **Instructions personnalisées** (Project Instructions / Custom Instructions) de l'interface de Claude.
   - OU dans le **System Prompt** si vous utilisez l'API (Anthropic, OpenAI, etc.).
5. Démarrez une nouvelle conversation avec votre assistant spécialisé !

## 🤝 Contribution

Vous avez une idée pour améliorer un prompt ? Vous souhaitez partager un nouveau skill ? 
Les contributions sont les bienvenues ! N'hésitez pas à proposer une *Pull Request*.

## ⚠️ Avertissement

Ces prompts sont des outils pour guider l'Intelligence Artificielle. Bien qu'ils soient conçus pour être le plus précis possible, il est indispensable de toujours vérifier et valider les informations générées, tout particulièrement lorsqu'il s'agit de démarches juridiques, administratives ou médicales.