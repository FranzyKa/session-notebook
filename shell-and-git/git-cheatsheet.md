<Git Cheatsheet>

<h2>Basic-Befehle</h2>

<p>
> ls <br>
> cd <br>
> cd .. <br>
> cd ordnername <br>
> ls -la (versteckte Datei mit anzeigen lassen) <br>
> mv + datei/ordner name + zielort <br>
> touch <br>
> mkdir <br>
</p>
<p>
<h2>Git Basic-Befehle</h2> <br>
<br>
> git status <br>
> git log<br>
<br>
</p>
<p>
<h2>Befehle, um ein neues Repository zu erstellen</h2><br>
<br>
> git init <br>
> git add + dateiname <br>
> git commit -m "message" <br>
> git branch - m main<br>
> git remote add origin + ssh link<br>
> git push -u origin main<br>
<br>
</p>
<p>
<h2>Push auf ein existierendes Rep</h2>
<br>
> git remote add origin + ssh link<br>
> git branch -m origin<br>
> git push -u origin main<br>
<br>
</p>
<p>
<h2>Ein Repo löschen</h2>
<br>
> rm .git<br>
<br>
</p>
<p>
<h2>Einen Ordner/Datei löschen</h2><br>
<br>
> rm -rf + dateiname
</p>

<h2> Branches </h2>
<br>
<p>
<strong>merge</strong> bedeutet einen <em>Feature-Branch</em> in den <em>main-Branch</em> einzufügen 
<br>
> git switch -c <em>branchname</em> = Einen neuen Branch erstellen & direkt zu ihm wechseln <br>
> git switch <em>branchname</em>    = zwischen Branches wechseln <br>
> git branch                        = lokales Branch anzeigen <br>
> git branch -a                     = alle Branches anzeigen (lokal+remote) <br>
> git branch -d <em>branchname</em> = einen Branch löschen <br>
</p>

<h2>Pull Request <em>PR</em></h2>
<br>
<p>PR können wir nutzen um Reviews für die Arbeit in einem Feature-Branch anzufordern.<br>
Ist eine Anfrage, einen Branch in einen anderen Branch zu mergen. Andere Entwickler überprüfen den PR und schlagen Änderungen vor. <br></p>
