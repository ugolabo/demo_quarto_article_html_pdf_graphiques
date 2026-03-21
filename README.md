# Démo Quarto

Article en format HTML axé sur les tableaux et les graphiques avec la langage R. Bouton droit vers: <a href="https://ugolabo.github.io/demo_quarto_article_html_pdf_graphiques/" target="_blank">site</a>.  
C'est le fichier 'index.html' ; avec sa version PDF : 'graphiques.pdf'.  
Il y a [deux façons de publier](#publier) un document Quarto sur GitHub. 

<img src="demo_article_quarto_html_pdf_graphiques.jpg" alt="" width="500px" >

Résultats de courses de pigeons.  
Production d'argent par les Espagnols en Amérique du Sud à l'époque coloniale (1720 - 1800).

## Publier

Ce repo utilise l'**Option 2**. Le build et le déploiement apparaissent dans l'onglet Actions, plus haut.

| Caractéristique      | Option 1 (Workflow complet)                                                                      | Option 2 (HTML statique)                                                                    |
|----------------------|--------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| **Fichiers sur GitHub**  | data/ + img/ + renv/ + .github/workflow/publish.yml + .qmd + _quarto.yml + renv.lock + .Rprofile | index.html                                                                                  |
| **Temps de déploiement** | long (en plus des changements dans Settings > Actions)                                           | rapide                                                                                      |
| **Mise à jour**          | Automatique au commit (git push, Add file sur GitHub ou édition sur GitHub avec Codespaces)      | Compiler localement, envoyer index.html sur GitHub (git push, Add file sur GitHub)   |
| **Confidentialité**      | Le code et les données sont sur GitHub ; le projet est reproduisible                             | Seul le résultat final est en ligne ; le projet source reste secret                         |
| **Calculs lourds**       | Limité par les serveurs GitHub                                                                   | Illimité (fait localement)                                                                  |
| **Avantages**            | Automatisation du workflow, édition en ligne                                                     | Confidentialité des données, partage de résultats simple                                    |
| **Page web**             | Settings > Pages, main branch                                                                    | Settings > Pages, gh-pages branch                                                           |
