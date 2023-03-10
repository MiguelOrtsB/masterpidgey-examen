# EXAMEN ENTORNOS DE DESARROLLO 2ª EVALUACIÓN  
## PARTE 1  
## **Repositorio masterpidgey-examen**  
1º. Vamos a crear un repositorio en nuestro GitHub llamado masterpidgey-examen, es muy sencillo, simplemente debemos ir al apartado **Repositories** y hacer click al botón verde **New** de la esquina superior derecha. Pondremos el nombre que queramos, añadiremos README (en nuestro caso no porque es un requisito posterior de la práctica), añadimos una licencia si se precisa y le damos a crear.  
![1](Capturas/f5.png)
![2](Capturas/f1.png)  
2º. Clonar nuestro repositio en local con el comando ***" git clone + enlace del repositorio masterpidgey-examen "***.  
![3](Capturas/f6.png)  
## **README**  
3º. Crear en nuestro repositorio local un documento README.md. Para ello primero nos tendremos que situar en la carpeta del repositorio con el comando ***" cd + nombre carpeta"***. Una vez dentro, podemos crear el README con el comando ***" touch README.md "*** para simplemente crearlo o con el ***" nano README.md "*** para crearlo y introducirnos para añadir algo a través de dicho editor (nano).  
![3.5](Capturas/f11.png)  
![4](Capturas/f7.png)  
## **Commit inicial**  
4º. Añadiremos al README.md los comandos utilizados hasta ahora, añadiremos los cambios con el comando ***" git add . "*** y haremos un commit inicial con el mensaje commit inicial con ***" git commit -m "mensaje" "*** para preparar para subir estos cambios.  
![5](Capturas/f9.png)
![6](Capturas/f8.png)  
## **Push inicial**  
5º. Ahora ya subiremos los cambios definitivamente al repositorio remoto con ***" git push "***.  
![7](Capturas/f10.png)  
## **Ignorar archivos**  
6º. Crear en el repositorio local un fichero llamado privado.txt con el comando ya conocido ***" touch privado.txt "***.  
![8](Capturas/f12.png)  
7º. Crear en el repositorio local una carpeta llamada privada con el comando ***" mkdir privada "***.  
![9](Capturas/f13.png)  
A continuación podremos ver que efectivamente se ha creado todo correctamente utilizando el comando ***" ls "***.  
![9.5](Capturas/f15.png)  
8º. Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git. Para ello, crearemos un archivo .gitignore con el comando ***" nano .gitignore "***, nos introducimos en él y escribimos el nombre de la carpeta y el archivo que queremos ignorar, guardamos con ***" Ctrl + x "***, confirmamos con ***Yes*** y ya estaría listo.  
![10](Capturas/f14.png)  
![11](Capturas/f2.png)  
## **Añadir fichero 1.txt**  
9º. Añadimos fichero 1.txt al repositorio local de nuevo con ***" touch "***.  
![12](Capturas/f16.png)  
Yo personalmente prefiero realizar un ***" git add, git commit y git push "*** antes de crear el tag para guardar todos los cambios y subirlos correctamente al repositorio remoto. Por lo que pueda pasar... suelo realizar esto bastante a menudo por si falla el programa, etc. 
![13](Capturas/f17.png)  
Nota* podemos ir lanzado ***" git status "*** para ver el estado del directorio y los cambios que se han preparado y los que no.  
## **Visualizar los commits realizados hasta el momento (el historial)**  
Esto se hace mediante el comando ***" git log "***.
![14](Capturas/f18.png)  
## **Crear el tag v0.1**  
10º.  Crear un tag v0.1 con ***" git tag -a v0.1 -m "Versión 1" "*** para capturar un punto en concreto en el historial de Git. Con el comando ***" git tag "*** a secas podremos visualizar el historial de tags hasta ahora.  
![15](Capturas/f19.png)  
## **Subir el tag v0.1**  
11º. Subir los cambios al repositorio remoto. En mi caso ya lo he hecho anteriormente como he indicado, por lo que en este punto simplemente subiré el tag con el comando ***" git push origin v0.1 "***.  
![16](Capturas/f20.png)  
## **Visualizar de nuevo los commits realizados hasta el momento (el historial)**  
Como no he realizado ningún commit más, utilizo la misma captura que la anterior.
![17](Capturas/f18.png)  
## **Crear una tabla**  
12º. Crear una tabla en el fichero README.md con la información del docente del módulo. De nuevo, nos introducimos en el archivo README.md en nano y creamos la tabla, guardamos cambios y salimos.  
![18](Capturas/f21.png)    
![19](Capturas/f3.png)  
|  NOMBRE  |  GITHUB  |
|----------|----------|
|Máximo Fernández Riera|https://github.com/maximofernandezriera|  
  
  De nuevo, para asegurar, realizo un ***" git add, git commit y git push "*** para subir la tabla.  
