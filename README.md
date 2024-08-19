# SERVEUR-TEST
## Creation d'un git action
## fichier pour run
## Installer du service sur le poste
## Creation du service gitaction
  //NE FONCTIONNE PAS

  
  En mode admin lancer cmd.exe
  sc create "GitHubActionRunner" binPath= "C:\actions-runner\run.cmd" start= auto
  sc start "GitHubActionRunner"

