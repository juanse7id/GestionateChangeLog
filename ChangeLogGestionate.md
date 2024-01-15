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
