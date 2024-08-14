# serveur-test
1. Mise a jout par fichier src
  Commande iristerm /console=cn_iptcp:127.0.0.1[23] C:\temp\test.scr
2. installation de git
   - git config --global user.name "Ton Nom"
   - git config --global user.email "ton.email@example.com"
4. Creation d'un runner
   - https://github.com/mondialtissus/serveur-test/settings/actions/runners/new
   - ajouter un dossier action-runner a C:\
   - lancer le depuis c:\action-runner la commande ./run.cmd
5. ATTENTION ne pas ajouter de dossier git!!
   ```markdown
   git submodule deinit -f -- DEV-USER
   git rm -f DEV-USER
   rm -rf .git/modules/DEV-USER
   ```