# OsbcVauriens

Export - by LIHU.

Colonnes :
- Player - \[son player id\]
- Name - nom du toon
- Side : Light, Dark, Neutral (y'a que Hondo comme ça pour l'instant)
- L/GL : Leader, Galactig Legend (ils sont tous aussi L, donc c'est pas réécrit)
- Role : Sup=Support, Tnk=Tank, Atk=Sttacker, Hlr=Healer
- Level : 1 à 85
- \* : nb d'etoiles
- GL : Gear Level
- RL : Relic Level
- Power : power du toon
- Max power : max power atteignable pour ce toon
- Skill1-Skill8, SK# Level, SK# Max : pour les 1 à 8 skills, son nom, son niveau actuel, son niveau max \[permet de determiner un perso pas fini...\]
  Dans le nom de skill, le préfixe : B=basic, S1=Special 1, S2=Special 2, U1=Ultimate 1, U2=Ultimate 2... suivi de omega, O pour omicron ou Z pour Zeta si le max de la skill s'obtient par l'un deux.
- Health..Spe crit hit : report intégral des stats du perso tel que sur swgoh.gg (chuuut pas de nom !)

Peut s'utiliser dans Excel : Fichier ouvrir, parcourir \[selon les versions d'excel\], sélectionner le type 'Fichier texte *.txt/.csv', cliquer sur le fichier puis ouvrir. la boite de dialogue d'import s'affiche => choisir format délimité puis clic suivant, sélectionner tabulation comme séparateur et décocher les autres puis clic Terminer.
Peut s'utiliser dans powershell ou powershell_ISE (pour ceux qui aiment) - p.ex. : $guilde = get-content guild.csv | convertfrom-csv -delimiter (\[char\] 9); $guilde | out-gridview

Bisous la guilde :)
