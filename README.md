~ Symfony Vide ~

Ce projet est un projet vide qui peut servir de "template" dans le but d'etre duppliquer.

Pour participer au projet vous devez travailler avec un git flow comme le suivant:
	
	
	"master/develop/feature"
	
~ Pour soumettre votre travail ~

~~~~
$ git pull
$ git add <vos fichiers modifiés> 
$ git commit -m "Votre message de commit"
$ git push develop
~~~~

Ensuite sur github vous pourrez aller faire votre PullRequest
Qui sera ensuite soumis à évalution

~ Pour lancer le projet symfony ~

	$ symfony console server:start

~ Pour tester le projet ~

	$ ./bin/phpunit
