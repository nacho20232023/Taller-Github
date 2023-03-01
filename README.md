# Taller-Github

SECURITY OPERATIONS

![image](https://user-images.githubusercontent.com/125692382/222054099-319ea844-c59b-4b4f-9ad2-65d2bec98597.png)


 

¿QUE ES DATA PROTECTION?

La protección de datos (data protection en inglés) es el conjunto de medidas y procesos diseñados para proteger la información personal y confidencial de las personas, empresas u organizaciones contra el acceso no autorizado, la pérdida, la corrupción o el robo. La protección de datos se refiere a cualquier información relacionada con una persona física identificada o identificable, como su nombre, dirección, número de identificación personal, información financiera o médica, entre otros.

La protección de datos es importante para proteger los derechos y la privacidad de las personas y para garantizar que los datos personales se procesen de manera legal, justa y transparente. Muchas jurisdicciones tienen leyes y regulaciones específicas sobre la protección de datos, y las empresas y organizaciones suelen estar sujetas a requisitos de cumplimiento de estas normas para garantizar la privacidad y seguridad de la información personal de sus clientes o usuarios.


![image](https://user-images.githubusercontent.com/125692382/222054265-e05553d1-5550-40dc-8489-3af3e1596e83.png)

 
Principios de protección de datos

Los principios clave de la protección de datos son salvaguardar y poner a disposición los datos en todas las circunstancias. El término protección de datos se utiliza para describir tanto la copia de seguridad operativa de datos como la continuidad del negocio/recuperación ante desastres (BC/DR). Las estrategias de protección de datos están evolucionando en dos líneas: disponibilidad de datos y gestión de datos.

La disponibilidad de datos garantiza que los usuarios tengan los datos que necesitan para realizar negocios, incluso si los datos se dañan o se pierden. Hay dos áreas clave de la gestión de datos que se utilizan en la protección de datos: la gestión del ciclo de vida de los datos y la gestión del ciclo de vida de la información. 

La gestión del ciclo de vida de los datos es el proceso de automatizar el movimiento de datos críticos al almacenamiento en línea y fuera de línea. La gestión del ciclo de vida de la información es una estrategia integral para valorar, catalogar y proteger los activos de información de errores de aplicaciones y usuarios, ataques de virus y malware, fallos de máquinas o interrupciones e interrupciones de las instalaciones. 

 ![image](https://user-images.githubusercontent.com/125692382/222054333-41bfd3a6-53c0-4af9-9f33-2c1f89279f4a.png)


Existen varias medidas que se pueden tomar para proteger la protección de datos, tanto si eres una persona que maneja información personal, como si eres una empresa u organización que la procesa. Aquí presentamos las herramientas para hacerlo:


ENCRIPTACIÓN DE DATA PROTECTION

![image](https://user-images.githubusercontent.com/125692382/222054386-79e77a1b-f49b-46cb-a9b1-d09a2f5aedd7.png)

 
¿Qué es la encriptación de datos?

La encriptación de datos es un proceso de codificación mediante el cual se altera el contenido de la información haciéndola ilegible, de esta manera se consigue mantener la confidencialidad de la información mientras viaja del emisor al receptor. En el actual mundo digital, lo que se altera son los bits que conforman las cadenas de datos de archivos, documentos, emails, imágenes, etc.

Aunque nos pueda parecer que la encriptación es un procedimiento relacionado con el mundo digital e Internet, puesto que la gran mayoría de datos e información que viajan por la Red lo hacen de manera encriptada, lo cierto es que existe desde mucho antes de que existieran los ordenadores e incluso que la luz eléctrica, ya que desde las primeras civilizaciones se han ido desarrollando formas para proteger el contenido de los mensajes.

¿Para qué sirve encriptar datos?

Encriptar archivos, documentos, mensajes, emails, imágenes o cualquier tipo de datos que circulen por la Red sirve para protegerlos de miradas indiscretas, es decir, para garantizar que la información viaja segura y se mantiene confidencial. Además, también puede servir para garantizar que no ha sido alterada o modificada y para acreditar el origen de la misma.

Por ejemplo, los mensajes de WhatsApp viajan cifrados de extremo a extremo, lo que quiere decir que ningún actor intermedio, ni siquiera el servidor, tiene acceso al contenido de estos. O cuando introducimos información en una página web con certificado HTTPS, esos datos se cifran automáticamente. También tenemos un ejemplo de cifrado en los certificados digitales, que debemos usar para poder acceder a determinados servicios o áreas de usuario de la administración.

Además, de acuerdo al RGPD, si la base de datos de nuestra empresa está encriptada y sufrimos una brecha de seguridad que afecte a los datos personales almacenados en ella, no tendremos obligación de notificar dicho incidente de seguridad ni a la AEPD ni a los interesados afectados, puesto que pese a que se haya podido extraer información, esta no será legible para los ciberdelincuentes.
¿Cómo funciona la encriptación de datos?

En la encriptación de datos actual se utiliza un algoritmo matemático para modificar el contenido que se quiere cifrar (dependiendo del sistema de cifrado, se usan diferentes algoritmos), para ello se genera una clave o claves que establecen la forma en que se «desordena la información» cuando se cifra y que después se emplea para descifrarla, es decir, volver a ordenarla.

Cuanto mayor sea la longitud de la clave, que se mide en bits, más seguro resultará el cifrado. Las longitudes habituales son de 128 y 256 bits para las claves privadas y de hasta 2048 bits para las públicas.

Actualmente, existen diferentes programas y sistemas de cifrado que realizan esta labor de forma automática, por lo que cuando los usamos para encriptar cualquier tipo de información, solo debemos preocuparnos de guardar las claves de cifrado en un lugar seguro y, de ser necesario, guardar una copia de seguridad de dichas claves.

![image](https://user-images.githubusercontent.com/125692382/222054507-a42ba147-b4c7-48bc-89a3-4a514d5ae067.png)

 
Tipos de encriptación de datos

Podemos hablar de tres tipos de encriptación:

•	Encriptación simétrica: En este tipo de cifrado, los datos se encriptan usando una única clave secreta de cifrado, de manera que emisor y receptor comparten una copia de esa clave. Los algoritmos utilizados en el cifrado simétrico se basan en operaciones sencillas como sustitución o permutación. Actualmente no es el método de encriptación más seguro e infalible, pero se sigue utilizando. Algunos sistemas de encriptación simétricos son:

o	DES (estándar de encriptación de datos)
o	Triple DES
o	AES (estándar de encriptación avanzado, que sustituyó al DES)
o	Blowfish
o	Twofish

•	Encriptación asimétrica: En este tipo de cifrado se emplean dos claves diferentes, una privada y otra pública, teniendo emisor y receptor un par cada uno. La clave pública debe ser conocida por ambas partes, mientras que la privada es secreta. De esta manera, la clave pública se utiliza para cifrar los mensajes, pero solo la clave secreta puede descifrarlos. Para que el cifrado asimétrico sea completamente seguro, es necesario completarlo con la autenticación de las partes, como hacen, por ejemplo, los certificados digitales. Ejemplo de sistema de encriptación asimétrica es:

o	RSA

•	Encriptación híbrida: Se trata de un sistema que combina técnicas de cifrado simétrico y de cifrado asimétrico, utilizando este último para transferir la clave simétrica por un canal no protegido. Este tipo de encriptación se usa, por ejemplo en estándares de cifrado como:

o	PGP (Pretty Good Privacy)
o	GnuPG
o	S/MIME

¿Cuándo debemos encriptar los datos?

Debemos encriptar los datos cuando queramos mantener la seguridad y confidencialidad de los mismos o cuando tengamos el mandato legal de hacerlo (puesto que hay leyes que obligan a cifrar determinada información). Si estamos manejando información sensible, secreta o que no queramos que pueda ser interceptada por terceros (por la razón que sea), deberemos encriptar los datos recurriendo a alguno de los métodos de cifrado existentes.

¿Cuándo puede ser obligatorio encriptar los datos?

El Reglamento (UE) 2016/679 y la Ley 3/2018, por tanto, obligan a encriptar los datos cuando se trate de datos sensibles, sean datos recabados para fines policiales sin el consentimiento de los interesados, sean datos derivados de casos de violencia de género, cuando así lo imponga una ley o si el resultado de la evaluación de impacto de un tratamiento de datos recomienda hacerlo como medida de seguridad, para reducir o eliminar un riesgo.

SISTEMA PKI y TLS

¿Qué es un sistema PKI?
La infraestructura de clave pública (PKI) es un sistema de procesos, tecnologías y políticas que permite cifrar o firmar datos. Con la PKI, es posible emitir certificados digitales que autentiquen la identidad de los usuarios, dispositivos o servicios.

 ![image](https://user-images.githubusercontent.com/125692382/222054653-2664c2c5-b1a4-4f62-92d4-1d20cf237085.png)


¿Qué es TLS?

La seguridad de la capa de transporte (TLS) es un protocolo criptográfico que asegura la conexión entre un servidor web y una aplicación web mediante el cifrado de datos. Se aplica a todos los datos que se intercambian en la red, incluidos los correos electrónicos, las sesiones de navegación web y las transferencias de archivos. Como resultado, los hackers no pueden acceder a los datos sensibles de los usuarios, como las credenciales de acceso y los números de las tarjetas de crédito.

![image](https://user-images.githubusercontent.com/125692382/222054694-025d8c30-a305-48fd-95d6-f10064993e67.png)



¿Que es Data Loss Prevention?

La prevención de pérdida de datos, o Data Loss Prevention (DLP), es un conjunto de herramientas, tecnologías y procesos diseñados para evitar la filtración o pérdida accidental o intencional de información confidencial y valiosa de una organización.

El objetivo de la DLP es proteger los datos sensibles de una empresa, como información financiera, datos de clientes, información de propiedad intelectual y secretos comerciales, y evitar que estos datos caigan en manos equivocadas o sean utilizados de manera inapropiada.

Las soluciones de DLP incluyen software que identifica, clasifica y supervisa el flujo de datos confidenciales a través de la red de la organización, así como también políticas y procedimientos que definen quién tiene acceso a estos datos y cómo deben ser manejados. También puede incluir la capacitación de empleados en seguridad de la información para reducir la posibilidad de errores humanos que puedan resultar en la pérdida o filtración de datos confidenciales.

 ![image](https://user-images.githubusercontent.com/125692382/222054756-e2332f50-46bb-4619-8e93-ecd54be004d8.png)


EMAIL SECURITY

La seguridad de correo electrónico o email security es el conjunto de medidas y tecnologías utilizadas para proteger los sistemas de correo electrónico contra amenazas de seguridad, como el spam, phishing, malware, virus y otras formas de ataques cibernéticos que pueden comprometer la privacidad, la integridad y la confidencialidad de los datos del usuario.

Las soluciones de seguridad de correo electrónico incluyen software antivirus, filtrado de correo no deseado (spam), autenticación de correo electrónico y cifrado de correo electrónico. El software antivirus busca y bloquea el malware y los virus que se pueden propagar a través de correo electrónico. El filtrado de correo no deseado reduce la cantidad de spam que llega a la bandeja de entrada del usuario. La autenticación de correo electrónico, como el protocolo SPF, DKIM y DMARC, ayuda a prevenir la suplantación de identidad y garantiza que los correos electrónicos enviados sean legítimos. El cifrado de correo electrónico protege el contenido del correo electrónico de accesos no autorizados al cifrar los datos transmitidos.

La seguridad de correo electrónico es esencial para la protección de la información confidencial y la privacidad del usuario, especialmente en entornos empresariales donde la información sensible se intercambia a través de correo electrónico de manera frecuente.

![image](https://user-images.githubusercontent.com/125692382/222054820-3b28bb50-7b65-4fdb-bea4-c36d8a1ba978.png)


 
