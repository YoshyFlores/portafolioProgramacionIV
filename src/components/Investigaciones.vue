<script setup>
import Bloque from "./InvesComponent.vue";
</script>
<template>


  <div class="container text-center">
  <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 1: Introducción a JavaScript</h2></div>
    
    <br />
    <div class="col-lg-6 mx-auto">
      <Bloque
        title="¿Qué es JavaScript?"
        text="Es un lenguaje de programación que ha sido diseñado con el propósito de que los desarrolladores puedan crear páginas webs interactivas. Brinda una gran gama de elementos que vuelven más atractivos a la vista los elementos que componen la página, lo que permite brindar al usuario una mejor experiencia en el sitio web.
        Este lenguaje de programación surgió como una tecnologia del lado del navegador para hacer que las aplicaciones fueran más dinámicas, por ejemplo, mediante JavaScript los navegadores eran capaces de responder a la interacción del usuario.
        JavaScript fue creado por Netscape en 1995. En 1994 cambio su nombre a ECMA International. 1997, JS envía su documentación para que ECMA cree une estándar. ECMAScript es la versión estandarizada. "
      />
      <Bloque
        title="Funcionamiento JavaScript"
        text=" El código de este es interpretado, mediante el motor V8 es traducido directamente a lenguaje de máquina. En la actualidad se puede utilizar tanto del lado del cliente como del lado del servidor. "
      />
      <Bloque
        title="JavaScript, lado del cliente: "
        text=" El funcionamiento en el navegador."/>
      <div class="text-center">
          <div class="border border-success p-2 mb-2"> <h7>El motor V8 está dentro del navegador.</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Todos los principales navegadores incluyen su propio motor JavaScript.</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Las funciones JavaScript realizan cambios en HTML y CSS.</h7></div>
      </div>
      <br/>
      <Bloque
        title=" JavaScript, lado del servidor: "
        text="uso del lenguaje de codificación del servidor de Backend."
        />
      <div class="text-center">
          <div class="border border-success p-2 mb-2"> <h7>El motor se encuentra en el servidor.</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Una función de JS puede acceder a la base de datos.</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Admite un alto nivel de personalización de la respuesta del sitio web según sus requisitos.</h7></div>
      </div>
      <br/>
      <Bloque title="Bibliotecas" text="Son colecciones de fragmentos de código previamente escritos que se pueden volver a utilizar para realizar funciones estándar de JavaScript."/>      
      <div class="text-center">
          <div class="border border-success p-2 mb-2"> <h7>Visualización de datos</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Manipulación del DOM</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Formularios.</h7></div>
      </div>
      <br />
      <Bloque title="Marcos" text="Colección de fragmentos de código escritos previamente que realizan diversas funciones y se pueden reutilizar."></Bloque>
      <br />
      <div class="text-center">
        <div class="p-3 bg-info bg-opacity-10 p-2 mb-2"> <h5>Tipos de datos, los siguientes son los admitidos según ECMAScript son:</h5></div>
        <div class="border border-success p-2 mb-2"> <h7>Boolean</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Null</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Undefined</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Number</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>String</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Symbol</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Object</h7></div>
      </div>
    </div>
      <br />
      <br/>
    <div class="container text-center">
  <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 2: Bootstrap, VueJS.</h2></div>
    
    <br />
    <div class="col-lg-6 mx-auto">
      <Bloque title="¿Qué es Bootstrap?" text="Marco de desarrollo web que ayuda a los desarrolladores a crear interfaces web. Concebido en 2011 por Marck Otto y Jacob Thornton. Ha tenido muchos cambios desde el día que se lanzo el 19 de agosto de 2011. Antes era una colección de reglas de CSS. Bootstrap 4 sigue siendo muy similar a sus antecesores. El propósito de este sigue siendo permitir a los desarrolladores el crear diseños y ayudar a desarrollar una apariencia con estilos interactivos." />
    <Bloque
        title="Diseño"
        text="Posee contenedores responsivos, capaces de ajustar el diseño de la pagina determinados por el tamaño de una pantalla. Tiene un diseño de cuadricula de 12 y columnas permiten organizar de forma flexible los elementos, así mismo tiene objetos multimedia que funcionan como bloques de construcción y clases de utilidad que permiten manipular los elementos de forma responsiva."
      />
      <Bloque
        title="Contenido"
        text="Formato básico que componen los documentos de las paginas web, basado en etiquetas y su estructura sirve para mostrar los contenidos de las páginas."
      />
      <Bloque
        title="Componentes"
        text="Mediante estos se puede construir características fundamentales de un sitio web. Estos abarcan las construcciones fundamentales que se esperaría de un kit de herramientas de desarrollo. "
      />
      <Bloque
        title="Soporte móvil"
        text="Permite crear sitios web compatibles con dispositivos móviles de una forma fácil. Está diseñado para funcionar en todas las resoluciones y tamaños de pantalla."
      />
      <Bloque
        title="Clases"
        text="Bootstrap ofrece una gran selección de clases de utilidad para encapsular las reglas de estilos necesarias."
      />
      <Bloque
        title="Compatibilidad"
        text="Soporta la mayoría de los navegadores modernos."
      />
      <Bloque
        title="Cuadricula"
        text="El sistema grid consiste en una serie de clases y consultas que ayudan a diseñar la página."
      />
      <Bloque
        title="Texto más grande"
        text="El tamaño de fuente es de 2px, aumentando de 14px a 16px. Bootstrap 4 reemplazó paneles, pozos y miniaturas con un nuevo concepto: tarjetas."
      />
      <Bloque
        title="Controles de formularios"
        text="Permite el tamaño del control de entrada, así como clases para denotar bloques y controles de entrada de nivel en línea. "
      />
      <Bloque
        title="Personalización"
        text="Permite la facilidad para personalizar los sitios, habilitando y deshabilitando preferencias CSS."
      />
      <Bloque
        title="¿Qué es VueJS?"
        text="Marco progresivo utilizado para construir interfaces de usuario. 
        Este está diseñado desde cero para ser adoptable de forma incremental. 
        La biblioteca principal se centra solo en la capa de vista y es fácil de 
        recoger e integrar con otras bibliotecas o proyectos existentes. Es una librería JavaScript pensada 
        para tener un framework para desarrollar páginas web. Vue permite crear 
        todas las vitas necesarias para la pagina de una forma dinámica, puede conectarse al servidor 
        para tener datos dinámicos de una base de datos."
      />
        <div class="text-center">
        <div class="p-3 bg-info bg-opacity-10 p-2 mb-2"><h5>Características Vue.JS</h5></div>
        <div class="border border-success p-2 mb-2"> <h7>Modularidad: Permite crear módulos que van a construir la aplicación completa. Los módulos deben tener funcionamiento independiente pero que al integrarlos deben trabajar.</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Reactividad: Capacidad de poder cambiar o modificar el valor de una etiqueta en tiempo real.</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Componentes web: Vue se basa en componentes y el rendering declarativo. Elementos independientes que pueden ser reutilizables.</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Virtual DOM: Manipular el DOM, capacidad de operar las etiquetas HTML. Vue crea una copia del DOM original, crea un objeto del DOM= Virtual DOM.</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Eventos y transiciones: La acción que realiza el usuario. El resultado de la acción.</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Lifecicle: Se puede controlar lo que ocurre antes de que se cargue el componente, lo que pasa justo al cargarse o al destruirse.</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Aplicaciones SPA: Posee un paquete especial para tener un sistema de rutas.</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>Mixins: Son funciones y lógica de los componentes que se pueden reutilizar y reusar en otros componentes web.</h7></div>
      </div>
