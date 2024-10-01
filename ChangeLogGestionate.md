# Gestionate ChangeLog
Registro e historial de cambios y actualizaciones del proyecto GESTIONATE

## Versión: 1.3.1
### 16/1/23
#
### **Added** (Se agregó)
- Filtros en la cantidad de días para NOVEDADES
- Leyenda "NO HAY NOVEDADES", cuando no las hay para RRHH y LIDER
-  IDs en los elementos de la app

### **Changed** (Se cambió)
- Dimensiones de visualización los comprobantes en COMPROBANTES
- Se movio botón de AGREGAR COMPROBANTES hacia esquina superior derecha
- Logica para que, Rol COLABORADOR, pueda visualizar novedades en estado OBSERVADA en LEGAJO
- Refactorización del código, en el componente de NOVEDAD

### **Fixed** (arreglado)
- En comprobantes, cuando se carga uno, se visualiza al instante
- En NOMINA, se alinearon los números de los empleados del menú
- Error que existía con las contraseñas en el login de la app
---- 


## Versión: 1.3.2
### 22/2/23
#
### **Added** (Se agregó)
- Bloqueó el botón de “Agregar Comprobantes ” en estado "Solo lectura"
- En “Novedades por Equipo” al cliquear en “Agregar Novedad (➕)”,se puede buscar a los colaboradores por nombre.

### **Changed** (Se cambió)
- Responsive en la sección de “Agregar comprobantes”

### **Breaking** (se quitó)
- Leyenda de “Configuración“ para los usuarios de tipo “Líder” y “Colaborador”
- Botón de “Eliminar comprobantes” (🗑️) cuando las novedades se encuentran en estado de “Solo lectura"

----
## Versión: 1.3.3
### 22/3/23
#
### **Added** (Se agregó)
- Sincronización de los conceptos
- Boton de "Activos" para filtrar los CONCEPTOS ACTIVOS 
- Leyenda de “Marque los ítems a sincronizar y acepte los cambios" en "Sincronizar en Conceptos"
- Botón de “Aceptar los cambios”, que se encarga de sincronizar aquellos ítems seleccionados. 
- Posibilidad de cambiar el estado de los conceptos, activos e inactivos (tocando el lápiz)
- Etiquetas (Activos, Inactivos y modificada) a los conceptos
- Medidas para realizar la exportación a tango, la misma cuenta con el botón de “Exportar a Tango” , la selección del tipo de novedad (Común o Adelantó), el formato (TXT o Excel) y en caso de seleccionar la opción de adelanto, vas a poder elegir las fechas (Dia 15 o dia 25)

### **Changed** (Se cambió)
- Cartel de "Error 404”
- Actualización del listado de conceptos

----
## Versión: 1.3.4
### 19/4/23
#
### **Added** (Se agregó)
- Spinner en el login, debajo del boton Ingresar 
- Rol de usuario ADMIN
- Seccion MANTENIMIENTO para ADMIN
- Selector que permite cambiar el período de "Sólo lectura"
- 2 selectores que modifican las fechas de ADELA
- Boton que pone la app en MANTENIMIENTO, solo va poder acceder a la app el ADMIN

### **Changed** (Se cambió)
- Validación de fechas apuntando al servidor para realizar las validaciones 
- Ver en el login la versión del autenticador
- En el área de Conceptos, el ADMIN puede habilitarlos o deshabilitarlos, el RRHH solo puede editarlos.

----
## Versión: 1.3.5
### 17/5/23
#
### **Added** (Se agregó)
- Sección de ayuda para los campos de "Configuración" del rol ADMIN
- Carpetas, donde se guardan todos los comprobantes por Fecha y por Cuil, que a su vez poseen subcarpetas de los distintos Cuils y las distintas Fechas

### **Changed** (Se cambió)
- Nombres de todos los comprobantes, este nuevo nombre incluye: ID de la novedad, Año, Mes, Cuil y Legajo

### **Fixed** (arreglado)
- Texto largo en observación de novedad  
- ADELA en exportacion de TXT

----
## Versión: 1.3.6
### 19/7/23
#
### **Added** (Se agregó)
- Dashboard PERSONAL para TODOS los usuarios
- Dashboard EQUIPO, para los LIDERES
- Dashboard RRHH, para los usuarios RRHH
- Sección NOTAS en las NOVEDADES, es una mensajería asincrónica

### **Changed** (Se cambió)
- Automatización de ETL (Tecnología)

### **Fixed** (arreglado)
- Spinner en cambio de estado de NOVEDAD

----
## Versión: 1.3.7
### 31/8/23
#
### **Added** (Se agregó)
- Filtro por empresa en listado de novedades nuevas en DASHBOARD RRHH
- Tango Delta 2
- Validación de conceptos de novedades de acuerdo al género

### **Changed** (Se cambió)
- Refactorizacion de los ETL (se incluyó la jornada reducida y completa)
- Leyenda al cargar comprobantes

### **Fixed** (arreglado)
- Bug rol LIDER, en crear novedades a los colaboradores desde equipo

----
## Versión: 1.3.8
### 15/9/23
#
### **Added** (Se agregó)
- En DASHBOARD PERSONAL, la tarjeta de “Saldo Dias de Estudio”
- En DASHBOARD RRHH, lista de "saldos de días de vacaciones", con un filtro por empresa y etiquetas color rojo para colaboradores que poseen menos de 6 meses en la empresa

### **Changed** (Se cambió)
- En CONTROL DE NOVEDADES, se comenzó a mostrar el detalle de la Novedad completa

