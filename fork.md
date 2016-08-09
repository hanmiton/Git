paos para fork
	upstrema 
		rama vinculo que se hace con el repo principal
	conecntar via remoto 
		git origin y upstream
	depues hacer un getch
		de origin/master y uptream/master
	se tendran dos ramas escondigas
		origin/master
		upstream/master
		master
	primero hacer un push para subir al forked repositroio
	hacemos pull para hacer la propuesta para la propuesta al repositorio
Comandos fork
	git remote add origin proyecto forked
	git remote add upstream proyeto principal
	git fetch upstrema
	git merger origin/upstrema
	git fecth origing
	git merge origin/master
	---cambios loca
	git fetch upstream
	git merge origin/upstream
	git push origin master

git remote -v
	para ver los remtoos que se encuentran conectados
0.34
Deployment 
	lelvar el codigo a propducion
Ambientes
	Development
		area local odnde se esta trabajando (fuera internet)
	Production
		servidro es donde se sube la app web
Ambientes
	Development
	Production
	Testing
		Un amgiente donde se hacen todas la preubas
	Staging
		Es un servidor experimental
Desarrollador principal 
	Solo necesita 2 ramas
		master 
		origin/master
git pull
	descargar cambios repositorio principal
	fetch+merge (upstream)
Proyect Management
	crear una oganizacion para el proyecto q se piensa deasarrollar
