## Bitrix24 integration process

### How to insert a new deal

- You need to create a new incoming webhook on bitrix24 plataform in the section https://via.bitrix24.com/devops/ -> Importar y exportar datos -> Importe clientes 

![alt text](image.png)

- Configure the fields as you want

- Copy the link and send

- Example for a new deal: https://via.bitrix24.com/rest/1/njchseo802in1k03/crm.lead.add.json?FIELDS[NAME]=Jose&FIELDS[PHONE][0][VALUE]=878852&FIELDS[CONTACT_ID]=1&FIELDS[COMMENTS]=chorizo&FIELDS[SOURCE_ID]=OTHER

- SOURCE_ID: OTHER (must be in capital).



### How to move a deal from new to contactos
- When a new deal comes to the CRM it goes to NEW (NUEVO)
- You need to configure the automatization of the FUNNEL STAGE.

#### Configure the automatization
- First you need to go to CRM
- Go to automatization (center menu on the right with the logo of a robot 🤖)
- In the stage you want to add a rule of automatization go to the sign + (add) and click it.
- Search for CAMBIAR ETAPA (CHANGE STAGE)

### CONFIGURE ETAPA
 ![alt text](image-1.png)
 - Ejecuciòn:  en paralelo
 - Hora: Inmediatamente
 - Condicion: Origer igual a Other

