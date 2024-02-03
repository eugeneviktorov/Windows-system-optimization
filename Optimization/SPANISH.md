### Configuración General <br> ¡TEN CUIDADO, TODAS LAS ACCIONES SE REALIZAN BAJO TU PROPIO RIESGO!

### Desactivación del Control de Cuentas de Usuario

En la búsqueda de "Panel de Control", selecciona "Iconos pequeños". "Cuentas de usuario", "Cambiar la configuración de Control de cuentas de usuario", cambia a "No recomendado".
<br><br>

### Panel de Control

ACTUALIZACIÓN: ¡No olvides aplicar!
Selecciona "Iconos pequeños", elige "Centro de Accesibilidad":
Desmarca "Leer siempre en voz alta" y "Desplazarse siempre por esta sección".

- Optimización de imágenes en pantalla - desmarca todas las casillas.
- Facilitar el uso del teclado:<br>
  / Configuración del controlador de puntero - desmarca todas las casillas y debajo de BLOQ NUM: desactivar;<br>
  / Configuración de repetición de teclas - desmarca todas las casillas;<br>
  / Configuración de filtros de entrada - desmarca todas las casillas.
- Uso de texto o imágenes en lugar de sonidos - selecciona "No".
- Facilitar el uso de paneles táctiles y tabletas - cambia "Narrador de pantalla" a "No" (si no hay una tableta y no hay restricciones de audición y visión).
  <br><br>

### Desactivación de la indexación de disco.

ACTUALIZACIÓN: ¡ATENCIÓN! Toma un tiempo prolongado.
Abre "Este equipo", haz clic derecho en el disco (C:), "Propiedades", desmarca la casilla "Permitir que se indexen los archivos del contenido" - "Aplicar" / "al disco y todos los archivos anidados" / "omitir todo".
<br><br>

### Lista de servicios que se pueden desactivar en Windows (operan en modo automático)

ACTUALIZACIÓN: Los servicios se recopilan de Windows 10-11, algunos de ellos pueden no estar en la versión 10 o 11, ten en cuenta este factor.<br>
Designaciones:<br>
(•) - desactivación solo para usuarios experimentados.<br>
(\*) - servicios que se pueden desactivar.<br>

| #   | Nombre del Servicio                                          | Propiedad                                                                             |
| --- | :----------------------------------------------------------- | :------------------------------------------------------------------------------------ |
| \*  | Servicio de Salud de Actualización de Microsoft              | Si has eliminado el programa Servicio de Salud de Actualización de Microsoft          |
| \*  | Superfetch o SysMain                                         | Se puede desactivar si se utiliza SSD y la cantidad de RAM es superior a 8GB          |
| •   | Servicio de Remedios de Windows                              | Si no usas actualizaciones de Windows                                                 |
| •   | Búsqueda de Windows                                          | Si no buscas archivos mediante la búsqueda                                            |
| •   | Servicio Biométrico de Windows                               | Si no utilizas contraseñas, PIN, huellas dactilares, Windows Hello                    |
| •   | Monitor de Integridad del Sistema Guard                      | Si no utilizas la verificación de la integridad de los archivos del sistema           |
| \*  | Servicio Auxiliar IP                                         | Si no utilizas el protocolo IPv6                                                      |
| \*  | Administrador de Impresión                                   | Si no tienes impresora y no utilizas funciones de impresión, incluyendo en PDF        |
| \*  | Administrador de Conexión de Acceso Remoto                   | Si no utilizas acceso remoto a través de VPN                                          |
| \*  | Administrador de Tarjetas Descargadas                        | Si no utilizas tarjetas de Windows                                                    |
| •   | Administrador de Credenciales Web                            | Si no utilizas Microsoft Store y las aplicaciones descargadas de él                   |
| •   | Aislamiento de claves CNG                                    | Si no utilizas contraseñas, PIN, huellas dactilares, Windows Hello                    |
| \*  | Uso de datos                                                 | Si no utilizas información de tráfico                                                 |
| •   | Cliente de Seguimiento de Enlaces Cambiados                  | Si no utilizas la transferencia de archivos NTFS en la red local                      |
| •   | Soporte de NetBIOS sobre TCP/IP                              | Si no utilizas la red local                                                           |
| \*  | Optimización de Entrega                                      | Si no utilizas actualizaciones de Windows                                             |
| \*  | Asistente de Inicio de Sesión de Microsoft                   | Si no utilizas productos de Microsoft                                                 |
| \*  | Nodo de Sincronización                                       | Si no utilizas correo de Windows y no has iniciado sesión con una cuenta de Microsoft |
| \*  | Servicio de Datos del Sensor                                 | Si no utilizas una tableta con Windows                                                |
| \*  | Servicio del Sensor                                          | Si no utilizas una tableta con Windows                                                |
| •   | Servicio de Caché de Fuentes de Windows                      | Si no actualizas Microsoft Office                                                     |
| \*  | Servicio de Licencias de Cliente (ClipSVC)                   | Si no utilizas Microsoft Store y las aplicaciones descargadas de él                   |
| \*  | Servicio de Supervisión de Sensores                          | Si no utilizas una tableta con Windows                                                |
| •   | Servicio de Plataforma de Dispositivos Conectados            | Si no utilizas: Escritorios virtuales, Cronología, Tu teléfono y Luz nocturna         |
| •   | Servicio de Usuario de Plataforma de Dispositivos Conectados | Si no utilizas: Escritorios virtuales, Cronología, Tu teléfono y Luz nocturna         |
| \*  | Servicio de Almacenamiento                                   | Si no utilizas Microsoft Store y las aplicaciones descargadas de él                   |
| •   | Nodo de Diagnóstico de Servicio                              | Si no utilizas el diagnóstico del equipo a nivel del sistema operativo                |
| \*  | Funcionalidades de Conexión de Usuarios                      | Recopilación y seguimiento de datos por parte de Microsoft                            |
| \*  | Centro de Actualización de Windows                           | Si no utilizas actualizaciones de Windows, Microsoft Store                            |

