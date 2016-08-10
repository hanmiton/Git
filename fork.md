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
Añadir website buena practica
README.md
	Blog Universidad
	[Descripción del Proyecto]
	[Instalacion]
		-requisitos
		-version
		-encargados del proyecto
	[Usage]
		como hacer uso
	[Documentacion]
	[roadmap]
	[licencia]
MIlstone 
	lineas de progreso
		Desarrollo de landing
wikis
	se puede usar pra escribir toda la historio del proeycot
imgur.com 
	para subir imagenes rapidas
pulse
Deployment
	tiener que ser totalmetne libre 
	es como llevo mi poryecto a internet
Despliegue
	Manual Deployment
		despliegue de forma manual
	Se hace un despliegue en el q hay menor trafico
Servidores
	hostgator
	digiralocena
	aws
	webfaction
INgresar servidor
	ssh urlservidro para ingresar por ssh
	ls (buscamos la carpeta donde subir las apps)
	cd webapps (entrando a los proeyctos qu ese encuentran alojados)
Servidore sy git
	cuando el servidor no tiene gi tse tiene que instlar git
Conectando servidor a host github
	Primera forma
		git init 
		git clone [url_repositorio]
rm -rf 
	comando para borrar carpetas
	Segunda forma
		git remote add orign [url]
		git pull origin master(fetch+merge)
git pull
	git fetch + git merge
Amazon Web SErvice
	.pem (ver qeu es)
	load balancer 
		guardias antes de entrar a la intancia
		porq puertos cada personas
Instancia aws
	Priemro crear keypair
	Security Groups
		Crear gurpo de seguridad
	Crear load balancer
	Creamos la instancia
GitHooks
	sirven para automatizar el deployment
Webfaction
namecheap 
	para comrpar dominios
depende del hosting para ver donde se tiene que almacenar las apps

deployment
	se hace un git pull desde el servidro por ssh y asi se despliega la app en poroduccion
load balancer
	es como un guardia q decide ocmo distribuir al servidro o Servidores