# 12-Instalar-GitHub-Desktop

# Introducción

GitHub Desktop es una aplicación de escritorio gratuita desarrollada por GitHub para facilitar el uso de Git en un entorno gráfico de usuario. Es compatible con Windows y MacOS. Con GitHub Desktop, los usuarios pueden realizar tareas comunes de Git, como clonar repositorios, crear ramas, realizar commits y fusiones, y sincronizar cambios con repositorios remotos, todo esto sin tener que utilizar la línea de comandos.

Además de facilitar el uso de Git, GitHub Desktop también ofrece una interfaz para interactuar con los repositorios alojados en [GitHub](http://github.com/), permitiendo a los usuarios ver y descargar los repositorios públicos, colaborar en proyectos de código abierto, y ver las actividades de sus colegas de trabajo.

Es una herramienta muy útil para aquellos que desean utilizar Git pero no desean o no tienen experiencia en el uso de la línea de comandos. Esta herramienta es especialmente útil para aquellos que desean colaborar en proyectos de código abierto en GitHub, ya que facilita el flujo de trabajo y la colaboración con otros miembros del equipo.

# Material Necesario

- [VirtualBox](https://github.com/RaulToribio/01-Instalar-VirtualBox)
- [Ubuntu 22.04.1 LTS](https://github.com/RaulToribio/02-Descargar-Ubuntu)
- [Crear Máquina Virtual](https://github.com/RaulToribio/03-Crear-Maquina-Virtual)
- [Configurar Máquina Virtual](https://github.com/RaulToribio/04-Configurar-Maquina-Virtual)
- [Instalar Ubuntu](https://github.com/RaulToribio/05-Instalar-Ubuntu)
- [Instalar Guest Additions](https://github.com/RaulToribio/06-Instalar-Guest-Additions)
- [Comandos Linux](https://github.com/RaulToribio/07-Comandos-Linux)

# Material de Referencia

- [Tutorial de GitHub Desktop en Ubuntu 20.04](https://edu.codigoiot.com/course/view.php?id=814)

# Instrucciones

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(1).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(1).png)

Debido a que GitHub Desktop está únicamente disponible para sistemas operativos Windows y MacOS, hay que realizar una instalación manual no oficial.

Dirigirse al repositorio de **berkorbay** donde proporciona las [Instrucciones de Instalación de GitHub Desktop](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1).

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(2).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(2).png)

Instalar gdebi-core con la línea de comando `sudo apt-get install gdebi-core`.

gdebi-core es una herramienta de instalación de paquetes para sistemas operativos basados en Debian, como Ubuntu. Es una versión mejorada de gdebi, que se utiliza para instalar paquetes en formato .deb. A diferencia de la herramienta de instalación de paquetes de Ubuntu, apt, gdebi-core se centra en la resolución de dependencias de los paquetes y puede manejar paquetes que tienen dependencias no satisfechas. Además, gdebi-core también verifica la integridad del paquete antes de instalarlo, lo que ayuda a evitar problemas de seguridad.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(3).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(3).png)

Ingresar contraseña.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(4).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(4).png)

Se habrá instalado gdebi-core.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(5).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(5).png)

Descargar el archivo de instalación con la línea de comando `sudo wget https://github.com/shiftkey/desktop/releases/download/release-3.1.1-linux1/GitHubDesktop-linux-3.1.1-linux1.deb`.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(6).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(6).png)

Se habrá descargado el archivo de instalación.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(7).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(7).png)

Instalar el paquete GitHubDesktop-linux-3.1.1-linux1.deb con la línea de comando `sudo gdebi GitHubDesktop-linux-3.1.1-linux1.deb`.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(8).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(8).png)

Confirmar la operación escribiendo “*Y*”.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(9).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(9).png)

Se habrá instalado el paquete GitHubDesktop-linux-3.1.1-linux1.deb.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(10).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(10).png)

Clic en el ícono “GitHub Desktop”.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(11).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(11).png)

Clic en “Sign in to GitHub.com”.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(12).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(12).png)

Ingresar la información de acceso a GitHub.com.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(13).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(13).png)

Clic en “Sign in”.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(14).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(14).png)

Clic en “Open Link”.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(15).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(15).png)

Clic en “Finish”.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(16).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(16).png)

Podremos utilizar las herramientas de Git con una interfaz gráfica.

Lo primero a realizar es clonar un repositorio.

Clic en “Clone **RaulToribio/Diplomado-Internet-de-las-Cosas**”.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(17).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(17).png)

Clic en “Clone”.

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(18).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(18).png)

Se habrá clonado un repositorio con ayuda de GitHub Desktop.

# Evidencias

![https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(18).png](https://raw.githubusercontent.com/RaulToribio/12-Instalar-GitHub-Desktop/main/Im%C3%A1genes/Instalar%20GitHub%20Desktop%20(18).png)

# Créditos

> [José Raúl Toribio Gabriel](https://github.com/RaulToribio)
> 

> [Codigo IoT](https://github.com/codigo-iot)
>