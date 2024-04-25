# modulo_de_usuarios

# COMPONENTES
proyecto
|-- frontend-nextjs
|   |-- components
|   |   |-- procesos
|   |   |   |-- gestion-usuarios                            # (res_users) 
|   |   |   |   |-- UserManagement                          # Componente
|   |   |   |   |-- UserForm.js                             # Formulario
|   |   |   |-- gestion-grupos-usuarios                     # (res_groups)
|   |   |   |   |-- GroupManagement                         # Componente
|   |   |   |   |-- GroupForm.js                            # Formulario
|   |   |   |-- gestion-contactos-comerciales               # (res_partner)  
|   |   |       |-- BusinessContactManagement               # Componente
|   |   |       |-- BusinessContactForm.js                  # Formulario
|   |   |-- ajustes
|   |   |   |-- configuracion-permisos                      # (ir.model.access)   
|   |   |   |   |-- PermissionConfiguration                 # Componente
|   |   |   |   |-- PermissionForm.js                       # Formulario
|   |   |   |-- configuracion-empresa                       # (res_company)
|   |   |   |   |-- CompanyConfiguration                    # Componente
|   |   |   |   |-- CompanyForm.js                          # Formulario
|   |   |   |-- configuracion-reglas-acceso                 # (ir.rule)    
|   |   |       |-- AccessRuleConfiguration                 # Componente
|   |   |       |-- AccessRuleForm.js                       # Formulario
|   |   |-- reportes
|   |       |-- registro-actividades                       # (res_users_log)
|   |       |   |-- ActivityLog                            # Componente
|   |       |-- auditoria-usuario                          # (res_users_deletion)
|   |           |-- UserAudit                              # Componente 


# PAGES 
proyecto
|-- frontend-nextjs
|   |     |-- pages
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                      # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 

# HOOKS 
proyecto
|-- frontend-nextjs
|   |-- hooks
 |           |   |-- gestion-usuarios                   # (res_users) 
|            |   |-- gestion-grupos-usuarios                         # (res_groups)
|            |   |-- gestion-contactos-comerciales      # (res_partner) 
|            |   |-- configuracion-permisos             # (ir.model.access)   
|            |   |-- configuracion-empresa              # (res_company)
|            |   |-- configuracion-reglas-acceso        # (ir.rule)     
|            |   |-- registro-actividades               # (res_users_log)
|            |   |-- auditoria-usuario                  # (res_users_deletion) 

# CONTROLLERS   
proyecto
|-- backend-nestjs
|   |-- src
|   |   |-- controllers
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                      # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 


# SERVICES  
proyecto
|-- backend-nestjs
|   |-- src
|   |   |-- services
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                      # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 


# DTO  
proyecto
|-- backend-nestjs
|   |-- src
|   |   |-- dto
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                      # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 

# MODULES  
proyecto
|-- backend-nestjs
|   |-- src
|   |   |-- modules
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                        # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 

# ENTITIES 
proyecto
|-- backend-nestjs
|   |-- src
|   |   |-- entities
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                      # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades              # (res_users_log)
|   |               |-- auditoria-usuario                 # (res_users_deletion) 

- Base de datos
  - res_users
  - res_groups
  - res_partner
  - ir.model.access
  - res_company
  - ir.rule
  - res_users_log
  - res_users_deletion

# Procesos
## Gestión de Usuarios (res_users)
Vista de lista para visualizar todos los usuarios, mostrando columnas como nombre, correo electrónico, y estado (activo/inactivo).
Formulario de detalles para crear o editar un usuario, incluyendo campos para nombre, correo electrónico, grupos de usuario, y configuraciones de acceso.
Acciones para activar, desactivar, o eliminar usuarios directamente desde la vista de lista.
## Gestión de Grupos de Usuarios (res_groups)
Vista de lista para todos los grupos de usuarios, incluyendo columnas para nombre del grupo y descripción.
Formulario de detalles para añadir o modificar grupos, con opciones para asignar permisos y usuarios miembros del grupo.
## Gestión de Contactos Comerciales (res_partner)
Vista de lista para contactos, mostrando nombre, dirección, teléfono, y correo electrónico.
Formulario de detalles para añadir o editar información del contacto, incluyendo campos personalizables como etiquetas y clasificaciones.
# Ajustes
## Configuración de Permisos (ir.model.access)
Vista de lista para permisos de modelo, mostrando el nombre del modelo, grupo al que pertenece, y permisos asignados (crear, escribir, leer, eliminar).
Formulario de edición para modificar los permisos de acceso a los modelos para diferentes grupos de usuarios.
## Configuración de Empresa (res_company)
Formulario único para configurar los detalles de la empresa, como nombre, logotipo, información fiscal, y dirección.
Opciones para añadir información adicional como configuraciones financieras y moneda predeterminada.
Configuración de Reglas de Acceso (ir.rule)
Vista de lista para reglas de acceso que muestra el nombre de la regla, modelo afectado, y el grupo de usuario aplicable.
Formulario para crear o editar reglas, con campos para definir condiciones de dominio y permisos.
Reportes
## Registro de Actividades (res_users_log)
Vista de lista para historial de actividades de usuarios, mostrando usuario, fecha y hora, y tipo de actividad.
Opciones para filtrar y buscar específicamente por usuario o rango de fechas.
Auditoría de Usuario (res_users_deletion)
Vista de lista para auditorías de acciones de eliminación de usuarios, mostrando detalles del usuario eliminado, quién lo eliminó, y cuándo.
Filtros y búsqueda avanzada para auditorías en periodos específicos o por usuario eliminador.


