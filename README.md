# hackmty2024

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

