# bot_invidentes
Este es un chatbot diseñado para realizar una visita al Real Jardín Botánico de Madrid más accesible, concretamente a personas invidentes.
Para crearlo se ha empleado Rasa, que se basa en Python, en una máquina de Linux.

Los pasos a seguir para instalar Rasa y Python y crear el entorno virtual del proyecto son:
En primer lugar, se instala la versión 3.7 de Python con los siguientes comandos:
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt install python3.7

Una vez instalada la versión 3.7 de Python, se crea un entorno virtual y se procede a activarlo:
python3 -m venv ./venvsource 
./venv/bin/activate

Al activarse de forma correcta, se puede ver que el símbolo del sistema pasa a tener el siguiente aspecto: 

(venv)/root/>

A continuación, se actualiza el pip a la última versión

pip install -U pip

Finalmente, ya podemos instalar Rasa en el entorno virtual

pip install rasa

Como ya se ha instalado Rasa, se puede crear ya el proyecto, en el cual desarrollaremos el chatbot. Para ello, se activa el entorno virtual.

source ./venv/bin/activate
 Con el entorno creado, clonamos el repositorio y podemos desplegar el chatbot en la terminal con el comando:
 
 rasa shell
