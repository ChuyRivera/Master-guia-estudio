#IA - Guía de estudio - Reto Master

### Computo en la nube
> inserte aquí definición de cómputo en la nube.

Es la entrega de servicios de cómputo através de internet

#### Conceptos

* __CapEx:__ Capital Expenditure o Gasto de Capital es literalmente la compra del equipo (la computadora, los servidores, el cableado, etc.).

* __OpEx:__ Operational Expenditure o Gasto de Operaciones, es el gasto que necesitas para funcionar.

* __Nube privada:__ Los recursos informáticos son de uso exclusivo de los usuarios de una empresa u organización la cual se encaga de el consumo de electricidad, seguridad, mantenimiento. El dueño es el responsable. Se usa cuando por reglamentación no puedes sacar los datos de tu servidor o de tu país.

* __Nube pública:__ Los servicios se ofrecen a través de la red de internet pública y están disponibles para cualquiera que quiera comprarlos, es decir, conseguir servicios de nube de terceros como Microsoft Azure. `Dentro de la nube pública tenemos 3 modelos de servicios`

    * __IaaS:__ Infraestructure as a Service, es que simplemente Azure se va a dedicar y te va a rentar el equipo. Por medio de la nube de Azure tu puedes hacer tu máquina virtual, tu servidor, etc. Tú te encargas de meterle el OS que quieras, librerias, etc.
    * __PaaS:__ Platform as a Service, Son sistemas que ya te dan el OS, te dan todo configurado y tú nomás llegas a montar su programa, tu página web, aplicación, etc.
    * __SaaS:__ Software as a Service, Es el software ya terminado, no tienes que programar ni configurar nada, solo es hacer uso del doftware/aplicación.

* __Nube híbrida:__ Entorno que combina una nube pública y un a nube privada, lo que permite compartir datos y aplicaciones entre ellas. Es cuando parte de tu infraestructura, tú los posees y tú te encargas de ello, pero otra parte está en una nibe pública.

* __Tolerancia a fallos:__ Se puede recuperar de errores, toma ventaja de los servicios de respaldo, recopilacióñ de datos y geodistribución en la nube. Tus datos están seguros en caso de desastre.

* __Agilidad:__ Implementación y configuración rápida de recursos de nube a medida que los requerimientos cambian.

* __Esaclabilidad:__ Capacidad de crecer.
    * __escalabilidad horizontal:__ Incremento en la capacidad de cómputo agregando más instancias del mismo recurso, es simplemente replicar los recursos.
    * __escalabilidad vertical:__ Incremento de la capacidad de cómputo agregando RAM o CPU al recurso.

* __Geografías:__ Zona que contiene 2 o más regiones de Azure.

* __Regiones:__ Espacio en el que hay por lo menos un centro de datos en Azure.

* __Zonas de disponibilidad:__ Centros de dato separados dentro de una region de Azure con electricidad, refrigeración y equippos independientes.

* __Elasticidad:__ La nube es elástica, tus recursos pueden crecer dependiendo de cuánto se requiera actualmente, está sujeto a cierto margen de cambio.

> Nota: La __elasticidad__ es automática, la __escalabilidad__ es manual. Ambas son para crecer los recursos y aguantar más usuarios.

* __Alta disponibilidad:__ Las aplicaciones tienen la capacidad de proporcionar servicio continuo incluso cuando ocurren errores o fallos dependiendo del _SLA_.
    * __SLA__(Service Level Agreement)__:__ El nivel de acuerdo de servicio, es el porcentaje de cuanto Asure se compromete a darte el servicio.

### Azure
Es la entrega de servicios de cómputa a travez de internet de Microsoft.

#### Categorías

* __Compute:__ Son los servicios que proporcionan capacidad de procesamiento y cómputo. Por ejemplo dentro de una página es el lugar dónde se procesa la información del usuario, los correos, etc.

* __Network:__ Proporciona servicios de red que permite conectar los recursos con el mundo exterior.

>Nota: __Storage__ y __Base de datos__ no son lo mismo y tienen funciones diferentes.

* __Storage:__ Proporciona servicios de almacenamiento de archivos y objeos. (videos, fotos, archivos que hacen ejecutar tu pagina web, etc)

* __Base de Datos (DB):__ Proporcionan servicios de base de datos para una amplia variedad de tipos y volúmenes de datos. Estas guardan información, guardan registros, no es recomendable para guardas cosas como videos o fotos.

* __IoT:__ Proporciona servicios de IoT para conectar y recibir información de sensores, relojes inteligentes maquinaria, etc.

* __Big Data:__ Servicios para el procesamiento y análisis de grandes cantidades de registros. Están optimizados para grandes cantidades de información. Arriba de 4TB de información ya es considerado Big Data.

* __DevOps:__ Ayuda a los equipos de desarrollo de software a automatizar y hace eficiente sus procesos. Ejemplo: GitHub.

* __IA:__ Servicios de Inteligencia Artificial son los que están encargados de usar los Cognitive services de Azure para detectar patrones o procescar imágenes, texto, video, etc.

* __Gobernanza:__ Establecer reglas y directivas que hay que seguir y garantizar que se apliquen para evitar situaciones como fallas de seguridad.

* __Recurso:__ Es la mínima expresión de un servicio de Azure.

* __Grupo de recursos:__ Contenedor lgico que incluye los recursos relacionados con una solución. Sirven para administrar mejor tus recursos.

>Nota: un __recurso__ obligatoriamente debe tener un __grupo de recuros__.