<br>

### Corrección del Cambio Automático de Brillo

Información para portátiles con procesadores Intel:
Si la luminosidad fluctúa al desconectar el cable de carga, debes abrir el "Centro de control gráfico de Intel", seleccionar "Sistema", "Energía" y en la sección "Ahorro de energía de la pantalla" desactivar el interruptor.
<br><br><br><br><br><br><br><br><br><br>

# Windows 10 <br> ¡TEN CUIDADO, TODAS LAS ACCIONES SE REALIZAN BAJO TU PROPIO RIESGO!

### Desactivación de las Notificaciones del Firewall de Windows o Windows Defender

Presiona Win + R, escribe regedit y pulsa Enter.<br>
En la ruta: Computadora\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender Security Center\Notifications<br>
En una ventana vacía, haz clic derecho, elige "Nuevo" y luego "Valor DWORD (32 bits)". Nómbralo DisableNotifications.<br>
Luego, abre el valor con doble clic y asigna el valor 1. Aplica y reinicia la PC.
<br><br>

### Configuración de Propiedades del Sistema

ACTUALIZACIÓN: ¡No olvides aplicar!<br>
En "Este PC", haz clic derecho y selecciona "Propiedades".<br>
En el menú contextual, abre "Configuración avanzada del sistema".

- Nombre de la computadora / según tu preferencia para cambiar el nombre.
- Avanzado / puedes desactivar todo en Rendimiento, pero no afectará significativamente el sistema. También puedes usar "Lograr el mejor rendimiento" incluso en PC menos potentes.
- Protección del sistema / habilitar protección para la unidad local (C:) (Sistema) y asignar de 7 a 12 GB de memoria.
- Acceso remoto (Si no deseas conexiones externas a tu PC, puedes desactivarlo).
  <br><br>

### PROGRAMA "Configuración"

#### 1. Sistema

- Notificaciones y acciones (puedes desactivarlo según tu preferencia) / también puedes editar las fichas de acciones rápidas según sea necesario.
- Enfoque asistido (se recomienda para usuarios avanzados)
  Desactiva todos los interruptores y marcas. En este menú, "Configurar lista de prioridades", desactiva los interruptores y elimina todas las aplicaciones.
- Energía y suspensión, configura los valores según tus necesidades / En este menú, "Configuración adicional", se abrirá el Panel de control de energía, donde puedes seleccionar Alto rendimiento (esto consumirá más batería en portátiles).
- Memoria / Desactiva la "Función de control de memoria".
- Tableta o Modo tableta (Aplica si la pantalla no es táctil): Nunca uses el Modo tableta / Solicitar permiso antes de cambiar de modo. En el mismo menú, "Cambiar configuración adicional de la tableta" y desactiva todos los interruptores.
- Multitarea: desactiva la línea de tiempo.
- Opciones comunes: Transmisión entre dispositivos, desactívalo (si no usas la conexión en línea entre PC y smartphone).
- Portapapeles: desactiva todos los interruptores y borra los datos. ACTUALIZACIÓN: (El portapapeles seguirá funcionando cuando uses Ctrl + C).

#### 2. Personalización

- Colores / Desactiva el efecto de transparencia.
- Pantalla de bloqueo: desactiva todos los interruptores.
- Temas / Puedes habilitar los iconos "Este PC" y "Papelera".