<br/>
    <Bloque title="Vue CLI" text="Vue tiene su propia interfaz de línea de comandos. Permite inicializar una aplicación Vue con la configuración que se desea."/>
      <br />
      <h5>Existen diferentes formas de inicializar una aplicación:</h5>
      <div class="text-center">
          <div class="border border-success p-2 mb-2"> <h7>vue init webpack</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>vue init webpack-simple</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>vue init browserify</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>vue init browserify-simple</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>vue init simple</h7></div>
      </div>
    </div>
      <br/>
      <br/>

    <div class="container text-center">
  <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 3: Rendering declarativo, Directivas personalizadas, Representación de lista.</h2></div>
    
    <br />
    <div class="col-lg-6 mx-auto">
      <Bloque title="¿Qué es el DOM?"/>
      <Bloque title="Rendering declarativo" text=""/>
      <h5>El rendering es una opción de VueJS que permite interactuar con el DOM, para lo cual se tendría:</h5>
      <div class="text-center">
          <div class="border border-success p-2 mb-2"> <h7>Vista: HTML</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Estado: Datos JS</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Usuario: interactúa e introduce cambios en la vista.</h7></div>
      </div>
      <br/>
      <Bloque text="En el acaso de la vista se encarga de decirle al estado que hay cambios, y el estado le responde con una nueva vista. Por otra parte, el estado se encarga de decirle a la vista como y cuando compilar y lo que debe esperar, a esta función se le llama como render."/>
      <div class="border border-success p-2 mb-2"> <h7>Comando para crear un proyecto: vue créate vuejs-app</h7></div>
      <div class="border border-success p-2 mb-2"> <h7>Comando para ejecutar el proyecto: npm run serve</h7></div>
      <br/>
      <Bloque title="Reder" text="Los sitios web dinámicos son creados cuando existe la posibilidad de representar datos."/>
      <Bloque title="Directivas" text="Son atributos especiales que se colocan en las etiquetas HTML y están prefijados por v-. Por ejemplo, v-for, v-bind, v-on. Estas permiten realizar acciones dinámicas que no se pueden realizar en HTML por si solo, pero vue permite utilizar sus etiquetas <template>"/>
  
  <div class="text-center">
    <div class="p-3 bg-info bg-opacity-10 p-2 mb-2"> <h5>Dichas directivas están formadas por varias partes:</h5></div>
    <div class="border border-success p-2 mb-2"> <h7>Directivas: es el nombre de la directiva, se puede abreviar con un carácter.</h7></div>
    <div class="border border-success p-2 mb-2"> <h7>Argumento: se indican con un parámetro.</h7></div>
    <div class="border border-success p-2 mb-2"> <h7>Modificador: Se puede modificar el comportamiento de las directivas.</h7></div>
    <div class="border border-success p-2 mb-2"> <h7>Valor: Se requiere establecer un valor. Se escribe como el valor de un atributo HTML.</h7></div>
  </div>
<br/>
<br/>
<div class="text-center">
<div class="p-3 bg-info bg-opacity-10 p-2 mb-2"> <h5>Tipos de directivas:</h5></div>
<div class="border border-success p-2 mb-2"> <h7>Directivas básicas: v-pre, v-once, v-model…</h7></div>
<div class="border border-success p-2 mb-2"> <h7>Directivas condicionales: v-show, v-if, v-else…</h7></div>
<div class="border border-success p-2 mb-2"> <h7>Directivas de bucles: v-for.</h7></div>
<div class="border border-success p-2 mb-2"> <h7>Directivas avanzadas: v-bind, v-on, v-slot…</h7></div>
<div class="border border-success p-2 mb-2"> <h7>Directivas personalizadas: proporcionan un mecanismo para asignar cambios de datos a un comportamiento arbitrario de DOM.</h7>
</div>
  </div>

      <br/>
      <Bloque title="Representación de lista" text="Se puede representar una lista usando la directiva v-for. La sintaxis requiere que especifique la matriz de origen para iterar, y un alias que se usará para hacer referencia a cada elemento en la iteración. "/>
      <br/>
    </div>

    <div class="container text-center">
  <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 4: Eventos, Manejadores de eventos, Modificadores de eventos, Clases y estilos en tiempo real.</h2></div>
    
    <br />
    <div class="col-lg-6 mx-auto">
    <br />
      <Bloque title="¿Qué son los eventos?" text="En JavaScript, la interacción con el usuario se consigue mediante la captura de los eventos que este produce. Un evento es la acción que el usuario realiza. 
      Los eventos se capturan mediante los manejadores de eventos. Se puede utilizar la directiva v-on para escuchar eventos del DOM.
      Para muchos controladores es más compleja por lo que es posible mantener el valor del atributo v-on, en este caso v-on también puede aceptar el nombre del método al que quiere llamar." />
      <Bloque title="Manejadores de línes" text="En lugar de enlazar al nombre de un método, se puede utilizar métodos en una declaración JavaScript"/>
      <Bloque title="Modificadores de eventos" text="VueJS proporciona modificadores de eventos para v-on para manejar detalles de eventos del DOM. Como: event.preventDefault() Oevent.stopPropagation()"/>
      <h5>Modificadores:</h5>
      <div class="container text-center">
    <div class="row g-2" >
    <div class="col-6" >
      <div class="bg-info-subtle p-2 text-dark bg-opacity-10">.stop</div>
    </div>
    <div class="col-6">
      <div class="bg-info-subtle p-2 text-dark bg-opacity-10">.prevent</div>
    </div>
    <div class="col-6">
      <div class="bg-info-subtle p-2 text-dark bg-opacity-10">.capture</div>
    </div>
    <div class="col-6">
      <div class="bg-info-subtle p-2 text-dark bg-opacity-10">.self</div>
    </div>
  </div>
      </div>
    
