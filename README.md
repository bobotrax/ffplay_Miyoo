<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="ffplay_pour_Miyoo_mini_0"></a>ffplay pour Miyoo mini</h1>
<p class="has-line-data" data-line-start="1" data-line-end="4">Version de ffplay pour la Miyoo mini d’après une version du génial <strong>Steward-fu</strong> :<br>
<a href="https://steward-fu.github.io/website/handheld/miyoo-mini/parasyte_build_ffplay.htm">https://steward-fu.github.io/website/handheld/miyoo-mini/parasyte_build_ffplay.htm</a><br>
<a href="https://github.com/steward-fu/miyoo-mini/releases">https://github.com/steward-fu/miyoo-mini/releases</a></p>
<p class="has-line-data" data-line-start="5" data-line-end="6"><strong>Modifications effectuées :</strong></p>
<ul>
<li class="has-line-data" data-line-start="6" data-line-end="7">Recompilation de ffplay pour qu’il démarre en 4:3 le format d’écran de la Miyoo.</li>
<li class="has-line-data" data-line-start="7" data-line-end="8">Changement d’icône.</li>
<li class="has-line-data" data-line-start="8" data-line-end="9">Changement du dossier VIDEO par Media/Videos pour rester dans l’esprit d’Onion OS.</li>
<li class="has-line-data" data-line-start="9" data-line-end="10">Ajout de quelques lignes dans <code>launch.sh</code> pour désactiver la mise en veille avant le lancement de la vidéo et le réactiver après la video.</li>
<li class="has-line-data" data-line-start="10" data-line-end="12">Ajout de l’option <code>autoexit</code> dans <code>launch.sh</code> pour qu’ffplay ce ferme à la fin de la vidéo.</li>
</ul>
<p class="has-line-data" data-line-start="12" data-line-end="14">Le binaire de <strong>Steward-fu</strong> est toujours dans le dossier bin sous le nom de “ffplay_16_9” pour ce qui veulent lancer ffplay en 16:9.<br>
Pour l’installation il suffit de déplacer le contenu du dossier SDCARD à la racine de la carte sd, et placer vos vidéos dans Media/Vidéos.</p>
<p class="has-line-data" data-line-start="15" data-line-end="16"><strong>Actions des touches :</strong></p>
<ul>
<li class="has-line-data" data-line-start="16" data-line-end="17">Haut : +60 secondes</li>
<li class="has-line-data" data-line-start="17" data-line-end="18">Bas : -60 secondes</li>
<li class="has-line-data" data-line-start="18" data-line-end="19">Gauche : -10 secondes</li>
<li class="has-line-data" data-line-start="19" data-line-end="20">Droite : +10 secondes</li>
<li class="has-line-data" data-line-start="20" data-line-end="21">A : Pause</li>
<li class="has-line-data" data-line-start="21" data-line-end="22">B : Image suivante</li>
<li class="has-line-data" data-line-start="22" data-line-end="23">X : +10 minutes</li>
<li class="has-line-data" data-line-start="23" data-line-end="24">Y : -10 minutes</li>
<li class="has-line-data" data-line-start="24" data-line-end="25">L1 : Changement du flux audio</li>
<li class="has-line-data" data-line-start="25" data-line-end="26">L2 : Changement du flux video</li>
<li class="has-line-data" data-line-start="26" data-line-end="27">R1 : Changement du flux audio, video et sous titres</li>
<li class="has-line-data" data-line-start="27" data-line-end="28">R2 : Changement du flux des sous titres</li>
<li class="has-line-data" data-line-start="28" data-line-end="29">Start : Bascule 4:3 vers 16:9</li>
<li class="has-line-data" data-line-start="29" data-line-end="30">Select : Changement d’effets de visualisations</li>
<li class="has-line-data" data-line-start="30" data-line-end="32">Menu : Enregistre la position et quitte</li>
</ul>
<p class="has-line-data" data-line-start="32" data-line-end="33">V1.1 - Suppression de la dépendence à parasyte, à priori ffplay a besoin que d'une seul librairie de parasyte.</p>
<p class="has-line-data" data-line-start="33" data-line-end="34">Merci à <strong>Steward-fu</strong>.</p>
<hr>
<p class="has-line-data" data-line-start="36" data-line-end="39">Version of ffplay for the Miyoo mini from a version of the awesome <strong>steward-fu</strong> :<br>
<a href="https://steward-fu.github.io/website/handheld/miyoo-mini/parasyte_build_ffplay.htm">https://steward-fu.github.io/website/handheld/miyoo-mini/parasyte_build_ffplay.htm</a><br>
<a href="https://github.com/steward-fu/miyoo-mini/releases">https://github.com/steward-fu/miyoo-mini/releases</a></p>
<p class="has-line-data" data-line-start="40" data-line-end="41"><strong>Modifications made :</strong></p>
<ul>
<li class="has-line-data" data-line-start="41" data-line-end="42">Recompiled ffplay to start in 4:3 the screen format of the Miyoo.</li>
<li class="has-line-data" data-line-start="42" data-line-end="43">Change of icon.</li>
<li class="has-line-data" data-line-start="43" data-line-end="44">Changed VIDEO folder to Media/Videos to stay in the spirit of Onion OS.</li>
<li class="has-line-data" data-line-start="44" data-line-end="45">Added some lines in <code>launch.sh</code> to disable the sleep mode before launching the video and re-enable it after the video.</li>
<li class="has-line-data" data-line-start="45" data-line-end="47">Added <code>autoexit</code> option in <code>launch.sh</code> to close ffplay at the end of the video.</li>
</ul>
<p class="has-line-data" data-line-start="47" data-line-end="49">The <strong>Steward-fu</strong> binary is still in the bin folder under the name “ffplay_16_9” for those who want to launch ffplay in 16:9.<br>
To install, just move the contents of the SDCARD folder to the root of the SD card, and place your videos in Media/Videos.</p>
<p class="has-line-data" data-line-start="50" data-line-end="51"><strong>Key Descriptions :</strong></p>
<ul>
<li class="has-line-data" data-line-start="51" data-line-end="52">Up button: +60 seconds</li>
<li class="has-line-data" data-line-start="52" data-line-end="53">Down key: -60 seconds</li>
<li class="has-line-data" data-line-start="53" data-line-end="54">Left button: -10 seconds</li>
<li class="has-line-data" data-line-start="54" data-line-end="55">Right button: +10 seconds</li>
<li class="has-line-data" data-line-start="55" data-line-end="56">A key: Pause</li>
<li class="has-line-data" data-line-start="56" data-line-end="57">B key: next frame</li>
<li class="has-line-data" data-line-start="57" data-line-end="58">X key: +10 minutes</li>
<li class="has-line-data" data-line-start="58" data-line-end="59">Y key: -10 minutes</li>
<li class="has-line-data" data-line-start="59" data-line-end="60">L1 key：Cycle audio channel</li>
<li class="has-line-data" data-line-start="60" data-line-end="61">L2 key：Cycle video channel</li>
<li class="has-line-data" data-line-start="61" data-line-end="62">R1 key：Cycle audio, video and subtitle channel</li>
<li class="has-line-data" data-line-start="62" data-line-end="63">R2 key：Cycle subtitle channel</li>
<li class="has-line-data" data-line-start="63" data-line-end="64">START：Full screen</li>
<li class="has-line-data" data-line-start="64" data-line-end="65">SELECT：Display effect</li>
<li class="has-line-data" data-line-start="65" data-line-end="67">MENU：save and leave</li>
</ul>
<p class="has-line-data" data-line-start="67" data-line-end="68">V1.1 - Removal of parasyte dependency, in principle ffplay only needs one parasyte library.</p>
<p class="has-line-data" data-line-start="68" data-line-end="69">Thanks to <strong>Steward-fu</strong>.</p>
