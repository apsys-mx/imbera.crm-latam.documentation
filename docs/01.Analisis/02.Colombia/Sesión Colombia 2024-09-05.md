# Sesión 2 Colombia IMS - Apsys

<iframe src="https://share.fireflies.ai/embed/meetings/0yZsL737bYPXazog" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

Se presentó el proceso de gestión de órdenes de servicio, que abarcó la creación de órdenes tanto por precarga masiva como manual, así como la transmisión a técnicos mediante dispositivos móviles.

Se detalló cómo los técnicos gestionan estas órdenes en una aplicación móvil, incluyendo la digitación de información del equipo, toma de evidencias fotográficas y la obtención de firmas de clientes.

También se abordó el proceso de resurtimiento de materiales, resaltando la integración con SAP y el procedimiento para verificar y validar materiales usados.

Además, se revisó el flujo completo del proceso de órdenes y se planificaron siguientes pasos, como sesiones para revisión en tiempo real y presentaciones adicionales relacionadas con la operación.

Las acciones acordadas incluyeron compartir documentación relevante y organizar sesiones futuras para asegurar la correcta implementación y control del proceso.

## Notas

### 📊 Presentación del proceso de gestión de órdenes de servicio (00:02 - 13:42)

- Proceso de creación de órdenes de servicio por precarga masiva o manual
- Transmisión de órdenes a técnicos por dispositivo móvil
- Gestión de órdenes por técnicos en aplicación móvil
- Obtención de catálogos y órdenes asignadas
- Digitación de información del equipo y servicio realizado
- Toma de evidencias fotográficas y firma del cliente

### 🔧 Proceso de resurtimiento de materiales (13:42 - 20:03)

- Integración con SAP para gestión de almacenes de técnicos
- Creación de ticket de resurtimiento por auxiliar
- Verificación de materiales utilizados contra vale de adeudo
- Resurtimiento de materiales en SAP por almacenista
- Cierre de orden sólo después de resurtimiento validado

### 🔄 Flujo del proceso y siguientes pasos (20:03 - 27:38)

- Revisión del flujo completo del proceso de órdenes
- Discusión sobre catálogos y estructuras de archivos
- Planificación de sesión para revisión en tiempo real del proceso
- Explicación breve del proceso para control de piso

### Compromisos

- Compartir flujos, presentaciones y archivo de precargas masivas (24:03)
- Organizar sesión con operación para revisión en tiempo real del proceso (25:08)
- Agendar sesión para presentación de piso, movimientos e instalaciones (26:28)

### Transcripción de la reunión

00:27
Speaker 3

Vale, pues bueno, como les comentaba Fran, pues esta es la presentación que nosotros tenemos para lo que es el tema de la gestión de las órdenes de servicio, de que desde el momento pues que se hace la petición directamente por parte del cliente para todo lo que es el proceso de la atención, vale? Entonces desde acá pues empezamos pues todo lo que es el tema de la gestión de la creación de la orden por medio de la precarga.

00:59
Speaker 3

Son dos formas que se pueden realizar realmente pues de forma masiva o de forma manual, tanto por la interfaz, en este caso lo que llega a la información directamente de nuestro cliente, en este caso Coca Cola o KOF, ellos nos generan las órdenes de servicio directamente pues por el SAP y nosotros por medio de una interfaz vamos y consultamos un FTPs y traemos la información para el cargue a PS9. Acá lo que estamos mostrando inicialmente pues es una forma del formato que tenemos para las recargas manuales y pues en los campos de abajo pues la configuración del FTP para lo que es la creación de los servicios de forma masiva por medio de la interfaz del cliente KOF.

01:46
Speaker 3

Posteriormente, pues cuando el sistema hace la creación de la orden de servicio, entonces nos trae a nosotros una orden con un número de identificación, nos trae la información del Cliente, la información a quién se le va a facturar y las fechas de creación y en el estado en que se encuentra, en este caso pues que sería en estado abierto. De igual manera, pues acá se nos asigna directamente a una unidad de negocio que nosotros empecemos a identificar de esta manera, pero corresponde realmente a cada una de las sucursales o de las ciudades en las que se está realizando este tema de los servicios.

02:27
Speaker 3

