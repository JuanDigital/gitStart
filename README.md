Instalando Git 
	sudo apt install git

Configurando Git
	git config --global user.name "JuanDigital"	
	git config --global user.email "juanperez1639@gmail.com"
Tres areas de git
	directorio de trabajo o archivos
	index intermedio para que reconozca los archivos
	git area ultimo comit o estatus actual

iniciando git 
	git init
	git status # que ha pasado aqui?

agregar archivos al index
	git add example.txt
	git add -A  # este comando es para agregar todos

Quita archivos del index
	git rm -- cached example.txt

un commit es un status en el tiempo
	git commit -m "status 1"
	git log
