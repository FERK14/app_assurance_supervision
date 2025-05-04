# Supervision IA - Assurances

Cette application Streamlit permet d'analyser les compagnies d'assurance à l'aide d'un modèle de machine learning et de générer des commentaires automatisés à l'aide de GPT-3.5.

## Fichiers
- `app_assurance_supervision.py` : script principal Streamlit
- `donnees_assurances_simulees.xlsx` : données simulées pour 30 compagnies d'assurance
- `requirements.txt` : dépendances Python
- `README.md` : ce fichier

## Instructions
1. Installez les dépendances : `pip install -r requirements.txt`
2. Exécutez l'app : `streamlit run app_assurance_supervision.py`
3. Ajoutez votre clé OpenAI dans `.streamlit/secrets.toml` ou dans Streamlit Cloud > Edit Secrets :

```
openai_api_key = "votre_clé_ici"
```
