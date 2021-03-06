Gitbook Plugins!
===============

**Gitbook Plugins** representan una buena opción si queremos extender las funcionalidades de nuestro Gitbook.
Entre estas funcionalidades destacan: incorporar videos de Youtube, ejercicios, incorporar fórmulas matemáticas, campos para introducir comentarios, ...
Podemos encontrar los Gitbook plugins que nos interesen en [Plugins Gitbook](http://plugins.gitbook.com)

>- #### primary::¿Cómo podemos instalar un plugin?

> - Creamos fichero **book.json** siguiendo la estructura:
>
```json
{
    "gitbook": "0.0.1",
    "title": "Gitbook para apuntes. Asignatura SYTW16-17",
    "plugins": [],
    "structure": {
    },
    "pluginsConfig": {
    }
}
```

> - A continuación, debemos instalarlo con el comando **npm install**:
>
```bash
 npm install  "nombre del plugin" --save-dev
```

> - Una vez que encontremos el plugin que necesitamos, debemos añadirlo a nuestro fichero book.json: 
>
```json
{
	"plugins": ["plugin 1", "plugin 2"]
}
```

> Los Gitbook Plugins son instalados automáticamente en [Gitbook.com](http://www.gitbook.com). Localmente, podemos ejecutar el siguiente comando para instalar y preparar todos los plugins para nuestros libros:
>
```bash
$ gitbook install
``` 