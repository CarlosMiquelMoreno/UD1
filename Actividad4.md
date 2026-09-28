## 1. SMTP spoofing

### Qué es
Un engaño a traves del correo que te intentaran sacar información por medio de pasarse por alguien que conozcas.

### Cómo se lleva a cabo
Se lleva acabo configurando las cabaceras de los correos, pudiendo asi poner en los correos, quien te lo envia y a quien le llega.

### Qué categoría(s) de amenaza compromete
Compromete a la autetificidad poniendo en riesgo la seguridad de los usuarios.

### Ejemplo o caso real
Un usuario envio muchos correos de manera que a quien les llegaran, se pensarían que fueran facturas o cosas sin pagar.

### Medida de prevención
SPF, DKIM y DMARC

## 4. Captura de cuentas de usuario y contraseñas

### Qué es
Es una vulnerabilidad activa que consiste en tomar el control total de credenciales legítimas aprovechando fallos de seguridad existentes.

### Cómo se lleva a cabo
Se ejecuta principalmente mediante el uso de herramientas de captura de tráfico de red como los sniffers(son herramientas que permiten capturar y analizar los datos que circulan por una red informática.), técnicas de ingeniería social como el phishing(es una técnica de engaño en la que un atacante se hace pasar por una persona o empresa de confianza para conseguir información privada), y la instalación de software malicioso registrador de pulsaciones (keyloggers, es un programa o dispositivo que registra las teclas que una persona pulsa en el teclado.).

### Qué categoría(s) de amenaza compromete
Compromete la categoría de Intercepción, cuando se capturan datos durante su transmisión, y la Suplantación de identidad, cuando las credenciales obtenidas se utilizan para hacerse pasar por otra persona.

### Ejemplo o caso real

En junio de 2025, hubo un caso que se considera la mayor exposición de datos de la historia, en el que se localizaron 30 conjuntos de datos en internet que sumaban 16.000 millones de registros de nombres de usuario, contraseñas, cookies de sesión y enlaces directos de inicio de sesión. 
Una gran cantidad de empresas de las mas famosas del sector fueron afectadas entre las que se encontraban multinacionales como Netflix, PayPal, Apple, Google, entre muchas otras.
Todo esto se originó mediante un malware instalado en los ordenadores de los usuarios, utilizando ingeniería social para que los propios usuarios lo descarguen e instalen sin darse cuenta.

### Medida de prevención
Utilizar contraseñas seguras y diferentes para cada cuenta, activar la autenticación de dos factores (2FA), evitar acceder a enlaces sospechosos y mantener actualizados el sistema operativo y los programas de seguridad.

## Fuente
