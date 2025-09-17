
# App: Explorer BDD Antoine (Hors-Site)

Cette application Streamlit vous permet de :
- Charger le fichier **HSC_Matrice prix Pilotes_2025.xlsx**
- Sélectionner d'abord l'**année**, puis le **projet**
- Voir instantanément les **chiffres clés** (SHAB, Sacc, prix hors VRD, etc.)
- Utiliser des **filtres avancés** (typologie, système, industriel) et exporter les résultats.

## Lancer l'application
1. Installez les dépendances (idéalement dans un virtualenv) :
   ```bash
   pip install -r requirements.txt
   ```

2. Lancez Streamlit :
   ```bash
   streamlit run app.py
   ```

3. Dans l'UI, importez votre fichier **HSC_Matrice prix Pilotes_2025.xlsx** (feuille "BDD Antoine").

> Remarque : l'app nettoie automatiquement les colonnes (espaces, unités) et harmonise les valeurs numériques.