### **Breaking** (se quitó)
-  En DASHBOARD PERSONAL, el formulario de solicitud de reunión

----
## Versión: 1.3.9
### 12/10/23
#
### **Added** (Se agregó)
- Validaciones al crear novidad tipo: "Matrimonio", "Excedencia", "Maternidad" y "Estudio"
- Nota de "error de usuario/contraseña" en el LOGIN

### **Breaking** (se quitó)
- Ordenamiento por “Impte/Cant y Certif.” en NOVEDADES POR EQUIPO
- Ordenamiento por "Departamento" en EQUIPO 

### **Fixed** (arreglado)
- Error de respuesta al sincronizar colaboradores (falta de datos en el legajo)
- Importador de CSV en “Novedades Externas”, con apellidos de 3 letras y con "Ñ"

----
## Versión: 1.3.9v2
### 07/11/23
#
### **Added** (Se agregó)
- Cartel de inactividad, que desloguea al usuario de la app
- Pop-up que notifica la fecha de cobro del adelanto de sueldo
- Responsive a la ventana “Notas”  de las novedades. 

### **Changed** (Se cambió)
- Ubicacion del numero de versión de la app

### **Breaking** (se quitó)
- Las novedades de “Lic. Familiar Enfermo” y “Lic Matrimonio” de la exportación del TXT

### **Fixed** (arreglado)
- Saldos de vacaciones, con nueva logica (redondea saldo a favor del colaborador)
- Bug de scroll en ventana de Novedades Nuevas en Dashboard
- Diferencias del cálculo de antigüedad

----
## Versión: 1.3.10
### 12/12/23
#
### **Added** (Se agregó)
- Guardado automático al subir comprobantes
- Actualización  versión de FUSE para rol COLABORADOR

### **Changed** (Se cambió)
- Autenticador Fava-auth
- Envío de mails con cuenta corporativa 

### **Fixed** (arreglado)
- Boton "EDITAR" repetido en novedad "A CORREGIR"
- Base de Datos, tabla ORIGEN NOVEDAD con formato de fechas erróneo.

----
## Versión: v1.24.S12
### 16/05/24
#
### **Added** (Se agregó)
- Servidor de testing.
- Boton ‘Cambio de Roles’ para usuarios: RRHH y LÍDER.
- Envio de mail de novedad RECHAZADA a colaborador y líder.

### **Changed** (Se cambió)
- Actualización del nuevo FUSE. 
- Actualización ANGULAR.
- Actualización versión JAVA.

### **Fixed** (arreglado)
- Se corrigió error al estar redactando una novedad observada que la app te expulsaba por inactividad.
- Al EDITAR CONCEPTO, cuando se editaba la ‘Cantidad máxima’, se debía seleccionar nuevamente la UNIDAD para que se habilite el botón de GUARDAR.
- Error visual en CONCEPTOS, al visualizar en la tabla, la columna de CANTIDAD, se visualizaban mal algunos valores.

----
## Versión: v1.24.S13
### 17/07/24
#
### **Added** (Se agregó)
- Al AGREGAR NOVEDAD, en estado ACEPTADA, el usuario se encuentra con un cartel que le informa que no puede subir comprobante. 
- Usuario LIDER tiene que ir a su perfil de COLABORADOR para CREAR NOVEDADES propias.
- Luego del cierre de novedades(25 al 30/31), se pueden crear novedades pero para el siguiente periodo. 

### **Changed** (Se cambió)
- Modificacion en tamaño de letras e idiomas en Pop-ups.
- Se fusionaron 2 departamentos: RED COMERCIOS (ADM. COM/ PROM COMER).
- Modificaciones en base de datos (FK)
- Refactorización  en el componente NOVEDAD.
- Modificaciones en ORIGENES, ahora los departamentos deshabilitados no aparecen en el desplegable.

### **Fixed** (arreglado)
- Mails a 'LIDERES', que llegaban duplicados.
- Correcciones UX-UI en: Ayuda colaborador, letra negrita en error de contraseñas y nombres de empresas RRHH.
- Correcciones en el SINCRONIZADOR.
- Novedades exportadas con tipo CUALI.
- Sincornizador de ORIGENES, fallaba por foco de MATERIAL.

----
## Versión: v1.24.S14
### 05/09/24
#
### **Added** (Se agregó)
- Pop-Up en CREAR NOVEDAD en periodo SOLO LECTURA, para avisar a los usuarios que la novedad que van a crear será creada en el siguiente periodo.

### **Changed** (Se cambió)
- En  ORÍGENES, los departamentos DESHABILITADOS, no aparecerán en la lista desplegable de NOVEDADES POR EQUIPO. 
- Renombrado de la Base de Datos: GESTIONATE.

### **Breaking** (se quitó)
- Bases de Datos que no se utilizan en PRODUCCIÓN.
- Archivos en TOMCAT de PREPROD.


### **Fixed** (arreglado)
- Las acciones que el LÍDER puede realizar en periodo de SOLO LECTURA: novedades OBSERVADAS, puede EDITAR, DESHACER y ACEPTAR/ RECHAZAR. COLABORADOR con novedad A CORREGIR, puede EDITAR/ ELIMINAR y quedar en estado NUEVA (editable).
- Correcciones visuales en Crear Novedad.
- Servicio de SINCRONIZAR que se llamaba 2 veces.
- Correcciones del lado de backend en el SINCRONIZADOR (renombre base de datos).
- Correcciones tabla ORIGENES.
- Correcciones USUARIOS REPETIDOS.


