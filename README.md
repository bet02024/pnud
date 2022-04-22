# Lunas-Pnud Chatbot!

![enter image description here](https://github.com/josebetomex/pnud/blob/main/chatbot.png?raw=true)

# Instalación




**Prerrequisitos**

Dependiendo de tu sistema operativo, instalar los siguientes componentes:

1) **Instalar Python 3.7 o 3.8 y PIP3**

2) **Instalar Rasa  3.0.2** -.> https://rasa.com/docs/rasa/installation
     
     $ pip3 install rasa==3.0.2
     
3) **Instalar Git**

4) **Clonar este repositorio**

     $ git clone https://github.com/josebetomex/pnud.git

5) **Entrenar el modelo**
	
	$ cd pnud
	$ rasa train

6) **Correr el Chatbot server Rasa**

	$ rasa run  --cors "*"

7) **Desplegar un cliente del chatbot en un servidor HTTP**

     Editar el archivo index.html (ejemplo de cómo implementar un widget del chatbot en una página  web).
   
     Modificar la **dirección IP** a donde está corriendo el Servidor de Rasa
     
     data-websocket-url="http://**18.188.115.189**:5005/socket.io"


8) **Interactuar con el chatbot.**

		Navegar en el navegador a la dirección donde se instaló el archivo index.html

9) **Modificar las imagenes**

 **- Detener el servidor Rasa**

 **- Modificar el siguiente archivo con las nuevas imágenes** 
   [domain.yml](https://github.com/josebetomex/pnud/blob/main/domain.yml
   "stories.yml")

	

 **- Re-entrenar el modelo:**

	$ rasa train

 - **Correr el servidor nuevamente**

	$ rasa run  --cors "*"

	