# Épica 1: Gestión de Usuarios
## Historias de Usuario:
HU1.1 - Visualizar Usuarios: Como administrador, quiero visualizar una lista de todos los usuarios con detalles como nombre, correo electrónico y estado, para tener un control y seguimiento fácil.
Tareas:
Implementar la vista de lista para usuarios.
Asegurar la correcta visualización de columnas para nombre, correo electrónico y estado.
HU1.2 - Crear y Editar Usuario: Como administrador, quiero crear y editar usuarios, incluyendo sus detalles como nombre, correo electrónico y grupos de usuario, para mantener la información actualizada.
## Tareas:
Desarrollar el formulario de detalles para crear y editar usuarios.
Integrar la funcionalidad para asignar grupos de usuario y configuraciones de acceso.
HU1.3 - Gestionar Estado de Usuarios: Como administrador, quiero activar, desactivar o eliminar usuarios desde la vista de lista, para administrar eficientemente el acceso al sistema.
## Tareas:
Implementar acciones en la vista de lista para cambiar el estado de los usuarios.
Desarrollar la funcionalidad de eliminación segura de usuarios.
# Épica 2: Gestión de Grupos de Usuarios
## Historias de Usuario:
HU2.1 - Visualizar Grupos de Usuarios: Como administrador, quiero ver todos los grupos de usuarios, incluyendo su nombre y descripción, para gestionar mejor las agrupaciones y permisos.
## Tareas:
Implementar la vista de lista para grupos de usuarios.
Mostrar correctamente las columnas para nombre del grupo y descripción.
HU2.2 - Administrar Grupos de Usuarios: Como administrador, quiero añadir o modificar grupos de usuarios, asignando permisos y usuarios miembros, para controlar el acceso a diferentes áreas del sistema.
## Tareas:
Desarrollar el formulario de detalles para añadir o modificar grupos.
Integrar la asignación de permisos y gestión de miembros del grupo.
# Épica 3: Configuraciones y Permisos
## Historias de Usuario:
HU3.1 - Configurar Permisos de Acceso: Como administrador, quiero configurar permisos de acceso a los modelos para diferentes grupos, para asegurar la protección y correcto uso de la información.
## Tareas:
Implementar la vista de lista y el formulario de edición para permisos de modelo.
HU3.2 - Configurar Detalles de la Empresa: Como administrador, quiero configurar los detalles de la empresa, incluyendo información fiscal y configuraciones financieras, para mantener la operación adecuada y cumplimiento legal.
## Tareas:
Desarrollar el formulario único para configurar detalles de la empresa.
HU3.3 - Definir Reglas de Acceso: Como administrador, quiero crear o editar reglas de acceso, definindo condiciones de dominio y permisos, para asegurar que los datos sean accesibles solo por usuarios autorizados.
## Tareas:
Implementar la vista de lista y formulario para reglas de acceso.
# Épica 4: Reportes y Auditoría
## Historias de Usuario:
HU4.1 - Registrar Actividades de Usuarios: Como administrador, quiero un registro de las actividades de los usuarios, incluyendo detalles como usuario, fecha y hora, para monitorear el uso del sistema.
## Tareas:
Desarrollar la vista de lista para el registro de actividades.
HU4.2 - Auditar Acciones de Eliminación de Usuarios: Como administrador, quiero una vista de las auditorías de acciones de eliminación de usuarios, para asegurar la transparencia y seguridad en la gestión de usuarios.
## Tareas:
Implementar la vista de lista para auditorías de eliminación de usuarios.
