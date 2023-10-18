# tpdevops
## les commandes utilisé

   29  200~ssh-keygen -t rsa -b 4096 -C rania.bensaoud@polytechnicien.tn
   30  ssh-keygen -t rsa -b 4096 -C rania.bensaoud@polytechnicien.tn
   31  cat ~/.ssh/id_rsa.pub
   32  git config --global user.name "bensaoudrania"
   33  git config --global rania.bensaoud@polytechnicien.tn
   34  ssh -T git@github.com
   35  git clone git@github.com:bensaoudrania/tpdevops.git
   36  cd tpdevops
   37  touch index.html
   38  echo "Contenu de votre fichier" > index.html
   39  git add index.html
   40  git add index.html
   41  git commit -m "Premier commit : ajout de index.html"
   42  git log
   43  git diff commit_id_1 commit_id_2
   44  git branch ma-fonctionnalite
   45  git checkout ma-fonctionnalite
   46  git add .
   47  git commit -m "Modification de ma-fonctionnalite"
   48  git add .
   49  git add .
   50  git commit -m "Modification de ma-fonctionnalite"
   51  git push origin ma-fonctionnalite
   52  git checkout ma-fonctionnalite
   53  git commit -am "Modification dans ma-fonctionnalite"
   54  git checkout master
   55  git commit -am "Modification dans master"
   56  git merge ma-fonctionnalite
   57  git add .
   58  git commit -m "Résolution du conflit"
   59  git flow init
   60  git flow init
   61*
   62  git flow init
   63  git branch
   64  git flow init
   65  git branch next-release
   66  git flow init
   67  git flow feature start ma-fonctionnalite
   68  git flow release start ma-version
   69  git flow feature finish ma-fonctionnalite
   70  git flow hotfix start mon-correctif
