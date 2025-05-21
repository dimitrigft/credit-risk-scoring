# Instructions pour exécuter notre projet

0. **Prérequis**
    Veuillez utiliser un IDE(VsCode,PyCharm etc) afin de pouvoir "lire" notre projet ensuite veuillez ouvrir le Folder credit-risk-scoring et lire la suite de ce readm

1. **Installer Pip** (si vous ne l'avez pas déjà) :
   - Ouvrez votre terminal associé à votre IDE
   - Tapez les commandes suivantes :
     python3 -m ensurepip --upgrade
    

2. **Installer Poetry** (si vous ne l'avez pas déjà) :
   - Toujours dans le même terminal,tapez la commande suivante :
     pip install poetry ou bien pip3 install poetry(si vous avez fait l'étape 1)
     

3. **Installer les packages référencés dans `pyproject.toml`** :
   - Toujours dans le même terminal, exécutez la commande suivante :
     poetry install
    
Il est possible qu'il y est un WARNING à la fin de cette commande, mais ce n'est pas important le projet pourra quand même être exécuter.  

Vous pouvez maintenant exécuter nos notebooks à condition de n'avoir aucune fenêtre de l'IDE sur lequel vous êtes actuellemment d'ouverte. Utilisez la commande **Run All** pour exécuter tout le code à la fois, en faisant cela votre interpréteur va vous demander de choisir un environnement:
    
    Sélectionnez Python Environnements
    Puis sélectionnez le kernel qui commence par projet_scoring...(Python 3.11.9)
    Si vous ne trouvez pas le Kernel en question veuillez fermez toutes vos fenêtres de l'IDE que vous utilisez et réessayer. Le Kernel devrait maintenant apparaître.

Notre projet va ensuite s'exécuter en allant jusqu'à la dernière cellule du notebook associé et vous pourrez exécuter les 3 notebooks que nous avons

PS: Vous pouvez aussi RUN cellule par cellule en sélectionnant la cellule souhaitée et en faisant SHIFT+Entrée, il est impératif d'exécuter les cellules dans le bon ordre, sinon certaines variables ne seront pas correctement créées et vous rencontrerez des erreurs.
