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
	Author
	Date
	Commit ID (SHA)
	
	