# FREEBSD-0
Clone de FreeBSD écrit en Pascal

<h2>Liste des fichiers</h2>

Voici la liste des différents fichiers proposés dans FREEBSD-0 :

<table>
		<tr>
			<th>Nom</th>
			<th>Description</th>	
		</tr>
		<tr>
			<td><b>AWK.PAS</b></td>
			<td>Cette commande permet de lancer le langage de programmation AWK.</td>
		</tr>	
		<tr>
			<td><b>CAL.PAS</b></td>
			<td>Cette commande permet d'afficher un calendrier. Cette commande est un équivalent de MSX-DOS ou UNIX.</td>
		</tr>
	        <tr>
			<td><b>CAT.PAS</b></td>
			<td>Cette commande permet d'afficher le contenu d'un/des fichiers. Cette commande est un équivalent de UNIX.</td>
		</tr>
		<tr>
			<td><b>CHMOD.PAS</b></td>
			<td>Cette commande permet de changer le mode des fichiers. Cette commande est inspiré de UNIX et Linux.</td>
		</tr>	
		<tr>
			<td><b>CHSH.PAS</b></td>
			<td>Cette commande permet de changer l'interpréteur de commande par défaut.</td>
		</tr>  
		<tr>
			<td><b>CKSUM.PAS</b></td>
			<td>Cette commande permet d'afficher la sommation de vérification CRC et le nombre d'octets de chaque fichiers. Cette commande est inspiré de Linux.</td>
		</tr>
		<tr>
			<td><b>CLEAR.PAS</b></td>
			<td>Cette commande permet d'effacer l'écran.</td>
		</tr>	
		<tr>
			<td><b>CP.PAS</b></td>
			<td>Cette commande permet de copier un fichier. Cette commande est inspiré de la commande UNIX.</td>
		</tr>	
		<tr>
			<td><b>CSPLIT.PAS</b></td>
			<td>Cette commande permet de séparer un fichier en plusieurs sections déterminé par des lignes de contextes.</td>
		</tr>	
	        <tr>
			<td><b>CUT.PAS</b></td>
			<td>Cette commande permet de supprimer des sections de chaque ligne des fichiers.</td>
		</tr>	
		<tr>
			<td><b>DD.PAS</b></td>
			<td>Cette commande permet de convertir un fichier tant qu'il se copie.</td>
		</tr>	
	        <tr>
			<td><b>DF.PAS</b></td>
			<td>Cette commande permet d'afficher l'espace libre sur le système de fichiers. C'est commande est inspiré de Linux et de cygwin.</td>
		</tr>
		<tr>
			<td><b>DIRNAME.PAS</b></td>
			<td>Cette commande permet de retourner le chemin seulement à partir d'un chemin complet de nom de fichier. Cette commande est un équivalent de UNIX et Linux.</td>
		</tr>
  		<tr>
			<td><b>DU.PAS</b></td>
			<td>Cette commande permet de comptabilisé l'espace occupé par un répertoire et ses enfants.</td>
		</tr>
<tr>
			<td><b>ECHO.PAS</b></td>
			<td>Cette commande permet d'afficher un message.</td>
		</tr>  
		<tr>
			<td><b>ENV.PAS</b></td>
			<td>Cette commande permet de fixer ou de demander le contenu des variables d'environnement du système d'exploitaiton.</td>
		</tr>  
		<tr>
			<td><b>EXPAND.PAS</b></td>
			<td>Cette commande permet de convertir des tabulations en espaces.</td>
		</tr>	
</table>

<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> <i>LEFICHIER.PAS</i></pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> <i>LEFICHIER.PAS</i></pre>
	
Par exemple, si vous voulez compiler CHSH.PAS, vous devrez tapez la commande suivante :

<pre><b>fpc</b> CHSH.PAS</pre>
	
<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/FREEBSD-0/blob/master/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/FREEBSD-0/blob/master/LICENSE">MIT</a>.</li>
</ul>
