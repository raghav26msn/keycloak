# keycloak

Open PowerShell or Windows Terminal and run command given in keycloak.txt file:

This command will:
- Download the Keycloak image if it isn't already available.
- Create a container named keycloak.
- Expose Keycloak on port 8080 of your Windows machine.
- Create an initial administrator account.
- Run Keycloak in development mode, suitable for local testing.
For local development only, use a stronger password if the port is accessible to other machines. Don't use these credentials in production.

Use below urlin browser to open keycloak.
http://localhost:9191/admin/master/console/

Default username and password is admin/admin123

Roles are USER and ADMIN

Users are 
1. appuser -> Password is user123
2. adminuser -> Password is admin123
