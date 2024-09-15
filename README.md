# hackmty2024

En primera instancia, esta no es una simple aplicación para agregar aquellas metas que te has propuesto, ya que además de tener función, nosotros en escalarla al siguiente nivel, por lo que se creó “INVICTOS”, una red social especializada en la interacción a través de tus hábitos, cuyo slogan es “Tan lejos como tú quieras llegar”.

En primera instancia, hemos de aclarar que en ningún momento se utilizó ninguna otra plataforma o lenguaje de programación más allá del ofrecido por Oracle APEX, por lo que, si bien no estábamos del todo familiarizados del todo con la plataforma, aún así conseguimos desarrollar una demo lo más cercana posible a nuestra idea original.

Así bien, si nosotros entramos a la aplicación de “INVICTOS”, nos aparece un Log in, donde un usuario ya registrado ingresa sus datos. Posteriormente, se nos redirige a la página de inicio, la cual contiene las publicaciones de los usuarios con los cuales eres amigo en la aplicación. Cada vez que cumplas una meta, podrás publicarlo en un feed compartido, donde otros podrán ver tu progreso, comentarlo y celebrarlo contigo.

Además, en esta misma página, es posible publicar una nueva foto, texto, dar like, e incluso eliminar alguna publicación siempre y cuando sea tuya.

Uno de nuestros apartados más importantes es aquel en el que es posible agregar un hábito a tu vida, en donde puedes incluso personalizarlo tanto como quieras en la descripción del mismo. Ya creado este hábito, éste se agrega tanto a tu gráfica de avance como a una lista con el resto de tus hábitos, la cual puedes revisar cuantas veces quieras.

Parte de esta experiencia como red social, es el poder ver también cómo van tus amigos, por lo que en su usuario, aparecerá su calificación con base en el promedio mostrado en la página de ADVANCE.

También es posible agregar nuevas tareas de tu día y visualizar mediante el calendario la fecha de inicio de cada una de ellas. 

A causa de los problemas técnicos que se nos presentan continuamente durante el uso de la plataforma, no se llegó a completar un prototipo de la idea original, en la cual también se buscaba una personalización aún mayor.

Por ejemplo, se buscaba implementar un chat uno a uno con alguno de tus amigos de la plataforma, en el cual ambos tienen la meta de completar un reto en común, en donde incluso podrías mostrarle fotos de tu progreso únicamente a este partner.

Se pretendía que cada usuario tuviera una experiencia personalizada en la cual diversas gráficas mostraran su progreso, así como el tiempo transcurrido desde que iniciaron su hábito, además de un diario en el cual podrían plasmar cómo se van sintiéndose acerca de su hábito, ya sea que lo mantuvieran privado o no.

En conclusión, INVICTOS busca ser una herramienta integral para ayudar a sus usuarios a crear, mantener y celebrar hábitos saludables, todo mientras interactúan con una comunidad de personas que comparten el mismo objetivo. Si bien el prototipo aún está en desarrollo, su potencial para convertirse en una plataforma clave en la creación de hábitos está claro

# Importación de Aplicación en Oracle APEX

Este documento proporciona instrucciones paso a paso para importar una aplicación de Oracle APEX utilizando un archivo `.sql` exportado.

## Prerrequisitos

Antes de comenzar, asegúrate de tener lo siguiente:

- Acceso a una instancia de Oracle APEX.
- Permisos adecuados para importar aplicaciones en Oracle APEX.
- Archivo `.sql` exportado de la aplicación APEX que deseas importar.

## Pasos para Importar una Aplicación en Oracle APEX

1. **Iniciar Sesión en Oracle APEX**:
   - Accede a tu entorno de Oracle APEX a través del navegador web.
   - Introduce tus credenciales de usuario (Workspace, Usuario, Contraseña) para iniciar sesión.

2. **Navegar a App Builder**:
   - Una vez dentro de Oracle APEX, selecciona el **Workspace** en el que deseas importar la aplicación.
   - Haz clic en **App Builder** en el menú principal.

3. **Seleccionar la Opción de Importación**:
   - En la página de **App Builder**, haz clic en el botón **Import** ubicado en la parte superior derecha de la pantalla.

4. **Subir el Archivo de Exportación (.sql)**:
   - Selecciona la opción **From File** para importar desde un archivo.
   - Haz clic en el botón **Choose File** y selecciona el archivo `.sql` exportado de tu aplicación APEX.

5. **Configurar las Opciones de Importación**:
   - Una vez que hayas subido el archivo, puedes configurar las siguientes opciones:
     - **Application ID**: Puedes mantener el ID original de la aplicación o generar uno nuevo. Selecciona `Auto Assign New Application ID` si no deseas sobrescribir ninguna aplicación existente.
     - **Build Status**: Asegúrate de que esté configurado como `Run and Build Application` para poder ejecutar y editar la aplicación.
   
6. **Iniciar el Proceso de Importación**:
   - Haz clic en el botón **Next** para proceder con la importación.
   - Revisa la información y confirma haciendo clic en **Install Application**.

7. **Verificación de la Importación**:
   - Una vez completada la importación, deberías ver un mensaje de éxito indicando que la aplicación se ha importado correctamente.
   - Ve al **App Builder** para verificar que la aplicación esté visible en la lista de aplicaciones.

8. **Probar la Aplicación Importada**:
   - Haz clic en el nombre de la aplicación importada para abrirla.
   - Haz clic en el botón **Run** (Reproducir) para ejecutar la aplicación y verificar que todo funcione correctamente.

## Problemas Comunes

- **Error de Cuota de Espacio Excedido (`ORA-01536`)**: Asegúrate de que el usuario tenga suficiente cuota de espacio en el *tablespace*. Contacta a un DBA si es necesario.
- **Problemas de Conectividad**: Asegúrate de que el servidor de APEX sea accesible y de que tienes permisos adecuados.

## Notas Adicionales

- Siempre realiza una copia de seguridad de tus datos y configuraciones antes de importar nuevas aplicaciones.
- Verifica la versión de Oracle APEX en tu entorno para asegurarte de que sea compatible con la aplicación exportada.

## Conclusión

Siguiendo estos pasos, puedes importar fácilmente aplicaciones en Oracle APEX utilizando archivos `.sql` exportados. Este proceso es esencial para migrar aplicaciones entre entornos o restaurar aplicaciones desde copias de seguridad.

##LINK DEL VíDEO DE PRESENTACIÓN

https://github.com/Checo894/hackmty2024
