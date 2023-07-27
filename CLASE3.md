# VULNERABILIDADES Y AMENAZAS

`   Vulnerabilidad`: son accidentes no voluntarios que se deben a fallos de diseño , configuracion e implementacion
`           Vulnerabilidades ya conocidas en recursos instalados`: son tipos mas comun, y son reconocibñles porque las empresas que        desarrollaron la aplicacion
`           Vulnerabilidades no conocidas en recursos no instalados`: se conocen las vulnerabilidades pero no afectaran porque se relaciona con aplicaciones que no estan instaladas.
`           Vulnerabilidades no conocidas`: en este caso nadie sabe frente a que tipo de debilidades se esta enfrentando ya que no fueron detectados. Son las mas peligrosas
#       Vulnerabilidades mas destacadas
`           Errores en la gestion de recursos`: permitir exceso de recursos afectando a la disponiblidad de la misma
`           Errores de configuracion`: problemas en la config del software
`           Factores humano`: Negligencias causadas generalmente por falta de formacion
`           Validacion de entrada`: fallo en la validacion de datos introducidos en aplicaciones
`           Salto de directorio`: Fallo en la depiuracion de un programa, en la validacion de caracteres especiales.
`           Permisos de control de acceso`: fallos en la proteccion y gestion de permisos.

`   Amenazas`: toda aquella accion que aprovecha una vulnerabilidad para atacar o invadir un sistema informatico.

# Analsis de reisgos
`   1.Definir el alcance de riesgos`: donde vamos analizar los riesgos
`   2.Identificar y valorar l9os activos de informacion`: del departamento , proceso o sistema del estudio
`   3.Identificar amenazas`: a las que estan expuestos estos activos.
`   4.Estudio y analisis de las caracteristicas`: Para identificar los puntos debiles o vulnerabilidades
`   5.Posibilidades de activos-amenaza`: Estimados la probabilidad de que la amenaza se materialice
`   6.Definir acciones`: una vez calculaod el riesgo, debemos tratar aquellos riegos que superen un limite.

# TROYANO 
Es un programa malicioso que se hace pasar por software legitimo, se clasifica como una amenaza grave para la segurifdad del sistema
y pueden tener efectos tales como acceder a queipos de forma remota, eliminar archivos, enviar archivos al intruso, modificar archivos, instalar otros programas.
#       Tipos de troyanos
`           Backdoors`: Infectan a tantos dispositivos como sea posible para crear un red zombi (botnet)
`           Keyloggers`: registran las pulsaciones del teclado para obtener la info.
`           Stealers`: acceden a los datos privados, analizan programas y envian la infromacion
`           Botnets`: convierte el dispositivo en un zombie, pudiendose utilizar para lo que quieren 

#       Costan de 2 partes
`           Servidor y cliente`
#       Puntos de entrada
`           Adjuntos en emails, dispositivo USB, Descargas`

# Puertos
Son las puertas hacia un determinado servicio, es decir, proveer una "entrada" a un sitio web o servidor mediante un puerto abierto que va a recibir solicitudes , por ejemplo si queres entrar al google se usara el puerto 80 para consumo de servicios, el puerto 53 esta el DNS que traduce nombres a direcciones IP, el puerto 4444 donde es un servicio para troyanos,  estos puertos  lo dispoine el sistema donde esta alojado la aplicacion web o el recurso 
` speedguide.net para saber para que sirve cada puerto`

#   Capa de transporte
`       UDP`: Protocolo de datagrama de usuario, es un protocolo sin conexoin que se ejecuta sobre IP
`       TCP`:  Protocolo de control de transmision: es un protocolo orientado a conexion que se ejectua sobre IP
`     Utilizados para la comunicacion extremo a extremo entre dos host`

#   Estados de los puertos
`       Puertos cerrados`: Estos puertos de red rechazan completamente todos los paquetes dirigidos hacia ellos 
`       Puertos filtrados`: el trafico de entrada y salida de estos puertos , esta regulado por agentes de red como los firewalls
`       Puertos abiertos`: el estado de un puerto se considera abierto cuando hay una aplicacion o servicio escichando en ese puerto y es accesible desde fuera de su red

#   Puertos normalmente abiertos (protegidos)
`       20 (FTP)`:` permite trasnferencia de archivos entre sistemas conectados a una red TCP
`       22 (SSH)`: su funcion es el acceso remoto a un servidor por medio de un canal seguro en el que toda info esta cifrada
`       25 (protocolo simple de trasnferencia de correo)`: protocolo  de red utilizado para el intercambio de mansajes de correo electronico entre ordenadores y otros dispositivos
`       53 (DNS)`: Permite enviar correos electronicos a traves de internet desde un dispositivo a un servidor de correo remoto
`       80 (http) protocolo de transferencia de hipertexto`: es la base de cualquier intercambio de datos en internet
`       443 (https) *seguro`: Es un protocolo de comunicacion que protege la integridad y la confidencialidad de los datos 

#   Ataques de escaneo de puertos
antes de lanzar su ataque sera un portscan, que le permitira saber info como la arquitecutra de la red, los servicios que ofrecemos en nuestros equipos y buscar agujeros o brechas de seguridad en los mismos.
`       Herammientas para escanear puertos`:
`              Netcat`: esta diseñada para enviar o recibir datos mediante los protocoloes TCP o UDP
`              Nmap` herramienta mas conocida para escaneo de puertos
`              Testdevelocidad.es` conocida por permitir a los usuarios conocer la velocidad de su conexion a internet 

 


 
