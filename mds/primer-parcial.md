# Examen Primer Parcial

#### 1. ¿Qué es y para qué sirve Visual Studio Code? 
Es un programa de códigos que sirve para poder escribir diferentes lenguajes y se fabrican principalmente en HTML.

####	2. ¿Qué es y para qué sirve la Terminal de Comandos? 
Espacio que sirve para poder escribir códigos, modificar archivos o documentos dentro de la computadora.

####	3. ¿Qué es y para qué sirve Markdown? 
Es un sistema de lenguaje para poder escribir usando un formato de texto plano fácil de personalizar un formato.

####	4. ¿Qué es y para qué sirve Git? 
Software para poder guardar cambios dentro de Visual Studio y poder transferirlos hacia GitHub. También sirve para que 2 o más desarrolladores trabajen en un mismo código.

####	5. ¿Qué es y para qué sirve GitHub? 
Es una plataforma para poder almacenar o publicar tus proyectos de Visual Studio Code; gracias con Git. 

####	6. ¿Para qué sirven los siguientes comandos: pwd, whoami, touch, mkdir, cp, mv, ls, clear, cd y rm? 
- **pwd**: sirve para mostrarte en que carpeta estas
- **whoami**: muestra la información del usuario
- **touch**:  sirve para crear archivos
- **mkdir**: sirve para crear carpetas
- **cp**: sirve para copiar información de un archivo/documentos y pegarla en otro
- **mv**: mueve o renombra un archivo
- **ls**: sirve para listar los archivos de una carpeta.
- **clear**: Sirve para limpiar los códigos dentro de la terminal de comandos
- **cd**: cambio de carpeta
- **rm**: borra archivos/carpetas
 
####	7. ¿Qué significan los siguiente caracteres en la terminal de Comandos: ./, ../, /, y ~? 
- 	./: sirve para ejecutar un archivo 
-	../: sube una carpeta atrás.
-	/: indica raíz del sistema.
-	~: muestra carpeta personal del usuario.

####	8. ¿Cómo se inicializa un repositorio en Git? 

``` bash
git init
```

####	9. ¿Cómo creas un repositorio en GitHub?
Desde la página de GitHub, en la parte superior derecha va haber un símbolo de "+". Lo presionas y de opciones ahi te va a dar la opción de crear un nuevo repositorio.
![Mi Cara:](/assets/Crear_Un_Repositorio.jpg)

#### 10. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub? 
``` bash
git remote add nombre-orígen https://github.com/usuario/repositorio.git
```


####	11. ¿Cuál es el flujo básico de trabajo en Git y GitHub?, explicalo indicando la secuencia de comandos. 

El flujo básico cuenta con consta de 4 estados, dichos estados son:

- **modified**: Es la carpeta donde almacena todos los archivos de tu computadora.
- **staged** : Es donde Git va registrando todos los cambios
- **committed** : Es donde los cambios ya se han registrado y manda un mensaje de envio.
- **remote**: Ya es aqui donde el directorio remoto ha enviado la información a GitHub

**Secuencia de comandos**
1. Guarda los cambios locales y los agrega al stage del repositorio.

``` bash
 git add .
```

2. Crea un commit y da un mensaje sobre el cambio.

``` bash
git commit –m “Un mensaje”
```
3. Los cambios se suben a GitHub

``` bash
git push
```

####	12. ¿Para qué sirve el archivo .gitignore? 
Sirve para ignorar algún documento a la hora de subirlas al repositorio



####	13. ¿Cuál es el propósito de una rama? 
Crea como copias del proyecto y las subdivide

####	14. ¿Qué es una fusión? 
Sirve para fusionar 2 o más ramas en una sola.

####	15. Explica los diferentes tipos de fusión que existen. 
- Fast-Forward: Una fusión automática
- Manual Merge: Todas las fusiones las haces por tu cuenta.
####	16. ¿Cómo puedes ver el historial de tu repositorio?
``` bash
git log 
```

####	17. ¿Cuál es el propósito de una etiqueta?
Puede marcar diferentes versiones de nuestro proyecto