#### 3. Aplicaciones

- Aplicaciones y características: desinstala las aplicaciones preinstaladas que no necesitas.
- Aplicaciones predeterminadas: configúralo según tus necesidades.
- Mapas sin conexión: desactiva todos los interruptores y usa "Eliminar todos los mapas".
- Inicio: puedes desactivar programas que se inician con la PC.

#### 4. Juegos

- Barra de juego de Xbox: desactiva todos los interruptores.
- Grabaciones: si no usas la grabación de pantalla, desactiva todos los interruptores.
- Modo de juego: actívalo.

#### 5. Funciones de Accesibilidad

- Narrador de pantalla: desactiva todos los interruptores (si no usas el narrador).
- Funciones de voz: desactiva todos los interruptores.
- Teclado: desactiva todos los interruptores.
- Ratón: desactiva todos los interruptores.

#### 6. Privacidad

ACTUALIZACIÓN: No olvides hacer clic en "Cambiar" y ajustar el interruptor según la situación.

- General: desactiva todos los interruptores excepto "Permitir que Windows rastree los lanzamientos de aplicaciones".
- Funciones de voz: desactiva todos los interruptores.
- Personalización de entrada manuscrita: desactiva todos los interruptores.
- Diagnóstico y comentarios: selecciona "Datos de diagnóstico necesarios". Luego, desactiva todos los elementos. Frecuencia de generación de comentarios (nunca). Eliminar datos de diagnóstico.
- Registro de actividades: desactiva todos los interruptores y elimina el registro de actividades.

<br>

ACTIVA O DESACTIVA TODOS LOS PERMISOS EN ESTAS RESOLUCIONES:

| Nombre de la Resolución       | Acción     |
| :---------------------------- | ---------- |
| Ubicación                     | ACTIVAR    |
| Cámara                        | ACTIVAR    |
| Micrófono                     | ACTIVAR    |
| Activación por voz            | Desactivar |
| Información de la cuenta      | Desactivar |
| Contactos                     | Desactivar |
| Calendario                    | Desactivar |
| Llamadas telefónicas          | Desactivar |
| Historial de llamadas         | Desactivar |
| Correo electrónico            | Desactivar |
| Tareas                        | Desactivar |
| Mensajería                    | Desactivar |
| Radio                         | Desactivar |
| Otros dispositivos            | Desactivar |
| Aplicaciones en segundo plano | Desactivar |
| Diagnóstico de aplicaciones   | Desactivar |
| Descargas automáticas         | Omitir     |
| Documentos                    | ACTIVAR    |
| Imágenes                      | ACTIVAR    |
| Vídeos                        | ACTIVAR    |
| Sistema de archivos           | ACTIVAR    |

<br>

#### 7. Actualización y seguridad

- Centro de actualizaciones de Windows, dentro de "Configuración adicional" desactiva todos los interruptores. Y dentro de "Optimización de entrega", desactiva la descarga desde otros PCs.
  <br><br>

### Desactivación de Microsoft Defender

Para desactivar Microsoft Defender, abre "Configuración" / "Actualización y seguridad"

/ "Seguridad de Windows" / "Abrir Seguridad de Windows".
"Protección contra virus y amenazas" / "Administrar configuración" y desactiva todos los interruptores.
ACTUALIZACIÓN: después de reiniciar la PC, Defender se volverá a activar.
<br><br><br><br><br><br><br><br><br><br>

# Windows 11 <br> ¡TEN CUIDADO, TODAS LAS ACCIONES SE REALIZAN BAJO TU PROPIO RIESGO!

### Configuración de Propiedades del Sistema

ACTUALIZACIÓN: ¡No olvides aplicar!
Haz clic derecho en "Este PC" y selecciona "Propiedades".
Se abrirán las configuraciones, busca "Enlaces relacionados" y abre "Configuración avanzada del sistema".

- Nombre de la computadora / según tu preferencia para cambiar el nombre.
- Avanzado / puedes desactivar todo en Rendimiento, pero no afectará significativamente el sistema. También puedes usar "Lograr el mejor aspecto" incluso en PC menos potentes.
- Protección del sistema / Habilita la protección para el disco local (C:) (Sistema) y asigna de 7 a 12 GB de memoria.
- Acceso remoto (Si no deseas conexiones externas a tu PC, puedes desactivarlo).

---

### PROGRAMA "Configuración"

#### 1. Sistema

