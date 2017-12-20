# release_safecryptomining by deathcult456
BTC donation adresse: 15WnvJt7GCasvWuntB6AJSwVfuG7p5r7Ev

ethereum donation:  b6f7d015910004953799793fc512309f5fbc0803

//nécessite .net framework 4.5 pour fonctionner

permet de managé un rig qui fonctionne sous nicehash et nanopool avec un redemmarage automatique lorsque le rig arrete de miner et l'envoi d'un sms si on est chez free par l'option "notification par sms" dans son espace perso section option.

v1.03 --> add "zpool" + "yiimp" 

v1.02 --> add pool and version.

v1.01 --> add try catch in tick() for check internet connexion.

v1.0 --> release.



Fichier de configuration: safecryptomining.exe.config  

Configuration :

"pool" value="nanopool" mettre votre pool: "nicehash" ou "nanopool"

"Adresse_BTC" value="BTC_adresse" Adresse bitcoin du miner.

"Worker_name" value="rigName"  nom du worker donner dans nicehash miner attention très important doit respecter la case!

"interval_temps" value="5000" intervalle de temps en milliseconde dans lequel le worker est testé.

"Restart_miner" value="true" redémarre le miner si probleme de minage, mettre FALSE si non utilisé.

"Utiliser_free_sms" value="true" utilise le service de free pour envoyé des sms, mettre FALSE si non utilisé.

"free_user" value="3x3x3x3" utilisateur donner dans la section option une fois l'option gratuite activée.

"free_pass" value="3x3x3x3" pass donner dans la section option une fois l'option gratuite activée.
