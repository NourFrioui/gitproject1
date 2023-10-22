# gitproject1
Partie 1 : Prépara on de l'environnement Git
cd OpenSSH
C:\Windows\System32\OpenSSH\ssh-keygen -t rsa -b 4096 -C "nourelhouda.frioui@polytechnicien.tn"
cat ~/.ssh/id_rsa.pubcat
git config --global user.name "NourFrioui"
git config --global user.email nourelhouda.frioui@polytechnicien.tn
./ssh -T git@github.com (Hi NourFrioui/gitproject1! You've successfully authenticated)
Partie 2: Créa on d'un nouveau projet
git clone git@github.com:NourFrioui/gitproject1.git
cd gitproject1
code .
Partie 3 : Concepts de base de Git
touch index.html
echo "Contenu de votre fichier" > index.html
git add index.html
git commit -m "Premier commit : ajout de index.html"
git log
git diff commit_id_1 commit_id_2
Partie 4 : Collaborer sur Git
git branch ma-fonctionnalite
git checkout ma-fonctionnalite
git add .
git commit -m "Modification de ma-fonctionnalite"
git push origin ma-fonctionnalite
Partie 5 : Utilisation de Gitflow
git flow init
git flow feature start ma-fonctionnalite
git flow feature finish ma-fonctionnalite
git flow hotfix start mon-correctif


