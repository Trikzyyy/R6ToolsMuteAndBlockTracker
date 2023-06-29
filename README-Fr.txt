Trikzy Block Bot V1 README.TXT

############################################
FR   -    Tous retour sont acceptés, positif comme négatif pour des amélioration, contactez sur mon twitter > @TrikzyR6 - Follow pour recevoir les nouvelles versions
############################################

Configurer Profiles.JSON (dans bloc-note si vous n'avez pas d'éditeur particulier) dans le dossier Profiles !!!NE PAS DEPLACER DE FICHIER
Modifier seulement les deuxieme parties des cases, par exemples "ton mail"  !!!NE PAS CHANGER LES NOMS DE VARIABLES "email","mdp","url2","lang"
Pour le lien du discord webhook > Créer un serveur discord (ou utiliser un déjà créer que vous possèdez>  Paramètre du serveur > Intégration > Webhooks > 
Nouveau webhook > Mettre le salon souhaités et copier l'URL du webhook, coller le dans "ton discord webhook"
Pour le bind_pseudo_tracker > mettre le bind que vous voulez pour la fonction de recherche par nom > lorsque vous cliquerez sur celui-ci une nouvelle page s'ouvre
Eviter les bind majuscule (mettre ";" et pas "." par exemple) et bind 1 seule touche. 
Choisissez un bind que vous appuyez jamais, car meme sur la page de r6 ca ouvrira la fonction (et sur toutes autres pages)
Si vous ne voulez pas ceci, simplement ne rien mettre > ca devrait ressembler a ceci "bind":""
Identique pour le bind_mute, celui ci permettant de mute/demute la page R6 lorsque vous appuyez sur le bouton (bien pour la phase de prep / renfo)
Ne pas rester appuyez sur les bind, ou cela ouvrira les pages infiniment, sécurité uniquement pour 1 sec de hold


############################################
NE PAS LANCER L'APP PLUS DE 5 FOIS EN 10 MIN, AU LANCEMENT ELLE SE CONNECTE AU COMPTE UBI, SI TROP DE CONNEXION D'UN COUP > BLOQUAGE TEMPORAIRE POSSIBLE (10min bloquer).
Lancer TrikzyBlockStatsTrackerV1.0.exe (app principale)
COMMENT CELA MARCHE
Lorsque une personne sera bloqué par votre compte ubisoft, le bot webhook va envoyer ses stats dans le salon choisi. 
Tous les stats sont en ranked, sauf si la personne n'a jamais jouer en ranked de la saison, ses stats de casu s'afficheront (kd, k/m) 
Pour toutes questions > mp twitter : @TrikzyR6
Si l'application ne répond plus, cela signifie qu'une erreur c'est produite, si vous trouvez la raison de l'erreur, contactez moi
Quand cela arrive, relancez juste l'app
Pour tous report de bug ou recommandation d'amélioration > mp twitter : @TrikzyR6

Si vous souhaitez mettre sur votre bureau l'app, créez un raccourci, ne déplacer rien

TrikzyPseudoTracker.exe :
App supplémetaire que j'ai ajouté pour la fonction de recherche par nom de l'application principale (TrikzyBlockStatsTracker).
Tu peux aussi l'utiliser sans l'app principale, si tu cherche simplement une personne.
Aucun interface fait dessus, vu que c'est supposé marcher avec l'app principal.
Si elle se ferme après la recherche, c'est que le compte n'existe pas et que mon cas d'erreur à un problème, si cela vous le fait, contactez moi avec le pseudo rechercher

autoexec :
Ce fichier va vous permettre de lancer automatiquement l'app lorsque vous lancerez R6, voir AUTOSTART-Fr pour plus d'info

svcl : 
C'est le .exe que j'utilise pour le mute/demute, vous avez pas besoin de le lancer, simplement laissez le dans le dossier sans le déplacer

switch : 
C'est le .bat utiliser pour mute/demute r6, si vous le lancez manuellement votre jeu sera mute ou demute