- Notificaciones (Puedes desactivarlas según tu preferencia, pero es mejor dejarlas).
- Energía y suspensión, configura los valores según tus necesidades / En este mismo menú, selecciona "Modo de energía" y elige "Máximo rendimiento" (esto consumirá más batería en portátiles).
- Memoria / Desactiva la "Función de control de la memoria".
- Intercambio con dispositivos cercanos - Desactiva (Si no usas la conexión en línea entre PC y smartphone).
- Solución de problemas - Cambia a "Preguntarme antes de solucionar problemas".
- Portapapeles, desactiva "Historial del portapapeles" y limpia los datos. ACTUALIZACIÓN: (El portapapeles seguirá funcionando cuando uses Ctrl + C).

#### 2. Personalización

- Colores / Desactiva el "Efecto de transparencia".
- Temas / Puedes habilitar los iconos "Este PC" y "Papelera".
- Pantalla de bloqueo / Desactiva todas las casillas y los interruptores. Estado de la pantalla de bloqueo - "Ninguno".
- Menú Inicio / Utiliza "Más anclado". Desactiva todos los interruptores.
- Barra de tareas / Puedes desactivar todos los interruptores según tu preferencia.
- Uso del dispositivo / Desactiva todos los interruptores.

#### 3. Aplicaciones

- Aplicaciones instaladas - desinstala los programas preinstalados que no necesitas.
- Aplicaciones predeterminadas: configúralo según tus necesidades.
- Mapas sin conexión - Desactiva los interruptores. "Actualizar mapas" desmarca "Actualizar automáticamente".
- Inicio - puedes desactivar los programas que se inician con la PC.

#### 4. Juegos

- Xbox Game Bar - Desactiva.
- Grabaciones - si no usas la grabación de pantalla, desactiva todos los interruptores.
- Modo de juego - Activa.

#### 5. Funciones Especiales

- Narrador de pantalla - Desactiva todos los interruptores y las marcas (si no usas el narrador).
- Funciones de voz - Desactiva todos los interruptores y las marcas.
- Teclado - Desactiva todos los interruptores y las marcas. ACTUALIZACIÓN: "Usar la tecla Impr Pant para abrir recortes" puedes dejarlo según tu preferencia.
- Ratón - Desactiva todos los interruptores y las marcas.

#### 6. Privacidad

- General - Desactiva todos los interruptores excepto "Permitir que Windows rastree los lanzamientos de aplicaciones".
- Funciones de voz - Desactiva todos los interruptores y las marcas.
- Personalización de entrada manuscrita - Desactiva todos los interruptores y las marcas. "Borrar el diccionario de usuario".
- Diagnóstico y comentarios - Desactiva todos los interruptores y las marcas, y "Eliminar datos de diagnóstico". Frecuencia de comentarios (nunca).
- Registro de actividades - Desactiva todos los interruptores y las marcas. Limpia el registro de actividades.

<br>

ACTIVA O DESACTIVA TODOS LOS PERMISOS EN ESTAS RESOLUCIONES:

| Nombre de la Resolución       | Acción     |
| :---------------------------- | ---------- |
| Ubicación                     | ACTIVAR    |
| Cámara                        | ACTIVAR    |
| Micrófono                     | ACTIVAR    |
| Activación por voz            | Desactivar |
| Notificaciones                | ACTIVAR    |
| Información de la cuenta      | Desactivar |
| Contactos                     | Desactivar |
| Calendario                    | Desactivar |
| Llamadas telefónicas          | Desactivar |
| Historial de llamadas         | Desactivar |
| Correo electrónico            | Desactivar |
| Tareas                        | Desactivar |
| Mensajería                    | Desactivar |
| Radio                         | Desactivar |
| Otros dispositivos            | Desactivar |
| Diagnóstico de aplicaciones   | Desactivar |
| Descargas automáticas         | Omitir     |
| Documentos                    | ACTIVAR    |
| Carpeta de descargas          | ACTIVAR    |
| Colección de música           | ACTIVAR    |
| Imágenes                      | ACTIVAR    |
| Vídeos                        | ACTIVAR    |
| Sistema de archivos           | ACTIVAR    |
| Recorte de pantalla           | ACTIVAR    |
| Recortes de pantalla y aplic. | ACTIVAR    |

#### 7. Centro de Actualización de Windows

- Desactiva todos los interruptores dentro de "Configuración avanzada". Y dentro de "Optimización de la entrega", desactiva la opción de descarga desde otros PCs.

---

### Desactivación de Microsoft Defender

Para desactivar Microsoft Defender, abre "Configuración" / "Privacidad y seguridad" / "Seguridad de Windows" / "Abrir la Seguridad de Windows".
"Protección contra virus y amenazas" / "Administrar configuración", desactiva todos los interruptores.
ACTUALIZACIÓN: después de reiniciar la PC, Defender se volverá a activar.
