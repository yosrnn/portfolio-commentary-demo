# portfolio-commentary-demo

## Objectif

Explorer l'automatisation de la génération de commentaires de performance de portfolio en utilisant des Large Language Models (LLMs) et le Retrieval-Augmented Generation (RAG).

Le notebook démontre :

1. Structuration de données financières
   - Données de performance de portfolio (returns, benchmark, allocation)
   - Contexte macroéconomique

2. RAG (Retrieval-Augmented Generation)
   - Récupération de contexte pertinent
   - Enrichissement du prompt avec des données factuelles

3. Génération avec LLM
   - Utilisation de l'API OpenAI (GPT-4)
   - Prompt engineering pour favoriser la factualité

4. Validations basiques
   - Vérification de cohérence des chiffres
   - Détection de valeurs aberrantes

##  Setup
```bash
pip install openai pandas numpy python-dotenv
```

Apprentissage

Ce projet a été développé en quelques jours comme exercice d'apprentissage. J'ai utilisé la documentation OpenAI, des tutoriels sur le RAG, et l'assistance d'outils IA pour comprendre certains concepts.

## Limitations

Ceci est un **demo d'apprentissage**, pas une solution production-ready.

Manque pour la production :
- Validation exhaustive des outputs
- Tests unitaires complets
- Gestion d'erreurs robuste
- Vector database pour du RAG scalable
- Workflow d'approbation humaine

## Concepts compris

Ce projet m'a permis de comprendre :
- Pourquoi le RAG est crucial en finance pour éviter les hallucinations
- L'importance du prompt engineering
- Les enjeux de validation en finance
- La différence entre un POC et la production

---