Acá se realiza lo que es ya el tema de la transmisión para los técnicos, se realiza de forma masiva o se puede realizar de forma individual, dependiendo cómo se requiera realizar en estos casos, dependiendo también del volumen de órdenes que se tengan para la asignación. Entonces acá pues esto es tarea realmente de cada uno de los diferentes auxiliares que están en las sucursales. Para el tema de la transmisión hacia el dispositivo móvil, que es el que hemos estado nosotros últimamente trabajando, realmente pues se tiene en cuenta lo que es la unidad de negocio, los rangos de fechas que se crearon la orden de servicio, el grupo de proveedores que para este caso es el grupo de ruta técnicos y pues el estado de la asignación que está en estado pendiente.

03:18
Speaker 3

Ya posterior de esto se realiza ya la transmisión, se le hace el envío de la orden de servicio para que pues el técnico la pueda recibir o tener directamente en su dispositivo móvil. ¿Esta parte pues es la de la transmisión, inicialmente pues lo que les digo si haces una validación y aquí ya se hace directamente la transmisión con los datos del técnico para que les llegue a la orden, vale? Esta ya es la visual directamente de la aplicación móvil que actualmente se está manejando pues en la primera imagen lo que nosotros hacemos en este caso, en esta parte lo que se hace directamente por cada uno de los técnicos es la obtención de los catálogos.

04:03
Speaker 3

En los catálogos pues se baja toda la información de lo que son los servicios, actividades, Diagnósticos y Repuestos y lo que es la información de los modelos de cada una de las neveras que se tienen creadas en PS9 para lo que es el tema de la asignación y la orden de servicio. De igual manera se hace la obtención de las órdenes de servicio y en la parte de abajo ustedes ven que aparece la información de cuántas órdenes tienen asignados cada uno de los técnicos. Este proceso pues lo tienen que realizar diariamente cuando se les haga la transmisión de las órdenes de servicio. Ya posterior pues el técnico empieza a validar lo que es el tema de la asignación o qué órdenes tiene en estado para la gestión.

04:45
Speaker 3

En este caso pues acá les aparece que tienen para un cliente de panadería 2000 en estado abierta y ya ellos empiezan a hacer la digitación, acá ya es la visual interna de la orden de servicio cuando el técnico le empieza a hacer la digitación de la orden hay que asignar directamente lo que es el modelo, la marca, la categoría y la serie y el número de activos pues los trae en muchas ocasiones los lleva por defecto en cuanto se acelere la Creación del Servicio, pero es acá una solicitud directamente por parte de los clientes, es que la idea cuando se haga la visita el técnico haga la actualización de los que son los datos de la serie y el número de activo para estar actualizando el tema de inventarios y las ubicaciones de los equipos. Posterior a ello se hace el proceso de gestión de la orden de lo que es ya directamente la asignación de los servicios, el tipo de actividad y la actividad que es en la primera imagen junto con el Tema del Voltaje y la Corriente.

05:51
Speaker 3

Es de aclarar que ese campo de hora de inicio se lo toma por defecto la aplicación una vez se haga la gestión o se dé por iniciada el tema de la digitación de la orden de servicio, también se le hace lo que es el Cargue del Material, se le está en estos momentos asignando un Retiro de Equipo 1, instalación de equipo foráneo que es de un equipo de transportes y la instalación valor.

06:21
Speaker 3

¿También en la tercera imagen se hace lo que son las tomas de evidencia, el cliente nos solicita que es la imagen de la nevera, en esas imágenes se les está cargando en una marca de agua lo que es la fecha y hora en la que se toma la foto, su solicitud directamente del cliente y para ya finalizar se hace lo que es el cargue de la firma del cliente haciendo la aceptación del servicio posterior a ello esto ya es dentro de la misma aplicación ya digámoslo así, es un módulo aparte de aplicación que son para la gestión de los servicios de postmit o equipos de dispensadores, son más que todo para los clientes de los dispensadores que se tienen de coca cola directamente en los puntos de cinemar o dispensadores automáticos de gaseosa, entonces a ellos se les hace lo que es el tema de el carga de información de lo que es la temperatura, presión de agua, el jarabe, la carbonatación y la fecha de celulosa, esos son datos importantes para el tema de la microbiología que se mantienen directamente en estos equipos que es un control que se les hace y pues se tiene que tener esa gestión vale?

07:41
Speaker 3

