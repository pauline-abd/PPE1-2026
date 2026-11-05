# Journal de bord du projet encadré

## 30 septembre 2026

### Ce que j'ai fait

Suite du cours, séance sur git et son fonctionnement global, prise en main de différentes commandes, et découverte des pipelines.

#### Pendant le cours

**Introduction sur le fonctionnement de github**
- Apprentissage des différentes commandes pour mettre à jour ma copie locale du dépôt distant github pour ce cours (`git status`, `git fetch`, `git pull`).
- On apprend les différences entre le dépôt local et le dépôt distant, ainsi que le système de mise à jour qui n'est pas automatiquement synchronisé: on peut mettre les changements effectués en local sur le dépôt distant, mais ce n'est pas obligatoire. 
- On apprend les éléments auxquels faire attention: la suppression de fichier (sur le dépôt local avec `rm`, ou sur le dépôt distant avec `git rm`), la diffusion de données privées par erreur (supprimer tout le dépôt), et les message à mettre sur les commit et les tag.
- On apprend à quoi servent les tags.

**Début d'un exercice individuel**
- Exercice individuel pour apprendre à manipuler certaines commandes Unix, notamment pour se balader entre les différents dossiers sur notre ordinateur, et comment manipuler et trier les fichiers de ces différents dossiers.
- Commandes importantes utilisées dans cet exercice: `pwd`, `mkdir`, `cd`, `wget`, `unzip`, `mv`, `ls`, `history`.
- Différence entre la commande man, et l'option `--help`, `man` ouvre une page manuel dont on sort en appuyant sur `q`, tandis que `--help` rend en sortie une description plus brève de l'utilisation de la commande. Toutes les commandes ont un manuel, mais pas toutes une option `--help`.

**Cours sur les pipelines:**
- J'ai eu du mal à comprendre comment fonctionne les pipelines pendant le cours, la différence entre la sortie standard d'erreur (stderr) et et la sortie standard (stdout) notamment au début, ainsi que la manière dont fonctionne concrètement les pipelines avec les caractères "pipe".

#### Après le cours

**Exercices git et pipelines:**
Deuxième partie de l'exercice pipelines => réfléchir à ce que chaque commande fait, comprendre comment chacune peut être utilisée pour la tâche demandée.
Ça m'aide de l'écrire sur une feuille de papier (ce que j'ai en input initial, ce que je souhaite en sortie finale, les étapes intermédiaires pour y arriver), et de noter à côté de chaque action souhaitée la commande adéquate; je crée un schéma visuel sinon j'ai du mal à comprendre par où commencer.
Au début, difficulté à comprendre l'utilité de `tail`, puis en relisant les consignes, je comprends qu'après avoir classé les lieux, j'aurais sûrement plus de 15 lieux dans ma liste, il faudra donc couper et garder les 15 dernières lignes. Idem `uniq`, mais en regardant les options de la commande, je comprends son utilité.

### Solutions que je veux partager

*N/A*

### Questions à discuter

Dans l'exercice sur les commandes: les fichiers images ont plusieurs extensions différentes, parfois ayant le même nom mais avec une casse différente, comment inclure les deux? comment connaître toutes les extensions sans devoir les regarder en listant (`ls`) les fichiers du dossier?
