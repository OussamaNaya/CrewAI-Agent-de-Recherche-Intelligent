# 🔍 Agent de Recherche Intelligent

Un agent de recherche automatisé utilisant CrewAI qui peut effectuer des recherches approfondies sur n'importe quel sujet en utilisant soit GPT-4o-mini soit Llama3.

## 🚀 Fonctionnalités

- **Multi-modèles** : Support pour GPT-4o-mini (OpenAI) et Llama3 (Ollama)
- **Recherche web** : Intégration avec l'API Serper pour des recherches en temps réel
- **Agent spécialisé** : Agent de recherche expert avec des capacités d'analyse avancées
- **Interface interactive** : Interface en ligne de commande simple et intuitive

## 📋 Prérequis

- Python 3.8+
- Clé API Serper (pour les recherches web)
- Clé API OpenAI (pour GPT-4o-mini)
- Ollama installé localement (pour Llama3)

## 🛠️ Installation

1. Clonez le repository :
```bash
git clone https://github.com/votre-username/research-agent.git
cd research-agent
```

2. Installez les dépendances :
```bash
pip install crewai crewai-tools python-dotenv langchain-openai langchain-community
```

3. Configurez vos variables d'environnement dans un fichier `.env` :
```env
SERPER_API_KEY=votre_clé_serper_ici
OPENAI_API_KEY=votre_clé_openai_ici
```

## 🎯 Utilisation

Lancez l'application :
```bash
python main.py
```

L'application vous demandera :
1. Si vous voulez utiliser GPT (yes/no)
2. Le sujet de recherche que vous souhaitez explorer

Exemple d'utilisation :
```
Welcome to the Research Agent!
Do you want to use GPT? (yes/no): yes
Enter the research topic: Intelligence artificielle en 2024
```

## 🏗️ Architecture

- **Agent de Recherche** : Spécialiste en recherche avec accès aux outils web
- **Tâche de Recherche** : Génère des résumés complets et détaillés
- **Crew** : Orchestre l'exécution des tâches par l'agent
- **Outils** : SerperDevTool pour les recherches web en temps réel

## 🔧 Configuration

### Modèles supportés :
- **GPT-4o-mini** : Modèle OpenAI rapide et efficace
- **Llama3** : Modèle local via Ollama

### Variables d'environnement :
- `SERPER_API_KEY` : Clé API pour les recherches web
- `OPENAI_API_KEY` : Clé API OpenAI (si utilisation de GPT)

## 📊 Sortie

L'agent fournit :
- Résumé détaillé du sujet recherché
- Points clés et tendances
- Insights et analyses approfondies
- Sources d'information synthétisées

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- Ouvrir des issues pour signaler des bugs
- Proposer des améliorations
- Soumettre des pull requests

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 🔗 Liens utiles

- [CrewAI Documentation](https://docs.crewai.com/)
- [Serper API](https://serper.dev/)
- [OpenAI API](https://platform.openai.com/)
- [Ollama](https://ollama.ai/)

---

*Développé par Oussama Naya avec ❤️ en utilisant CrewAI*