Una vez se hace el cierre de la orden, cuando se firma ya se procede directamente por parte del técnico hace la transmisión desde el dispositivo móvil hacia PS para que el auxiliar continúe la gestión, entonces hay en la misma opción de órdenes de servicio, ellos seleccionan enviar órdenes y ya en la segunda imagen se da la información de que la orden de servicio fue enviada correctamente para que el auxiliar haga la gestión. Ya acá en un módulo que tenemos también en psnub se le puede hacer el seguimiento de las órdenes que en el momento el técnico tiene en gestión o que están todavía en proceso, esto con el fin de hacerle la trazabilidad y verificar cómo está avanzando el técnico y se puede verificar por parte del auxiliar qué órdenes tiene que entrar a empezar a gestionar.

08:36
Speaker 3

Aquí vemos tres estados que están lo que es el estado de finalizada, cancelada y cerrada y ya con esto pues el auxiliar continúa el proceso, ya es declarar una parte acá que cuando el técnico envía la orden a a ellos les sale en estado cerrado pero en PS para la gestión del auxiliar y continuar el proceso a ellos siempre les va a aparecer en el estado finalizado, es un dato que hay que tener presente para el tema de esta parte de las gestiones de la orden cuando se hace en el envío directamente de los técnicos. ¿Acá qué es lo que se hace?

09:14
Speaker 3

La validación por parte del auxiliar, él tiene que entrar a validar el servicio, el tipo de sean relacionadas al proceso que se les está solicitando a los técnicos en la orden y el tema de los comentarios o la documentación del servicio de realmente qué fue lo que se le realizó. También entran pues a verificar el tema de las fotos y la ubicación real que esté tomando realmente pues la transmisión directamente desde el punto de atención.

09:46
Speaker 3

Acá pues ellos entran a validar también lo que es el tema del producto instalado que es lo que les mencioné a un inicio, el técnico hace la digitación o el cargue de la información tanto del modelo, la serie y la placa para el tema de actualizaciones de datos y acá pues en la parte de actividad ellos hacen lo que es el tema ya la verificación de la actividad que se realizó y los datos del técnico que hizo la gestión de la orden de servicio.

10:17
Speaker 3

En el campo de gastos de tiempos y materiales, acá se carga pues todo lo que es la información o nos muestra mejor dicho la información en esta parte del campo de materiales lo que es la información de los materiales que se utilizaron, en este caso pues solamente se está haciendo la utilización de un material eliminado que en people pues nosotros tenemos una configuración de que para el cierre de las órdenes toda orden debe de contar como mínimo con un material eliminado para que se pueda proceder con el cierre.

10:53
Speaker 3

Ya entramos acá a la parte de los datos adicionales que esto es lo que les mencionaba, acá nos carga lo que es la información del voltaje y el amperaje de la nevera y también nos muestra en este campo de fotografías lo que es la firma del cliente y la evidencia de las tres fotos que el técnico toma en el momento en que realiza el registro fotográfico de la aplicación. En esta parte es donde nosotros podemos verificar que realmente el equipo corresponde al que se les está a ellos indicando y pues que si reviso realmente pues el tema de la actividad o la gestión, vale en el folio de impresión de la OS pues siempre vamos a colocar el mismo número de la orden de servicio para el tema del cierre.

11:39
Speaker 3

Acá en notas pues en el campo de notas la información pues lo que vamos a ver lo que se nos está indicando por parte del cliente, acá hay un comentario que dice que la nevera no enfría, que presenta un ruido fuerte y pues que está ubicada en la dirección con el barrio y toda la información del teléfono para que el técnico de pronto se pueda contactar con la persona y acá pues ya entramos a la parte del ticket de resurtimiento, ya para lo que es el tema de la reserva de los materiales, esto ya es directamente contra SAP, esto aplica pues para los tres, cuatro módulos que nosotros manejamos, ruta, piso, movimientos e instalaciones, este ticket por lo general a veces lo ejecutan los mismos auxiliares o en su caso pues a veces el mismo ticket lo puede crear hasta el mismo almacenista, dependiendo pues de los procesos que manejen en cada una de las sucursales.

12:50
Speaker 2

