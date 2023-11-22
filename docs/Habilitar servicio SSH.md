**Nota: Asegúrate de que estás utilizando una versión de Windows 10 o superior para que admita la característica OpenSSH**

#### Configurar el servicio OpenSSH Authentication Agent para que inicie automáticamente:

1. Dirígete a Inicio y escribe `servicios` y abre la aplicación que aparece con el mismo nombre.

2. En la lista de servicios busca OpenSSH Authentication Agent y dale a `click derecho > propiedads`. Si no encuentras el servicio sigue los pasos de la siguiente sección [[#Habilitar el servicio OpenSSH Authentication Agent]]

![[37a2efbc-9c05-49f8-8e67-2f2e9f56db27.png]]

3. En la ventana que emerge, elige en `Tipo de inicio: Automatico` tal cual como se muestra en la imagen.

![[56d7896a-8d70-45e9-a24b-2f58907d4d2b.png]]

4. Si el botón `Iniciar` es clickeable, actívalo para correr el servicio de forma inmediata sin tener que esperar a que inicie el sistema nuevamente.

Ahora, el servicio OpenSSH Authentication Agent se iniciará automáticamente cada vez que inicies Windows. Puedes usarlo para administrar tus claves SSH y autenticarte en servidores remotos de forma más segura.

#### Habilitar el servicio OpenSSH Authentication Agent:

1. Abre la aplicación "Configuración" en Windows 10. Puedes hacerlo presionando la tecla `Win + I` o buscándola en el menú Inicio.

2. En la ventana de Configuración, selecciona "Aplicaciones".

3. En la columna de la izquierda, haz clic en "Aplicaciones y características".

4. Busca e ingresa a la opción "Características opcionales" y selecciona "Agregar una característica".

5. Se abrirá una ventana emergente de "Características opcionales" con una lista de características disponibles. Desplázate hacia abajo hasta encontrar "Cliente OpenSSH" y selecciónalo. Luego, haz clic en el botón "Instalar".

6. Espera a que Windows instale el cliente OpenSSH. Una vez que se complete la instalación, verás un mensaje de confirmación.

Ahora puedes crear claves SSH con la ayuda de la herramienta continuando desde [[6. Aprovisionamiento#^22b995|aquí]]