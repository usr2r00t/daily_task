# README

## 1. Recoder "mkdir" (en Ruby)
- saisie d'un mot au lancement            => un dossier va être créer
- saisie de plusieurs mots                => uniquement le 1er dossier demandé sera créer
- pas de saisie de suite de caractères    => message d'erreurs


## 2. GoogleSearcher
Ouverture d'un onglet Google Chrome et lance une recherche automatique
- Saisie d'un ARGV à l'exécution du programme
- Si rien n'ai saisi, le programme va lui dire comment ça marche
- L'ARGV correspond à ce que l'utilisateur veut rechercher sur Google
- Récupération de l'ARGV et construire une URL à partir de l'ARGV
- Ouverture d'un nouvel onglet à partir de cette recherche

### Etapes
- La recherche "How to center a div" sera : https://www.google.com/search?q=how+to+center+a+div
- Utiliser la gem Launchy
- Créer un alias permanent
  - alias search="ruby /home/ton/chemin/vers/google_searcher.rb"
  - Saisir : $ search how to center a div


## 3. Création d'un dossier ruby
- Création d'une commande `mkdiruby`
- Création d'un dossier récupérant le nom de l'ARGV
  - Si aucun ARGV ou un ARGV de plusieurs mots
    - => dire à l'utilisateur comment s'en servir et s'arrêter
  - dossiers __lib__
  - Création du fichier __Gemfile__ (gems de THP)
  - `git init`
  - Création du fichier __.env__, puis on le met dans le fichier __.gitignore__
  - Création du dossier __lib__
  - `rspec --init`
  - Création d'un __README.md__ (qui va dire que c'est un programme Ruby)
  - Création d'un __alias__ `mkdiruby` permanent
