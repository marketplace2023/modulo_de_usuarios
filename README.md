# modulo_de_usuarios

COMPONENTES           
proyecto
|-- frontend-nextjs
|   |--   components
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                    # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion)           


PAGES 
proyecto
|-- frontend-nextjs
|   |     |-- pages
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                    # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 

HOOKS 
proyecto
|-- frontend-nextjs
|   |-- hooks
 |           |   |-- gestion-usuarios                   # (res_users) 
|            |   |-- gestion-grupos-usuarios                    # (res_groups)
|            |   |-- gestion-contactos-comerciales      # (res_partner) 
|            |   |-- configuracion-permisos             # (ir.model.access)   
|            |   |-- configuracion-empresa              # (res_company)
|            |   |-- configuracion-reglas-acceso        # (ir.rule)     
|            |   |-- registro-actividades               # (res_users_log)
|            |   |-- auditoria-usuario                  # (res_users_deletion) 

CONTROLLERS   
proyecto
|-- backend-nestjs
|   |-- src
|   |   |-- controllers
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                    # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 


SERVICES  
proyecto
|-- backend-nestjs
|   |-- src
|   |   |-- services
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                    # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 


DTO  
proyecto
|-- backend-nestjs
|   |-- src
|   |   |-- dto
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                    # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 

MODULES  
proyecto
|-- backend-nestjs
|   |-- src
|   |   |-- modules
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                    # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 

ENTITIES 
proyecto
|-- backend-nestjs
|   |-- src
|   |   |-- entities
|   |           |-- procesos
|   |           |   |-- gestion-usuarios                   # (res_users) 
|   |           |   |-- gestion-grupos-usuarios                    # (res_groups)
|   |           |   |-- gestion-contactos-comerciales      # (res_partner)  
|   |           |-- ajustes
|   |           |   |-- configuracion-permisos            # (ir.model.access)   
|   |           |   |-- configuracion-empresa             # (res_company)
|   |           |   |-- configuracion-reglas-acceso       # (ir.rule)     
|   |           |-- reportes
|   |               |-- registro-actividades             # (res_users_log)
|   |               |-- auditoria-usuario                # (res_users_deletion) 

Base de datos
res_users
res_groups
res_partner
ir.model.access
res_company
ir.rule
res_users_log
res_users_deletion