</div>
<br/>
    <div class="col-lg-6 mx-auto">
      <h5>Modificadores de teclas</h5>
      <h6>Vue proporciona alias para las claves más utilizadas:</h6>
      <div class="container text-center">
  <div class="row g-2" >
    <div class="col-6" >
      <div class="bg-info-subtle p-2 text-dark bg-opacity-10">.enter</div>
    </div>
    <div class="col-6">
      <div class="bg-info-subtle p-2 text-dark bg-opacity-10">.tab</div>
    </div>
    <div class="col-6">
      <div class="bg-info-subtle p-2 text-dark bg-opacity-10">.delete</div>
    </div>
    <div class="col-6">
      <div class="bg-info-subtle p-2 text-dark bg-opacity-10">.esc</div>
    </div>
    <div class="col-6">
      <div class="bg-info-subtle p-2 text-dark bg-opacity-10">.left</div>
    </div>
    <div class="col-6">
      <div class="bg-info-subtle p-2 text-dark bg-opacity-10">.right</div>
    </div>
  </div>
  </div>
</div>
    </div>
    </div>
<br/>
<br/>
<div class="col-lg-6 mx-auto">
      <Bloque title="Clases y estilos reactivos" text="Uso de binding para obtener clases y estilos reactivos"/>
      <Bloque title="Binding :class" text="Se puede definir clases al igual que con el atributo class pero aquí se usa comillas simples dentro de las comillas dobles, solo si se trata de un data se obvian las comillas simples. Se puede aplicar varias clases a una etiqueta HTML."/>
      <Bloque title="Bindig : style" text="Se puede cambiar el estilo de algún elemento HTML en tiempo de ejecución. Vue también nos permite usar los atributos class y style junto con los binding :class y :style."/> 
      <br/>
    </div>
    </div>
    

    <div class="container text-center">
  <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 5: Sistema de Componentes, Introducción al sistema de Componentes, Crear Componentes Custom.</h2></div>
    
    <br />
    <div class="col-lg-6 mx-auto">
    <br />
      <Bloque title="Introducción a los componentes" text="Componentes: En Vue.js es la forma de utilizar una instancia tantas veces como sea necesario. Mediante estos se puede crear elementos propios HTML que fácilmente se pueden utilizar en toda la aplicación." />
      <Bloque title="Registro Global de Componentes" text="Este se realiza al llamar al método component de Vue. Que se registre de forma global significa que estará disponible en cualquier componente de Vue. "/>
      <Bloque title="Registro Local de Componentes" text="Resulta que con el tiempo puede parecer sencillo comenzar a acumular componentes de manera global aun cuando no se utilicen en todas las vistas de una aplicación. Para esto Vue aporta la flexibilidad de agregar los componentes que se utilizarán en un componente específico."/>

    <h2>¿Comunicación entre Componentes: propiedades y eventos?</h2>
    <br/>
    <h3>Pasando datos mediante métodos</h3>
    <Bloque text="Envío de datos entre componentes: En Vue.js se envían datos desde un componente padre hacia el hijo mediante sus propiedades ( props ) y desde el componente hijo hacia el padre mediante eventos ( $emit )."/>
  
    <br/>
    <h2>Pasando datos mediante eventos</h2>
    <Bloque text="Paso de datos con el bus de eventos: un bus de eventos no es más que otra instancia de Vue. Una instancia que puede tener las mismas propiedades que cualquier otra instancia."/>
    <br/>

    </div>
  </div>

  <div class="container text-center">
    <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 7: Introducción al desarrollo con PHP.</h2></div>
    <br/>
    <div class="col-lg-6 mx-auto">
      <Bloque title="¿Qué es PHP?" text="Lenguaje de programación de código abierto, 
      su acrónimo PHP hace referencia a Hypertext Preprocessor. Cuando se dice de código abierto 
      indica que normalmente estos softwares son gratuitos y es posible acceder a su código fuente. 
      El origen de PHP se remonta a 1995 cuando Rasmus Lerdorf desarrollo el producto PHP/FI, 
      el que consistía en un conjunto de Scripts de Perl a los que llamó Personal Home Page Tools. 
      Ramus Lerdorf en vista de la necesidad de dotar de mayor funcionalidad a sus scripts, 
      fue escribiendo una mayor implementación utilizando C que permitía la comunicación 
      con Bases de Datos y el desarrollo de aplicaciones web dinámicas." />

      <Bloque title="¿Cómo funciona?" text="El usuario escribe una URL una ruta o dirección para 
      poder localizar una página web, imagen, servidor etc. en su navegador y éste envía una petición 
      al servidor web. Un servidor web es la maquina o computador donde se almacena una página web. 
      El servidor lee la página PHP (la interpreta). Envía al navegador del usuario un documento compilado en formato HTML." />


      <div class="list-group">
        <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
          ¿Qué puede hacer?
        </a>
        <a class="list-group-item list-group-item-action">Ejecutar Scripts en la parte del servidor.</a>
        <a class="list-group-item list-group-item-action">Son necesarios: Analizador PHP (CGI ó módulo), un servidor web y navegador.</a>
        <a class="list-group-item list-group-item-action">Ejecución de Scripts desde la línea de comandos.</a>
        <a class="list-group-item list-group-item-action">Escritura de aplicaciones gráficas clientes por medio de una extensión llamada PHP-GTK.</a>
        <a class="list-group-item list-group-item-action">Puede ser utilizado en Linux, Unix, Microsoft Windows, Mac OS X, RISC OS, etc.</a>
        <a class="list-group-item list-group-item-action">Soporta Apache, Microsoft Internet Information Server, Personal Web Server, y etc.</a>
      </div>

      <br/>
      <br/>
      <ul class="list-group">
        <div class="p-3 bg-info bg-opacity-10 p-2 mb-2">VENTAJAS DE UTILIZAR PHP</div>
        <a class="list-group-item list-group-item-action list-group-item-info">Es libre y de código abierto.</a>
        <a class="list-group-item list-group-item-action list-group-item-info">Su curva de aprendizaje es rápida.</a>
        <a class="list-group-item list-group-item-action list-group-item-info">Se puede obtener fácil acceso a diferentes sistemas de gestión de bases de datos.</a>
        <a class="list-group-item list-group-item-action list-group-item-info">La programación en este lenguaje se puede hacer desde cualquier editor de texto.</a>
        <a class="list-group-item list-group-item-action list-group-item-info">Existe una comunidad muy grande alrededor del mundo desarrollando en PHP y mejorándolo día a día.</a>
        <a class="list-group-item list-group-item-action list-group-item-info">El cliente, hace la petición al servidor, éste ejecuta acciones y devuelve información al cliente.</a>
      </ul>
      <br/>
      <ul class="list-group">
        <div class="p-3 bg-info bg-opacity-10 p-2 mb-2">¿Qué se necesita para ejecutar ficheros PHP?</div>
        <a class="list-group-item list-group-item-action list-group-item-info">✓ Un servidor con soporte activado para PHP.</a>
        <a class="list-group-item list-group-item-action list-group-item-info">✓ Ficheros con la extensión .php, que han de ser tratados por PHP.</a>
        <a class="list-group-item list-group-item-action list-group-item-info">✓ Es habitual tener instalada una base de datos como MySQL o análoga.</a>
      </ul>
      <br/>
      
      <br />
    </div>

      <div class="container text-center">
      <div class="col-lg-6 mx-auto">
        <Bloque title="Variables" text="Las variables se representan con un signo de dólar ($) seguido por el nombre, 
        que es sensible a minúsculas y mayúsculas.
        Un nombre de variable válido tiene que empezar con una letra o con un carácter 
        de subrayado, seguido de letras, números y caracteres de subrayado, sin espacios:" />

        <div class="text-center">
          <div class="border border-success p-2 mb-2"> <h7>El operador de asignación es =</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>El operador comparador de igualdad es ==</h7></div>
          </div>
          <br/>
          
            <Bloque text="Variables reservadas son las que PHP define con valores por defecto, están disponibles sin necesidad 
            de requerir librerías y no se puede cambiar su contenido:" />

          <div class="text-center">
            <div class="border border-success p-2 mb-2"> <h7>$_SERVER: Información del entorno del servidor y de ejecución.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>$_GET: Variables en el encabezado HTTP GET.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>$_POST: Variables recibidas en el encabezado HTTP GET.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>$_COOKIE: Variable con la cual podemos crear, acceder, editar o destruir Cookie.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>$_FILES: Variables que llegan al servidor con archivos mediante carga.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>$_REQUEST: Es una variable de array asociativo que por defecto contiene el contenido de $_GET, $_POST y $_COOKIE.</h7></div>
            </div> 
            <br/>
      </div>

            <div class="container text-center">
            <div class="col-lg-6 mx-auto">
              <Bloque title="Modo Local" text="Si deseamos trabajar en modo local, existen muchos servidores de prueba gratuitos como WampServer, 
              Xampp o AppServ que instalan el servidor web, el intérprete PHP y el servidor de bases de datos MySQL." />
            </div>
            </div>
      
      </div>
      <div class="col-lg-6 mx-auto">
        <h5>Consideraciones especiales:</h5>
        <div class="text-center">
            <div class="border border-success p-2 mb-2"> <h7>-	La instrucción echo permite escribir en pantalla un texto o el contenido de una variable.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>-	En PHP no hace falta declarar una variable. Es un espacio de memoria en el computador destinado para almacenar un valor. antes de su uso, ni establecer su tipo.</h7></div>
            </div>
        <br/>
      </div>
      <div class="col-lg-6 mx-auto">
        <Bloque title="Tipos de datos" text="En PHP no es obligatorio indicar el tipo de datos al que pertenece una variable. Existen los siguientes tipos:
        integer: enteros positivos, negativos (se pueden representar en hexadecimal) float, double: con decimales string: cadena de caracteres boolean: tipo lógico, valores true o false." />
      </div> 


      <div class="container text-center">
        <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 8- Loops, Arreglos, Funciones.</h2></div>
        <br/>
      </div>
      <br />
      <div class="col-lg-6 mx-auto">
      <Bloque title="Loops- Bucles" text="En php un bucle es usado para ejecutar una declaración o un bloque de declaraciones, varias veces hasta cumplir la condición específica. PHP soporta:" />
    </div>

    <div class="col-lg-6 mx-auto">
      <Bloque title="▸for loop" text="Se utiliza cuando el usuario sabe de antemano cuántas veces debe ejecutarse el bloque. Es decir, el número de iteraciones se conoce de antemano." />
      <div class="text-center">
        <div class="border border-success p-2 mb-2"> <h7>-Se conocen como bucles controlados por entrada.	</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>-Hay tres parámetros principales para el código: la inicialización, la condición de prueba y el contador.</h7></div>
        </div>
    </div>
    <br/>
    <div class="col-lg-6 mx-auto">
      <Bloque title="▸while loop" text="Es un conocido como un ciclo de control de entrada, primero verifica la condición al comienzo del ciclo y, si es verdadero, ingresa al ciclo y ejecuta el bloque de instrucciones, y continúa ejecutándolo como siempre y cuando la condición sea cierta." />
    </div>
    <div class="col-lg-6 mx-auto">
      <Bloque title="▸do-while loop" text="Bucle de control de salida, es decir que primero ingresa al bucle, ejecuta las declaraciones y luego verifica la condición. Por ende, una declaración se ejecuta al menos una vez al usar el bucle do..while.  Después de ejecutar una vez, el programa se ejecuta siempre que la condición sea verdadera." />
    </div>
    <div class="col-lg-6 mx-auto">
      <Bloque title="▸foreach loop" text="Se utiliza para iterar sobre matrices. Para cada contador de bucle, se asigna un elemento de matriz y el siguiente contador se desplaza al siguiente elemento." />
    </div>
    <div class="col-lg-6 mx-auto">
      <Bloque title="Arrays" text="Son un tipo de estructura de datos que nos permite almacenar múltiples elementos de un tipo de datos similar en una sola variable, lo que nos ahorra el esfuerzo de crear una variable diferente para cada dato. Estos permiten crear una lista de elementos similares, a los que se puede acceder utilizando su índice o clave." />
    </div>
    <div class="col-lg-6 mx-auto">
    <Bloque
        title="Tipos de matrices en PHP:"
        text="Matrices indexadas o numéricas: una matriz con un índice numérico donde los valores se almacenan linealmente."
      />
        <div class="text-center">
        <div class="border border-success p-2 mb-2"> <h7>Usan números como claves de acceso.</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>La clave de acceso es una referencia a una ranura de memoria en una variable de matriz.</h7></div>
        <div class="border border-success p-2 mb-2"> <h7>La clave de acceso es utilizada cuando queremos leer o asignar un nuevo valor a un elemento de matriz.</h7></div>
      </div>
      <Bloque
        title="▸ Matrices asociativas: "
        text="Una matriz con un índice de cadena donde en lugar de almacenamiento lineal, a cada valor se le puede asignar una clave específica. Usan nombres descriptivos para claves de identificación."
      />
      <Bloque
        title="▸ Matrices multidimensionales: "
        text="Una matriz que contiene una matriz única o múltiple dentro de ella y se puede acceder a través de múltiples índices.
        Contienen otras matrices anidadas. Permiten agrupar datos relacionados."
      />
      </div>
      <div class="col-lg-6 mx-auto">
        <h5>Array Functions</h5>
        <div class="text-center">
            <div class="border border-success p-2 mb-2"> <h7>Count(): se usa para contar el número de elementos que contiene una matriz php.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>Is_array(): se usa para determinar si una variable es una matriz o no.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>sort(): se utiliza para ordenar las matrices por los valores. Si los valores son alfanuméricos, los ordena en orden alfabético y si los valores son numéricos, los ordena en orden ascendente. Elimina las claves de acceso existentes y agrega nuevas claves numéricas. La salida de esta función es una matriz numérica.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>Ksort(): se usa para ordenar la matriz usando la clave.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>Asort(): se usa para ordenar la matriz usando los valores.</h7></div>
          </div>
        <br/>
      </div>
      <div class="col-lg-6 mx-auto">
        <Bloque title="Funciones" text="En PHP las funciones son una pieza o bloque de código reutilizables que realiza una función específica. Toma la entrada del usuario en forma de parámetros, realiza ciertas acciones y da la salida. Las funciones pueden devolver valores cuando se les llama o simplemente pueden realizar una operación sin devolver ningún valor." />
        <div class="text-center">
          <h5>¿Por qué usar funciones?</h5>
        <div class="text-center">
            <div class="border border-success p-2 mb-2"> <h7>Mejor organización del código: las funciones de PHP permiten agrupar bloques de código relacionado que realizan una tarea específica juntos.</h7></div>
            <div class="border border-success p-2 mb-2"> <h7>Reutilización: una vez definida, una función puede ser llamada por varios scripts en nuestros archivos PHP. </h7></div>
            <div class="border border-success p-2 mb-2"> <h7>Fácil mantenimiento: las actualizaciones del sistema solo deben realizarse en un lugar.</h7></div>
        </div>
      </div>
      </div>
      <br/>
      <div class="col-lg-6 mx-auto">
      <div class="text-center">
        <h5>Funciones integradas de PHP: son funciones predefinidas en PHP, existen funciones:</h5>
      <div class="text-center">
          <div class="border border-success p-2 mb-2"> <h7>Funciones de cadena</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Funciones numéricas</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Funciones de fecha</h7></div>
      </div>
      </div>
    </div>
      <br/>

      <div class="col-lg-6 mx-auto">
      <div class="text-center">
        <h5>Funciones definidas por el usuario</h5>
      <div class="text-center">
          <div class="border border-success p-2 mb-2"> <h7>Existen tareas de rutina en su aplicación, como agregar datos a la base de datos.</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Realizar comprobaciones de validación de los datos.</h7></div>
          <div class="border border-success p-2 mb-2"> <h7>Autenticar usuarios en el sistema, entre otras.</h7></div>
      </div>
      </div>
      </div>
      <br/>
      <br/>

      <div class="container text-center">
        <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 9: Programación orientada a objetos.</h2></div>
      </div>
      <div class="col-lg-6 mx-auto">
        <Bloque text="Las clases especifican las características de un conjunto de objetos, y un objeto es la instancia de una clase. Un objeto es un modelo de los objetos que se encuentran en el mundo real, 
        estos objetos contienen información que será utilizada para resolver un grupo de tareas con características en común; además poseen funcionalidades concretas, es decir específicas para cada objeto." />
      </div>
      <div class="col-lg-6 mx-auto">
        <Bloque title="Conceptos Básicos de POO en PHP" text="Es un paradigma de programación que usa objetos y sus interacciones para diseñar aplicaciones y programas de computadora. 
        Se basa en varias técnicas incluyendo herencia, modularidad, polimorfismo, y encapsulamiento. Su uso se popularizó a principios de la década de 1990. 
        Actualmente son muchos los lenguajes de programación que soportan la orientación a objetos. 
        El término de POO indica más una forma de diseño y una metodología de desarrollo de software que un lenguaje de programación, 
        ya que en realidad se puede aplicar el Diseño Orientado a Objetos, a cualquier tipo de lenguaje de programación.
        " />
        </div>

        <div class="col-lg-6 mx-auto">
        <div class="container text-center">
          <div class="row g-2">
            <div class="col-6">
              <div class="bg-info-subtle p-2 text-dark bg-opacity-10">Abstracción</div>
            </div>
            <div class="col-6">
              <div class="bg-info-subtle p-2 text-dark bg-opacity-10">Encapsulamiento</div>
            </div>
            <div class="col-6">
              <div class="bg-info-subtle p-2 text-dark bg-opacity-103">
                <div class="text-center">
                  <div class="border border-success p-2 mb-2"> <h7>Es un proceso de interpretación y diseño que implica reconocer y enfocarse en las características importantes de una situación u objeto, y filtrar o ignorar todas las particularidades no esenciales.</h7></div>
                  <div class="border border-success p-2 mb-2"> <h7>Dejar a un lado los detalles de un objeto y definir las características específicas de éste.</h7></div>
                  <div class="border border-success p-2 mb-2"> <h7>Centrarse en lo que es y lo que hace un objeto, antes de decidir cómo debería ser implementado.</h7></div>
              </div></div>
            </div>
            <div class="col-6">
              <div class="bg-info-subtle p-2 text-dark bg-opacity-10"><div class="text-center">
                <div class="border border-success p-2 mb-2"> <h7>Permite asegurar que la información del un objeto está oculta del mundo exterior.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>Consiste en agrupar en una Clase los tributos con un acceso privado y los métodos con un acceso público.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>Acceder o modificar los miembros de una clase a través de sus métodos.</h7></div>
            </div></div>
            </div>
          </div>
        </div>
        </div>
        <br/>
        <div class="col-lg-6 mx-auto">
          <div class="container text-center">
            <div class="row g-2">
              <div class="col-6">
                <div class="bg-info-subtle p-2 text-dark bg-opacity-10">Herencia</div>
              </div>
              <div class="col-6">
                <div class="bg-info-subtle p-2 text-dark bg-opacity-10">Polimorfismo</div>
              </div>
              <div class="col-6">
                <div class="bg-info-subtle p-2 text-dark bg-opacity-103">
                  <div class="text-center">
                    <div class="border border-success p-2 mb-2"> <h7>Permite crear clases a partir de otras ya existentes, obteniendo métodos y atributos similares a los ya existentes.</h7></div>
                    <div class="border border-success p-2 mb-2"> <h7>La nueva clase puede utilizar la misma implementación de su superclase o especificar una nueva implementación.</h7></div>
                    <div class="border border-success p-2 mb-2"> <h7>Es la relación entre una clase general y otra clase más especifica.</h7></div>
                    <div class="border border-success p-2 mb-2"> <h7>Es un mecanismo que nos permite crear clases derivadas a partir de clases base.</h7></div>
                    <div class="border border-success p-2 mb-2"> <h7>Nos permite compartir automáticamente métodos y datos entre clases, subclases y objetos.</h7></div>
                  
                  </div></div>
              </div>
              <div class="col-6">
                <div class="bg-info-subtle p-2 text-dark bg-opacity-10"><div class="text-center">
                  <div class="border border-success p-2 mb-2"> <h7>Son comportamientos diferentes, asociados a objetos distintos, pueden compartir el mismo nombre; al llamarlos por ese nombre se utilizará el comportamiento correspondiente al objeto que se esté usando.</h7></div>
                  <div class="border border-success p-2 mb-2"> <h7>Sistemas Orientados a Objetos:</h7></div>
                  <div class="border border-success p-2 mb-2"> <h7>- Son aquellos que en su código interno están formados por instancias de clases que interactúan entre sí para lograr un objetivo común.</h7></div>
                  <div class="border border-success p-2 mb-2"> <h7>- La OOP surge bajo la premisa de mejorar el ciclo de Desarrollo de Software, hacerlo más claro, ordenado, eficiente, reutilizable y fácil de mantener.</h7></div>
                </div>
              </div>
              </div>
            </div>
          </div>
          </div>
          <br/>
          <div class="col-lg-6 mx-auto">
            <Bloque title="¿Qué es una Clase?" text="Hace referencia a la implementación total o parcial de un tipo abstracto de dato, para mayor comprensión podemos visualizar las clases como los 
            esquemas o moldes que nos permitirán crear objetos o instancias concretas. " />
          </div>
          <div class="col-lg-6 mx-auto">
            <Bloque title="Entidad" text="Es empleada para denominar todo aquello cuya existencia es perceptible por algún sistema animado, en la POO está íntimamente relacionado con la identificación de clases." />
          </div>
          <div class="col-lg-6 mx-auto">
            <Bloque title="Componentes de las clases"/>
            <ul class="list-group">
              <li class="list-group-item list-group-item-dark">✓ Atributos: características propias de cada objeto, que nos permiten diferenciarlo de otros.</li>
              <li class="list-group-item list-group-item-dark">✓ Métodos: Son las acciones que puede realizar un objeto o clase</li>
              <li class="list-group-item list-group-item-dark">✓ Método Constructor: es un método público de uso específico que todas las clases lo integran de manera predeterminada, es utilizado para crear una instancia de una clase.</li>
              <li class="list-group-item list-group-item-dark">✓ Parámetros: valores que se pasan como argumentos para crear un objeto, para ejecutar una función o para llevar a cabo una acción específica.</li>
              <li class="list-group-item list-group-item-dark">✓ Instancia u objeto: implementación real o concreta de un tipo de dato (Clase), esta adopta todas las características de la clase y puede utilizar todos los métodos y propiedades ahí definidos. Los objetos pueden interactuar con otros objetos y cambiar sus propiedades.</li>
            </ul>
          </div>
          <br/>

          <div class="col-lg-6 mx-auto">
            <Bloque title="Ventajas de las Clases sobre la programación funcional"/>
            <ul class="list-group">
              <li class="list-group-item list-group-item-dark">✓ “La POO es un conjunto de técnicas para obtener calidad interna en nuestro código como medio para obtener calidad externa”. </li>
              <li class="list-group-item list-group-item-dark">✓ Cuando se trabaja con POO es que es obligatorio realizar un análisis de nuestra aplicación e identificar con anticipación el conjunto de clases que se implementarán, esto no es necesariamente así en la programación funcional.</li>
              <li class="list-group-item list-group-item-dark">✓ Se expanden las posibilidades de desarrollo, ya que no hay restricciones en los tipos de datos.</li>
              <li class="list-group-item list-group-item-dark">✓ Estructuras de datos heterogéneas.</li>
              <li class="list-group-item list-group-item-dark">✓ Permite la reutilización de componentes software.</li>
              <li class="list-group-item list-group-item-dark">✓ Es muy fácil organizar de manera adecuada el código y se aprecia una proyección más comprensible de cómo funcionará la aplicación.</li>
              </ul>
          </div>
          <br/>

          <div class="col-lg-6 mx-auto">
            <Bloque title="Utilidad de la creación de un Modelo" text="Un modelo es una representación del software que necesitamos desarrollar, el modelado es esencial en la construcción de software ya que permite:"/>
            <ul class="list-group">
              <li class="list-group-item list-group-item-dark">✓ Comunicar la estructura compleja. </li>
              <li class="list-group-item list-group-item-dark">✓ Especificar el comportamiento deseado del sistema.</li>
              <li class="list-group-item list-group-item-dark">✓ Comprender mejor lo que estamos construyendo.</li>
              <li class="list-group-item list-group-item-dark">✓ Descubrir oportunidades para simplificar el el funcionamiento del programa.</li>
              <li class="list-group-item list-group-item-dark">✓ Reutilizar el código que hemos creado.</li>
              </ul>
          </div>
          <br/>
          <br/>

  
          <div class="container text-center">
            <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 10- Clases abstractas-Interfaces</h2></div><br/>

          </div>

          <div class="col-lg-6 mx-auto">
        <Bloque title="Clases abstractas" text="-	Estas no pueden ser instanciada, pero pueden declarar la existencia de los métodos, 
        pero no su implementación. Puede contener métodos no-abstractos, pero debe de contener al menos un método abstracto. De igual forma los métodos abstractos deben ser definidos en las clases heredadas, pero deben tener la misma visibilidad. La implementación debe tener la misma “firma”: la declaración de tipos y el número de argumentos. Pueden definir métodos y propiedades abstractas, con lo que su respectiva implementación en la subclase es obligatoria. Los elementos abstractos DEBEN ser sobrescritos en la subclase. Y se utiliza “abstract” para definir 
        elementos abstractos (solo dentro de clases abstractas)." />
        </div>
        </div>
        <div class="col-lg-6 mx-auto">
          <h5>Miembros abstractos</h5>
          <div class="text-center">
              <div class="border border-success p-2 mb-2"> <h7>-	Puede tener atributos e implementar métodos y propiedades como una clase normal, además puede tener miembros abstractos (métodos y propiedades).</h7></div>
              <div class="border border-success p-2 mb-2"> <h7>-	Los miembros abstractos NO tienen implementación (están vacíos).</h7></div>
              </div>
            </div>
            <br/>

        <div class="col-lg-6 mx-auto">
          <h5>Interfaces</h5>
            <div class="text-center">
                <div class="border border-success p-2 mb-2"> <h7>-	Son mecanismos para que puedan interactuar varios objetos no relacionados entre sí.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Son protocolos o “contratos” que obligan la herencia.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Contienen las declaraciones de los métodos, pero no su implementación.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Son plantillas de comportamiento que deben ser implementados por otras clases.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Una clase que herede de una interfase debe implementar todas las definiciones contenidas en ella.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Los elementos de la interfase no llevan los modificadores “public” o “abstract”.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	TODOS los elementos declarados dentro de una inteface se consideran públicos y abstractos.</h7></div>
              </div>
        </div>
        <br/>
        <br/>


        <div class="container text-center">
          <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 11- Introducción a Laravel, Características, Ecosistema, Servidores, Instalación en Windows, Conectando a una BD MySQL con Laravel.</h2></div>
        </div>
        <div class="col-lg-6 mx-auto">
          <Bloque title="¿Qué es MVC?" text="Modelo-Vista-Controlador es un patrón arquitectónico que separa una aplicación en tres componentes lógicos principales Modelo, Vista y Controlador.
          Cada componente de la arquitectura está construido para manejar un aspecto de desarrollo específico de una aplicación. MVC separa la lógica empresarial y la capa de presentación entre sí.
          " />
        </div>
        <div class="col-lg-6 mx-auto">
          <Bloque title="HTTP" text="Protocolo que permite la obtención de recursos, como documentos HTML. Es la base de cualquier intercambio de datos en la Web y es un protocolo cliente-servidor, lo que significa que las solicitudes son iniciadas por el destinatario, generalmente el navegador Web." />
        </div>
    
        <div class="col-lg-6 mx-auto">
          <Bloque text="Utiliza métodos de solicitud específicos para realizar diversas tareas. Todos los servidores HTTP utilizan los métodos GET y HEAD, pero no todos admiten el resto de estos métodos de solicitud:" />
            <div class="text-center">
                <div class="border border-success p-2 mb-2"> <h7>GET solicita un recurso específico en su totalidad</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>HEAD solicita un recurso específico sin el contenido del cuerpo. </h7></div>
                <div class="border border-success p-2 mb-2"> <h7>POST agrega contenido, mensajes o datos a una nueva página en un recurso web existente.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>PUT modifica directamente un recurso web existente o crea un nuevo si es necesario.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>DELETE se deshace de un recurso específico.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>TRACE muestra a los usuarios cualquier cambio o adición realizada a un recurso web.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>OPCTIONS muestra a los usuarios qué métodos HTTP están disponibles para una URL específica.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>CONNECT convierte la conexión de solicitud en un túnel TCP / IP transparente.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>PATCH modifica parcialmente un recurso web. </h7></div>
                
              </div>
        </div>
        <br/>
        <div class="col-lg-6 mx-auto">
          <Bloque title="El servidor" text="Un servidor es como un recibidor. Se encuentra en la entrada del bar o aplicación web." />
        </div>
        <br/>
        <div class="col-lg-6 mx-auto">
          <Bloque title="El middleware" text="Permite establecer comunicación entre varias tecnologías. Se ubicará entre un servidor y el cliente. Funciona como vigilante." />
        </div>
        <div class="col-lg-6 mx-auto">
          <Bloque title="El controlador" text="Son el vinculo entre lo que ve el usuario y el sistema entre sí. Responde a un conjunto de órdenes. Procesa el conjunto de órdenes. Las rutas son la columna vertical de la aplicación." />
        </div>
        <div class="col-lg-6 mx-auto">
          <Bloque title="GET/POST" text="Hay cuatro verbos de solicitud HTTP básicos: GET, POST, PUT y DELETE." />
        </div>
        <div class="col-lg-6 mx-auto">
            <div class="text-center">
                <div class="border border-success p-2 mb-2"> <h7>GET se usa para recuperar y enumerar información, como obtener un menú, tomar una bebida u obtener un número de cheque de abrigo.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>POST se utiliza para crear una nueva entrada en la base de datos de la aplicación, como agregar al inventario de una barra o revisar su abrigo.</h7></div>
              </div>
        </div>
        <div class="col-lg-6 mx-auto">
          <Bloque title="Las vistas" text="-Una solicitud GET puede generar una vista. Todo Lo que el usuario está visualizando." />
          <Bloque title="El modelo" text="-Que cosas se van a necesitar." />
        </div>

        <div class="col-lg-6 mx-auto">
          <Bloque title="¿Qué es Laravel?" text="Es un Framework con una sintaxis elegante y expresiva. Un Framework proporciona una estructura y un punto de partida para crear aplicaciones.
          Se esfuerza por proporcionar una experiencia de desarrollador increíble, al tiempo que proporciona funciones poderosas como la inyección de dependencias exhaustiva, una capa de abstracción de base de datos expresiva, colas y trabajos programados, pruebas de integración y unidad, y más.
          " />
        </div>

        <div class="col-lg-6 mx-auto">
          <h5>Características:</h5>
            <div class="text-center">
                <div class="border border-success p-2 mb-2"> <h7>-	Un sistema de rutas, mediante las cuales es fácil crear y mantener todo tipo de URLs amistosas a usuarios y buscadores, rutas de API, etc.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Un sistema de abstracción de base de datos, con un ORM potente pero sencillo de manejar, mediante el que podemos tratar los datos de la base de datos como si fueran simples objetos.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Un sistema para creación de colas de trabajo, de modo que es posible enviar tareas para ejecución en background y aumentar el rendimiento de las aplicaciones.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Varias configuraciones para envío de email, con proveedores diversos.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Un sistema de notificaciones a usuarios, mediante email, base de datos y otros canales.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Una abstracción del sistema de archivos, mediante el cual podemos escribir datos en proveedores cloud, y por supuesto en el disco del servidor, con el mismo código.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>-	Gestión de sesiones.</h7></div>
              </div>
        </div>
        <br/>
        <div class="col-lg-6 mx-auto">
          <h5>Servidores</h5>
            <div class="text-center">
                <div class="border border-success p-2 mb-2"> <h7>Servidor interno: seria la opción más básica, que se consigue mediante un simple comando de consola. php artisan serve.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>Laravel Valet: disponible para Mac, permite crear virtuales hosts mediante comandos de consola.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>Homestead: esta opción es la más avanzada y se basa en virtualización, con lo que se obtiene un entorno profesional que se adapta a las condiciones del servidor.</h7></div>
                <div class="border border-success p-2 mb-2"> <h7>Cualquier otro servidor web habitual: por supuesto, Laravel además puede usarse cualquier servidor local PHP que se disponga, entre los que recomendamos Laragon, Xampp o Mamp.</h7></div>
                </div>
        </div>
        <br/>




        <div class="col-lg-6 mx-auto">
          <Bloque title="Instalación" text="Laravel utiliza composer para manejar sus dependencias, el framework Laravel hace uso de una colección de paquetes o componentes propios y de terceros para agregarle funcionalidades a las aplicaciones. Por tanto, es necesario un gestor de dependencias que se encargue automáticamente de crear proyectos, instalar, actualizar o eliminar componentes y a su vez las dependencias de éstos." />
        </div>

        <div class="container text-center">
          <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end"><h2>Semana 12- CRUD con Laravel-Formularios con Laravel.</h2></div><br/>

        </div>

        <div class="col-lg-6 mx-auto">
      <Bloque title="¿Cómo crear un CRUD?" text="-	Se crea la tabla para la cual se creara el CRUD, seguido se realizara el proceso de migración." />
      <img
        src="../assets/tarea/c.jpg"
        class="img-fluid mb-5"
        alt="Jornalizacion"
        width="700"
        height="700"
    />
    <Bloque title="" text="-	Agregar la ruta de recursos." />
      <img
        src="../assets/tarea/d.jpg"
        class="img-fluid mb-5"
        alt="Jornalizacion"
        width="700"
        height="700"
    />
    <Bloque title="" text="-	Crear controlador y modelo." />
      <img
        src="../assets/tarea/r.jpg"
        class="img-fluid mb-5"
        alt="Jornalizacion"
        width="700"
        height="700"
    />
    <Bloque title="" text="-	Crear controlador y modelo." />
      <img
        src="../assets/tarea/u.jpg"
        class="img-fluid mb-5"
        alt="Jornalizacion"
        width="700"
        height="700"
    />
    <Bloque title="" text="-	Editar modelo." />
      <img
        src="../assets/tarea/dd.jpg"
        class="img-fluid mb-5"
        alt="Jornalizacion"
        width="700"
        height="700"
    />
    <Bloque title="" text="-	Agregar vistas." />
      <img
        src="../assets/tarea/v.jpg"
        class="img-fluid mb-5"
        alt="Jornalizacion"
        width="700"
        height="700"
    />
    <img
        src="../assets/tarea/a.jpg"
        class="img-fluid mb-5"
        alt="Jornalizacion"
        width="700"
        height="700"
    />
    <img
        src="../assets/tarea/f.jpg"
        class="img-fluid mb-5"
        alt="Jornalizacion"
        width="700"
        height="700"
    />
    <img
        src="../assets/tarea/g.jpg"
        class="img-fluid mb-5"
        alt="Jornalizacion"
        width="700"
        height="700"
    />
    <Bloque title="" text="-	Ejecutar la aplicación." />
    <img
      src="../assets/tarea/ar.jpg"
      class="img-fluid mb-5"
      alt="Jornalizacion"
      width="700"
      height="700"
    />


      </div>
      </div>

















</template>
