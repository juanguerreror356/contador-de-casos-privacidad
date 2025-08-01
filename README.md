# contador-de-casos-privacidad

```html
<!DOCTYPE html>

Política de Privacidad – Contador de casos  
Fecha de última actualización: 1 de agosto de 2025

1. Introducción  
Esta política de privacidad describe cómo la extensión Contador de casos recopila, utiliza y protege la información de los usuarios. Esta extensión es una herramienta interna destinada a representantes de servicio al cliente para llevar el conteo de los casos gestionados cada día y semana.

2. Datos que recopilamos  
La extensión recopila y almacena únicamente los siguientes datos:

- LDAP del agente y nombre de líder: Se solicitan al iniciar sesión en la extensión para identificar al usuario y asociar sus casos.  
- ID de cada caso: El número de identificación del caso gestionado que el agente introduce manualmente.  
- Fecha y hora del clic: Se registra automáticamente la fecha y hora locales (zona América/Bogotá) cada vez que el usuario marca un caso como ON u OFF.  
- Tipo de caso: Indica si el caso fue atendido en WhatsApp (ON) o por correo electrónico (OFF).  
- Meta semanal y progreso: El objetivo de casos que el agente define para su semana y el porcentaje de avance.  

3. Cómo usamos los datos  
Los datos recopilados se utilizan únicamente para:

- Llevar un registro individual de los casos atendidos por cada agente.  
- Calcular estadísticas diarias y semanales (totales ON/OFF, progreso hacia la meta y ranking entre agentes).  
- Enviar notificaciones motivacionales al usuario cuando alcanza ciertos hitos (25 %, 50 %, 75 % y 100 % de su meta semanal) y recordatorios relacionados con la meta diaria mínima.  

Estos datos no se utilizan con fines comerciales ni se comparten para publicidad.

4. Almacenamiento y compartición de datos  
Los datos se guardan de las siguientes maneras:

- En el dispositivo del usuario: Se usan las APIs chrome.storage y chrome.storage.sync para conservar localmente el LDAP, el líder, los contadores y la meta semanal. Esto garantiza que la información persista entre sesiones de navegador.  
- En Google Sheets: Cada vez que se registra un caso, la extensión envía los datos al script de Google Apps Script administrado por la empresa. Ese script guarda cada evento en una hoja de cálculo compartida (una pestaña por agente) para consolidar la información y generar estadísticas de equipo.  

La extensión no comparte datos con terceros ajenos a la organización ni con servicios publicitarios. Toda la información se usa exclusivamente para fines internos de productividad.

5. Conservación de los datos  
Los datos se conservan durante el tiempo necesario para el análisis interno de rendimiento. Los registros diarios y semanales se mantienen en la hoja de cálculo con fines estadísticos y de mejora continua. Los usuarios pueden solicitar la eliminación de sus datos comunicándose con el responsable indicado en la sección 6.

6. Responsable del tratamiento y contacto  
El responsable del tratamiento de los datos es Mercado Libre Colombia S.A.S.  
Si tienes preguntas sobre esta política o deseas ejercer tus derechos de acceso, rectificación o supresión de datos, escribe a:  
juansebastian.guerrero@mercadolibre.com.co

7. Cambios en la política  
Nos reservamos el derecho de modificar esta política de privacidad.  
Si realizamos cambios significativos, notificaremos a los usuarios mediante un aviso en la extensión o por los canales habituales de comunicación interna.

