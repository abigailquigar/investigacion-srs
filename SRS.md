# SRS – BusTrack

## Requerimientos del sistema

### 3.1 Requerimientos funcionales

**RF-01. Visualización de ubicación del autobús**

- **ID:** RF-01
- **Descripción:** El sistema deberá mostrar en un mapa la ubicación actual del autobús en tiempo real.
- **Prioridad:** Alta.
- **Criterio de aceptación:** El usuario podrá visualizar la posición del autobús en el mapa.

**RF-02. Actualización de ubicación**

- **ID:** RF-02
- **Descripción:** El sistema deberá actualizar automáticamente la ubicación de los autobuses.
- **Prioridad:** Alta.
- **Criterio de aceptación:** La posición mostrada deberá actualizarse cuando el autobús cambie de ubicación y se reciban nuevos datos GPS.

**RF-03. Visualización de rutas**

- **ID:** RF-03
- **Descripción:** El sistema deberá mostrar las rutas disponibles de los autobuses.
- **Prioridad:** Alta.
- **Criterio de aceptación:** El usuario podrá consultar las rutas disponibles dentro de la aplicación.

**RF-04. Identificación de autobuses**

- **ID:** RF-04
- **Descripción:** El sistema deberá identificar cada autobús mediante un código o número asignado.
- **Prioridad:** Media.
- **Criterio de aceptación:** El usuario podrá distinguir los autobuses mostrados en el mapa mediante su identificador.

**RF-05. Consulta de transporte cercano**

- **ID:** RF-05
- **Descripción:** El sistema deberá permitir al usuario consultar los autobuses cercanos a una ubicación seleccionada.
- **Prioridad:** Alta.
- **Criterio de aceptación:** Al seleccionar una ubicación, el sistema mostrará los autobuses cercanos cuando exista información disponible.

###  Requerimientos no funcionales

**RNF-01. Seguridad y privacidad**

- **ID:** RNF-01
- **Descripción:** El sistema no deberá solicitar datos personales de los usuarios para consultar las ubicaciones de los autobuses.
- **Prioridad:** Alta.
- **Criterio de aceptación:** El usuario podrá consultar el mapa y las rutas sin registrarse ni proporcionar información personal.

**RNF-02. Rendimiento**

- **ID:** RNF-02
- **Descripción:** La aplicación deberá cargar el mapa y mostrar la información de ubicación de manera rápida.
- **Prioridad:** Alta.
- **Criterio de aceptación:** El mapa deberá mostrarse en un máximo de 5 segundos bajo condiciones normales de conexión.

**RNF-03. Disponibilidad**

- **ID:** RNF-03
- **Descripción:** El sistema deberá estar disponible para los usuarios durante el funcionamiento del servicio de transporte.
- **Prioridad:** Alta.
- **Criterio de aceptación:** El usuario podrá acceder a la aplicación siempre que el servicio y la conexión estén disponibles.
