Este documento te guiará a través de los pasos para agregar una clave SSH y autorizarla para usar con una organización en GitHub. Asumimos que ya tienes una clave SSH pública en tu portapapeles ya que la [[6. Aprovisionamiento#^75db08|herramienta de aprovisionamiento]] te ha llevado hasta este punto.

#### Paso 1: Iniciar Sesión en tu Cuenta de GitHub

Si aún no tienes la sesión iniciada en GitHub, la pagina a la cual se te dirigió te solicitará que lo hagas. La cuenta debe pertenecer a la organización de EXO. Si necesitas ayuda con esto debes solicitarlo al área de sistemas.

#### Paso 2: Agregar la Clave SSH a tu Cuenta de GitHub

En esta instancia te encontrarás en la sección para agregar llaves SSH `SSH and GPG keys`.
Haz clic en el botón `New SSH key` y sigue los siguientes pasos para agregar la llave:

![[49a5d4e7-18f8-4b81-aa3e-4e7a394f7c1a.png]]

1. En el campo `Title`, puedes darle un nombre descriptivo a tu clave SSH (por ejemplo, "Mi Clave SSH para aprovisionamiento de credenciales").

2. En el campo `Key`, pega la clave SSH pública que tienes en tu portapapeles.

3. Haz clic en el botón `Add SSH key` para guardar la clave.

![[72e2f0d8-07c5-4d2a-b1ac-9a0c1c74ab7e.png]]
#### Paso 3: Autorizar la Clave SSH para una Organización

1. Luego de agregar la llave, regresaras a la pagina anterior. Allí haz click en el menú desplegable `Configure SSO`.

2. Haz clic en la organización para la cual deseas autorizar la clave SSH en el botón `Authorize`.

![[88b1f1c9-51ec-45a3-9db4-c2f6e61b72a2.png]]

¡Listo! Ahora has agregado tu clave SSH y la has autorizado para usar con una organización en GitHub. Puedes utilizar esta clave SSH para acceder al repositorio de credenciales de manera segura. Ahora regresa a la herramienta de aprovisionamiento y presiona `enter` para indicar que esta acción ya ha sido realizada. Continua con la guía desde [[6. Aprovisionamiento#^89cd6f|aquí]].

