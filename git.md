Empezando curso git actualizado 
GITHUB
	control de versiones git
	github plataforma que gestionaa el almacenamiento de los poryectos
	Es distribuido quiere de cir cada proyecto es independiente
Arquitectura de Arbol
	Areas
		Local
			Working directory
			Area de prepacion(stage Area) => prepacracion de archivos antes del repositiro final
		Repository
			donde se encuentra almacenando el codigo 
Working Area
	Dodne trabajas turs archiovos
Stagin Area
	Donde se preparan los archivos
Final 
	Repositorio donde se encuentra la historioa de neustor poryecot
Terminal
	Es un programa que puede lanzar comandos a tu computadora o un servidor
Comandos iniciales
	git --version ( ver version de git la cual se encuentra instalada)
	git config --global user.name hanmiton (configurar nombre que se usara en git)
	git config --global user.email hanmilton_12@outlook.com (configuraicon correo dentro de git)
	git config --list ( ver toda la configuraicon de git)
	git help <comando> (te muestra toda la documentacion acerca de un comando en git)
Git Workflow
	git status ( se puede observar el estado de neustro poryecto cambiso que se han realizado en q archivos)
git init
	iniciar un repositrio de git
git add <favicon.ico>
	agregando en stage area un solo archivo
git add -A
	añdiendo todos los archivos
git commit -m "..........."
	hacienod un commit para guardar todos los cambios ocn un mensaje
git log
	para ver como se fueron hacer los cambios
	--oneline
		Quita fechas y solo lanza los commits
	--oneline --graph
		Siver para ver las ramas
git config --global alias.superlog <comadno>(creacion de alias para un comando)
git Reset
	git reset --hard
	git reset --hard <id-commit>(id-commit desde este commit hasta mas actuales se borra)
git reset --mixed [SHA commit]
	no te borra tu area de trabajo
	se sule usar pra ahcer suam de commits
	no esta listo pra hacer un commit
git reset --soft
	se esta listo para hacer un commit
git checkout [commit-id]
	con esto se crea un brach distinto si se desea guradar lso cambios
Analizando un commit
	parent
		parent es el padre de dicho commit
	Author
	Date
	Commit ID (SHA)

Ramas
	Una linea laterna de itempo, enl a historia de nuestor reposritorio
	Ideas-Features-BugFixes
Comando para poder commits personalizado
	git config --global alias.nicelog 'log --oneline --graph --all'
Git checkout [branch]
	te permite cambair de ramo ejemplo master-experimental
Fusiones
	git merge experimentasl (nos pemite realczar las fusiones)
	Soluciones de conflictos
		Fast-Forward
			cuando se editan distintons tipos de archivos y se desea hacer el merge
		Manual-Merge
			Cuando se ataca la misma linea de codigo y esto toca hacerlo manual
Rebase
	Los commits se ubican adelante del ultimo commit de master
	Pero master sigue en el ultimo commit

	git checkout -b experimental
al

Git merge
	te ubicas en la rama a la cual vas a realizar el merge
	git merge experimental (especificamos la rama que queremos que se haga merge)
Manual Merge
	git branch -d experimental (apra borrar rama)(no sepude obrra si no se a ehcho una fusion)
	tratar de trabajar en documetnos diferente spra evitar manaul merge
--amend
	espara rectificar en el ulitmo commit
git commit -am 
	 para no tener que hacer el add y subir directamente los cambios
amend
	Se peude hacer un cambio al ultimo commit
	git commit -m "......" --amend
git log --decorate
	indica en que punto se encutnra el HEAD
git log --stat
	te indica que lineas fueron las que se modificaaron
git log -p 
	te indica q se modifico pero con un div
git log --pretty=format:"%cn, hizo comi dia %cd"
	para armar mensajes con lso commits
git log -#
	te muestra los ultimos commits
git log --after="today"
git log --before="today"
git log --grep="mensaje"
	bueno para encontrar palabras dentro de los commits
git log -S"git"
	busca dentro del codigo 
WORKFLOWS
	como logramos que varios profesionasl trabajen sobre un proyecto sin matrase
GTIHUB
	servicoi de hosting apra repositorios
	2 bases
		Exploracion(Clone)
		Colaboración
GITHUB EXPLORER
	git clone 
		 para clonar un repositroio
conexion via ssh
	github
		settings
			ssh keys
Creando lalve ssh key
	ssh-keygen -t -rsa -b 4096 -C "hanmilton_12@outlook.com"
	-rsa algoritmo que se va usar par generar la llave
	-4096 # nuemro de bit s para la lalve
git remote add origin <donde se queire conectar>
probando key des peus de lcone