Bueno, básicamente con respecto al ticket de resortimiento, nosotros tenemos una integración contra SAP, entonces acá lo que hace este resurgimiento de materiales o bueno, inicialmente cada técnico, les comento, cada técnico tiene un almacén en SAP, cada uno de ellos tiene un stock de repuestos básicamente dentro de su almacén, cuando ellos hacen el gasto o el consumo de estos repuestos, pues eso queda mencionado dentro de la orden de servicio y cuando se realiza el cierre de la orden de servicio, pues aparece el nombre del técnico y qué materiales ha utilizado de su stock o de su almacén de SAP, entonces por ello se realiza este tema del ticket de resurgimiento para resurgirle nuevamente los materiales almacén de SAP. ¿Qué están haciendo acá?

13:42
Speaker 2

¿Básicamente el auxiliar al resurtir los materiales le está diciendo almacenista Mira, este técnico Luis Alfonso Millán gastó estos materiales en estas órdenes de servicio, se lo pasan almacenista, me ayudas a ver? Cuando realizan el ticket de resurtimiento, ellos imprimen esa hoja, dice ticket de resortimiento de material, aparecen absolutamente todos los materiales que utilizó el técnico y en qué órdenes de servicio. Esta hoja se la imprimen y se la entregan almacenista y el almacenista va y compara con un documento que le entregan al técnico en físico, una hoja de una orden despacho cuando le entrega los materiales día a día. ¿Qué pasa?

14:30
Speaker 2

Los técnicos tienen que venir almacén a diario a resurtir sus materiales, siempre ellos deben tener el stock completamente lleno. Esta es la esta es la orden de servicio o el vale de adeudo más bien, que le entrega el almacenista al técnico cuando le entrega materiales, si el diligencia sumano le firma el técnico que recibió esos materiales y se almacenan en su valga la redundancia, almacena SAP. Cuando se hace el resurtimiento, el almacenista tiene que comparar la hoja impresa del ticket de resurtimiento versus el vale de adeudo y tienen que coincidir todos los materiales, esto garantiza que el técnico pues sí está consumiendo los materiales que se le entregaron y en qué órdenes de servicio y en qué servicios hizo el consumo de los materiales.

15:26
Speaker 2

Después de esto o de este cruce que hace el almacenista ya le da la indicación al auxiliar que cierren la orden de servicio. Recordemos que les decía que cuando el técnico transmite el estado de la orden, quedan finalizadas. Esta orden no se puede cerrar hasta que tenga su ticket de resurtimiento, le hayan resurtido los materiales, verificado que sean los materiales que consumieron. Acá básicamente pues ya es un proceso que hace el almacenista donde ya está haciendo como el resurtimiento de todos los materiales. Entonces va, verifica pues la fecha de dónde va a ser el resortimiento, el id persona que es el técnico, va y lo busca y hace simplemente un resurgimiento desde people a SAP. ¿Listo?

16:13
Speaker 2

Y acá ya nos dice que hubo una respuesta de SAP recibida, que SAP ya recibió ese resurgimiento de materiales, o sea, ya le volvió a asignar los materiales al técnico en su almacén de SAP. Y acá básicamente pues ya nos muestra cómo el almacenista hace el resurgimiento en SAP. Digamos que pues esto en este punto no es relevante, muestra más simplemente el módulo de resortimiento de materiales en SAP para que se le devuelvan al stock del técnico. Entonces, básicamente ese sería el proceso que tenemos actualmente con People en el módulo de ruta. Igual aprovecho los minutos que me quedan, les comparto aquí el flujo de lo que les acabo de explicar. Eder, me confirman cuando vean mi pantalla.

17:05
Speaker 4

Ya la puedo ver.

17:08
Speaker 2

Entonces, básicamente pues llega el proceso de la creación de la orden de servicio. Estos son los datos inicialmente más importantes al momento de realizar la creación de la orden de servicio, que es el cliente, el contacto, la dirección, el número del cliente detallista, el ID, a quién le van a facturar. Hay dos maneras de realizar la creación de la orden de servicio con una interfaz que tenemos con COF, mediante un SFTP o una precarga masiva. Básicamente dentro de una misma interfaz, cuando generan la creación de la orden de servicio, ella llega en estado abierta. ¿Quién tiene esta orden de servicio en estado abierta? La auxiliar de digitación o la auxiliar de servicio. Ellos cuando tienen la orden de servicio, tienen que asignarle esta orden al técnico desde PeopleSoft. Entonces ellos van a un módulo, asignan inicialmente, ya la orden queda asignada.

