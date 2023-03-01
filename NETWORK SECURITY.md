# Taller-Github

**2. NETWORK SECURITY**

![Imagen 1](https://user-images.githubusercontent.com/125692036/222238508-515da319-6240-45a9-918f-35e3ed4af89c.jpg)

La seguridad de la red es un tema complejo en el que se ven envueltas muchas tecnologías diferentes con configuraciones que, en muchas ocasiones, resultan complicadas.
El problema de seguridad que hay que abordar es la separación entre lo que está en la red y en los endpoints o los sistemas host que están vinculados a ellos. Tanto la tecnología de la red como la de los endpoints incluye cifrado y control de acceso, pero en la red también hay una seguridad de perímetro y segmentación.
Los tipos de seguridad de red que implemente deberían basarse en el entorno de las amenazas. Esto incluye las vulnerabilidades, vectores y agentes de amenazas actuales. Por lo tanto, los controles deben añadirse al entorno de su red para reducir la probabilidad y el impacto de un posible ataque. 

A.	FIREWALL

![Imagen 1](https://user-images.githubusercontent.com/125692036/222238894-1a51f426-49d9-472a-b07f-1afd5d12ab8d.png)

Un firewall es un dispositivo de seguridad de la red que monitorea el tráfico de red —entrante y saliente— y decide si permite o bloquea tráfico específico en función de un conjunto definido de reglas de seguridad.
Los firewalls han constituido una primera línea de defensa en seguridad de la red durante más de 25 años. Establecen una barrera entre las redes internas protegidas y controladas en las que se puede confiar y redes externas que no son de confianza, como Internet. 
Un firewall puede ser hardware, software o ambos.


TIPOS DE FIREWALLS

•	Firewall proxy.
Un firewall proxy, uno de los primeros tipos de dispositivos de firewall, funciona como gateway de una red a otra para una aplicación específica. Los servidores proxy pueden brindar funcionalidad adicional, como seguridad y almacenamiento de contenido en caché, evitando las conexiones directas desde el exterior de la red. Sin embargo, esto también puede tener un impacto en la capacidad de procesamiento y las aplicaciones que pueden admitir.
•	Firewall de inspección activa.
Un firewall de inspección activa, que ahora se considera un firewall “tradicional”, permite o bloquea el tráfico en función del estado, el puerto y el protocolo. Monitorea toda la actividad desde la apertura hasta el cierre de una conexión. Las decisiones de filtrado se toman de acuerdo con las reglas definidas por el administrador y con el contexto, lo que refiere a usar información de conexiones anteriores y paquetes que pertenecen a la misma conexión.
•	Firewall de administración unificada de amenazas (UTM).
Un dispositivo UTM suele combinar de forma flexible las funciones de un firewall de inspección activa con prevención de intrusiones y antivirus. Además, puede incluir servicios adicionales y, a menudo, administración de la nube. Los UTM se centran en la simplicidad y la facilidad de uso.

Firewall de administración unificada de amenazas (UTM)
Un dispositivo UTM suele combinar de forma flexible las funciones de un firewall de inspección activa con prevención de intrusiones y antivirus. Además, puede incluir servicios adicionales y, a menudo, administración de la nube. Los UTM se centran en la simplicidad y la facilidad de uso.

•	Firewall de próxima generación (NGFW).
Los firewalls han evolucionado más allá de la inspección activa y el filtrado simple de paquetes. La mayoría de las empresas están implementando firewalls de próxima generación para bloquear las amenazas modernas, como los ataques de la capa de aplicación y el malware avanzado.
Según la definición de Gartner, Inc., un firewall de próxima generación debe incluir lo siguiente:
•	Capacidades de firewall estándar, como la inspección activa
•	Prevención de intrusiones integrada
•	Control y reconocimiento de aplicaciones para ver y bloquear aplicaciones riesgosas
•	Rutas de actualización para incluir futuras fuentes de información
•	Técnicas para afrontar amenazas de seguridad en constante evolución.

Si bien estas funcionalidades se están convirtiendo cada vez más en el estándar para la mayoría de las empresas, los NGFW pueden hacer más.

B.	IDS/IPS

 ![Imagen 1](https://user-images.githubusercontent.com/125692036/222240654-fc336a69-208b-477b-8316-984fa50891ff.jpg)

•	¿Cuáles son las diferencias entre un IDS y un IPS?
En resumen, el IPS agrega la posibilidad de bloquear ataques y además protege de forma proactiva la red, mientras que el IDS no permite bloquear y protege de forma reactiva la red.
•	¿Qué es el IDS IPS y para qué sirve?
Un sistema de detección de intrusos (Intrusion Detection System, IDS) es un sistema de supervisión que detecta actividades sospechosas y genera alertas al detectarlas.
•	¿Cuáles son las diferencias entre un IDS y un IPS?
En resumen, el IPS agrega la posibilidad de bloquear ataques y además protege de forma proactiva la red, mientras que el IDS no permite bloquear y protege de forma reactiva la red.
•	¿Cómo funciona el IDS?
IDS (Intrusion Detection System) o sistema de detección de intrusiones: es una aplicación usada para detectar accesos no autorizados a un ordenador o a una red, es decir, son sistemas que monitorizan el tráfico entrante y lo cotejan con una base de datos actualizada de firmas de ataque conocidas.
•	¿Qué es un sistema SIEM?
SIEM definida La Administración de eventos e información de seguridad, SIEM, para abreviar, es una solución de seguridad que ayuda a las organizaciones a detectar y analizar amenazas y responder a ellas antes de que afecten a las operaciones del negocio.
•	¿Cuál es la diferencia entre un IPS y un firewall?
El IPS no utiliza dirección IP como lo hace un firewall, ni funciona igual que un cortafuegos, el IPS permite poner normas y restringir acceso a usuarios, aplicaciones y a host siempre y cuando se detectan que estos están teniendo actividades mal intencionadas o código malicioso en el tráfico de la red.
•	¿Qué es un Data Loss Prevention?
Definición de DLP Los productos de DLP usan reglas de negocio para clasificar y proteger la información confidencial y crítica, para que los usuarios no autorizados no puedan intercambiar datos de manera accidental o malintencionada, cosa que podría poner en riesgo a la organización.
•	¿Qué es mejor un firewall o un IDS?
De ahí que sea habitual que los dos trabajen juntos: el cortafuegos se encarga de bloquear intentos externos de ataque y la inteligencia del IDS protege de posibles fugas de información desde dentro.
•	¿Cuáles son las diferencias entre un IDS y un IPS?
En resumen, el IPS agrega la posibilidad de bloquear ataques y además protege de forma proactiva la red, mientras que el IDS no permite bloquear y protege de forma reactiva la red.
•	¿Dónde colocar un IPS?
Uno de los lugares más comunes para implementar un IDS es cerca del firewall. Dependiendo del tráfico a monitorizar, se coloca por delante o por detrás del firewall para monitorizar el tráfico sospechoso, originado desde dentro o desde fuera de la red. Cuando se coloca en el interior, el IDS debe estar cerca de la DMZ.
•	¿Dónde se coloca un IPS?
El IPS se sitúa en línea dentro de la red IPS y no sólo escucha pasivamente a la red como un IDS (tradicionalmente colocado como un rastreador de puertos en la red).
•	¿Qué es un ataque IPS?
En resumen, un sistema de prevención de intrusos o Intrusion Prevention System (IPS), también conocido como sistema de prevención de detección de intrusiones (IDPS), es una tecnología que vigila una red para detectar cualquier actividad maliciosa que intente aprovechar la vulnerabilidad conocida


C.	¿QUÉ ES UN SERVIDOR PROXY?

![Imagen 3](https://user-images.githubusercontent.com/125692036/222241057-8d4e6453-108c-4957-8807-4e5bb7b4bed2.png)

 Proxy es una herramienta conocida por proporcionar anonimato en Internet al ocultar la dirección IP pública del usuario. Estas aplicaciones funcionan como intermediario entre la comunicación de un navegador con Internet. En lugar de hacer una solicitud de forma directa para, por ejemplo, acceder a una página web, con un proxy la solicitud se envía a un servidor proxy que luego enviará la solicitud para acceder al sitio desde una IP diferente. Como se ilustra en la siguiente imagen, la computadora necesita pasar por el servidor proxy para acceder a Internet.                                                                                                                                                                          
•	El proxy puede las siguientes cumplir algunas de funciones:                       
•	Control de acceso: es posible que los administradores del servidor proxy permitan que ciertos usuarios tengan o no acceso a Internet a través de restricciones en su propio inicio de sesión o direcciones IP, proporcionando al entorno una capa adicional de protección.
•	Filtrado de contenido: al estar en el medio del camino, el servidor también permite, o no, el acceso a ciertos sitios. Entre las reglas que se pueden aplicar están aquellas para bloquear sitios web específicos, pudiendo llegar a bloquear categorías completas.
Ejemplo: el usuario Despreocupado da Silva es un empleado de la empresa ACME, que generalmente puede navegar por Internet a través del proxy, ya que su usuario tiene permiso para hacerlo. A cierta hora del día, el Sr. Despreocupado intenta acceder al sitio de Facebook y recibe un mensaje de bloqueo que indica que el acceso a la red social está bloqueado. Después de algunas horas del día, Despreocupado intenta acceder a algunos sitios más, incluidos algunos relacionados con la inversión, pero todos están bloqueados y muestran el mensaje de que la categoría Inversión/Finanzas no está permitida.
En el caso de Facebook, solo un sitio fue bloqueado, mientras que, en el caso de los sitios destinados al mercado financiero, todos están bloqueados teniendo en cuenta que toda la categoría es parte de la regla de bloqueo.
•	Caché: otro uso muy común para Web Proxies es hacer que realicen la función de caché. Esto hace que el proxy, después de acceder a una página, almacene el contenido de la misma en su sistema. Después de eso, las otras solicitudes a esta misma página no tendrán que ir a Internet, porque el contenido ya está almacenado en la memoria del proxy.
Para ilustrar, el Sr. Despreocupado accede a un sitio web llamado www.123.com. Como el servidor se configuró para almacenar en caché, almacena todo el contenido al que el Sr. Despreocupado accedió. Después de unos minutos, otro usuario, el Sr. Tranquilo, también quiere acceder al mismo sitio (www.123.com). Cuando intenta acceder, el proxy ni siquiera busca en Internet para responder a la solicitud de la página, ya que tiene todo en la memoria y muestra el sitio almacenado para el Sr. Tranquilo, ahorrando así el uso de Internet de ACME.Estas son funciones ampliamente utilizadas de un servidor proxy web e ilustran un escenario de uso común para la mayoría de las empresas.
•	¿Cuál es la diferencia entre un proxy y una VPN?
 
Aunque en algunos aspectos una VPN funciona de manera similar a un Proxy, ya que ambos funcionan como u servidor intermediario entre el equipo de un usuario y el resto de internet, son sistemas pensados para cubrir  necesidades diferentes, tal como hemos explicado en el artículo diferencias entre proxy y una VPN. Sin embargo,  a continuación te proponemos observar cuatro diferencias fundamentales entre estas dos tecnologías que son clave a la hora de decidir qué opción es la más adecuada.
•	Las VPN encriptan el tráfico de los usuarios para hacerlo más seguro, mientras que en los Proxys esto no sucede.
•	Los Proxys operan a nivel de aplicación y solo redirigen el tráfico de un programa, mientras que las VPN lo hacen a nivel de sistema operativo y redirigen la totalidad del tráfico.
•	Los Proxys suelen ser mucho más rápidos que las VPN, sobre todos los proxy que son de pago, ya que los gratuitos no nos proporcionaran una velocidad tan optima y presentan riesgos adicionales que desarrollamos más abajo en la sección Riesgos y ventajas de usar un proxy.
•	Mientras que los Proxys solo ocultan nuestra dirección IP, las VPN ofrecen mayor seguridad y privacidad, aunque sin dudas tendremos que tener cuidado con aquellas que son gratuitas.
•	¿Cuándo debería usar un proxy?
Cuándo utilizar un proxy dependerá de muchos factores, fundamentalmente de nuestras necesidades. Más allá de las ventajas y desventajas que nos proporciona el uso de un proxy, y aunque muy a menudo son utilizados para acceder a servicios que están bloqueados en determinado país, a continuación listaremos situaciones en las cuales utilizar un proxy puede resultar una buena opción.
•	Siguiendo con el ejemplo planteado en la introducción, cuando intentamos acceder a una web o servicio de streaming cuyo contenido está restringido a un país o región un servidor proxy nos puede ayudar a sortear estas limitantes, aunque también es cierto que servicios como Netflix cuentan con tecnologías antiproxy que nos impiden evadir estos mecanismos, pero a grandes rasgos siempre que necesitemos saltar un firewall o restricción geográfica ,un proxy nos puede ser de utilidad.
•	Otra situación que puede llevar a tener que usar un proxy, que dicho sea de paso es una de las principales razones por las que se usa esta tecnología, es la necesidad del anonimato. Debido a que el proxy impide que el origen se conecte al destino de forma directa vía HTTP/HTTPS, como hemos explicado anteriormente, sirve para esconder nuestra dirección IP pública, tanto al navegar como al realizar conexiones a servicios utilizando otros protocolos de Internet.
•	Dado que los servidores proxys no requieren la instalación de software adicional para su funcionamiento, se vuelven muy atractivos cuando no contamos con un sistema con las mayores prestaciones para operar. En este sentido, si quisiéramos reemplazar determinada funcionalidad con una VPN podríamos tener inconvenientes dado que las VPN consumen mayores recursos del sistema mientras que los servidores proxy apenas afectan al rendimiento de nuestro equipo.
•	Otra razón por la que suele usarse un proxy es para aprovechar la funcionalidad de cache con la que cuentan, ya que mejora mucho la respuesta de ciertos recursos a los cuales necesitemos acceder y se optimiza velocidad de conexión.
•	Riesgos y ventajas de usar un proxy
Si bien a lo largo del articulo hemos desarrollado las funcionalidades y características del uso de servidores proxy, a continuación nos enfocamos en los riesgos, desventajas y ventajas que conlleva el uso de esta tecnología.
•	Riesgos y desventajas
•	Aunque la carga de páginas web sea más rápida gracias a la función de caché, es posible que la navegación general sea más lenta debido a que se usa un intermediario para procesar la información.
•	Hemos comentado que se podría acceder a sitios web restringidos geográficamente, pero también se podría dar el efecto contrario, ocurriendo que los servidores web bloqueen nuestro acceso si el servidor proxy nos ubica en un país no aceptado por el servidor de destino.
•	Hay que tener cuidado con algunos servicios de proxy, en especial los gratuitos, ya que aunque prometen anonimato, en realidad podrían estar filtrando datos y poniendo en riesgo  nuestra privacidad, dado que en casi todos los casos se guardan logs de todo lo que hacemos. Esta información luego se utiliza con fines “estadísticos” o puede quedar sujeta a disposición de los propietarios de los proxys que utilicemos. Por lo tanto, se recomienda evitar transmitir información sensible como credenciales de usuarios y contraseñas mientras que estemos utilizando proxys, a menos que seamos nosotros los propietarios del proxy o sepamos que son de confianza.
•	Ventajas
•	Sin dudas usar un proxy nos otorga mayor grado de anonimato, ya que se navega por Internet a través de una IP que esta oculta.
•	En ocasiones se puede acceder a sitios web cuyo contenido está restringido o bloqueado geográficamente y también las funciones de caché reducen los tiempo de carga al acceder a los sitios web.
•	Otra ventaja, sobre todo para los propietarios de un proxy, es que podemos bloquear y filtrar páginas web; por ejemplo, aquellas que tengan contenido malicioso, e incluso podemos bloquear direcciones IP. También podemos disfrutar de otras funcionalidades, como el registro de logs, que permite tener un registro de todo lo que sucede en nuestra navegación, tanto de entrada como de salida, o la posibilidad de agregar autenticación y mejorar la seguridad del proxy. Incluso existe la posibilidad de crear blacklists para bloquear listas de sitios o direcciones no deseadas.

D.	GATEWAY

![Imagen 5](https://user-images.githubusercontent.com/125692036/222241438-1cf45602-0e83-4c1c-a658-3e19f64c03df.png)
 

•	¿Qué es y qué hace un gateway?
Gateway es un término en inglés que significa puerta o portal, un sistema o equipo cuya función básica es establecer comunicación entre múltiples entornos. Con él, es posible realizar la conexión entre equipos ubicados en diferentes redes y que se comunican a través de diferentes estándares. En resumen y desde una perspectiva general, actúa como puente entre dos universos, analizando y tratando la información según definiciones preestablecidas y el tipo de función a la que se destina.
En el entorno industrial, se pueden utilizar como intermediarios para la comunicación remota, sensores, actuadores, transmisores y otros dispositivos de campo con los sistemas de control y supervisión en una planta de producción. En este caso, el gateway actúa como un traductor universal para redes o equipos que operan en base a diferentes protocolos, lo que significa que permite la comunicación entre diferentes entornos y arquitecturas. Puede, por ejemplo, recibir datos de convertidores de frecuencia a través del protocolo CANOpen, convertirlos en paquetes estándar de Ethernet y llevar esos datos a un sistema de supervisión SCADA a través del protocolo MQTT.
Un gateway también puede ser un PLC con tecnología avanzada que soporta una amplia gama de protocolos de comunicación que actúan como puente entre otros controladores de diferentes marcas que operan en base a diferentes estándares.
¿Por qué debería usar un gateway en mis aplicaciones de IoT?
Con el rápido avance de la digitalización en los procesos industriales, es cada vez más común ver fábricas inteligentes con aplicaciones para recopilar y compartir datos a través de máquinas, dispositivos y sistemas de producción conectados. En estos entornos, se puede utilizar un controlador multiprotocolo programable para actuar como un gateway IoT, haciendo la conexión entre la nube y la red de control PLC, sensores u otros dispositivos inteligentes. De esta forma, todos los datos que viajan entre el proceso y la nube pasarían por el gateway.
El uso de un gateway IoT puede traer numerosos beneficios a las aplicaciones más simples de la industria, como la reducción de costos de infraestructura, por ejemplo. Hoy en día, los sensores más avanzados del mercado generan decenas de miles de datos por segundo, lo que requiere una alta capacidad de transmisión desde el enlace de Internet. Con el fin de evitar una cantidad innecesaria de procesamiento de datos y, en consecuencia, la necesidad de expandir las inversiones en ancho de banda, se puede utilizar un gateway IoT para mediar la conexión entre los sensores y la base de datos, enviando a la nube solo la información más relevante.

D.DDOS PROTECTION 

 ![Imagen 6](https://user-images.githubusercontent.com/125692036/222241641-2b73b260-ff02-44d3-8500-918cc5df3277.jpg)
 
•	Técnicas de protección DDoS
Reduzca la superficie expuesta a ataques
Una de las primeras técnicas para mitigar los ataques DDoS es minimizar la superficie del área que puede ser atacada y por lo tanto, limitar las opciones de los atacantes lo que permite construir protecciones en un solo lugar. Queremos asegurarnos de no exponer nuestra aplicación o nuestros recursos a los puertos, protocolos o aplicaciones de donde no esperan ninguna comunicación. Por lo tanto, minimizar los posibles puntos de ataque nos permite concentrar nuestros esfuerzos para mitigarlos. En algunos casos, podemos hacerlo si colocamos nuestros recursos informáticos por detrás de lasRedes de distribución de contenido (CDNs) o Balanceadores de carga y restringir el tráfico directo de Internet a ciertas partes de nuestra infraestructura, como los servidores de bases de datos. En otros casos, puede utilizar firewalls o listas de control de acceso (ACLs) para controlar qué tráfico llega a las aplicaciones.
Plan para escalado 
Existen dos consideraciones claves para mitigar ataques DDoS volumétricos de gran escala, la capacidad del ancho de banda (o tránsito) y la capacidad del servidor de absorber y mitigar los ataques.
Capacidad de tránsito. Cuando diseñe sus aplicaciones, asegúrese que su proveedor de alojamiento le brinde conectividad a Internet amplia y redundante para administrar grandes volúmenes de tráfico. Dado que el objetivo final de los ataques DDoS es afectar la disponibilidad de sus recursos/aplicaciones, debe ubicarlos, no solo cerca de sus usuarios finales, sino también de los grandes intercambios de Internet que brindarán a sus usuarios un acceso fácil a su aplicación, incluso durante grandes volúmenes de tráfico. Además, las aplicaciones web pueden ir un paso más allá si emplean redes de distribución de contenido (CDN) y servicios inteligentes de resolución de DNS que proporcionan una capa adicional de infraestructura de red para servir contenido y resolver consultas DNS desde ubicaciones que a menudo están más cerca de sus usuarios finales.
Capacidad del servidor. La mayoría de los ataques DDoS son ataques volumétricos que utilizan muchos recursos. Por lo tanto, es importante que pueda escalar rápidamente sus recursos de computación. Puede hacerlo con la ejecución de recursos informáticos más grandes o aquellos con características como interfaces de red más extensas o redes mejoradas que admitan volúmenes más grandes. Además, también es común usar balanceadores de carga para monitorear y cambiar cargas continuamente entre recursos para evitar sobrecargar cualquier recurso.
Conozca qué es el tráfico normal y anormal
Cada vez que detectamos niveles elevados de tráfico que golpean a un host, la base es poder aceptar solo el tráfico que nuestro host pueda manejar sin afectar la disponibilidad. Este concepto se llama limitación de velocidad. Las técnicas de protección más avanzadas pueden ir un paso más allá y solo aceptan de manera inteligente el tráfico que es legítimo cuando se analizan los paquetes individuales. Para hacer esto, debe comprender las características del buen tráfico que generalmente recibe el objetivo y poder comparar cada paquete con esta línea de base.
Implemente firewalls para ataques sofisticados de aplicaciones
Una buena práctica es utilizar un Firewall de aplicaciones web (WAF) contra ataques, como la inyección SQL o la falsificación de solicitudes entre sitios, que intentan aprovechar una vulnerabilidad en su propia aplicación. Además, debido a la naturaleza única de estos ataques, debería poder crear fácilmente mitigaciones personalizadas contra solicitudes ilegítimas que podrían tener características como disfrazarse de buen tráfico o provenir de direcciones IP incorrectas, geografías inesperadas, etc. A veces también puede ser útil para mitigar los ataques, ya que pueden obtener un soporte experimentado para estudiar los patrones de tráfico y crear protecciones personalizadas.
