## Groupe:
    * HAMDI Abdelaziz
    * BENJARRAD Saad
    * MIKHAEEL Pola Issa Helmy  
    * SCHLANGER Sarah



# Installation et exécution

### Prérequis
- Avoir Python installé.
- Avoir pip (le gestionnaire de paquets Python) installé.

### Étapes pour récupérer et exécuter le projet
1. Clonez le dépôt GitHub :
   ```bash
   git clone https://github.com/thehamdiaz/streamlitbot.git
   cd streamlitbot
   ```

2. Installez les dépendances nécessaires :
   ```bash
   pip install -r requirements.txt
   ```

3. Créez un nouveu dossier **.streamlit** dans le projet **streamlitbot**

4. Créez un nouveu fichier **secrets.toml** dans le dossier **.streamlit**

5. Copiez collez les lignes de code ci-dessous dans le fichier **secrets.toml**

```
# .streamlit/secrets.toml
OPENAI_API_KEY = "YOUR_API_KEY"
```
Mettez à jour la valeur de "YOUR_API_KEY" avec votre clé Openai et sauvegardez le fichier.


6. Exécutez l'application Streamlit :
   Pour lancer la première application :
   ```bash
   streamlit run chatbotgpt.py
   ```