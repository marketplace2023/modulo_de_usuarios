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

 