18:01
Speaker 2

Ahora tienen que ir a otro módulo de People a transmitirle la orden a su dispositivo móvil. El asignar no significa que el técnico ya la pueda ver. Si no se la transmiten, ya el técnico dentro del dispositivo móvil va a la recepción básicamente de las órdenes, él le da a obtener órdenes, se le actualiza el celular o la aplicación y ya se le actualizan todas las órdenes que le transmitió el auxiliar anteriormente, él desde su celular hace toda la digitación de la orden, el servicio, actividad, tipo de actividad, etc. Todo lo que ya vieron anteriormente en el dispositivo móvil, él hace toda su gestión y él nuevamente transmite a PeopleSoft, él le da a enviar órdenes, esa orden viaja del aplicativo móvil a PeopleSoft y llega en estado finalizado, nuevamente le llega al auxiliar de servicio o al auxiliar de digitación.

18:54
Speaker 2

Esa persona tiene que ir a buscar esa orden de servicio y tiene que validar los datos. Ellos revisan pues si inicialmente si requiere algún cambio en las actividades, si la orden de servicio requiere hacerle algún cambio, si el técnico digitó algo mal o si la orden de servicio o puso un material que no era. Básicamente eso lo tiene que detallar y validar muy bien el auxiliar de servicio. Si no tiene ningún cambio, pues simplemente van a revisar el tipo de materiales que gastan. Si tiene que hacer algún cambio, pues el mismo desde Peoplesoft, el mismo auxiliar hace los ajustes. Si el técnico se equivocó en algo, escribió algo mal, el mismo auxiliar hace los ajustes. Volvemos al mismo punto, llegamos al mismo punto que es la utilización de materiales.

19:42
Speaker 2

Si el técnico utilizó materiales para este servicio, se tiene que realizar un ticket de resurtimiento para que le puedan resurgir sus materiales a su almacén de SAP. Si él no utiliza materiales, simplemente sea el cierre de la orden sin hacer todo el tema del proceso de SAP o de resurtimiento de materiales en SAP. Ya cuando la orden está cerrada, pues ya el almacenista desde el módulo de SAP hace el resurtimiento internamente. Esto básicamente, esto como a grandes rasgos es el módulo de ruta. No sé si hasta el momento tengan alguna duda con respecto a ruta.

20:26
Speaker 4

¿Pues ahorita en lo que acabas de platicar no me suben algunas dudas.

20:37
Speaker 3

Que.

20:37
Speaker 4

Tienen que ver por ejemplo con los catálogos por la cercanía que tenemos con el proceso de ruta en México, entiendo que hay una serie de catálogos que se están ocupando para el tema de servicios, tipo de servicio, actividad, etc. Entiendo que durante todo el proceso, además de esos que mencioné, pues va a haber varios otros más, no? Y por al principio mencionabas que se hace una carga tanto por medio de un archivo, una carga masiva, como cargas individuales o cargas por medio de una plantilla o de manera manual como lo comentaste. Este las estructuras de los archivos también son importantes, tanto la plantilla que da el cliente o el archivo que nos proporciona el cliente, como la que ÿ se utiliza actualmente, si es alguna plantilla de excel para hacer las cargas manuales.

21:40
Speaker 4

Y digo, ahorita serían de las preguntas que me surgieron así en la explicación que acabas de dar, ya revisando el proceso como lo platicamos anteriormente con alguna orden, pues seguramente se vayan saliendo más dudas al respecto.

22:00
Speaker 2

Vale, sí, pues la idea esa realmente pues realizar el proceso en tiempo real con una orden y con el auxiliar de digitación.

22:07
Speaker 2

La idea pues en este punto era como para que ustedes tuvieran como un abrebocas por decirlo así, un poquito más de claridad para cuando exactamente del proceso, para cuando el auxiliar empiece a hacer su proceso, porque pues lo que comentaba su Alonso es pues también dependemos mucho del tema de la operación, de su tiempo y entendemos que ellos también tienen que hacer sus actividades, entonces pues la idea es que ellos vayan haciendo sus actividades diarias mientras están en la sesión con nosotros, poder que ellos nos digan pues cuáles son los problemas más frecuentes, qué es lo que más se les presenta, pero a medida de que ellos vayan haciendo pues su actividad diaria así pues podemos también evidenciar ellos cómo hacen su actividad diaria.

