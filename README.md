Version de ffplay pour la Miyoo mini d'après une version du génial Steward-fu :
https://steward-fu.github.io/website/handheld/miyoo-mini/parasyte_build_ffplay.htm
https://github.com/steward-fu/miyoo-mini/releases

Modifications effectuées :
	- Recompilation de ffplay pour qu'il démarre en 4:3 le format d'écran de la Miyoo.
	- Changement d'icône.
	- Changement du dossier VIDEO par Media/Videos pour rester dans l'esprit d'Onion OS.
	- Ajout de quelques lignes dans launch.sh pour désactiver la mise en veille avant le lancement de la vidéo et le réactiver après la video.
	- Ajout de l'option autoexit dans launch.sh pour qu'ffplay ce ferme à la fin de la vidéo.

Le binaire de Steward-fu est toujours dans le dossier bin sous le nom de "ffplay_16:9" pour ce qui veulent lancer ffplay en 16:9.
Pour l'installation il suffit de déplacer le contenu du dossier SDCARD à la racine de la carte sd, et placer vos vidéos dans Media/Vidéos.

Actions des touches :
	- Haut : +60 secondes
	- Bas : -60 secondes
	- Gauche : -10 secondes
	- Droite : +10 secondes
	- A : Pause
	- B : Image suivante
	- X : +10 minutes
	- Y : -10 minutes
	- L1 : Changement du flux audio
	- L2 : Changement du flux video
	- R1 : Changement du flux audio, video et sous titres
	- R2 : Changement du flux des sous titres
	- Start : Bascule 4:3 vers 16:9
	- Select : Changement d'effets de visualisations
	- Menu : Enregistre la position et quitte

Merci à Steward-fu.

------------------------------------------------------------------------

Version of ffplay for the Miyoo mini from a version of the awesome steward-fu :
https://steward-fu.github.io/website/handheld/miyoo-mini/parasyte_build_ffplay.htm
https://github.com/steward-fu/miyoo-mini/releases

Modifications made :
	- Recompiled ffplay to start in 4:3 the screen format of the Miyoo.
	- Change of icon.
	- Changed VIDEO folder to Media/Videos to stay in the spirit of Onion OS.
	- Added some lines in launch.sh to disable the sleep mode before launching the video and re-enable it after the video.
	- Added autoexit option in launch.sh to close ffplay at the end of the video.

The Steward-fu binary is still in the bin folder under the name "ffplay_16:9" for those who want to launch ffplay in 16:9.
To install, just move the contents of the SDCARD folder to the root of the SD card, and place your videos in Media/Videos.

Key Descriptions :
    - Up button: +60 seconds
    - Down key: -60 seconds
    - Left button: -10 seconds
    - Right button: +10 seconds
    - A key: Pause
    - B key: next frame
    - X key: +10 minutes
    - Y key: -10 minutes
    - L1 key：Cycle audio channel
    - L2 key：Cycle video channel
    - R1 key：Cycle audio, video and subtitle channel
    - R2 key：Cycle subtitle channel
    - START：Full screen
    - SELECT：Display effect
    - MENU：save and leave

Thanks to Steward-fu.
