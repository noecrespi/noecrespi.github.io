# create-new-revealjs-template

## Instalación
1. Hacer clic en 'Usar esta plantilla'
1. Asignar un nombre a su presentación y se creará en su propia cuenta/org de GitHub
1. Personalizar según sea necesario
1. Si se clona el repositorio localmente, también necesitamos obtener los archivos del submódulo con `git submodule update --init --recursive`
1. Empujar las diapositivas completadas de vuelta a GitHub
1. Configurar los ajustes de sus páginas de GitHub para mostrar las diapositivas desde _sucuenta_.github.io/_nombre_de_repositorio_ (o incluso un dominio personalizado).


## Actualización de Reveal.js

* Puede recibir alertas de Dependabot de GitHub para advertirle sobre vulnerabilidades en el código Reveal.js. Para hacer que desaparezcan, actualice el submódulo.
* Use el comando `git submodule update --rebase --remote` en la **raíz** del repositorio (no en el directorio de submódulos) para actualizar.
* Enlace para obtener información sobre la actualización de submódulos https://stackoverflow.com/questions/1979167/git-submodule-update

## License

* MIT Licensed as per Reveal.js itself

## Contributing

* Feel free to make suggestions and PRs to the template repo
