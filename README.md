# Assistant RAG

Assistant RAG développé avec LangChain, ChromaDB, Ollama et Gradio.

## Fonctionnalités

- Indexation des documents TP1 à TP4.
- Recherche sémantique avec ChromaDB.
- Génération des réponses avec Ollama.
- Interface utilisateur réalisée avec Gradio.
- Affichage des sources utilisées pour chaque réponse.

## Technologies

- Python 3.12
- LangChain
- ChromaDB
- Ollama
- Gradio

## Structure du projet

```
documents/        # Documents PDF indexés
db_tp/            # Base vectorielle ChromaDB
prj_rag.ipynb     # Notebook principal
pyproject.toml    # Configuration du projet
uv.lock           # Verrouillage des dépendances
```

## Lancement

1. Installer les dépendances.
2. Démarrer Ollama.
3. Exécuter `prj_rag.ipynb`.
4. Ouvrir l'interface Gradio et poser des questions sur les documents.

## Auteur

Charles Boumba

Projet réalisé dans le cadre du TP LangChain / RAG.