22:51
Speaker 2

Sí, con respecto pues al tema de las órdenes de servicio, la creación de la precarga masiva, si se maneja un archivo en Excel, ellos después lo pasan a un archivo plano que es un txt con esa plantilla y ellos ya lo suben a un FTP que tenemos para la carga masiva, ya con esa plantilla pues ya se cargan masivamente las órdenes o desde people pueden crear una orden individual, igualmente esto pues lo vamos a ver ya en tiempo real, lo que sí queríamos pues es para que tengan un poquito más de claridad de cómo es el proceso al momento de que tengamos ya la sesión con parte de la operación.

23:30
Speaker 4

Sí, sí, la verdad es que lo que nos explicaste si es un buen punto de partida, de referencia para ir empezando a revisar cuál es el proceso y entender de mejor manera ya que hagamos los ejemplos, igual si nos pudieras compartir la información, si nos pudieras compartir incluso algún ejemplo de un archivo o de la plantilla que se utiliza actualmente para poder revisarla, nos sería de bastante.

24:03
Speaker 2

Ayuda y claro que si yo les comparto finalizando la reunión, les comparto los flujos, las presentaciones y el archivo de precargas masivas. De igual manera para control piso es básicamente muy similar el proceso, simplemente que acá no interviene la aplicación móvil, acá mismo pues los auxiliares le dan el ingreso al equipo, ellos mismos validan el equipo, pasa autorización de cliente, el diagnóstico pues acá el técnico le hace un diagnóstico previo al recibir el equipo, al recibir la nevera, hace un diagnóstico, coloca qué materiales se va a consumir, cuánto puede costar el diagnóstico o la reparación más bien y el cliente decide si aprueba o no el diagnóstico. Si el cliente aprueba, el auxiliar de piso hace absolutamente todo lo que hace el técnico en el celular, pero lo hace desde People Software.

24:55
Speaker 2

Básicamente él gestiona todo el ingreso de la nevera, gestiona toda la orden de servicio y la cierre a la misma. Entonces, pues ya finalizando la reunión, organizó la información y se las envío y ya quedaríamos entonces pendientes con la tarea de nuestra parte para pues tener el tema organizado, hablar con la operación y sacar el tiempo pues tanto para control piso como ruta.

25:25
Speaker 4

Claro, claro. Muchas gracias.

25:28
Speaker 2

Listo. No, a ustedes por el tiempo. Muchas gracias. No sé si tengamos algo más adicional.

25:43
Speaker 4

Pues este, en la sesión de ayer se comentó o Agustín quedó en tener ya la selección de las órdenes para alguna fecha en particular. No sé si en mi caso ustedes pueda haber ya alguna fecha de referencia que en la que ustedes ya puedan tener las órdenes. Y por comentabas que hay otra representación de los movimientos, no sé si para, perdón, la presentación de lo de piso, no sé si vaya a ver algo similar para movimientos e instalaciones. Ÿ voy a agendar la siguiente sesión si es que vamos a hacer alguna otra presentación de información similar a la.

26:28
Speaker 2

Que acaban de realizar y podríamos agendarla para el día de mañana a esta misma hora para mostrarles piso, aprovechamos y demostramos movimientos e instalaciones. No tenemos la presentación de movimientos e instalaciones porque es básicamente lo mismo. Sí, pero pues podemos explicarles también en tiempo real ya con People para que se lleven la idea. Sí, entonces si me podrías apoyar y si tienen la disponibilidad para mañana a esta misma hora, agendamos para que revisen piso y ya queda de mi parte la tarea ahorita hablar con la operación para que ellos me entreguen la disponibilidad y podérselas confirmar a ustedes.

27:07
Speaker 4

Ok, pues creo que no había, no habría inconveniente de que hiciéramos la otra sesión mañana, Oscar, desde tiempos ÿ, déjame.

27:17
Speaker 1
Lo confirmo con Eric y les confirmo si les parece bien.

27:26
Speaker 2

Ok, perfecto. Entonces eso sería todo. Muchísimas gracias.

27:30
Speaker 1
Gracias a todos por su tiempo.

27:32
Speaker 3

Buen día.

27:37
Speaker 4

Gracias a todos.