![20](Capturas/f22.png)  
## **Colaboradores**  
Poner a github.com/maximofernandezriera como colaborador del repositorio masterpidgey-examen. Esto se hace una vez dentro del repositorio en GitHub, vamos al apartado **" Settings "**, luego a **" Collaborators "** en la parte izquierda y añadimos el usuario del colaborador que queremos con el botón verde **" Add people "** visible en la imágen.  
![21](Capturas/f4.png)  
## PARTE 2  
## **Contribución al proyecto first-contributions**  
Para la contribución a este proyecto realizaremos los pasos siguientes:  
## **Forkear este repositorio**  
1º. Lo primero será hacer **" Fork "** del repositorio first-contributions para crear una copia en nuestros repositorios. Esto lo haremos con el botón de la parte superior.  
![22](Capturas/f24.png)  
![23](Capturas/f23.png)  
![24](Capturas/f25.png)  
## **Clonar el repositorio**  
2º. Para ello primero tendremos que salir de la carpeta de masterpidgey-examen, y posicionarios de nuevo en la rama **main**.  
![25](Capturas/f27.png)  
3º. Ahora realizaremos un ***" git clone + enlace repositorio copiado "***.  
![26](Capturas/f28.png)  
## **Crear una rama**  
4º. Lo primero, nos introduciremos en la carpeta del repositorio clonado con un ***" cd first-contributions "***.  
![27](Capturas/f29.png)  
5º. A continuación, crearemos una nueva rama, que es una línea independiente de desarrollo, con ***" git branch + nombre de la rama "***. Seguidamente haremos un ***" git checkout + nombre de la rama "*** para meternos en dicha rama.  
![28](Capturas/f30.png)  
## **Crear los cambios necesarios y realizar commit** 
6º. En mi caso añadiremos un archivo .md con mi nombre, algo sencillo y visual para que realmente se vea que se han realizado estos cambios. Haremos ***" git add . "*** y ***" git commit "*** para preparar todo para subir estos cambios.  
![29](Capturas/f31.png)  
## **Push de los cambios a GitHub**  
7º. Subimos los cambios definitiamente a GitHub con el comando ***" git push --set-upstream origin rama-miguel "***.  
![30](Capturas/f32.png)  
## **Configurar el control remoto para el Fork**  
Ahora vamos a conectar todo lo realizado a nuestro repositorio (sincronizar los cambios).  
8º. Primero listaremos todos los repositorios remotos con ***" git remote -v "***. 
![31](Capturas/f33.png)  
9º. Ahora configuraremos un nuevo repositorio remoto para que se sincronice con la rama, este será el repositorio original del que nos bifurcamos. Utilizaremos el comando ***" git remote add upstream + enlace repositorio original"***.  
![32](Capturas/f34.png)  
10º. Si volvemos a listar los repositorios veremos que se han añadido dos más.  
![33](Capturas/f35.png)  
11º. Para sincronizar los cambios, realiaremos un ***" git fetch upstream "***.  
![34](Capturas/f36.png)  
12º. Volveremos a introducirnos en nuestra rama main con ***" git checkout main "***.  
![35](Capturas/f37.png)  
13º. Por último, fusionaremos los cambios que se hayan realizado en la rama principal del repositorio original con ***" git merge upstream/main "***.  
![36](Capturas/f38.png)  
## **Pull Request**  
Para acabar con la parte dos y con nuestro exámen solo queda realizar la solicitud de extracción al repositorio original, en la que el propietario nos la tendrá que aceptar para que se visualicen los cambios.  
1º. Para ello cuando entremos en GitHub en el repositorio first-contributions nos saltará un mensaje **" Compare & pull request "** en verde en el que tendremos que hacer click, a continuación se nos abrirá la solicitud y tendremos que hacer click en el botón inferior verde **Create pull request** para confirmar la solicitud (podemos añadir algún mensaje si queremos). Ahora solo faltará esperar a que el propietario acepte los cambios, como he comentado anteriormente, y ya podremos visualizarlo y habremos terminado todo.  
![37](Capturas/f39.png)   
![38](Capturas/f40.png) 
![39](Capturas/f26.png)  
## CONCLUSIÓN  
Este exámen ha sido una muy buena práctica para trabajar con el control de versiones con Git y GitHub, automatizar los comandos en la consola Git Bash y aprender el proceso de clonar repositorios, añadir cambios, crear solicitudes de extracción y un largo etc que nos servirá en nuestro día a día como desarrolladores al realizar proyectos y sobre todo en equipos.











