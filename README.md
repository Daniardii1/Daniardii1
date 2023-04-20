<h1 align="center">Hi 👋, I'm Daniel Cifuentes Jimenez</h1>
<h3 align="center">A passionate software developer from Spain</h3>

- 🌱 I’m currently learning **C#, SOLID and Clean Code, Docker and design patterns among others**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/daniardii1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="daniardii1" height="30" width="40" /></a>
<a href="https://www.linkedin.com/in/daniel-cifuentes-jimenez/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/daniel-cifuentes-jimenez/" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> </p>

**C#**

Se trata de un lenguaje de *alto nivel* y *POO*, diseñado por Microsoft para la plataforma .NET. En cuanto a sus características se encuentran: 

- ***Tipado estático (***y además ***fuertemente tipado)***, pues las variables y expresiones deben ser declaradas con un tipo específico y su tipo no puede cambiar durante la ejecución del programa. 
- ***Gestión automática de memoría,*** ya que utiliza un recolector de basura para gestionar la memoria, lo que quiere decir que el programador no debe preocuparse por liberar memoria utilizada por objetos que ya no se utilizan. 
- ***Seguridad de tipos,*** ya que realiza comprobaciones en tiempo de compilación para garantizar que los tipos de las variables y expresiones son coherentes y seguros. 
- ***Interoperabilidad,*** pues está diseñado para funcionar en conjunto con otros lenguajes y tecnologías de .NET, como Visual Basic, C++ y ASP.NET. 
- ***Multiplataforma,*** pues a partir de la llegada de .NET Core, los programas escritos en C# puede ejecutarse en Windows, macOS y Linux. 
- ***Asincrónico,*** pues cuenta con un fuerte soporte para la programación asincrónica, permitiendo programas que realicen múltiples tareas en paralelo. Esto se lleva a cabo con palabras clave como *async* y *await.* 

C# es un lenguaje diseñado para compilar a **CIL (Common Intermediate Language,** antes conocido como MSIL, *Microsoft Intermediate Language***)** y, posteriormente, ser ejecutado en la plataforma .NET a través del **CLR (Common Language Runtime)**, esta práctica es la que hace posible que el código C# se pueda ejecutar en diferentes plataformas, ya que CIL es independiente de las plataformas, por lo que mientras la plataforma tenga instalado el CLR correspondiente podrá ejecutar la aplicación. 



**CIL →** Es un lenguaje intermedio utilizado por .NET y generado por el compilador de C# (o cualquier otro lenguaje .NET). Este lenguaje es independiente de la plataforma, y aunque se parece al lenguaje ensamblador, es más fácil de leer y escribir y de más alto nivel. Sus instrucciones se llaman *opcodes* y representan todas las operaciones que se pueden realizar en .NET, éstas son compiladas en código nativo y posteriormente ejecutadas por el  CLR. 

**CLR →** Entorno de ejecución de tiempo de ejecución que compila el código CIL en código máquina para que se pueda ejecutar en el SO subyacente. Además proporciona características importantes como la **gestión automática de la memoria, el control de excepciones, la seguridad de tipos y la recolección de basura**; así como una amplia biblioteca de clases y tipos base. 

- **Garbage collector →** se encarga de administrar la memoria utilizada por los programas en tiempo de ejecución. Su objetivo principal es liberar la memoria que ya no es necesaria o que ha quedado inaccesible para el programa, evitando así fugas de memoria o errores por referencias inválidas, es decir permite administrar de forma segura. Es el encargado de permitir la **gestión automática de memoria**. 

Cuando hablamos de ***unmanaged resources (recursos no administrados)*** debemos de tener en cuenta que entonces somos nosotros los encargados de administrar manualmente la memoria y de liberarla, para ello debemos usar el método .**Dispose()** que libera la memoria de ese componente. 

-----

<a name="_pix1r13fo965"></a>**ESTRUCTURA PROYECTO**

- **.sln →** archivo de solución de VS, es un archivo de texto que describe la estructura del proyecto. Contiene información sobre qué proyectos se incluyen en la solución, cómo se relacionan entre sí y cómo se construyen. También tiene información sobre la configuración de depuración y lanzamiento. 
- **.csproj →** archivo de proyecto de VS, es un archivo XML que describe los archivos que se incluyen en el proyecto, así como sus referencias, propiedades y configuración de compilación. Es el archivo utilizado por el compilador de C# para generar el archivo ejecutable. 
- **.cs →** archivos de código fuente de C# que contienen el c´dogio que define las clases, interfaces y otros tipos que se utilizan en el proyecto, son los que contienen la lógica de la aplicación y se compilan para generar el archivo ejecutable. 
-----

<a name="_1hd20mkh29x0"></a>**SINTAXIS** 

La **sintaxis** es la apariencia y estructura del código; mientras que la **semántica** es lo que representa las partes del código, permitiéndonos conocer cómo se comporta al ejecutarse. 

Todas las **sentencias** en C# deben terminar con **;** . 

<a name="_4bnnmdbeqtic"></a>**Tipos de datos**

Existen dos tipos de conversiones de datos: 

- **Conversión implícita/automática →**  la cual es permitida únicamente entre los siguientes tipos de datos: 

- sbyte → short, int, long, float, double, decimal
- byte → short, ushort, int, uint, long, ulong, float, double, decimal
- short → int, long, float, double, decimal
- ushort → int, uint, long, ulong, float, double, decimal
- int → long, float, double, decimal
- uint → long, ulong, float, double, decimal
- long → float, double, decimal
- char → ushort, int, uint, long, ulong, float, double, decimal
- float → double

Cabe destacar que si el valor a convertir no se encuentra dentro del rango permitido por el tipo de destino, se producirá un error, pues para que sea posible se requerirá de una conversión explícita mediante el operador de conversión correspondiente. 

- **Conversión explícita →** aquella en la que se especifica de forma explícita una conversión de un tipo de dato a otro mediante una expresión de conversión. P.e **(tipodedatonuevo)datoviejo**

Otra opción para realizar una conversión segura de tipos (**casting**) es a través de **as** que en caso de no poder realizar la conversión porque ésta sea incompatible, devuelve un ***null***, en vez de lanzar una excepción. **tipodedatoviejo as tipodedatonuevo** P.e 

**object obj = “Hola mundo”;** 

**string str = obj as string;** 

**if (str != null)** 

**{**

`     `**Console.WriteLine(str);**

**}**

**else** 

**{**

`      `**Console.WriteLine(“No se pudo convertir el objeto a string.”);**

**}**

**>Tipos de datos simples/básicos/primitivos** que permiten almacenar un único valor, el cual se encuentra en la memoria (esto quiere decir que las variables de estos tipos de datos contienen una copia del valor real en lugar de una referencia a una ubicación de memoria). Datos que se almacenan en la pila/steak.  

**Nota →** en C# es posible el uso de **var** también en los tipos de datos simples (tal y como ocurre con los complejos) permitiendo declarar variables (a la vez que se inicializan, sino no funciona) sin indicar explícitamente el tipo, ya que el compilador toma el tipo según lo que se indique a la derecha. Esta práctica **solo es posible dentro de métodos y bucles.** 

P.e 	

**var nombreVariable = valorVariable;**	     en vez de	**tipodeDato nombreVariable = valorVaribale;** 

- Tipos numéricos enteros → hay 4 tipos para almacenar enteros en Java. Se diferencian entre sí por el nº de bytes utilizados en el almacenamiento y el rango de valores que pueden representar. Permiten el almacenamiento de números negativos y positivos. 

- **Bytes →** Variable más pequeña que ocupa un único byte en memoria. 

Puede ser ***byte*** que va de 0 a 255 o bien ***sbyte*** que tiene en cuenta el signo y va de -128 a 127. 

**byte nombrevar = num;** 

- **Short →** almacena valores de -32768 a 32767 y ocupa 2 bytes de memoria. También puede ser ***ushort*** en cuyo caso va desde 0 a 65535.	     **short nombrevar = num;** 

- **Int →** almacena valores -2\*10^9 a 2\*10^9 y ocupa 4 bytes de memoria. También puede ser ***uint*** en cuyo caso va desde 0 a 4\*10^9.	**int nombrevar = num;** :

- **Long →** es mucho más grande que el anterior y ocupa 8 bytes. Se utiliza también para contener datos digitales. Siguiendo el mismo patrón de short e int, existe ***ulong***. 

**long creditCardNumber= 1234\_5678\_9012\_3456L;;** 

- Tipos numéricos en punto flotante → permiten representar números muy grandes y pequeños, además de decimales. Cabe destacar que se admite el uso de **separadores de números \_** haciendo más legible los números largos; el uso de **enº, Enº.**  

- **Float →** permite contener decimales simples (hasta 7 decimales de precisión) y ocupa 4 bytes de memoria. Para considerarse un float deberá de indicarse el sufijo **f o F**.  

- **Double →** se usa exclusivamente para decimales dobles (hasta 15 decimales de precisión) y ocupa 8 bytes. Se suele utilizar en aplicaciones científicas y de ingeniería donde se necesitan cálculos complejos y un rango de valores más amplio (-1,7 \* 10^308 a 1,7 \* 10^308). Si **no se indica sufijo** o se indica **d o D** se considerará un double.

- **Decimal →** se diferencia del anterior porque tiene mayor rango (hasta 28-29 decimales de precisión) y ocupa 16 bytes. Suele ser utilizado en aplicaciones financieras donde se requiere de alta precisión decimal (-7,9 \* 10^28 a 7,9 \* 10^28). Para considerar un decimal se deberá indicar el sufijo **m o M**. 

Se recomienda, que cuando queramos inicializar una variable de tipo decimal a 0, en vez de usar 0 directamente usemos *decimal.Zero*. 

- **Boolean →** sus valores pueden ser ***True*** o ***False***, o lo que es lo mismo **1** o **0**.	**boolean nombrevar = false/true;** 

- **Char →** almacena un solo carácter y ocupa 2 bytes. Se usa ‘ ‘. 		**char nombrevar = ‘char’;** 

**>Tipos de datos complejos/estructurados - clase - objeto/de referencia**, que permiten almacenar múltiples valores de tipos primitivos más simples (del mismo tipo o no), al mismo tiempo. Estos reciben el nombre de **objetos** porque se utilizan para representar objetos. En este caso, los tipos contienen una referencia a una ubicación de memoria en la que se almacena el valor real. Estos se almacenan en el **montón/heap**, por eso la gestión de la memoria que ocupan es más compleja y menos eficiente. 

**Nota →** en C# es posible el uso de **var** para ahorrar tiempo de escritura de código, lo que permite es que al instanciar objetos de tipos complejos solo de deba indicar el tipo a la derecha de la instancia tras la palabra new, sin tener que hacerlo a la izquierda de la instancia previo al nombre de la instancia. Pues al poner var se entiende que el nombre de la instancia será del tipo que se indique a la derecha. Hay que tener mucho cuidado con esta práctica ya que a veces puede hacer más difícil la lectura del código y en algunas empresas puede prohibir y/o restringir su uso. Esta práctica **solo es posible dentro de métodos y bucles.**

Es **útil para crear tipos anónimos → var nombreObj = new {};**

P.e 

**var nombreObj = new TipodeDato();** 	   en vez de 	**TipodeDato nombreObj = new TipodeDato();** 

- **Cadenas de caracteres →** a pesar de que se considera un objeto, cuando declaramos una cadena lo hacemos igual que con los tipos de datos simples/primitivos. Cabe destacar que un objeto String es **inmutable,** es decir, no se pueden modificar después de haberse creado, por lo que los métodos que parecen modificar un String devuelven realmente un nuevo String que contiene la modificación. 

**String →** Almacena un conjunto de caracteres. Se usa “ “.  Si quisiéramos hacer un bloque de texto podemos hacer usando **+** o bien poner el bloque de texto entre **“”” “””** (tres comillas dobles), en cuyo caso tenemos que tener en cuenta que los espacios en blanco consecutivos y las tabulaciones se eliminan, por lo que si queremos tabular o usar más de un espacio debemos usar el guión medio **-** .

Todos los tipos de datos básicos puede ser transformados a String, basta con que usemos el método **toString** de la clase que recoge dicho tipo de dato, por ejemplo para pasar un integer y un float a string bastaría con **Integer.toString(nº a convertir);** y **Float.toString(nº).**  Cabe destacar que no es una conversión real, sino que devuelve una instancia de String. 

[**Métodos y operadores con cadenas](https://learn.microsoft.com/es-es/dotnet/api/system.string?view=net-7.0#Immutability)** 

**Interpolación de cadenas**

Una **cadena interpolada** es aquella en la que se pueden incluir expresiones de interpolación (variables o expresiones, incluidos objetos, arrays, operaciones, métodos, etc…). Para ello, la sintaxis a utilizar es: 

`	`**$”*aquí va la cadena  {aquí va la expresión o variable}*“**  

**>**Cabe destacar que no puede existir espacio entre $ y “, y que se puede aplicar sobre bloques de cadena, es decir cuando usemos “”” “”””. 

**>**Por otro lado,  si queremos **formatear** las expresiones y/o variables dentro de las llaves, también es posible, utilizando una sintaxis especial, como p.e 

{numero:f2} donde f2 indica el nº de decimales con el que queremos mostrar *numero*. En vez de **f** para indicar el **nº de decimales**, podemos usar **c** para el **valor monetario**, **d** para indicar que sea un **entero**, **p** para indicar porcentajes (con el nº indicamos el nº de decimales), **e** para indicar en formato de **nº e**, . 

Es importante saber que ocurre lo mismo con el formateo de Datetime (tema extenso que se tocará en otro apartado). 

**>**Si queremos incluir llaves dentro de la cadena (es decir, que se vean como parte del texto) , basta con indicar **{{ … }}.** Esto se debe a que dependiendo del nº de **$** al principio, se considerarán { cuando haya un nº mayor de { seguidas que el nº de $. P.e $$” … “ entonces se considerará { dentro del texto cuando hayan {{{, es decir >2 llaves seguidas. 

**>**Dado que los **dos puntos** se suelen usar en muchas expresiones de interpolación, si queremos que éstos aparezcan como parte del texto debemos poner antes **\**. Ocurre lo  mismo si queremos usar **comillas dentro de comillas**. 

**>**Si queremos indicar una expresión de interpolación que sea un operador condicional como el **operador ternario**, éste debemos indicarlo entre paréntesis {(aquí va el operador ternario)}. 

**>**Dentro de las {}, la sintaxis a utilizar podrá también ser de la siguiente forma 

**{expr/varDeInterpolación},alineación:formato}** 

Donde la **alineación** es un entero con signo que indica el ancho de campo, es decir la tabulación y/o margen que hay  entre la la expresión o variable y el resto de palabras. Si el valor es < longitud de la cadena se omite y se utiliza la longitud de la cadena como el ancho. Si el nº es positivo, se considera que los elementos están alineados a la derecha, por el contrario si es negativo se considerará que es la alineación a la izquierda. Es importante que, si queremos usar alineación indiquemos la coma previamente. 


- **Arrays →** Colección de datos del mismo tipo, es decir un conjunto de datos/elementos donde cada uno se representa en una posición que está identificada gracias a uno o más índices numéricos enteros (empieza en 0). El **tamaño de un array no se puede modificar una vez creado**. 

La sintaxis para declararlo es (aunque cabe destacar que podemos declarar por un lado y posteriormente crear el objeto indicando el tamaño): 

`	`**tipodedato[] nombredelarray=new tipodedato[cantidad de datos];**	//Array de una dimensión | **vectores** 

`	`**tipodedato[,] nombredelarray=new tipodedato[cant de datos 1ª Dim, cant de datos 2ªDim];**     //Array de dos dimensiones | **matrices**
**
`										        `//1ªDim = Filas ||2ªDim = Columnas

\*\*Nota, si se trata de un array de tipos de datos simples, basta con poner **nombredelarray=new tipodedato[]**. 

Para escribir datos en un array la sintaxis es: 

**nombredelarray[posiciónqueocupaeldato] = dato;**

Si queremos declarar y dar valor a la vez, podemos hacerlo de la siguiente manera: 

**tipodedato[] nombredelarray = new tipodedato[] {ponemos el valor de los datos separados por comas};**     //tipos simples

//El tamaño del array será igual al nº de datos introducidos 

**tipodedato[] nombredelarray = new tipodedato[]** 

**{**

**new tipodedato(argumentosconstructor), tantos como queramos**

**};**     //tipos complejos

`       `//El tamaño del array será igual al nº de datos introducidos 

Para recorrer los elementos de un array, será necesario el uso del bucle for, iniciando en 0 hasta el tamaño del array, el cual podremos conocer usando la función **nombredelarray.length** (esta devuelve el tamaño del array, recordemos que si el tamaño es 5 y yo solo he inicializado 3, lo 2 restantes igualmente tendrán el valor predeterminado, p.e 0 si fuesen elementos de tipo entero). Otra opción es usar un **bucle for each** que se usa de la siguiente manera (*por cada tipodedato “dato” que esté en nombrarray hacemos {. . .})*: 

`	`**for (tipodedato dato: nombrearray) {**

`	`**System.out.println(“El dato es: “ + (dato)));**

**}**

Para usar el valor contenido en alguna posición:  **nombredelarray[posicion]**

Podemos encontrar varias [**propiedades](https://learn.microsoft.com/es-es/dotnet/api/system.array?view=net-7.0#properties) **y  [métodos](https://learn.microsoft.com/es-es/dotnet/api/system.array?view=net-7.0#methods)** de clase Array que pueden resultar muy útiles para trabajar con ellos.**  

- **Enumeración ([Explicación y Ejemplos](http://puntocomnoesunlenguaje.blogspot.com/2013/04/java-enum-enumerados-en-java.html)) →** tipo de datos definido por el usuario que solo puede tomar como valores los definidos en una lista de constantes. Por convenio se suelen escribir los valores del enun en mayúsculas al tratarse de constantes 

Para declararlo (se pueden declarar dentro y fuera de4 una clase pero nunca dentro de un método): 

`	`**enum nombredelEnum {VALOR1, VALOR2, VALOR3…};** 

Para declarar variable del tipo enumCreado: 

**nombredelEnum nombreVariable;** 

Para inicializar la variable de nuestro tipo enum, no obstante, cabe destacar que podemos declarar la variable e inicializarla a la vez: 

**nombreVariable = nombredelEnum.VALOR;** 

Entre los métodos que proporciona este tipo de dato se encuentran: 

- **name() →** devuelve un string con el nombre de la constante que contiene. 
- **ordinal() →** devuelve un entero con la posición de la constante según está declarada en el enum. La primera constante corresponde a la posición cero. 
- **toString()**
- **equals(objetoAComparar)** 
- **compareTo(enumAComparar) →** permite comparar el enum que usa el método con el enum que se pasa como argumento, de forma que se van comparando la cte de un enumerado con la equivalente a la posición del otro enum. Devuelve un nº negativo, cero o un nº positivo según el objeto sea menor, igual o mayor que el que recibe como parámetro. 
- **values() →** devuelve un array que contiene todas las constantes de la enumeración que está usando el método. 

Es importante saber que al ser un **tipo creado por el usuario** puede contener **métodos** y **atributos**: 

- El constructor debe ser **private** o **package** pero no public. 
- Los valores constantes deben estar relacionados con un atributo. Las constantes se deben definir primero, antes que cualquier otro atributo o método, y en caso de que hayan atributos o métodos se deben de terminar con **;** . 
- No debe contener métodos de tipo *set* ya que los valores que se relacionan con las constantes, se deben asignar en el constructor cuando se crean y ya no se pueden modificar. 

Ejemplo

**//Declaración del enum**

**public enum Precios {** 

`     `**PRECIONORMAL(100), PRECIOVIP(80);  //los valores se pasan al constructor**                                     

`     `**private double precio;**

`     `**private Precios(double p){**

`         `**precio = p;**

`     `**}**

`     `**public double getPrecio() {**

`         `**return precio;**

`     `**}**

**}**

**//Clase principal**

**public class Enum3 {**  

`    `**public static void main(String[] args) {**

`        `**Precios p = Precios.PRECIOVIP;     //precio = 80**                                                          

`        `**System.out.println(p.getPrecio()); //muestra 80**

`    `**}**

**}**


- **Colección →** es un objeto que a su vez contiene un conjunto de objetos. Se diferencia del array en que el array  es un objeto con elemento estático de cierta longitud, por ello se debe especificar la cantidad de elemento que contiene sin poderse modificar; además puede tener objetos vacíos y, en lugar de devolver el nº real de elementos presentes en él, devuelve su capacidad. Mientras que la colección es un objeto con un **conjunto dinámico de elementos,** esto quiere decir que puede aumentar o disminuir y que su tamaño depende del nº real de elementos que contiene (no puede contener huecos a menos que el programador lo especifique). 

.NET proporciona muchas colecciones comunes. Cada **tipo de colección** está diseñada para un fin específico, variando en cómo almacenan, ordenan y comparan elementos y cómo realizan búsquedas. Entre las más comunes se encuentran [(recomendaciones según uso)](https://learn.microsoft.com/es-es/dotnet/standard/collections/#choose-a-collection) : 

- ***System.Collections.Generic →*** espacio de nombres que contiene las **clases de colecciones genéricas** en .NET. Una colección genérica es útil cuando todos los elementos de la colección tienen el mismo tipo, esto hace que estas colecciones proporcionen mayor seguridad de tipos (al permitir agregar solo los tipos de datos deseados) y un mejor rendimientos que las colecciones no genéricas del espacio de nombre *System.Collections.* 

Entre las **clases más comunes** que incluye este espacio de nombres se encuentran: 

- **List<T> →** lista dinámica de objetos del tipo T. Funciona muy similar a un Array (se pueden acceder los elementos mediantes **índice basado en 0**) pero con las peculiaridades y diferencias de las colecciones. 

La sintaxis para crear una lista → 

**List<tipoDeDato> NombreDeLista = new List<tipoDeDato>();**  //tipos simples 

`	`**List<tipodedato> NombreDeLista = new List<tipodedato>()** 

**{**

**new tipodedato(argumentosconstructor), tantos como queramos**

**};**     //tipos complejos

Por otro lado, en cuanto a sus **métodos** más comunes se encuentran: 

- **.Add(T item) →** añade un elemento al final de la lista. 
- .**AddRange(List<T> list) →** permite agregar una lista a la actual. 
- **.Insert(int index, T item) →** inserta un elemento en la lista en el índice especificado. 
- **.Remove(T item) →** elimina la primera aparición del elemento especificado de la lista. 
- **.RemoveAt(int index) →** elimina el elemento en el índice especificado de la lista. 
- **.Contains(T item) →** determina si un elemento está en la lista. 
- **.IndexOf(T item) →** devuelve el índice de la primera aparición del elemento especificado en la lista. En caso de que dicho elemento no exista, devuelve un -1. 
- **.Sort() →** se trata de un método **mutable** (modifica los valores del objeto en el que se usa). Ordena los elementos de la lista.  
- **Count →** es una **propiedad** de List<T> que almacena el nº de elementos de la lista. 

- **Queue<T>  →** Son listas que siguen un orden FIFO. Podemos decir que su funcionamiento de adición es igual al de una pila; sin embargo la salida de los elementos es inversa, similar a cuando hacemos una cola para entrar a un sitio. Hay que tener en cuenta que cuando iteramos en una cola empezamos a recorrerla desde el principio de la misma, por ello vamos a ver que la iteración es inversa a lo que ocurre en la pila.  

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.001.png)

`	`**nombreCola.Enqueue(T item);**		//Añadir elemento al final de la cola

`	`**nombreCola.Dequeue();**		//Elimina y devuelve el primer elemento de la cola

`	`**nombreCola.Peek();** 			//Devuelve el primer elemento de la cola sin eliminarlo

- **Stack<T> →** Son listas que siguen un orden LIFO. Podemos decir que su funcionamiento de adición es igual al de una cola; sin embargo la salida de los elementos es inversa, similar a como vamos apilando los platos y así mismo los vamos cogiendo de la torre. Hay que tener en cuenta que cuando iteramos en una pila empezamos a recorrerla desde la cima (top de la misma), por ello vamos a ver que la iteración es inversa a lo que ocurre en la cola. 

`	`**nombrePila.Push(T item);**		//Añadir elemento al top de la pila (como los platos apilados)![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.002.png)

`	`**nombrePila.Pop();**			//Elimina y devuelve el primer elemento de la pila, es decir el del top)

`	`**nombrePila.Peek();** 			//Devuelve el primer elemento de la pila sin eliminarlo, el del top

- **LinkedList<T> →** colección de elementos organizados en una lista enlazada. Los elementos pueden ser insertados o eliminados de la lista de manera eficiente en cualquier posición, es decir a diferencia de una pila o cola, permite el acceso aleatorio.  

Si vamos agregar/borrar elementos constantemente, se recomienda usar mejor este tipo de lista que la lista normal, ya que por cómo se configuran, LinkedList es mucho más eficiente. [Buena explicación de esta diferencia](https://www.youtube.com/watch?v=MYPtLPL0oCQ&ab_channel=pildorasinformaticas) 

- **Dictionary<TKey, TValue> →** colección de pares de clave y valor que se organizan según la clave, es decir en vez de utilizar índices para acceder a los valores, se utiliza la clave. 



- **HashSet<T> →** Colección de elementos únicos no ordenados. Se utiliza principalmente para buscar y eliminar elementos duplicados en una colección, ya que no pueden haber valores repetidos. 

- **SortedList<TKey, TValue> →** Proporciona una versión ordenada (por clave) de la clase Dictionary<TKey, TValue>. Permite acceder a sus elementos tanto desde el índice de base cero como por la clave del elemento. 

- ***System.Collections →*** espacio de nombres que contiene las **clases de colecciones no genéricas** en .NET. Una colección no genérica  es aquella que no almacena los elementos como objetos de tipo específico, sino como objetos de tipo *Object*. Es por esto último que decimos que no cuenta con los beneficios de seguridad que las genéricas, y por ello se recomienda usar mejor las genéricas o las pertenecientes al espacio de nombres *System.Collections.Concurrent*. 

- **ArrayList →** Internamente funciona como un array, pero su tamaño puede aumentar o disminuir según sea necesario. 
- **Hashtable →** colección de pares clave-valor no ordenado que se pueden buscar mediante una clave. Es útil cuando se necesita un acceso rápido a los elementos por clave, pero no se requiere un orden específico. 
- **SortedList →** Proporciona una versión ordenada (por clave) de la clase Hashtable. No obstante, tiene un costo de rendimiento ligeramente mayor que Hashtable. 
- **Queue →** Son listas que siguen un orden FIFO. 
- **Stack →** Son listas que siguen un orden LIFO. 

- ***System.Collections.Concurrent →*** espacio de nombres que contiene **clases de colecciones concurrentes** en .NET. Estas clases proporcionan una manera segura para que varios subprocesos accedan y modifiquen colecciones de forma concurrente sin necesidad de bloquear el acceso a la colección completa. 

Entre las más comunes se encuentran *ConcurrentBag, ConcurrentDictionary, ConcurrentQueue, ConcurrentStack,* entre otras. 

- ***System.Collections.ObjectModel →*** espacio de nombres que contiene clases que implementan colecciones especializadas y proporciona interfaces para implementar colecciones personalizadas. 

- **ObservableCollection<T> →** permite implementar colecciones que pueden notificar a sus suscriptores de los cambios en la colección. 

- ***System.Collections.Immutable →*** espacio de nombres que contiene tanto colecciones genéricas como no genéricas, con la característica de ser inmutables. Estas son útiles cuando se necesita mantener una colección constante, inmutable y segura en el tiempo. Permiten garantizar la integridad de los datos y evitar cambios inesperados, por lo que pueden ser útiles en aplicaciones distribuidas y paralelas, ya que permiten el acceso concurrente a los datos sin bloqueos ni sincronización. 


Peculiaridades 

**>** Todas las colecciones que implementan **IEnumerable** o **IEnumerable<T>** se considera **iterable**, por lo que permiten recorrer en iteración la colección a través de un foreach, in y For Each…Next. Por otro lado, cualquier colección que implementa **IEnumerable<T>** se considera un tipo **consultable** y se puede consultar con LINQ. 

**>** Todas las colecciones se pueden copiar en una matriz unidimensional con límite inferior de cero mediante el método **CopyTo**; no obstante el orden de los elementos de la nueva matriz se basará en la secuencia en la que los devuelve el enumerador. 

**>** Las colecciones tienen ***capacidad** (nº de elementos que puede contener)* y ***recuento*** (*nº de elementos que realmente contiene*). La mayoría expanden automáticamente su capacidad cuando se alcanza la actual (la memoria se reasigna y los elementos de la antigua se copian en la nueva) lo cual reduce el código para utilizarla, pero perjudica el rendimiento. Por eso, cuando sea posible se recomienda establecer la capacidad estimada de la colección para evitar múltiples reasignaciones. 

- **Tipos definidos por el usuario →** clases para realizar todas las operaciones o tareas posibles (leer y escribir archivos, ejecutar apps, enviar correos,crear cadenas…). 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

<a name="_h1qbkmpqdo6k"></a>**Variables**

**tipodedato  nombredevar = valordevar;** 

*Nombre de la variable* **→** Todas las variables deben de empezar o bien con una letra o bien con un guión bajo \_. 

Cada tipo puede almacenar una cantidad de bytes, por lo que si al declarar una variable se supera los bytes para el tipo de dato, la información extra se excluirá produciendo un error. 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

<a name="_swm9ucwbkyg5"></a>**Operadores** 

- **Aritméticos →** utilizados para cálculos aritméticos entre variables, cuyo resultado será el valor devuelto como resultado de la operación. 

- *Dos operandos* 


|**Operador**|**Uso**|
| :-: | :-: |
|**+ [suma]**|op1 + op2|
|**- [resta]**|op1 - op2|
|**\* [multiplicación]**|op1 \* op2|
|**/ [división]**|op1 / op2|
|**% [módulo]**|<p>resto de la división op1 / op2</p><p></p><p>Si tenemos op1 % op2 = r deberá de cumplirse la igualdad op1 = op2 \* nºdevecesquedcabeenop1 + r </p><p></p><p>Si op1 > op1 entonces el módulo se hace como hemos visto siempre, hago la división como si fuese entera y lo que me sobre (resto) será el módulo p.e → 8 mod 5 = 3</p><p>Si op1 < op2 entonces el módulo siempre va a ser D → 5 mod 8 = 5 </p><p>Si op1 es un nº negativo entonces el módulo va a ser igual a hacer op2 + op1 p.e → -5 mod 6 = 1 Es por esto que cuando queramos implementar un contador que va decrementando de 1 en 1 y queremos que una vez llegue a 0, vuelva otra vez a valer lo que valía inicialmente entonces basta con que hagamos: (count - 1) % contadormax</p><p>P.e → si mi contador empieza en 5 tendríamos que hacer (count -1) % 6 por lo que count siempre va a ser menor que 6 lo que hará que el resultado de esa operación de módulo sea siempre count -1, excepto cuando count - 1 = -1 en cuyo caso -1 mod 6 = 5 </p>|



- *Un operando (operadores unarios)*  


|**Operador**|**Uso**|
| :-: | :-: |
|**++ [incremento en 1]**|<p>op++</p><p></p><p>evalúa el valor op antes de incrementarlo, por lo que se usa primero op y luego ya se aumenta su valor en 1 </p>|
|**++ [incremento en 1]**|<p>++op</p><p></p><p>evalúa el valor op después de incrementarlo, por lo que primero aumenta op en 1 y luego ya opera con op</p>|
|**-- [decremento en 1]**|<p>op--</p><p></p><p>evalúa el valor op antes de decrementarlo, por lo que se usa primero op y luego ya se disminuye su valor en 1 </p>|
|**-- [decremento en 1]**|<p>--op</p><p></p><p>evalúa el valor op después de decrementarlo, por lo que primero disminuye op en 1 y luego ya opera con op</p>|
|**ejemplos**|<p></p><p>int i = 1, j; //declaramos i y j como integers y definimos i a 1</p><p>j = i++; </p><p>//aquí el valor de j=1 pero i=2 ya que i se incrementa tras producirse la operación de asignación j = i++; </p><p></p><p>int i = 1, j; //declaramos i y j como integers y definimos i a 1</p><p>j = ++i; </p><p>//aquí el valor de j=2 e i=2 ya que i se incrementa antes de  producirse la operación de asignación j = ++i.  </p>|

- **Condicionales →** utilizados para decidir entre algunas expresiones de comparación simples. El resultado es un boolean (verdadero o falso) que depende de que se cumplan o no las condiciones. 


|**Operador**|**Uso**|
| :-: | :-: |
|**&& [and]**|<p>expresion1  && expresion2</p><p></p><p>Es true cuando ambas condiciones son true, por lo que si op1 es false, directamente ni evalúa op2 sino que devuelve false</p>|
|**|| [or]**|<p>expresion1 || expresion2</p><p></p><p>Es false cuando ambas condiciones son false, por lo que si op1 es true, directamente ni evalúa op2 sino que devuelve true</p>|
|**! [negación]**|<p>! expresion</p><p></p><p>Devuelve el contrario de op, es decir si es true devuelve false y viceversa</p>|
|**& [and]**|<p>expresion1 & expresion2</p><p></p><p>Funciona exactamente igual que and, pero en este caso siempre evalúa ambas condiciones con independencia de que la primera sea true o false</p>|
|**| [or]**|<p>expresion1 | expresion2</p><p></p><p>Funciona exactamente igual que or, pero en este caso siempre evalúa ambas condiciones con independencia de que la primera sea true o false</p>|
|**:? [ternario if-then-else]**|<p>(expresión)**?**valor1**:**valor2</p><p></p><p>Funciona como un if-then-else, de forma que se evalúa la expresión y si ésta es  verdadera se retorna el valor1, de lo contrario se retorna el valor2. Se suele utilizar mucho para decidir qué valor asignar. </p><p></p><p>P.e int v1 = 5 //Asignamos 5 a la var. entero v1</p><p>int v2 = 4 //Asignamos 4 a la var.entero v2</p><p>int mayor //creamos una var. entero llamada mayor</p><p>mayor = (v1 > v2)?v1:v2 </p><p>system.out.println(“El mayor de los dos números es ” + mayor)</p><p>//A mayor en este caso se le asignará el valor de v1, ya que se cumple la expresión. </p>|
|**instanceof [Comprobar si objeto está en clase]**|<p>obj instaceof clase</p><p></p><p>Su función es comprobar que un objeto (obj) pertenece a una clase en concreto, de forma que este operador devuelve un boolean. </p>|

- **De igualdad o relaciones →** utilizados para comparar variables/datos compatibles entre sí (numéricos, carácter/cadenas o booleanos) de forma que devuelve un boolean (verdadero o falso) según se cumpla o no la comparación indicada a través del operador. 



|**Operador**|**Uso (serán true cuando sea cierta la relación)**|
| :-: | :-: |
|**== [igual que]**|op1  == op2|
|**!= [distinto que]**|op1  != op2|
|**< [menor que]**|op1 < op2|
|**> [mayor que]**|op1  > op2|
|**<= [menor o igual que]**|op1 <= op2|
|**>= [mayor o igual que]**|op1 >= op2|

- **A nivel de bit →** son utilizados cuando necesitamos manipular datos a nivel de bits, como, por ejemplo, habilitar o deshabilitar *flags* (variables que pueden tomar 2 valores, generalmente representados en bits). Dado que en los lenguajes no existe un tipo de “un bit” predefinido, se suelen usar variables de tipo entero (int) para definir flags. 



|**Operador**|**Uso (serán true cuando sea cierta la relación)**|
| :-: | :-: |
|**>> [desplaza a la derecha]**|<p>op1  >> op2</p><p></p><p>Desplaza los bits de op1 a la derecha tantas veces como indique op2. Rellena los huecos que quedan con el bit de signo. Esto quiere decir que el bit menos significativo (más a la derecha) se pierde y por la izquierda se añade 0 si el desplazamiento es positivo o bien 1 si el desplazamiento es negativo. </p><p>\*\*Desplazar un bit a la derecha implica dividir entre 2\*\*</p><p></p><p>P.e 2 >> 1 == 1 → 0000 0010 → 0000 0001</p><p>-2 >> 1 == -1 → 1111 1110 → 1111 1111</p>|
|**<< [desplaza a la izquierda]**|<p>op1 << op2</p><p></p><p>Desplaza los bits de op1 a la izquierda tantas veces como indique op2. Rellena los huecos que quedan con 0. Esto quiere decir que el bit más significativo (más a la izquierda) se pierde y por la derecha se añade un 0. </p><p>\*\*Desplazar un bit a la izquierda implica multiplicar por 2\*\*</p><p></p><p>P.e 1 << 1 == 2 → 0000 0001 → 0000 0010</p><p>-3 << 1 == -6 → 1111 1101 → 1111 1010</p>|
|**>>> [desplaza a la derecha sin signo]**|<p>op1 >>> op2</p><p></p><p>Desplaza los bits de op1 a la derecha tantas veces como indique op2. Rellena los huecos que quedan con 0. Esto último es lo que lo diferencia de >>. </p>|
|**& [and binario]**|<p>op1  & op2</p><p></p><p>Se va realizando el and entre cada bit, dando lugar a un nuevo número binario. Cabe destacar que 1 es true y 0 es false.</p><p></p><p>P.e 0101 & 0011 == 0001</p>|
|**| [or binario]**|<p>op1 | op2</p><p></p><p>Se va realizando el or entre cada bit, dando lugar a un nuevo número binario. Cabe destacar que 1 es true y 0 es false.</p><p></p><p>P.e 0101 & 0011 == 0111</p>|
|**^ [xor binario]**|<p>op1 ^ op2</p><p></p><p>El funcionamiento de XOR es que sólo será true cuando op1 y op2 sean distintos, de lo contrario será false.</p><p>Se va realizando el xor entre cada bit, dando lugar a un nuevo número binario. Cabe destacar que 1 es true y 0 es false.</p><p></p><p>P.e 0101 & 0011 == 0110</p>|
|**~ [complemento]**|<p>~op </p><p></p><p>Equivale a la negación pero en binario, de forma que invierte todos los bit que componen al número binario. </p><p></p><p>P.e ~0111 == 1000</p>|


- **De asignación →** modifican el valor de una variable u objeto a otro distinto. 



|**Operador**|**Uso (serán true cuando sea cierta la relación)**|
| :-: | :-: |
|**+= [suma]**|op1  = op1 + op2|
|**-= [resta]**|op1 = op1 - op2|
|**\*= [multiplicación]**|op1 = op1 \*op2|
|**/= [división]**|op1  = op1 / op2|
|**%=  [modulo]**|op1 = op1 % op2|
|**&= [and]**|op1 = op1 &  op2|
|**|= [or]**|op1 = op1 | op2 |
|**^= [xor]**|op1 = op1 ^ op2|
|**<<= [desplaza a la izquierda]**|op1 = op1 << op2|
|**>>= [desplaza a la derecha]**|op1 = op1 >> op2|
|**>>>= [desplaza a la derecha sin signo]**|op1 = op1 >>> op2|


`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

<a name="_5llknq8aoqsx"></a>**Control de flujos**

- **if-else →** los paréntesis, es decir la condición es obligatoria. Además permite el uso de **break** y **continue** los cuales se explican más abajo. Se pueden anidar los if. Cabe recordar el uso del operador ternario como alternativa (explicado en operadores condicionales arriba). 

Sintaxis: 

`	`**if (condicion) {**
**


**} else if(condicion) {**

**} else {**

**}**

**Nota →** Si un if solo tiene en su interior una sentencia (una línea) no será necesario que indiquemos las {}. 

- **switch →** en *expresion* se puede indicar una variable o bien una expresión que devuelva cualquier tipo; de forma que se analiza las múltiples posibilidades para esa única variable o expresión. Cada caso tendrá su resultado, pudiendo indicarse cualquier sentencia/s cuando se cumpla dicho caso; si la variable/expresión no coincide con ninguno de los casos indicados en el switch, se ejecutarán las sentencias indicadas en ***default*** (éste no es obligatorio ponerlo). 

Cabe destacar el uso de: 

- **Break →** permite salir del switch sin que sean evaluadas el resto de opciones. No es necesario usarlo, pero si queremos que encontrada la opción correcta no se evalúen las demás, debemos indicarlo (pues de lo contrario se evaluarán varias, es decir aquellas en las que no se haya indicado un break, eso se conoce como cases *anidados*). 

Esta sentencia también es utilizada como **control de bucles**, permitiendo terminar de forma abrupta una iteración y salir completamente del bucle sin que se ejecuten ninguna de las sentencias ni iteraciones restantes del bucle; no obstante, siempre es más recomendable hacer el bucle de forma que cuando la condición evaluada sea falsa se salga de ella. 

- **Goto →** permite hacer saltos a otras partes de nuestro código, y en el caso de un switch permite hacer cosas para posteriormente saltar a otro case. En definitiva permite transferir el control del programa a una etiqueta específica en otro lugar del código u a otro case en los casos de los switch. Es de las pocas instrucciones que permiten saltar hacia atrás o hacia adelante en el flujo de ejecución del programa. 

No obstante, su uso no es muy recomendado debido a que puede hacer el código más difícil de entender y mantener, además de llevar a problemas de lógica y errores difíciles de detectar. 

P.e: 

`	`**goto etiqueta;** 

`	`**…**

`	`**etiqueta:** 

`	     `**//Código que se ejecuta después del goto**

`	`En cuanto a la sintaxis de un switch: 

**switch (expresion/variable) {**

**case valor1:**				En cada case cuando no ponemos nada (solo el valor) es como si fuese un == valor, 

`	`**sentencias1;**			por lo que  si queremos usar otros **operadores de comparación** podemos hacerlo. 

`	`**break;**				Cabe destacar que, en vez de usar && u ||, debemos usar ***and*** u ***or***. 

**case < valor2:**				Además, **se puede pasar más de un valor a evaluar** al switch, p.e switch(var1, var2)

`	`**sentencias2;**

`	`**break;**

**. . .**

**default:**

`	`**sentencias\_default;**

`	`**break;**

**}**

- **while →** itera mientras la expresión que evalúa sea verdadera y evalúa antes de iterar, es decir ejecuta reiteradamente las sentencias de su interior mientras que la expresión booleana sea verdadera.

`	`Sintaxis: 

**while (expresion\_booleana/condicion\_de\_permanencia) {**

**. . .**	

`	`**}**

Permite el uso de las sentencias: 

- **Break** (explicado en el switch). 

- **Continue →** interrumpe la iteración en curso dentro del bucle pero sin salir del bucle por completo, es decir no sale del bucle sino que pasa a la siguiente iteración del mismo sin llegar a ejecutar las sentencias siguientes a la sentencia *continue* de la iteración actual.  Su uso normal es cuando queremos hacer comprobaciones en el bucle, de forma que completada una comprobación específica, no es necesario continuar verificando las comprobaciones restantes. 

Esta sentencia a diferencia de break, si que es exclusiva de los bucles, pues si se detecta esta sentencia fuera de un bucle saltará un error de compilación. 

- **for y foreach→** permite iterar n veces. Además permite el uso de **break** y **continue** (Explicado en switch y while respectivamente). 

Sintaxis: 

**for (init\_expr; cond\_expr; update\_expr) {**

`	`**. . .**

**}**

Donde **init\_expr** contiene un expresión de inicialización del bucle, es decir el valor inicial desde el que se empieza a iterar (podemos declarar e inicializar dicha “variable” a pelo ahí en la cabecera o inicializarla antes y simplemente nombrarla en la cabecera); **cond\_expr** contiene la expresión o condición de permanencia en el bucle, es decir en el momento en que se deja de cumplir, se deja de iterar; **update\_exp** contiene la expresión de actualización, es decir el nuevo valor del iterador en cada vuelta (se actualiza el valor de init\_expr, normalmente se suele usar i++ o i --). 

// Se puede utilizar con todas aquellas clases que implementen la interfaz **IEnumerator** 

**foreach (tipodedato vartipodedato in nombrearray)** 

**{**

`      `**...**

**}**

- **do-while →** itera mientras la expresión que evalúa sea verdadera y evalúa después de iterar, esto quiere decir que siempre se ejecuta al menos una vez. Además permite el uso de **break** y **continue** (Explicado en switch y while respectivamente). 

Sintaxis: 

**do {**

**} while (expresion\_booleana/condicion\_de\_permanencia)**

**\*\*Nota\*\* →** Cabe destacar que el uso de **return** implica salir de la función, rompiendo un bucle si se encuentra en él y devolviendo en valor que se indique a continuación del *return*. 

-----

<a name="_cn98v26mnsw"></a>**MODIFICADORES DE ACCESO Y/O PALABRAS RESERVADAS**

Es importante tener en cuenta que los modificadores de acceso sólo se aplican a los miembros de una clase (métodos/atributos/propiedades) y no a la clase en sí misma. Pues la clase en sí misma puede ser *pública o interna* con independencia de los modificadores de acceso que se apliquen a sus miembros. 

- **public →** indica disponibilidad global del método/atributo/propiedad desde cualquier punto del programa, es un modificador de acceso que determina desde dónde y quién puede acceder a él. [aplicable también a una clase en sí misma] 
**


- **private →** se trata de un modificador de acceso que permite que solo se pueda acceder al método/atributo/propiedad desde la propia clase en la que se está declarando. Los campos|atributos, propiedades y métodos son private por defecto, a menos que se indique lo contrario utilizando otro modificador de acceso. 

- **protected →** se trata de un modificador de acceso que hace que los miembros de una clase (métodos/atributos) sólo sean accesibles desde dentro de la misma clase o desde clases derivadas de ella. 

- **internal →** se trata de un modificador de acceso que hace que los miembros de una clase (métodos/atributos/propiedades) sólo sean accesibles desde dentro del mismo ensamblado (es decir, desde un mismo archivo DLL o EXE, aunque un ensamblado puede contener uno o más archivos de este tipo). [aplicable también a una clase en sí misma]

Las clases, por defecto son internas, a menos que se indique lo contrario mediante el uso de otro modificador de acceso. 

\*\* Se puede utilizar **protected internal** lo cual indica que los miembros de una clase sean accesibles desde dentro del mismo ensamblado o desde clases derivadas de ella. 

- **final →** permite establecer un método, clase o variable como final (ver explicación para cada uno en su apartado correspondiente). 

- **static →** cuando usamos esta palabra al declarar un campo / propiedad / método lo que estamos determinando es que dicho elemento pertenece única y exclusivamente a la clase en la que se encuentra. Esto quiere decir que cuando queramos utilizarlo no debemos hacerlo a través de la instancia de la clase, es decir a través de un objeto, sino que debemos hacerlo a través de la misma clase.

Por lo tanto, todo aquello que sea estático puede ser utilizado sin que exista instancia alguna y nunca se podrá usar a través de ningún objeto de dicha clase. Cabe destacar que también se puede determinar una clase como estática, en cuyo caso TODOS los elementos que se declaren dentro de ésta también deberán ser estáticos, además como es de esperarse una clase estática no podrá ser instanciada (un ejemplo de este tipo de clase es Math). . 

- **new →** Permite la creación de un nuevo objeto (tipo de datos complejo), es decir permite instanciar una clase. 

-----

<a name="_mf1hjp7cmzsl"></a>**CLASES Y OBJETOS**

Una clase suele estar representada por la siguiente estructura: 

**modificadoresdeacceso class NombreClase{** 

`	`**// Definición de *propiedades/atributos* (características del elemento que describimos con la clase)**

`	`**// Definición de los *métodos* (comportamiento y funcionalidades del elemento)**

**}** 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

Existen **cuatro tipos de clases** que son: 

- **Clase estática →** Para determinar una clase como estática debemos de indicar tras su modificador de acceso la palabra reservada **static** (explicación en apartado palabras reservadas) y antes de la palabra *class*. Como vimos anteriormente, este tipo de clase no puede ser instanciada y sólo puede contener miembros estáticos, lo cual quiere decir que se puede usar dicha clase directamente desde la clase y en ningún caso desde un objeto creado de dicha clase. 

Un ejemplo de este tipo de clase es Math.

`	`**modificadorDeAcceso static class nombreDeLaClase {}**

- **Clase abstracta →** clase común que posee atributos y métodos, y que tiene **al menos un método abstracto** (definido pero no implementado, es decir especificando solo su nombre, tipo de retorno y argumentos de entrada) y **no admite métodos estáticos**. Cabe destacar que pueden haber constructores; no obstante, debemos tener en cuenta que solo servirán como “plantilla” para las clases hijas, ya que NO se pueden crear objetos de una clase abstracta, por lo que de forma directa dicho constructor no será utilizado para crear un objeto de la clase abstracta, sino para ser heredado; es por ello que dichos constructores deberán de ser creados como *protected.* 

En cualquier caso **TODOS los métodos abstractos deben ser implementados por las clases hijas** de la clase abstracta que los define (haciendo sobrescritura a través de @Override). 

Las clases abstractas **no se instancian** (no se puede usar para crear un objeto, para crear uno deberemos hacerlo a través de sus clases hijas), sino que se emplean como bases para la herencia, es decir para otras clases llamadas **clases  concretas o reales**.  

Con la abstracción captamos los comportamientos (métodos) y atributos de un objeto, ocultando detalles y mostrando solo información esencial.   

Declarar variables privadas en una clase abstracta es absurdo, ya que nunca se utilizarán; por lo que los niveles de visualización deben ser **public** o **protected**.  

En cuanto a la sintaxis para declarar una clase como abstracta añadimos **abstract** antes de la palabra class. En el momento en que se declare como tal la clase, Netbeans nos mostrará el fichero \_\_\_.java con las figuras en gris en vez de en colores, así sabremos que la clase es abstracta. 

Para la creación de métodos abstractos, también es necesario usar la palabra **abstract** antes de indicar el tipo de retorno. 

Ejemplo: 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.003.png)

La clase Figura es una clase abstracta porque no tiene sentido calcular su área, ya que cada figura tiene una forma de calcularla, es decir no tiene sentido calcular el área de Figura pero sí el de sus hijos (círculo y  cuadrado). 

Vemos que cada hija tiene un atributo propio, radio en el caso de círculo y lado en el caso del cuadrado. Además el método abstracto de Figura es implementado por círculo y cuadrado de formas diferentes (son distintas fórmulas). 










- **Clase final →** aquellas clases que acaban con la cadena de herencia, es decir no se puede heredar más allá de una clase final. Para establecer una clase como tal se debe utilizar la palabra clave ***final***. 

- **Clase pública →** se puede acceder a ellas desde otras clases o mediante herencia. Son accesibles en el mismo paquete donde se declaran; o bien desde otros paquetes donde previamente tienen que ser importados. 

Al igual que los tipos de métodos, las clases pueden ser no ***public, private*** (sólo puede ser accedida desde la misma clase y nada más)*** o ***protected*** (visible en la clase donde se define y en cualquiera de sus subclases). 

- **Clase sincronizable →** este modificador indica que los métodos definidos en la clase están sincronizados, es decir que no se puede acceder desde diferentes hilos a la vez, y el sistema se encarga de colocar los flags para evitarlo. Esto permite modificar las mismas variables desde diferentes hilos sin sobrescribirlas. 

- **Clases anidadas ([Ejemplos](https://www.tutorialesprogramacionya.com/javaya/detalleconcepto.php?codigo=170)) →** método de agrupación lógica que solo se usa cuando una clase sólo es útil para otra clase, por lo que es lógico incrustarse en esa clase. Gracias a esta práctica se añade **encapsulación** (sean A y B dos clases donde B necesita acceder a un miembro privado de A. Al ocultar B en A, los miembros de A pueden declararse privados y accesibles para B. Además B en sí mismo puede ocultarse del mundo exterior).  

Una clase anidada tiene acceso a los miembros (incluidos los privados) de la clase en la que está anidada, y de igual forma la clase envolvente puede acceder a los de la clase anidada. Así pues, decimos que el alcance de una clase anidada está limitado por el alcance de su clase envolvente), ya que la clase anidada no deja de ser un miembro de la clase envolvente y como miembro, dicha clase anidada puede ser declarada *private, public, protected* o *private*. 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.004.png)![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.005.png)

- **Estática →** en el caso de las clases internas, no podemos crear un objeto de clase interno sin que exista previamente creado un objeto de clase externo. No obstante, cuando se trata de una clase anidada estática, **sin que exista un objeto de clase externa creado, puede haber un objeto de clase anidada estática**, es decir el objeto de una clase anidada estática no está fuertemente asociado con el objeto de la clase externa. 

Sin embargo, una clase anidada estática **no puede referirse directamente a variables de instancia o métodos definidos en su clase envolvente** (a variables/métodos estáticos sí), sino que debe usarlos a través de una referencia de objeto, es decir habiendo sido creado previamente un objeto de la clase externa.  

Este tipo de clase **si puede declarar miembros estáticos**, por lo que sí puede declarar main() y por ende  está clase se puede invocar directamente desde el símbolo(terminal) del sistema. 

En cuanto a la sintaxis se crea un objeto de esta clase: 

**claseenvolvente.claseanidada nombreobjtinterna = new claseexterna.claseanidada();** 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.006.png)

- **Internas (no estáticas/InnerClass) →** como hemos indicado antes, en el caso de este tipo de clases, no podemos crear un objeto de clase interno sin que exista previamente creado un objeto de clase externo; es decir, el objeto de clase interno siempre está asociado con el objeto de clase externo. Es por esto último que para crear una clase interna, primero debe crearse una instancia de la clase externa, luego dentro de dicho objeto creado, se debe crear el objeto interno mediante la siguiente sintaxis: 

`	`**claseexterna.claseinterna nombreobjtinterno = nombreobjexterno.new claseinterna();**

Sin embargo, **una clase interna sí puede acceder directamente a los miembros estáticos y no estáticos de la clase externa**, es decir sin tener que hacer referencia a ningún objeto externo.  

Dentro de esta **no** será posible **declarar miembros estáticos** y debido a ello no podemos declarar el método main(), por lo que la clase interna no se puede invocar directamente desde el símbolo del sistema. 

- **Locales ([Ejemplos](https://barcelonageeks.com/clase-interna-local-en-java/)) →** clases internas que se definen dentro de un bloque (cuerpo de un método, un bucle for o un if entre otros, es decir conjunto de cero o más declaraciones de llaves equilibradas/iguales) y su alcance está restringido a dicho bloque, es decir solo se pueden usar dentro de él. Por lo que decimos que éstas no son miembros de ninguna clase envolvente, sino que pertenecen al bloque en el que están definidas. Esto significa que **no puede tener ningún modificador de acceso asociado** a ellas (private, public, static, protected), aunque sí que pueden marcarse como finales o abstractos. Estas clases deben **instanciarse en el bloque en el que están definidas.** ![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.007.png)

Estas clases pueden **acceder a las variables** o parámetros del bloque que las encierra (p.e o  en el ejemplo); y podrá acceder a las variables locales (p.e local en el ejemplo), solo si dichas variables/parámetros se declaran como **finales** o son **efectivamente finales**. [recordemos que una **variable efectivamente final** es aquella cuyo valor no cambia una vez inicializada].

Cuando se **compila** un programa que contiene una clase interna local, el compilador genera dos archivos **.class**, uno para la clase externa (clase exterior) y otro para la clase interna que tiene la referencia a la externa (exterior$1interior.clase). . 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.008.png)

- **Anónimas ([ejemplos](http://programmingbabel.blogspot.com/2017/09/clases-anonimas-java-anonymous-classes.html)) →** clase interna sin nombre para la que se crea un único objeto, ésta puede ser útil al crear una instancia de un objeto con ciertos “extras” como anular métodos de una clase o interfaz sin tener que subclasificar una clase. Así pues, concluimos que para crear una clase anónima es necesario haber definido una interfaz, una clase o una clase abstracta, ya que la clase anónima lo que hará será implementar la interfaz definida o sobreescribir los métodos definidos.  

Se consideran una solución rápida para implementar una clase que **se va a utilizar una vez** y de forma inmediata, es decir permite **declarar e instanciar una clase al mismo tiempo** (clase anónima).

La clase anónima puede implementar cualquier cantidad de interfaces, pero la clase anónima **solo puede implementar una interfaz a la vez**; la clase regular puede extender una clase e implementar cualquier cantidad de interfaces simultáneamente, pero la anónima puede extender una clase o implementar una interfaz **pero no ambas a la vez**; la clase anónima **no tienen ningún constructor porque no tiene nombre**. 

En cuanto al **acceso a variables** esta clase tiene acceso a los miembros de su clase envolvente, pero no puede acceder a variables locales en su ámbito adjunto que no estén declaradas como finales o efectivamente finales. Por otro lado, al igual que todas las clases anidadas internas no se puede declarar inicializadores estáticos o interfaces de miembros de una clase anónima y ésta puede tener miembros estáticos siempre que sean variables constantes. Así pues, decimos que las clases anónimas pueden declarar: 

- Campos
- Métodos adicionales. 
- Inicializadores de instancia. 
- Clases locales. 

En cuanto a su sintaxis es como la invocación de un constructor, con la diferencia de que hay una **definición de clase contenida en un bloque de código ({})**, pudiendo estar la clase anónima definida dentro de un método o fuera.  

**Saludo frenchGreeting = new Saludo() {}**  

//Saludo sería el tipo de dato de cualquier superclase o interfaz que vamos a extender o implementar

//frenchGreeting sería el nombre de una variable que va a almacenar nuestra implementación 

//Saludo() el nombre de la superclase/interfaz a extender/implementar como un constructor sin argumentos 

//Los corchetes contendrán dentro la implementación 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

<a name="_5ayry0bhbr42"></a><a name="_75x49daoes57"></a>**Constructor**

*Método especial* que se invoca cada vez que se genera un objeto de la clase a la que él pertenece (a través de él se podrá dar valores iniciales a los atributos que tiene ese objeto). No obstante, no funciona exactamente como un método, sino que tiene un comportamiento distinto. 

C# genera un método constructor **por defecto** para cada clase; sin embargo nosotros también podemos hacerlo. Dependiendo de las necesidades que tenga cada proyecto, **una clase puede tener uno o varios constructores**.  Cada método constructor debe cumplir con las siguientes **características**: 

- Tener el mismo nombre de la clase a la que pertenece. 
- Deben ser declarados como públicos para que puedan ser invocados desde fuera de la clase, aunque no se utiliza la palabra reservada void en la sintaxis (a pesar de que el constructor no devuelve ningún valor). 
- Suele ser el primer bloque de código que se construye cuando se está haciendo la clase. 
- Puede tener o no parámetros, depende de lo que requiera el proyecto. 
- Solo se ejecuta cuando es invocado para crear una instancia de un objeto, es decir siempre debe utilizarse precedido por la palabra reservada new. 

**Tipos de constructores:** 

- **Por defecto →** es el que asume el compilador por defecto cuando el programador no lo declara de manera explícita. Dado que implica no inicializar los atributos, éstos toman los valores predeterminados dependiendo del tipo de datos que se haya declarado. **P.e public Persona() {**

- **Con parámetros →** lo crea de forma explícita el programador respetando siempre las características que establece C# y permite dar valores específicos a los atributos de un objeto creado. **P.e public Persona(String nombre, String apellidos, int edad) {**

Si creamos un constructor parametrizado  nunca se va a crear automáticamente el constructor por defecto, por lo que será necesario que lo hagamos nosotros.  


**\*\*Nota () →** Cuando se crea una clase hija, ésta hereda todos los miembros (métodos/atributos) de la clase padre/base, incluyendo los constructores. Por lo que si en una clase hijo no definimos explícitamente un constructor, se utiliza automáticamente el constructor predeterminado (sin parámetros) de la clase base. Sin embargo, si se define un constructor en la clase hija, este puede requerir que se llame a un constructor de la clase base para inicializar los miembros heredados de la clase base. Es en estos casos donde entra en juego la palabra **base** para inicializar los miembros heredados de la clase base. P.e

**public class DerivedClass : BaseClass**			la clase hija llama al constructor predeterminado de la clase base, de forma que se 

**{**						asegura que los miembros heredados de la clase base se inicializan correctamente 

`	`**public DerivedClass() : base()**			antes de ejecutar el código adicional de inicialización en el constructor de la c. hija. 

`	`**{**

`	`**//Código adicional de inicialización** 

**}**

**}**

**public class DerivedClass : BaseClass**			En este caso ocurre lo mismo pero utilizando un constructor con parámetros. Cabe 

**{**						destacar que si quiero incluir otro parámetro más al constructor de la clase derivada

`	`**public DerivedClass(int Value) : base(value)**	lo puedo hacer, simplemente a la clase padre solo debo mandar los del constructor 

**{**					del padre a través de base. 

**//Código adicional de inicialización** 

**}**

**}**



Además de con constructores, la palabra **base** nos permite inicializar atributos de la clase padre y sobreescribir métodos de la clase padre para luego invocarlos con *base*. En este caso a diferencia de los constructores, deberemos de indicar el nombre del método/atributo, **base.nombremetodo\_atribut()**; para poder invocarlo. Cabe destacar **(!!!)** que solo se permite el acceso a la clase base en un constructor, método de instancia y en un descriptor de acceso de propiedad de instancia (getters y setter, es decir accessors), en cualquier otro caso dará error. 

Si queremos hacer esto mismo, pero en vez de tomando un constructor de la clase padre, tomando otro de los constructores de la propia clase entonces usamos **this(parametros del constructor al que se invoca).** 

**—--------------------------------------------------------------------------------------------------------------------------------------------**

<a name="_p5z354akc6zj"></a>**Métodos || funciones**

Son las funciones que se pueden llamar en el interior de una clase o por otras clases y que permite al objeto la capacidad para cambiar su estado. La sintaxis es:

`	`**[ModificadoresAcceso] TipoRetorno nombreMétodo ([lista\_de\_argumentos]) [excepciones]**

**{**

`		`**BloqueDeCódigo**

`		`**return (en caso de que retorne algún valor)**

**}** 

- *lista\_de\_argumentos →* es opcional, se utiliza para enviar información al cuerpo del método. Es literalmente lo mismo que los parámetros cuando creamos funciones/procedimientos en otros lenguajes. Los valores de dichos parámetros, si los hubiese, se pasan al usar el método. Al declarar una función la lista de argumentos deben de formarse por el tipo de dato y el nombre del argumento tal y como se vaya a usar dentro de la definición de la función.
- *Tipo de retorno →* representa el tipo de datos devueltos después de ejecutar la tarea, es decir el tipo de dato que usamos tras ***return***. Si no se devuelve nada, debemos poner **void**.
- *Modificadores de Acceso →* En ellos ponemos si el método es público o privado (*public/private*), y además el tipo de método que es en caso de que haya que especificarlo (p.e si es *static*).

Existen distintos **tipos de métodos**: 

- **Métodos private →** aquellos que solo se pueden utilizar dentro de la clase. Los métodos, por defecto son private, a menos que se indique lo contrario mediante el uso de otro modificador de acceso. 
- **Métodos public →** aquellos que pueden ser invocados desde el exterior de la clase. 
- **Métodos protected →** aquellos que pueden ser empleados por la clase donde son definidos y en las clases derivadas (herederas) de ella. 
- **Métodos internal →** aquellos que pueden ser accesibles y visibles desde el mismo ensamblado en el que se encuentra definido. 
- **Método final →** aquellos que no pueden ser anulados ni modificados, pues si se hereda de una clase y la clase heredera intenta sobrescribir un método declarado como final, se producirá un error de compilación.

**class A** 

**{**

`    `**final void m1()** 

`    `**{**

`        `**System.out.println("Este es un método final.");**

`    `**}**

**}**

**class B extends A** 

**{**

`    `**void m1()**

`    `**{** 

`        `**// COMPILACIÓN-ERROR!** 

`        `**System.out.println("Ilegal!");**

`    `**}**

**}**

- **Métodos estáticos o de clase →** son aquellos que se caracterizan porque pueden ser llamados sin instanciar ningún objeto de la clase (ya que si intentamos utilizar un método estático a través del nombre del objeto creado, veremos que hay un error). Sabemos que un método es estático porque va precedido por la palabra **static**.

Estos métodos solo pueden acceder a variables estáticas o de clase, y no pueden acceder a variables de instancia a menos que se cree un objeto y se acceda a las variables de instancia a través de ese objeto.  

**nombreDeLaClase.nombreDelMetodo();**

**—--------------------------------------------------------------------------------------------------------------------------------------------**

<a name="_151nm1srdbn"></a>**Sobrecarga de métodos**

Se trata de una forma de **polimorfismo estático|paramétrico** y consiste en dar el mismo nombre pero diferentes parámetros (nº y nombres), de forma que cada método puede realizar una tarea diferente pero compartiendo el mismo nombre. La importancia radica en poder relacionar los métodos a través de un nombre común, aunque cumplan distintas funciones manteniendo la calidad en el código y reutilizando funciones sin extender la cantidad de líneas de código. 

**Nota \*\* →** en ningún caso, podremos aplicar la sobrecarga si cambiamos el tipo de retorno, esto quiere decir que aunque se pueda cambiar el nº y/o tipo de parámetros, NO podemos cambiar el tipo de retorno del método. 

P.e: 

`	`**public int Sum(int a, int b) {**

`	`**return int.Parse(a) + int.Parse(b);** 

**}**

**public int Sum(int[] numbers)**

**{**

`	`**int result = 0;** 

**int i = 0**

**while (i < numbers.Length)** 

**{**

`	`**result += numbers[i];** 

`	`**i++;** 

**}**

**}**

<a name="_9p43ycfilmvx"></a>**Sobreescribir métodos** 

Se trata de una forma de **polimorfismo dinámico|ad hoc** y consiste en que una clase hija cambie la implementación de un método que ha sido heredado de la clase padre. De forma que la subclase anula la implementación de la superclase proporcionando un método con la misma forma (mismo nombre, nº y tipo de parámetros, así como mismo dato de retorno), en caso de que queramos modificarlo por completo; o bien utilizarlo y simplemente ampliar dicha funcionalidad. 

Para poder llevar a cabo esta práctica debemos de incluir en el método de la clase padre la palabra reservada ***virtual*** tras el modificador de acceso del método y antes de su tipo de dato de retorno; y por otro lado incluir en el método de la clase hija la palabra reservada ***override*** tras el modificador de acceso del método y antes de su tipo de dato de retorno. 

P.e (anular el del padre dando lugar al método con la misma forma pero distinta funcionalidad) 

`	`**public class A** 

`	`**{**

`		`**public virtual string Hi()**

`		`**{**

`	`**return “Hola soy A”;**

**}**

**}**

**public class B : A**

**{**

`	`**public override string Hi()**

`	`**{**

`	`**return “Hola soy B”;** 

**}**

**}**

(si en vez de anular la implementación realizada por el padre, queremos ampliarla podemos hacerlo usando **base,** que se explica en el apartado de constructores)

`	`**public class A** 

`	`**{**

`		`**public virtual string Hi()**

`		`**{**

`	`**return “Hola soy A”;**

**}**

**}**

**public class B : A**

**{**

`	`**public override string Hi()**

`	`**{**

`	`**return base.Hi() +  “Hola soy B”;** 

**}**

**}**


**Sobrecarga vs Sobreescritura (uso)**

La sobrecarga de métodos es útil cuando se desea proporcionar una funcionalidad similar pero con diferentes parámetros. Por ejemplo, se puede tener un método *CalcularArea* que acepte un parámetro de radio para calcular el área de un círculo y otro método *CalcularArea* que acepte dos parámetros para calcular el área de un rectángulo. La sobrecarga de métodos permite que el mismo nombre de método se utilice para diferentes propósitos.

La sobrescritura de métodos, por otro lado, se utiliza cuando se desea modificar el comportamiento de un método en una subclase. Por ejemplo, se puede tener una clase Animal con un método Sonido que devuelve un sonido genérico para todos los animales. Si se desea que los perros hagan un sonido diferente al de los gatos, se puede crear una subclase Perro que sobreescriba el método Sonido para devolver el ladrido de un perro en lugar de un sonido genérico.

En resumen, la sobrecarga de métodos se utiliza para proporcionar diferentes formas de hacer lo mismo con diferentes parámetros, mientras que la sobrescritura de métodos se utiliza para modificar el comportamiento de un método en una subclase.

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

<a name="_uod0bqfmcok0"></a>**Variables || atributos || campos**

`	`**[ModificadoresAcceso] TipodeDato nombreDeLaVariable = ValorDeLaVariable;** 


Los campos, por defecto son private, a menos que se indique lo contrario mediante el uso de otro modificador de acceso. Por otro lado, se recomienda empezar el nombre de los campos privados con un **\_** para así saberlos diferenciar de los parámetros recibidos en los constructores (aunque recordemos que siempre será mejor práctica utilizar el this. ); normalmente por convención se considera que los campos que empiezan con un **guión bajo** son privados. 

- **Variables estáticas o de clase →** aquellas variables específicas de cada clase y no para cada objeto. Éstas se usan para definir constantes que son comunes a todos los objetos en una clase o variables que solo son significativas para el conjunto de la clase. Sabemos que una variable es estática porque va precedida por la palabra **static**. 

Dado que se vincula con la clase y no con el objeto, en vez de usar *this* (para usarla desde dentro de la clase) o el nombre del objeto (para usarla desde fuera de la clase), debemos usar directamente el nombre de la clase (**nombredelaclase.varestatica**). Cabe destacar que **se puede modificar** el contenido de una variable estática, en cuyo caso dicho valor se modificará para toda la clase y todas las instancias que se creen de ella. Esto último es útil si por ejemplo queremos tener un contador de cuántas instancias se hacen de una clase.  

Lo importante es que las variables estáticas siempre se inicializan antes que cualquier objeto de la clase. 

P.e 

**public class People**

` `**{**

`            `**public static int Count = 0;**

`            `**public string Name { get; set; }**

`            `**public int Age { get; set; }**

`            `**public People()**

`            `**{**

`                `**Count++;**		// Esto hará que cada vez que se use el constructor, es decir cada vez que se instancia la clase 

`            `**}**			// la variable Count incremente, y dado que ésta variable/campo es estática lo hará de forma 
**
`			`// global para la clase,. 

`            `**public static string GetCount()**

`            `**{**

`                `**return $"Esta clase se ha utilizado {Count} veces";**

`            `**}**

` `**}**


- **Variables de instancia →** Son aquellas que deben inicializarse tras la creación de una clase. Se declaran dentro de la clase y fuera del cuerpo de los métodos. Son del tipo global y pueden ser utilizadas por cualquier método no estático que las llame. 

- **Variables efectivamente finales ([ejemplos](https://javadesdecero.es/palabra-clave/final/)) →** aquellas que tras ser inicializadas, no varían su valor, se diferencian de las variables normales porque no se puede reasignar su valor (pues en tal caso salta error de compilación). Para declarar una **variable final** basta con poner la palabra ***final*** antes del tipo de dato, su inicialización se puede producir luego. Se diferencia de las variables **const** de C++, porque no tiene que inicializarse si o si al se declarada, sino que puede asignarse el valor más adelante, pero **solo una vez**. 

**OJO**, podemos declarar **variables finales de referencia**, que son aquellas que al declararlas no las inicializamos (no le damos valor) y que posteriormente cambiamos el estado interno del objeto señalado por esa variable de referencia (**cuidado, no confundir con una reasignación**) como se indica en el siguiente ejemplo: 

//Programa Java para demostrar

// la variable final de referencia

**class JDC {**

`    `**public static void main(String[] args) {**
**
`        `//una variable final de referencia

`        `**final StringBuilder cadena=new StringBuilder("Java");**

`        `**System.out.println(cadena);**
**
`        `//cambiando estado interno de referencia del objeto

`        `//por variable de referencia final 'cadena'

`        `**cadena.append("desdeCero");**

`        `**System.out.println(cadena);**

`    `**}**

**}**

**This →** permite hacer referencia al objeto actual de la clase en la que nos encontramos, es decir, a una instancia concreta de la clase y nos sirve para usar los métodos y atributos de esa clase desde cualquier punto del código que define la clase. Equivale al *self.* de python. Por eso suele verse delante de los atributos en los constructores y en los getters/setters ya que lo normal es que los parámetros tengan los mismos nombres que los atributos de la clase, de forma que al poner el this, podemos diferenciar entre los parámetros y los atributos|propiedades de la propia clase donde se usan. Su sintaxis es **this.nombreatributo\_metodo;** 

En conclusión, al utilizar *this* dentro de una clase, podemos acceder a cualquier miembro de la misma, razón por la cual solo tiene sentido utilizarlo dentro del contexto de una instancia de objeto. Cabe destacar, que al igual que como ocurre con base, no se puede usar this en un método estático. 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

<a name="_36besu8vb9bv"></a>**Propiedades** 

Son similares a los atributos|campos de una clase, con la diferencia de que en este caso cuentan con ***accessors*** encargados de permitir acceder, leer y/o escribir sobre ellos. Es decir, una propiedad es una forma de exponer los campos de una clase para que puedan ser accedidos por código externo, proporcionando una interfaz más segura y conveniente que los campos de la clase, al controlar el acceso a los mismos y validar los valores que se asignan.  

De esta forma, las propiedades pueden ser de **solo lectura (get), de escritura (set) o de ambas (set y get).** 

Las propiedades también pueden tener un modificador de acceso como public, private, internal o protected, para controlar el acceso a ella desde fuera de la clase, al igual que sus accessors (**descriptores de acceso, get y set**). En cuanto a su sintaxis (parece un método pero sin el uso de ()) : 

`	`**[modificadoracceso] tipodedato nombrePropiedad {** 

**[modificadoracceso] get{}**

**[modificadoracceso] set{}** 

**}**

**\*\*** Otra práctica es que al declarar una propiedad pongamos en su cuerpo **{get; set;}**, es decir indicando los descriptores de acceso vacíos, de forma que no realizan ninguna acción adicional a obtener y/o establecer el valor de la propiedad. En este caso lo que hace el compilador de  C# es que crea de forma automática la funcionalidad básica de dichos descriptores de acceso, es decir, devolver el valor del campo de respaldo (con el que está asociado la propiedad) y/o modificarlo. Si por algún motivo, el campo no ha sido inicializado, su valor predeterminado dependerá del tipo de dato de la propiedad. P.e si se trata de una propiedad de tipo int, el valor predeterminado será 0.

Así pues, podemos decir que esta **forma abreviada** se utiliza cuando queremos que la propiedad haga de campo, es decir cuando no queremos declarar de manera explícita un campo.  Se usa mucho en **interfaces** ya que en ellas no usamos campos sino solo propiedades. 

**\*\*** Podemos **dar valor a las propiedades directamente en el momento de instanciar la clase**, como se podrá ver en el ejemplo de a continuación. 

**\*\*** Si no estamos controlando que la propiedad siempre adquiera un valor porque hemos usado la forma abreviada {get; set;} entonces en el tipo de dato de la propiedad debemos indicar un **?** como p.e → **public string? Name { get; set; }** esto hará que si no damos valor a Name en el momento de instanciar la clase, Name valga “”. 

**\*\*** Por convención solemos indicar las propiedades públicas con **la primera letra en mayúscula (y prevo \_ en caso de que se trate de una propiedad privada)**, de forma que se pueda diferenciar respecto al campo con el que se asocia gracias a esa letra en mayúscula. Además, no tiene porque ser del mismo tipo que el campo al que vamos a permitir el acceso, como veremos en el siguiente ejemplo: 

**class Persona**

**{**

`	`**private string nombre;** 

`	`**private int edad;** 

`	`**public string Nombre {get; set;}**
**


`	`**public string Edad**

**{**

`	`**get**		//Su función siempre será devolver el valor de la propiedad 

`	`**{**

`		`**return total.ToString();** 

**}**

**set**			//Su función siempre será permitir la modificación de la propiedad, por defecto siempre

**{**			//que se use se pasará *value* que es el valor nuevo con el que queremos modificarlo. 

`	`**if (value < 0)** 

`		`**value = 0;** 

`	`**total = value;** 

**}**

**}**

**}** 

//Uso de la clase Persona 

**Persona persona1 = new Persona();** 

//Usando accessor set de la clase Persona1

**persona1.Nombre = “Juan”;** 

**persona1.Edad = 30;** 

//Usando accessor get de la clase Persona1

**Console.WriteLine(“Nombre: “ + persona1.Nombre);**

**Console.WriteLine(“Edad: “ + persona1.Edad);**

//También es posible inicializar las propiedades en el momento en que se crea un objeto de clase

**Persona persona2 = new Persona() {**

`	`**Nombre = “Pepo”,** 

`	`**Edad = 30**

**}**

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

Para **instanciar una clase** o lo que es lo mismo, **crear un objeto** en base a una clase se debe seguir la siguiente sintaxis: 

`	`**NombreDeLaClase NombreQueQueremosPonerAlObjeto = new ConstructorDeLaClase(ValoresDeLosParámetros)**

**Nota →**  no será posible instanciar una clase estática. 

**Nota →** se pueden inicializar las propiedades en el momento en que se instancia un objeto, tal y como se ve en el ejemplo anterior. 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

<a name="_k43y4h8g2bu9"></a>**Herencia** 

Característica que permite crear una clase tomando como base a otra clase ya existente, lo que permite reutilizar código y especializarlo. P.e a partir de la clase Persona se puede crear otras clases más especializadas a través de la herencia que respondan a las necesidades de cada tipo de persona, como un desarrollador, médicos, etc. 

Cuando una clase hereda de otra clase**, la heredera recibirá TODOS los atributos (estado) y métodos (comportamiento) de la clase padre (superclase)**, e incluso si la heredera no tiene método constructor, heredará el del padre. Sólo se podrá heredar de una superclase directamente, es decir **no hay herencia múltiple (**sólo es posible con las interfaces)**.** 

Cada subclase podrá añadir sus propias variables/atributos y métodos para diferenciarla de las otras subclases. Además las subclases podrán **sobrescribir** los **métodos heredados** de las superclases, como se explica en el apartado correspondiente. 

Es muy importante tener claro el uso de ***base*** para poder compaginar los constructores de la clase padre e hija (para ello ver el apartado de constructores en el que se explica) ya que debemos, como mínimo, pasarle los argumentos del constructor de la clase padre al crear el constructor de la clase hija. 

En cuanto a la sintaxis para conseguir la herencia: **class nombreclasehija :  nombreclasehija {}**

-----

**Tipos anónimos** 

Tipo de objeto que se crea en tiempo de compilación y que no se declara explícitamente en el código fuente. Es una forma rápida y conveniente de crear objetos que contienen un conjunto de propiedades y valores, sin tener que crear una clase separada para ello. 

Peculiaridades: 

- Los nombres de las propiedades deberán de ser válidos en C#, y los valores deberán de ser de cualquier tipo de datos válidos. 

- Este tipo es ***ReadOnly*,** lo que quiere decir que no se pueden modificar los valores de sus propiedades, sino solo leerlos. 

- Por otro lado, se pueden **crear arrays de tipos anónimos** pero se debe tener en cuenta que los objetos dentro de ellos deben de tener la misma estructura, es decir cada new no puede contener un nº de propiedades diferente ni con nombres distintos. 

`	`**var nombreArray  = new[]**

`	`**{**

`	`**new {identicasPropiedadesEnTodos},**

**new {identicasPropiedadesEnTodos}	//Podemos poner tanto objetos como queramos**

**}**

- **No se pueden usar como tipos de retorno de funciones/métodos ni como tipos de parámetros de métodos** ya que su definición es implícita y no se puede referenciar desde otro lugar en el código.  

**Tampoco se pueden crear listas de tipos anónimos (ni ningún tipo de colección genérica**), ya que en una lista es necesario indicar si o si el tipo 

-----

<a name="_pbkzrulg7r04"></a>**INTERFACES**

Las **interfaces** complementan a las **clases abstractas**, pues como ya sabemos, en C# no existe la herencia múltiple (no se puede heredar de más de una superclase/clase padre), por lo que aparece el concepto de la implementación de interfaces (que aunque es muy similar al funcionamiento de herencia, NO es lo mismo ya que una interfaz no es una clase) que si permite que **una clase implemente varias interfaces** (Lo más similar a la herencia múltiple que encontramos en C#). 

Las interfaces son MUY importantes para abstraer y poder llevar a cabo principios de diseño como la Inyección de dependencias. 

Las interfaces van a ser un **conjunto/colección de anexos/miembros,** los cuales no son más que métodos, propiedades(campos, por eso usamos propiedades abreviadas), eventos e indexadores. Estos deberán de cumplir con las siguientes características: 

- **No pueden tener cuerpo**, es decir no estar implementador, nos limitamos a declarar la firma de método o propiedad. 
- Siempre **públicos**, lo cual serán de forma predeterminada por lo que no es necesario especificar explícitamente el modificador de acceso *public*. 
- Siempre son **abstractos**, lo cual serán de forma predeterminada por lo que no es necesario especificar explícitamente el modificador *abstract*. 
- **No pueden ser estáticos**. 

La sintaxis para declarar una interfaz → se lleva a cabo mediante la palabra reservada ***interface*** de la siguiente manera **interface nombreinterfaz{ //miembros de la interfaz }**   //Por convención, el nombre de todas las interfaces **tienen que empezar con una I mayúscula**

La sintaxis para implementar una interfaz → hacemos lo mismo que cuando heredamos una clase. Si además una misma clase quiere implementar varias interfaces, ponemos el nombre de las mismas separados por comas. 

Es importante tener en cuenta que cuando una clase implementa una interfaz, debe de definir/implementar TODOS los miembros, pues es un contrato a seguir (p.e el **contrato para pertenecer a un club**, siendo cada interfaz un club y una clase puede pertenecer a todos los clubs que quiera siempre y cuando cumpla con los contratos que cada uno de ellos imponga), es decir todas clases que la implementen TIENEN que implementar todos sus miembros. 

Ejemplo: 

` `Ejemplo2: ![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.009.png)

**interface IAnimal**

**{**

`    `**void Eat();**

`    `**void Sleep();**

**}**

**class Dog : IAnimal**

**{**

`    `**public void Eat()**

`    `**{**

`        `**Console.WriteLine("The dog is eating.");**

`    `**}**

`    `**public void Sleep()**

`    `**{**

`        `**Console.WriteLine("The dog is sleeping.");**

`    `**}**

**}**


**\*\*Nota →** se pueden crear arrays de una interfaz. Como sabemos una interfaz no se puede instanciar, pues previamente se tiene que implementar por una clase para instanciar objetos de ésta última; no obstante, cuando declaramos el array lo que estamos haciendo es una cápsula de objetos. Es por esto que los **new** de objetos que ponga dentro si que tienen que ser instancias de objetos un ejemplo: 

`        `**IFish[] fishs = new IFish[]**

`        `**{**

`            `**new Siren(100),**

`            `**new Siren(300),**

`            `**new Shark("Tiburoncin", 70)**

`        `**};**

Vemos que creamos un array de IFish que contendrá distintos objetos, dichos objetos podrán ser de cualquier clase que haya implementado a IFish, como por ejemplo lo son Siren y Shark. (Para ver el código completo ver el proyecto *POOInterfaces.* 

Igualmente, si quisiéramos hacer un array de solo sirenas pues haríamos un array ISiren[] sirens = new Siren[] en cuyo caso sólo contendrá objetos de tipo sirena. 

-----

<a name="_1ip43tb792zr"></a>**GENERICOS (Generics)** 

Los **genéricos** son una herramienta muy útil para crear clases, interfaces y métodos que puedan trabajar con diferentes tipos de datos. De forma que en lugar de especificar el tipo de dato que se va a usar, se utiliza un tipo genérico que se especifica al crear la clase y al instanciar objetos de ella, puede tener cualquier nombre, aunque normalmente utilizamos *T* por mera convención. De forma que cuando se vaya a crear una variable, propiedad u objeto en vez de poner un tipo como *int, string, float,* etc, podemos el nombre del tipo genérico que queramos permitiendo mejorar la seguridad de tipos y el rendimiento, ya que no es necesario hacer conversiones de tipos en tiempo de ejecución. 

Sintaxis para crear una clase genérica: 

`	`**class NombreDeMiClase<T>**

`	`**{**

`		`**//Código que queramos en el que se use el tipo genérico p.e si la clase fuese MyList<T>: :** 

`		`**private T[] \_elements;**

**private int \_index = 0;**  
**


`		`**public MyList(int n)**

`		`**{**

`			`**\_element = new T[n];**

`		`**}**

`		`**public void Add(T e)**

`		`**{**

`			`**if(\_index < \_elements-Length)**

`			`**{**

`				`**\_elements[\_index] = e;**

`				`**\_index++;**

**}**

**}**

//De esta manera da igual el tipo del cual sea T porque siempre vamos a añadir con Add dicho elemento al array creado. 

`	`**}**

Sintaxis para instanciar una clase genérica: 

`	`**NombreDeMiClase<tipodelquequieroquesea> NombreDeObjeto = new NombreDeMiclase<tipodelquequieroquesea>();** 


**\*\*Nota →** Cuando queramos inicializar, devolver un valor vacío de T, como no sabemos si el tipo utilizado acepta null, lo que usamos siempre es **default(T)** que devolverá el valor predeterminado del tipo de datos T,el cual podrá ser null, 0, false, “”, etc.

**\*\*Nota →** Para ver el código completo de ejemplo ver *Genericos*.

-----

<a name="_41b524oap7xp"></a>**MÉTODO MAIN**

Es el más importante en nuestro programa, pues conlleva el punto de entrada y salida de nuestra aplicación (en él se inicializa y finaliza el control de un programa), siendo su principal tarea dirigir las llamadas a otras funciones y métodos en C#. Es por todo ello que main debe ser **static** **(**dado que main es lo primero que se ejecuta, no tiene un objeto para instanciar**),** no public (es private por defecto) y declararse dentro de la clase que le da el nombre a nuestra aplicación.

**public class NombreDeLaApp {**

`	`**public static void main(String[] args) {**

`		`**. . . .**

**}**

**}**

Particularidades: 

- Siempre recibe **argumentos** (del programa)** del tipo **String** y de ningún otro, pues si le pasamos un int lo convertirá a un String. No obstante, **se puede declarar sin un parámetro string[]** y usar el método ***GetCommandLineArgs()***. 
- Podrá **devolver** **void, int, Task** o **Task<int>** (en estos dos últimos casos podrá incluir el modificador ***async)***.  
- Cuando este método es llamado desde otro método, se crea un array con los argumentos del programa y lo podemos recorrer/mostrar su contenido por medio de un bucle for. Cabe destacar que el nombre de dicho array será **args**, y para acceder a él podremos usar **args[nº]** o para conocer cuántos hay **args.length**; aunque podremos cambiar la palabra **args** por cualquier otro nombre que queramos. 

A diferencia de C y C++, el nombre del programa no se es el primer argumento de línea de comandos, pero si el primer elemento del método *GetCommandLineArgs()*. 

Así pues, con todo lo dicho anteriormente, la siguiente lista muestra la **signaturas válidas** para Main: 

**public static void Main() { }**

**public static int Main() { }**

**public static void Main(string[] args) { }**

**public static int Main(string[] args) { }**

**public static async Task Main() { }**

**public static async Task<int> Main() { }**

**public static async Task Main(string[] args) { }**

**public static async Task<int> Main(string[] args) { }**

**Instrucciones de nivel superior, programas sin métodos Main**

A partir de C#9, no es necesario incluir explícitamente un método Main en los proyectos de aplicación de consola. En su lugar, se puede usar *instrucciones de nivel superior* para minimizar el código. En este caso, el compilador genera una clase y un punto de entrada de forma implícita. Por lo que podemos directamente lanzarnos a escribir las líneas de código. La **reglas** para poder usar esta práctica son: 

- **Solo un archivo de nivel superior**, pues si tenemos varios archivos dentro de nuestro proyecto, sólo uno de ellos puede tener instrucciones de nivel superior, ya que solo puede haber un punto de entrada del programa. (De lo contrario saldrá error). 
- **Ningún otro punto de entrada,** si escribimos un método Main de forma explícita, el compilador lo ignorará como un punto de entrada y mostrará un warning. 
- **Espacios de nombres,** todas las instrucciones de nivel superior están implícitamente en el espacio de nombres global (*namespaces global*). Aunque puede contener namespaces y definiciones de tipos, siempre y cuando aparezcan **después de las instrucciones de nivel superior**. 
- Las instrucciones de nivel superior pueden hacer referencia a la variables **args** y llamar al método asincrónico con **await**. 
- **Código de salida para el proceso**, para devolver un valor **int** cuando se finaliza la aplicación, se debe usar ***return.*** 

Así pues, la **signatura** del método de punto de entrada dependerá de lo que incluyan las instrucciones de nivel superior: 

`	`Si incluye *await* y *return* 	**static async Task<int> Main(string[] args)**
\*
`	`Si incluye *await* 		**static async Task Main(string[] args)**
\*
`	`Si incluye *return* 		**static int Main(string[] args)**
\*
`	`No incluye ni *wait* ni *return*	**static void Main(string[] args)**
\*


-----


<a name="_h7z0r55r5pnb"></a>**PAQUETES Y LIBRERÍAS** 

Una  **librería/biblioteca** es un código prescrito,  precompilado y reutilizable que nos proporciona diferentes funcionalidades y puede contener funciones o clases que realizan una tarea específica y se pueden enlazar o invocar. Mientras que los **paquetes** son colecciones de módulos, que pueden contener varías o solamente una librería junto con sus dependencias y metadatos asociados. 

En C# un paquete es una unidad de distribución de código que contiene uno o más ensamblados; y la bibliotecas se implementan como ensamblados, que son archivos DLL o EXE que contienen el código compilado. Así pues, en C# las bibliotecas y paquetes son esencialmente lo mismo, ya que ambos son ensamblados que contienen código que puede ser reutilizado en diferentes proyectos. Sin embargo, los paquetes generalmente se refieren a las bibliotecas que se distribuyen a través de un administrador de paquetes, mientras que las bibliotecas se pueden distribuir de otras forma, como a través de archivos ZIP o inclusión directa del código fuente en un proyecto.

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

Cabe tener en cuenta que los paquetes en C# son lo **primero que se declara** y se debe declarar en **minúsculas**. La sintaxis para declarar paquetes es → **using NombreDelPaquete** 	

En C#, los paquetes y bibliotecas se gestionan a través de un administrador de paquetes, el más utilizado es NuGet, que se integra en VS y permite buscar, instalar y actualizarlos en un proyecto. Para agregar uno a un proyecto podemos hacerlo siguiendo estos pasos: 

1. Clic derecho en el proyecto de la ventana solución → *Administrar paquete NuGet.* 
1. Buscamos el paquete que queremos instalar por su nombre. 
1. Damos click en instalar una vez encontrado, para agregarlo al proyecto. 
1. Si queremos utilizar un paquete que no está disponible en NuGet, podemos descargar el archivo de la página web del proveedor y agregarlo al proyecto manualmente. Para ello, hacemos clic derecho en la ventana solución del proyecto → *Agregar → Referencia.* 
1. Seleccionamos el archivo. 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

Nosotros también podemos crear librerías, para ello las **importamos** (tanto si son nuestras ubicadas en otra parte del programa general o de Java). En los siguientes ejemplos podemos ver la sintaxis a llevar a cabo (debe indicarse al principio del programa después de declarar los paquetes: 

- **import paquetequesea.otropaquete.\*;		//Se importan todas las clases pertenecientes a “otropaquete”.** 
- **import paquetequesea.otropaquete.MiClase;		//Se importa directamente una clase del paquete** 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

Entre las **librerías estándar más importantes** se encuentran: 

- **java.applet →** se incluyen clases para crear applets.
- **java.awt →** se incluyen las clases para crear interfaces de usuario con ventanas.
- **java.net →** se incluyen clases que admiten aplicaciones que acceden a redes TCP/IP.
- **javax.swing →** se incluyen clases para crear interfaces de usuario mejorando AWT. 

- **java.time →** se incluyen clases para el manejo de fechas. Estas clases surgen de Joda-Time (biblioteca gratuita y de código abierto) cuyos desarrolladores trabajaron junto a Oracle para mejorarla. entre sus clases destacan: 

- **LocalDate →** Muestra fechas sin la hora, lo cual nos conviene para declarar, sumar, restar o comparar fechas.
- **LocalTime →** Es igual que el anterior, pero se utiliza en la gestión de horas, sin fechas asociadas, para poder compararla, sumar o restar. 
- **LocalDateTime →** Mezcla de las dos primeras, lo que te permite hacer los mismos cálculos con fechas y horas al mismo tiempo. 
- **Instant →** es igual a la anterior, aunque almacena un punto en el tiempo, es decir, una fecha y hora, pero almacenando su valor como un timestamp de UNIX (cantidad de segundos transcurridos desde la medianoche UTC del 1/1/1970, sin contar segundos intercalares).
- **ZonedDateTime →** Similar a LocalDateTime, pero considerando una zona horaria concreta (mientras que las anteriores no). 
- **Period →** esta clase permite recuperar la diferencia entre fechas para diferentes períodos (segundos, min, días…) y agregar estas diferencias a las fechas. 
- **Duration →** similar a la anterior pero solo para la gestión de horas. 

- **java.io →** se incluyen clases que manejan entradas/salidas. 

- **Serializable →** interfaz de marcador (no tiene métodos ni atributos), por ello las clases que lo implementan no tienen que implementar ningún método. Se implementa cuando queremos que las instancias de dicha clase (la que está implementando java.io.Serializable) se serialicen (se realiza mediante ObjectOutputStream) o deserialicen (se realiza mediante ObjectInputStream). 

El hecho de que una clase implemente esa interfaz no significa que sea heredera de ella. 

[Ejemplo de cómo serializar y deserializar un objeto en Java](https://www.geeksforgeeks.org/serializable-interface-in-java/)  p.e public class Persona  implements Serializable{	

Tanto los arrays y las cadenas, como los tipos básicos de Java son serializables, pues se trata de objetos que tienen propiedades que hacen referencia a otros objetos. 

- **PrintWriter() →** Como hemos visto se trata de un objeto perteneciente a la clase **java.io**. Este constructor acepta como parámetro un archivo si queremos que escriba en un archivo, o una cadena de caracteres si queremos decirle el nombre del archivo en el que queremos escribir. Otro parámetro (opcional) es ***autoFlush*** que no es más que un boolean que indica si queremos que tenga autoflushing (forzar a que se vuelque/escriba todo el contenido) o no. 

Como tercer parámetro (opcional) podemos pasar un Charset, es decir el tipo de codificación (p.e UTF8 o UTF16). 

Creado el objeto tipo PrintWriter, podemos usar cualquiera de sus métodos: 

- **print(), println()**
- **printf() →** este como ya vimos en C, permite formatear el string con el uso de %. 
- **close() →** para cerrar el fichero, en caso de que hayamos elegido uno para escribir sobre él. 
- **checkError() →** permite comprobar si hay un error 
- **append() →** permite concatenar las cadenas (aunque como ya sabemos podemos hacerlo también a pelo dentro de los print mediante **+**). 
- **flush() →** permite hacer flush en la salida, es decir volcarlo todo. Se recomienda hacer flush antes de cerrar, es decir antes de usar close(). 

- **java.lang →** se incluyen varias pero esenciales clases del lenguaje, como Object, Thread o Math. Este se importa a los archivos de código Java de forma predeterminada, es decir no tenemos que hacerlo expresamente nosotros. 

- **System →** contiene varios métodos de entrada y salida de datos por pantalla y de salida de error. Proporciona un stream que es una especie de canal por donde fluyen los datos tanto de entrada (a través del teclado), como de salida (a través de la pantalla u otro dispositivo). 

Esta clase posee tres métodos estáticos: 

- **Standard Input Stream (System.in) →** se utiliza junto con la clase **Scanner** para ingresar datos por teclado o desde un archivo. P.e Scanner entrada=new Scanner(System.in) 
- **Standard Output Stream (System.out) →** se utiliza junto a la función **print/println/printf** para la salida de información por pantalla. **P.e System.out.printIn(“Lo que queramos mostrar”)**
- **Standard Error Stream (System.err) →** también se utiliza junto a la función **print/println/printf** pero incluyendo una e que representa error. **P.e System.err.printIn(“Mensaje de Error”+e)** 
- **System.exit(códigodeestado) →** permite salir del programa actual al finalizar la ejecución de la máquina virtual Java. Además toma un código de estado de finalización del programa (**0** indica **terminación exitosa**, y cualquier otro valor indica una **terminación fallida**, normalmente **1** o **-1**).

**\*\*Nota →** cuando queramos concatenar varios datos en un mismo print, bastará con poner **+**. Si lo que ponemos no es una cadena directamente usando “ “, sino una variable, bastará con poner el nombre de la variable sin comillas. 

**\*\*Nota →** con el método **printIn** el mensaje se muestra en pantalla y luego el cursor queda en el renglón siguiente; mientras que al usar **print** se muestra el mensaje y el cursor queda al final de la línea. 

Por otro lado, desde la v1.5 de java, está disponible **printf**, cuyo funcionamiento es igual al conocido en C: 

Permite mostrar una cadena de texto con formato por la salida estándar, admitiendo un nº variable de argumentos. En el caso de la cadena **format** ésta contiene símbolos de sustitución que serán reemplazados con el resto de argumentos en estricto orden, es decir debemos indicar entre “ “ todo lo correspondiente a format y seguido de una , se deberán de indicar el nombre de las variables que sustituirán a los símbolos de sustitución: 

- **%d** reemplazará un **entero** con **formato decimal.**  
- **%f** reemplazará un **real** con **formato decimal** (podemos indicar el nº de decimales % .**3f**)
- **%s** reemplazará una **cadena de caracteres.**   
- **%c** reemplazará un **carácter.**   
- **%lu** reemplazará un **long unsigned**.

- **Thread →** Clase, explicada en MULTITAREA. 
- **Runnable →** Interfaz, explicada en MULTITAREA. 

- **java.util →** se incluyen clases que permiten el acceso a los recursos del sistema, etc. 

- **Scanner →** mejor clase para recibir información (datos primitivos) a través del teclado y/o de ficheros. No obstante, cabe destacar que si deseamos un método de entrada con limitaciones de tiempo, esta clase no es muy eficaz. 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.010.png)

Para utilizarla hay que crear un objeto de clase Scanner. 

`	`**Scanner nombrevar1=new Scanner(parámetro que indica de dónde proceden los datos);**  

//Si ponemos System.in como parámetro, se considerará el teclado. Por el contrario podemos poner cualquier archivo a leer

Para capturar la información ingresada es necesaria otra variable que “reciba” los datos introducidos por el teclado (debemos repetir este proceso cada vez que queramos  pedir algo por teclado..):

`	`**tipovar nombrevar2=nombrevar1.método;** 
**


El método podrá ser cualquiera de los siguientes (cabe destacar que si ingresamos un tipo de dato que no es el esperado, Java nos da error): 

- **nombrevar2.next() →** lee un String hasta encontrar un delimitador, generalmente un espacio. Usando **nombrevar2.useDelimiter();** al cual se le debe pasar como parámetro el delimitador que queremos, por ejemplo “\\s\*, \\s\*”  establece que el delimitador es una coma precedida o no de uno o más espacios y seguida o no de uno o más espacios, pues \\s es un espacio y el asterisco indica cero o más. 
- **nombrevar2.nextBoolean() →** Lee valores booleanos. 
- **nombrevar2.nextByte() | nextDouble() | nextFloat() | nextShort() | nextInt() | nextLong()** 
- **nombrevar2.nextLine →** Lee un String hasta encontrar un salto de línea. Devuelve la línea siguiente a leer. 
- **nombrevar2.hasNextLine() o Byte, Int etc etc→** nos devuelve un boolean que indica si hay o no una línea, byte, int etc etc  más que leer. 

Una vez creada la variable objeto y recibido su contenido (se hace en el momento de crear el objeto (nombrevar2). Cuando ya no queramos usarlo más, pasamos a cerrar la clase con el siguiente método:

**nombrevar1.close() →** Cierra la clase Scanner luego de utilizarla. (nombrevar1) 

- **ArrayList →** esta clase proviene de la interfaz *Collection*  -> *List,* pues esta última implementa a AbstractList, la clase de la que hereda ArrayList. En cuanto a la diferencia frente a un Array es la misma diferencia entre una colección (ArrayList es una) y los Array como podremos ver en el apartado correspondiente. No obstante, la sintaxis si varia un poco: 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.011.png)

Para declarar un array → **ArrayList<tipodedato> nombredelarray = new ArrayList<tipodedato>();** 

Para acceder al dato de una posición concreta → **nombredelarray.get(posicion)**;

Para añadir elemento al array (cabe destacar que los objetos se añaden en orden FIFO, por lo que el último que entra ocupa la última posición de la lista) → **nombredelarray.add(valordeldato);** 

Modificar el valor de una posición → **nombredelarray.set(posicion, nuevovalor);**

Borrar uno/todos el/los elemento/s → **nombredelarray.remove(posicion);  || nombredelarray.clear();** 

Cuando borramos un elemento la tabla se recoloca, por eso cuando borremos un elemento por su valor (usando bucles e if ) y no por su posición, debemos salir de las estructuras (if, bucles…) para que Java pueda reacomodar el array. 

En la explicación de colecciones hay más métodos como size. 

- **LinkedList →** esta clase proviene de la interfaz *Collection -> List,* pues esta última implementa la clase AbstractList que a su vez hereda en AbstractSequentialList, la clase de la cual hereda LinkedList. Esta representa una **lista doblemente enlazada** (ida y vuelta), esto quiere decir que todas las posiciones . Gracias a ello también puede ser usada/tratada como una **pila** o **cola,** ya que permite insertar/eliminar los elementos del principio y del final, es decir permite tanto el orden FIFO como LIFO. ![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.012.png)

Como se puede observar el elemento del principio solo apunta hacia el de adelante y el último solo apunta hacia el anterior; mientras que los del medio apuntan tanto hacia delante como hacia atrás. 

Dado que tanto LinkedList como ArrayList son implementadas por la interfaz *List*, ambas pueden utilizar los mismos métodos (añadir elementos, cambiarlos, borrarlos…). No obstante, dado que LinkedList no tiene los elementos indexados y puede ser alterada tanto por el principio como por el final, LinkedList incluye unos métodos específicos para llevarlo a cabo por el principio de la lista o el final de la misma: 

Para declarar un array → **LinkedList<tipodedato> nombredelarray = new LinkedList<tipodedato>();** 

Para acceder al dato de una posición concreta → **nombredelarray.\***; **|| getFirst || getLast || get(posición)**

Para añadir elemento a la lista→ **nombredelarray.\*; || addFirst || addLast || add()** //Este equivale a addLast (FIFO)

Modificar el valor de una posición → **nombredelarray.set(posicion, nuevovalor);** 

Borrar uno/todos el/los elemento/s → **nombredelarray.\*; || removeFirst() || removeLast() || remove(posicion) ||                   nombredelarray.clear();** 

Cuando estemos llevando a cabo la eliminación de un elemento cuya posición desconocemos, utilizaremos bucles e if. En ese caso tenemos que tener en cuenta que una vez encontrado el elemento y borrado debemos salir de las estructuras para dejar que Java reacomode la lista acomodándose los punteros. 

En la explicación de colecciones hay más métodos como size. 

- **Stack →** esta clase hereda de *Vector* que a su vez es implementada por la interfaz *Collection*. La **pila** a diferencia de los ArrayList y los LinkedList, tiene ordenación **LIFO**, es decir el último en entrar es el primero en salir. En cuanto a su sintaxis es muy similar: 

Para declarar un array → **Stack<tipodedato> nombrepila= new Stack<tipodedato>();** 

Para acceder al dato de una posición concreta → **nombredelarray.get(posicion**; 

Para añadir elemento a la pila→ **nombrepila.push(datoaañadir);**   //Este equivale a ordenación LIFO

Modificar el valor de una posición → **nombrepila.set(posicion, nuevovalor);** 

Borrar uno/todos el/los elemento/s → **nombrepila.pop();**     //Elimina el último elemento que entró (LIFO)**  

`                 `**nombrepila.clear();** 

Buscar en una pila directamente → **nombrepila.search(datoabuscar);** 

`        `//Devuelve la posición que ocupa en la pila (empieza en 1 y no en 0, y es según el 

`                          `orden LIFO, es decir el **último en entrar ocupa la 1 posición**. Devuelve **-1** si no lo 

`	         `encuentra.

`	         `Este no funciona expresamente con objetos (clases instanciadas). 

Obtener el último elemento añadido a la pila → **nombrepila.peek();**

En la explicación de colecciones hay más métodos como size. 

-----

<a name="_i6709oszcw6m"></a>**ESTRUCTURA DE PROYECTO** 

1. Declaramos los paquetes.  
1. Importamos otros paquetes o propios. 
1. Declaramos una clase pública que deberá contener el método main(), el cual es el método principal de todo proyecto. 
1. Declaramos las variables, puede ser antes o después del main(). 
1. Declaramos el método main, su presencia es imprescindible, pues es el punto de entrada a nuestra App. Sin este método no funcionará el programa.
1. Declaraciones de variables de instancias, para trabajar con un objeto dentro de nuestro programa , precisamos instanciar (crear) el objeto, al crearlo puede tener variables distintas a otro objeto de la misma clase. 
1. Definición de constructores. 
1. Definición de métodos. 
1. Comentarios. 

-----

<a name="_6ak7mxrfkeoo"></a>**EXCEPCIONES JAVA** 

Errores producidos en tiempo de ejecución como consecuencia de un fallo en una instrucción del programa, como al dividir por cero, no abrir un archivo correctamente…etc. Las excepciones producirán **mensajes de error en la pantalla y finalizan la ejecución del programa**; además se crea un objeto de alguna clase (dependiendo del tipo de error que haya ocurrido) que contendrá información sobre el error que se generó y nos proporcionará los métodos necesarios para obtener dicha información. 

La **clase padre** de dichas clases es **Throwable**, está da lugar a dos subclases *Error,*  errores** (situación que no se espera y que interrumpe la ejecución del programa) y *Exception,* excepciones (situación que no se espera pero que se puede capturar y en base a ello dirigir el flujo del programa hacia otro lado). 

Existen **dos tipos** de excepciones en java: 

- Propias de Java como lenguaje![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.013.png)
- Personalizadas (creadas por nosotros mismos) 

Existen innumerables excepciones propias de Java las cuales se van tomando con la experiencia y que iré poniendo en la siguiente lista: 

- **RuntimeException →** se tratan de excepciones NO comprobadas y ocurren dentro de la máquina virtual de Java durante el tiempo de ejecución, suelen ser errores del programador. 

- **ArithmeticException →** se produce por errores en cuanto a operaciones aritmetológicas no permitidas. 
- **ArrayIndexOutOfBounds →** se produce cuando el índice es negativo y ≥ que el tamaño del array. 
- **NullPointerException →** se produce cuando se intenta usar una referencia nula en el uso de un objeto. 

- **IOException →** señala algún tipo de error en una operación de entrada/salida (suelen ocurrir al procesar archivos u operaciones de red).  Se conocen como *excepciones comprobadas*, pues no son culpa del programador. P.e una sentencia que debe leer un archivo, hemos puesto bien la ruta y no hay errores de sintaxis, pero alguien removió ese archivo y el programa no lo encuentra para utilizarlo.

- **FileNotFoundException →** error de entrada/salida que indica que cuando se abrió el archivo, no existía en el sistema de archivos. 

- **ClassCastException →** se produce si se realiza una operación de cast en un tipo de objeto que no es una instancia. 
- **IllegalArgumentException →** señala que el valor de un argumento no es válido y generalmente se usa para verificar una condición previa al comienzo de un método. 
- **ClassNotFoundException →** se produce cuando se intenta cargar una clase, pero no existe. Suele darse porque la biblioteca no está disponible en el classpath cuando se inicia el programa o la app requiere otra versión de una biblioteca. 
- **NoClassDefFoundError →** equivale a la anterior, con la diferencia de que la clase existe en tiempo de compilación, pero no en tiempo de ejecución. 
- **NoSuchMethodException →** se produce cuando no se encuentra el método. Esto es posible cuando una nueva versión de la biblioteca elimina un método o cambia su firma con un cambio no compatible con versiones anteriores. 
- **SQLException →** se produce al acceder a una base de datos relacional, p.e si la instrucción SQL no tiene la sintaxis correcta. 
- **StackOverflowError →** se produce cuando hay demasiadas llamadas recursivas a un  método. 
- **InterruptedException →** se produce cuando se interrumpe un thread p.e por usar hilos y operaciones simultáneas. 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

<a name="_pyse97o9jtch"></a>**Control de excepciones** 

Permite automatizar una enorme cantidad de código que antes tenía que añadirse “manualmente”, pues simplifica el control de errores al hacer que nuestro programa cree un bloque de código llamado **controlador de excepciones**, que se ejecutará automáticamente cada vez que se produzca un error, permitiendo así que no se requiera verificar de forma manual el éxito o fracaso de todas las llamadas del método u operación específicos. 

Java define una serie de excepciones estandarizadas para los errores más comunes de los programas, así el programa es capaz de percibir y controlar dichas excepciones; además la biblioteca API de Java hace un uso extensivo de las excepciones. 

El control de excepciones se administra a través de **cinco palabras clave** que crean un subsistema interconectado donde utilizando una, se utilizan las demás ( [ejemplos](http://dis.um.es/~bmoros/Tutorial/parte9/cap9-3.html)  [OtroEjemplo+](https://www.tutorialesprogramacionya.com/javaya/detalleconcepto.php?codigo=165) ) : 

- **try →** dentro de este bloque se debe incluir el código, de forma que si ocurre una excepción dentro de dicho bloque, ésta se lanzará. 
- **catch →** permite capturar la excepción que se le indique y manejarla de manera sensata. Equivale un poco al “else” del try, pues se ejecutará cuando se dispara una excepción en el bloque try. 
- **finally →** es un bloque opcional, que en caso de usarlo, se ejecuta siempre, con independencia de que se haya ejecutado únicamente el try o se haya ejecutado el catch, es decir con independencia de que se produzca o no un error.   
- **throw (lanzar) →** permite lanzar excepciones manualmente. Es decir, en la parte del código que queramos indicamos a través de esta sentencia que se debe lanzar la excepción que indiquemos, de alguna manera es como forzarla. La sintaxis para poder usarlo:

`	`**if (n==0) throw new nombreexcepción(“mensaje que queremos que se muestre en la terminal”);** 
**

**
`	`o bien sin new, pero usandolo dentro del catch

Tras esto, Java hará escalar la excepción hacia arriba hasta hallar dentro de otro método un bloque de código que la capture (*try-catch*), si no lo encuentra, seguirá subiendo hacia el método inmediato superior a ver si lo encuentra allí, si sigue sin encontrarlo, el programa se detiene. 

- **throws (lanza un 3º, es decir un método) →** si un método es capaz de provocar una excepción que no maneja él mismo, debería de usar throws. Permite identificar la lista (separadas por ,) posible de excepciones que un método puede lanzar. Éste se utiliza para todas las subclases de la clase *Exception* excepto si es de tipo RuntimeException o cualquiera de su subclases. Por ello se suele utilizar junto a throw, solo que en este caso no se indica como sentencia del bloque sino que se usa antes de las {} del método. 

`	`**\_\_\_ nombremétodo(argumentos) throws excepciones {}** 

→ try y catch se utilizan juntos, la sintaxis para ello es la siguiente: 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.014.png)

**try{** 

**//bloque de código para monitorear errores**

**}**

**catch (TipoExcepción1 ex0b){			\*\***

**//Manejador para TipoExcepción1**

**}**

**catch (TipoExcepción2 ex0b){**

**//Manejador para TipoExcepción2**

**}**

**SI HUBIESE UN RETURN, ÉSTE DEBE INDICARSE FUERA DEL TRY AND CATCH** 

**\*\***Lo que contiene el catch dentro del paréntesis debe de ser el nombre exacto de la excepción o el nombre de la clase superior (en ese caso sería *Exception,* pues todas las excepciones provienen de ésta). Por otro lado, *ex0b* puede ser sustituido por cualquier letra/nombre, ya que sencillamente será la variable que guarde la información del error producido.***   

Cuando creamos **excepciones personalizadas**, la clase debe heredar siempre de ***Exception***. 

-----

<a name="_x4nf8dx5dv1o"></a>**JSON** 

JSON (JavaScript Object Notation) es un formato ligero de **intercambio de datos** que se utiliza para enviar y recibir datos entre aplicaciones web (se pueden comunicar aplicaciones de lenguajes diferentes). Es una alternativa al formato XML (este supone aprox un 75% de metainformación para un 25% de información, lo cual no es tan óptimo), razón por la que JSON es mejor, además de ser fácilmente legible por humanos y por máquinas. 

La razón por la que JavaScript aparece en las siglas de JSON es porque cada vez que guardamos datos con JSON, almacenamos un objeto JavaScript. 

Se basa en una estructura de pares de **nombre/valor** (los valores pueden ser cadenas de texto, números, objetos, matrices, valores booleanos y valores nulos (null)), y se utiliza principalmente para representar datos estructurados en forma de **objetos** o **matrices**. 

Su sintaxis** es muy sencilla, donde los datos se representan como una colección de pares de nombre/valor, separados por comas, y delimitados por **llaves {}** para **objetos** y **corchetes []** para **matrices**. p.e: 

Objeto → **string json = “{\”Name\”: \”LoliPop”, \”Brand\”: \”Fiesta\”}”;**	      //Usamos \ solo para escapar las comillas dentro de las comillas

Matriz → **string json2 = “[“ +** 

` `**“{\”Name\”: \”LoliPop”, \”Brand\”: \”Fiesta\”},” +** 	//Los objetos deben de separarse con , 

` `**“{\”Name\”: \”LoliPop”, \”Brand\”: \”Fiesta\”}” +** 

**“]”;**
**


C# como la mayoría de lenguajes, tiene métodos para convertir formato JSON a objetos y viceversa, evitándonos tener que hacerlo a mano, para ello debemos importar el paquete System.Text.Json para poder usar la clase **JsonSerializer**, tanto para serializar (método **Serialize)** como para deserializar (método **Deserialize**):: 

- ***Convertir objeto a formato Json →* string nombreObjetoJson = JsonSerializer.Serialize(nombreDeObjetoaConvertir);** 

- ***Convertir formato Json a objeto →*** 

**NombreClaseObjeto nombreInstaciaObjeto = JsonSeializer.Deserializer<NombreClaseObjeto>(nombreDeJsonAConvertir);**

**NombreClaseObjeto[]                                                                                         <NombreClaseObjeto[]>**  	//Si es una matriz



\*\***Nota →** ver qué es **serializar** (objeto en cadena JSON)**  y **deserializar** (cadena JSON en un objeto) en el [Glosario.](https://docs.google.com/document/d/1awoy3Nl8ITfb-t5iZXxphebcRHGZIcaW9a7weKu-qKo/edit) 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

**Creación de ventanas y componentes**

Las **ventanas de la biblioteca AWT** se incluyen en la clase **Frame**. Podemos crear una GUI usando Frame de **dos formas ([Ejemplos](https://quejava.com/tutorial-de-java-awt-para-principiantes/))**: 

- *Ampliación/extensión de la clase Frame* *→*  consiste en crear una clase heredera de Frame. La diferencia entre el código cuando lo hacemos de esta manera en vez de la siguiente, es que al no tener que crear una instancia de un objeto frame, no debemos indicar **nombreobjeto.método**, sino que usamos los métodos de Frame de forma directa. 

- *Creando la instancia de la clase Frame directamente* → Cuando creamos una instancia de un objeto Frame, éste contendrá borde y título además de la posibilidad de incluir una barra de menú:  

**Button botonTitulo = new Button(“Texto del botón”);**	//Creamos un botón

**Frame miFrame = new Frame (“Título de la ventana”);** 	//Crear ventana

**miFrame.setLayout(new FlowLayout());**	//FlowLayout es un controlador de posicionamiento que pone los componentes encadenados en forma

`				`//de lista, de izquierda a derecha. 

**miFrame.add(botonTitulo);**		//Añadimos el objeto botón al frame

**miFrame.setSize(100, 200);**		//Indicamos el ancho y alto (respectivamente) que queremos que tenga la ventana

**miFrame.setVisible(true);**		//Hacemos visible la ventana


Para poder interactuar con una interfaz visual, es decir, para poder reaccionar y ejecutar código cuando se presionan los botones, se mueve el ratón, se escribe, etc., se deben administrar los eventos. Un **evento** es una señal que comunica a una aplicación que ha sucedido algo importante. P.e usuario hace click en un control en un formulario, el formulario puede provocar un evento click y llamar a un procedimiento que controla dicho evento. 

Los eventos de Java se organizan dentro del paquete **java.awt.event** (importamos java.awt.event.\*): 

- **java.awt.AWTEvent →** base para los eventos utilizados para la construcción de GUIs. 
- **java.util.EventObject →** clase base para todos los eventos en Java. 

**(Esto mejor verlo en ejemplos y en las explicaciones de los componentes)** Para implementar de manera sencilla algunos controladores de evento, el paquete **java.awt.event** incluye una clase base **XxxAdapter** que implementa la interfaces **XxxListener**. Los eventos **XxxEvent** tienen una interfaz **XxxListener** asociada, gracias a la cual podemos definir manejadores de eventos: 

- **MouseAdapter →** para manejar los eventos del ratón.
- **WindowAdapter** para manejar los eventos de ventana (cerrarla, minimizarla, hacerla pequeña). 
- **ActionListener →** para especificar qué va a hacer una aplicación al presionar un botón. 

-----

**APPLETS**

Programas escritos en **Java** (o cualquier lenguaje compatible con código generado por Java como Jython y Scala, entre otros) y que forman parte de los componentes de una página web. Se utilizan para añadir funcionalidad a las páginas web que no se pueden satisfacer utilizando solo HTML; y su objeto es ser lo suficientemente pequeño para proporcionar una determinada funcionalidad bien definida. 

El código del applet es ejecutado por el propio navegador utilizando la JVM, lo cual permite que el código sea independiente del SO que ejecuta el navegador. 

Estos programas nacieron con Java (**1995**) y se fueron popularizando. No obstante, los applets (junto a Java) se enfrentan a grandes **críticas por su seguridad**, lo que ha dado lugar a que cada vez más sean los buscadores que bloquean las versiones anteriores de Java, en especial con la creciente popularidad HTML5. Así pues, el uso de subprogramas ha disminuido convirtiéndose en una **tecnología que tiende a desaparecer.** 

**Applets vs Scripts Javascript →** applets son más difíciles de programar y requiere de conocimientos básicos o medios del lenguaje Java.  No obstante, los applets son mucho menos dependientes del navegador y, dado que Java es más potente que Javascript, el nº de aplicaciones de los applets podrá ser mayor. 

Cabe destacar que los applets son más lentos de procesar y tienen un espacio muy delimitado en la página donde se ejecutan, es decir no se mezclan con todos los componentes de la página ni tienen acceso a ellos. Es por ello que con los applets de Java no podremos hacer directamente cosas como abrir ventanas secundarias, controlar Frames, formularios, capas, etc. 

Algunos ejemplos de funciones que utilizan applets son: 

- Agregar secuencias de imágenes y efectos visuales. 
- Agregar imágenes con sonido y efectos sonoros. 
- Uso de funciones especializadas, como p.e, applets para calcular el valor del ángulo inscrito en una circunferencia y circuncentro de un triángulo. 
- Animación de texto y efectos especiales. 
- Crear tablas y gráficos. 
- Crear juegos simples. 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

**Creación de un applet (ver ejemplos en proyecto ventana)**

Para crear un applet, se debe hacer a través de una **clase heredera de la clase Applet** (incluida en el paquete **java.applet**, por lo que debemos importar java.applet.\*). Si utilizamos la biblioteca de gráficos **Swing**, se puede usar la clase **JApplet** (incluida en el paquete **javax.swing,** por lo que debemos importar javax.swing.JApplet) para heredar de ésta en vez de la mencionada anteriormente.

-----

<a name="_bt9bcuj5kpx0"></a>**ACCESO A FICHEROS** 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.015.png)

Los ficheros de texto son los más sencillos de manejar, éstos pueden ser creados con un programa Java o un editor de texto y así mismo luego pueden ser leídos desde el programa Java o desde el editor de texto. Son de gran utilidad, entre otras cosas porque nos permite salvar los datos de un programa en un fichero y luego restaurarlo (aunque si la cantidad de datos es muy grande lo más apropiado es usar una base de datos). 



















El **tratamiento de ficheros** debe regirse por la siguiente secuencia ([Ejemplos](https://chuwiki.chuidiang.org/index.php?title=Lectura_y_Escritura_de_Ficheros_en_Java) ): 

1. **Abrir un fichero,** pues de lo contrario cuando queramos acceder al contenido saldrá un error. 

- **FileReader →** podemos abrir un fichero de texto para leer usando esta clase. Ésta nos permite leer caracteres. Sin embargo, esta clase no contiene métodos para leer líneas completas. 

Para solventar este último problema, usamos la clase **BufferedReader (**recibe como parámetro el fichero y como segundo parámetro opcional el tamaño del buffer**)** que si que permite leer líneas completas, debemos construir/instanciar un *BufferedReader* a partir del *FileReader*. 

Cabe destacar el uso de algunos de los **métodos importantes de BufferedReader ([Ejemplos](http://ayudaitver.blogspot.com/2014/07/uso-basico-del-bufferedreader.html#metodos) )**: 

- **close() →** vacía el buffer (volcándolo en el disco)  y lo cierra. 
- **mark(nº) →** establece una marca en la posición actual del apuntador del flujo. De forma que cuando se llame al método **reset()** se pueda regresar a la última marca hecha. 

Cabe destacar que se debe pasar como parámetro el nº de caracteres que pueden ser leídos y aún mantener la marca, es decir que si se rebasa ese número de caracteres, la marca será descartada y no se podrá volver a ella. 

- **read() →** lee un solo carácter del flujo y retorna un nº entero correspondiente al valor de código ASCII que representa a ese carácter. Dado que el código ASCII en la mayoría de casos no será de mucha utilidad, será necesario hacer casting de entero a carácter. 
- **readLine() →** lee una línea, es decir va leyendo caracteres hasta encontrarse con el carácter \n (salto de línea) o \r (retorno de carro). 
- **ready() →** este método nos devuelve un boolean indicando si aún hay caracteres en el flujo para ser leídos, o por el contrario hemos alcanzado EOF (End Of File), que en el caso de los archivos de texto EOF = -1. 
- **skip(nº) →** mueve el apuntador del flujo las posiciones necesarias para evitar el nº de caracteres indicado como parámetro. 
- **lines() →** devuelve las líneas que hay en el buffer de lectura. 

Como alternativa para leer un fichero de texto línea por línea, podría usarse **Scanner** tal y como se explica más arriba (en paquetes). [Ejemplo de como hacerlo con Scanner](https://chuwiki.chuidiang.org/index.php?title=Lectura_de_teclado_en_java#Ejemplo_de_lectura_de_un_fichero_con_Scanner)  

- **FileWriter →** podemos abrir un fichero de texto para escribir en él desde cero, en cuyo caso al instanciar un objeto de tipo FileWriter pasamos el nombre del fichero como parámetro y ya; o bien si queremos añadir texto al final de un fichero ya existente, hacemos lo mismo pero pasamos un segundo parámetro correspondiente a un boolean que true. 

En este caso ocurre lo mismo que con la lectura, si queremos ir línea por línea y no caracter por caracter, debemos hacer uso de **BufferedWriter (**recibe como parámetro el fichero y como segundo parámetro opcional el tamaño del buffer**).**  

Cabe destacar el uso de algunos de los **métodos importantes de BufferedWriter**: 

- **close() →** vacía el buffer (volcándolo en el disco)  y lo cierra. 
- **write(nº) →** escribe un solo carácter, que será el pasado como parámetro. Teniendo en cuenta que al igual que read(), trata los caracteres según su código ASCII.  
- **write(string, nºoffset, nº) →** escribe el string que se le indica como parámetro. El segundo parámetro deberá indicar la posición a partir de la cual se va a escribir el string, p.e si es “Hello Geeks” y ponemos un offset igual a 6, entonces lo que se escribirá en el buffer será “Geeks” . Por último debe pasarse un nº que indique el tamaño (nº de caracteres) que tendrá la cadena en cuestión. 
- **newLine() →** escribe una línea de separación. 
- **flush() →** vacía el buffer sin cerrarlo, es decir se limita a volcarlo en el disco**.**  

**\*\*Nota →** si usamos FileReader o FileWriter para leer/escribir, se hará físicamente sobre el disco duro, si vamos escribiendo y leyendo de pocos en pocos caracteres, el proceso se hace costoso y lento al implicar muchos accesos a disco duro. Es por ello que se recomienda el uso de los Buffered, pues lo que hacen es añadir un buffer intermedio, de forma que solo se accede al disco cuando el buffer se llena o cuando a través de un método se indica expresamente. 

1. **Leer/modificar/guardar datos.** 
1. **Cerrar el fichero,** pues de lo contrario es posible que no se guarde ningún dato, ya que el buffer no llega a vaciarse (los datos preparados permanecen en la memoria intermedia hasta que el buffer se llene o se da el aviso de cierre y pasan a ser volcados en el disco). Es por este motivo que se suele incluir en el ***try-catch*** un ***finally*** con el close() dentro, de forma que siempre se garantice el cierre del fichero. 

La **clase File** es de gran importancia a la hora de tratar con ficheros pues como vemos en los ejemplos es lo que se utiliza en primer lugar para luego ya complementarlo con las clases vistas anteriormente, ésta incluye los siguientes métodos (entre otros [Ejemplos](https://somoshackersdelaprogramacion.es/la-clase-file-de-java) ): 

`  `**\*\*** recordemos que previamente al uso de estos métodos, es necesario crear una instancia de File indicando la ruta en la que se encuentra (o encontrará) el archivo: 

- **NombreInstanciaFile.createNewFile()** → Permite crear un archivo, devolviendo un boolean que indica si ha sido posible crear el fichero o no. 
- **NombreInstanciaFile.exists() →** devuelve un boolean que indica si el fichero existe o no. 
- **NombreInstanciaFile.isFile()** o **NombreInstanciaFile.isDirectory() →** devuelve un boolean indicando si es un fichero o un directorio respectivamente según usemos uno u otro. 
- **NombreInstanciaFile.canRead()** o **canWrite()** o **canExecute() →** devuelve un boolean indicando si se tiene o no el permiso, según se use un método u otro. 
- **NombreInstanciaFile.delete() →** permite borrar el fichero. Conviene después de borrar comprobar si existe. 
- **NombreInstanciaFile.getAbsolutePath() →** permite obtener la ruta completa del fichero. 
- **NombreInstanciaFile.getName() →** permite obtener el nombre del fichero. 
- **NombreInstanciaFile.getParent() →** permite obtener la ruta padre, es decir la ruta del directorio que contiene un fichero. 
- **NombreInstanciaFile.length() →** permite obtener el tamaño de un fichero en bytes. 
- **NombreInstanciaFile.isHidden() →** devuelve un boolean que indica si el fichero está oculto o no. 
- **NombreInstanciaFile.listFiles() →** devuelve un array de objeto de tipo File, es decir un array que contiene todos los ficheros y directorio de un determinado directorio. 
- **NombreInstanciaFile.mkdir() →** permite crear un directorio. 
- **NombreInstanciaFile.setExecutable(boolean)** o **setReadable** o **setWritable →** según se indique en el boolean que se pasa por parámetro permite establecer los permisos de un fichero.
-----

<a name="_6qb9sbb7gi5y"></a> **MULTITAREA ([Buenos Apuntes](http://informatica.uv.es/iiguia/LP/teoria/apuntes/cuatr1/tema3_2_concurrencia2.pdf) )**

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.016.png)

Java trae un soporte integrado diseñado exclusivamente para la programación **multihilo/multithread**, este tipo de programas constan de varias partes en su código (donde cada una de ellas reciben el nombre de **hilo o thread**) que se pueden ejecutar de manera simultánea e independiente. 

Existen **dos tipos de multitarea**: 

- **Multitarea basada en procesos →** teniendo en cuenta que un **proceso** es un programa en ejecución. Este tipo de multitarea basada en procesos permite que se puedan ejecutar varios programas a la vez. 


- **Multitarea basada en hilos →** teniendo en cuenta que un **hilo o subproceso** es la unidad de código más pequeña que se puede distribuir y que NO pueden existir fuera de un proceso (pues pertenece a él); todo proceso cuenta con mínimo un hilo de ejecución “*hilo principal*” que se establece al iniciar un programa. Este tipo de multitarea basada en hilos permite que un programa pueda realizar muchas tareas (ejecutar muchos hilos) al mismo tiempo. 

**Ventajas →** permite escribir código más eficientemente, pues los programas pueden realizar diferentes tareas durante un tiempo de inactividad, haciendo el programa mucho más potente. P.e cuando un hilo/(parte) de nuestro programa envía un archivo a través de internet, otro hilo/(parte) puede leer la entrada del teclado y otro hilo/(parte) puede almacenar el siguiente bloque de datos para enviar. 

Es importante comprender que la naturaleza multiproceso de Java se aplica tanto a **sistemas multiprocesador** (varias CPUs/procesadores) como a **sistemas monoprocesador** (una sola CPU/procesador). En éste último caso (sistemas monoprocesador), en el que solo existe un núcleo, la CPU se comparte mediante la ejecución simultánea de subprocesos(hilos), cada uno de los cuales contiene un bloque de tiempo de CPU. 

Cabe destacar que en un sistema monoprocesador no es que se estén ejecutando los hilos al mismo tiempo, sino que se usa el tiempo de inactividad de la CPU, es decir se van otorgando tiempos a cada uno de los hilos, siendo estos tiempos tan rápidos que da la sensación de que todo está pasando de forma simultánea (**conmutación de contextos**). Mientras que en los multiprocesador si que pueden ejecutarse diferente subprocesos/hilos a la vez. 

`	`**—--------------------------------------------------------------------------------------------------------------------------------------------**

**Clase Thread**

Clase incluída en **java.lang**, permite gestionar los hilos a través de sus **métodos**, entre los cuales destacan: 

- **start() →** método que inicia la ejecución de la tarea/subproceso/hilo. El método invoca a run() y devuelve inmediatamente el control a la tarea/hilo/subproceso que lo ha llamado. 

Se debe tener en cuenta que si el sistema sólo tiene núcleo, no se ejecutan varios subprocesos a la vez, sino que se usa el tiempo de inactividad de la CPU, a diferencia de un multiprocesador. 

- **stop() →** método que hace que se detenga un determinado hilo inmediatamente. Esta suele ser una forma tosca de parar un subproceso, especialmente si se ejecuta en el subproceso actual; es por ello que para parar un hilo de una manera más sofisticada se recomienda mejor el uso de algunas variables para que el método run() salga ordenadamente. 

- **run() →** método que forma la estructura principal de los hilos que se están ejecutando, este método es el único que tiene la interfaz Runnable y se invoca mediante start(). Es por esto que todas las clases derivadas de Thread deben de sobrescribir el método run(). 

La ejecución del método run de un Thread puede realizarse **concurrentemente** con otros método run de otro Thread y con el método main. 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.017.png)![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.018.png)













- **currentThread() →** devuelve un objeto de tipo hilo/subproceso correspondiente al subproceso que se está ejecutando actualmente. 
- **sleep(nº) →** permite suspender el subproceso actual durante el **nº de milisegundos** especificado como parámetro. Pasados los milisegundos indicados, el hilo estará nuevamente disponible. (Los relojes asociados con la mayoría de los intérpretes de Java no podrán lograr una precisión superior a 10 ms). 
- **yield() →** permite cambiar el contexto entre el subproceso actual y el siguiente subproceso en ejecución que se encuentre disponible, es decir el hilo actual cede su tiempo de CPU. De esta manera se garantiza que los subprocesos de baja prioridad/importancia no se queden sin recursos, es decir, también puedan tener el tiempo de CPU que les corresponda. 
- **suspend() →** toma un subproceso y hace que pare la ejecución sin llegar a finalizar el subproceso del sistema ni el estado de un subproceso en ejecución anterior. 

Si se suspende la ejecución de un subproceso, podemos llamar al método resume() en el mismo proceso y ejecutarlo nuevamente. 

- **resume() →** se usa principalmente para reanudar un hilo que está en estado de suspensión. No existe ninguna garantía de que vaya a iniciarse el hilo de inmediato, ya que es posible que un subproceso con más prioridad se encuentre ejecutándose en ese momento, pero el método resume() hace que vuelva a ser un candidato a ser ejecutado. 
- **getPriority() →** devuelve la prioridad del subproceso actual, es decir, un valor entre 1 y 10. 
- **setPriority(nº) →**  asigna al hilo la prioridad indicada por el argumento que se pasa. La clase Thread facilita **constantes predefinidas** para la prioridad como: 

- MIN\_PRIORITY → 1
- NORM\_PRIORITY → 5
- MAX\_PRIORITY → 10

- **setName(String) →** este método permite identificar al hilo con un **nombre menmónico,** por lo que se puede depurar mejor los programas multihilo. Este nombre aparecerá en todas las líneas de trazado que se muestran cada vez que el intérprete Java imprime excepciones no capturadas. Por otro lado, **getName()** nos devuelve el valor actual (tipo String) asignado como nombre al hilo en ejecución mediante *setName()*. 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.019.png)

El hilo se encuentra “vivo” cuando está en estado “Ejecutable” o “No ejecutable”. 




![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.020.png)![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.021.png)














![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.022.png)![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.023.png)

El criterio para la ejecución de múltiples hilos sobre una CPU se basa en prioridades, de forma que se ejecuta en cada instante el hilo con prioridad más alta (si tuviesen la misma prioridad se selecciona de forma arbitraria). Los **hilos heredan la prioridad del hilo que los crea**, y los hilos de prioridad baja sólo se podrán ejecutar cuando todos los hilos de prioridad superior pasen al estado “No ejecutable”. 

**Interfaz Runnable**

En el caso de que queramos hacer concurrentes objetos heredados de otra clase que no sea Thread (p.e un Objeto Círculo que hereda de la clase Figura), nos encontramos con un problema y es que no podemos hacer que también herede de Thread. Ya que Java admite heredar solo de 1 clase pero implementar múltiples interfaces; es por eso que en tales casos se deberá de utilizar la **interfaz Runnable**. El funcionamiento es muy similar, aunque con ciertas diferencias: 

- La interfaz no se hereda, se implementa. 
- Al igual que con Thread, la clase que implemente la interfaz Runnable también deberá implementar el método *run()*. 
- El lanzamiento de una tarea no se puede hacer directamente con start() porque el objeto creado no será un hilo, sino que deberá de crearse un hilo de ejecución con Thread al que se pasará el objeto que implementa la interfaz Runnable y ya posteriormente usar el método start. 

P.e 

`	`**class Circulo extends Figura implement Runnable {...}** 

`	`**Circulo c = new Circulo();**

`	`**Thread elHilo = new Thread(c);** 

`	`**elHilo.start();** 

Como vemos el mecanismo es más indirecto que heredar de Thread, pero evita el problema de la herencia múltiple. 

**Sincronización de hilos**

La sincronización se basa en el concepto **monitor** (no es un hilo, sino un objeto “normal” al que pueden acceder varios Thread), aunque no existe ese tipo de datos como predefinido (no hace falta ya que Java asocia un monitor a todos los objetos). 

Java trata de manera automática el problema de la exclusividad de acceso a un objeto mediante la definición de método (o bloques) ***synchronized***. De forma que el programador debe preocuparse de tratar la sincronización de tipo **Cooperación**, que se realiza mediante las operaciones ***wait()/notify()***.

El **monitor** permite hacer un objeto de acceso seguro que asegura el uso excluyente del objeto, es decir que en cada instante sólo una tarea está haciendo uso de él, para ello (que un método se considere monitor) dicho método público debe definirse como ***synchronized***.  Dentro de dicho método se utilizarán los métodos: 

- ***wait() →*** el hilo actual se espera hasta que otro hilo envíe una notificación (notify) al mismo objeto. Es probable que wait lance Excepción, por lo que se recomienda hacer catch de *InterruptedException***.** 
- ***notify() →*** activa un hilo que está esperando en el monitor del objeto. 
- ***notifyAll()*** → activa todos los hilos que están esperando en el monitor del objeto, por lo que los hilos “compiten” por el objeto y sólo uno obtiene el bloqueo. 

-----

**MODELO TRES CAPAS**

La arquitectura de tres capas es un diseño que añade un nivel intermedio en el proceso. Las **capas** son independientes que se ejecutan en una plataforma diferentes 

En las arquitecturas **tradicionales** de tres capas,se instala la interfaz de usuario en el ordenador del usuario final (cliente), mientras que la arquitectura **basada en web** transforma la interfaz de búsqueda (navegador web) en una interfaz de usuario final. 

![](Aspose.Words.ce493cb2-47e8-494b-b1ec-dbd7691ec639.024.png)

- **Primera capa [cliente de la app, navegador web] →** nivel de **presentación**, que incluye no solo el navegador, sino también el servidor web responsable de presentar los datos en un formato adecuado (formato en el que lo ve el cliente). Corresponde a la capa **vista** del MVC que define los elementos destinados a representar la información y a interactuar con el usuario, abarcando el código de la app encargado de reproducir la visualización de las interfaces de usuarios, es decir código encargado de renderizar los estado de nuestra app en HTML. 

Es por tanto, la representación del modelo, es decir los datos y la lógica del negocio, de una manera adecuada para que el cliente pueda interactuar. Así pues, la vista demanda la información al modelo por medio del controlador, ya que la vista trabaja con los datos pero no tiene un acceso directo a éstos. 

- **Segunda capa [servidores de apps, *Apache, Tomcat, servlets*] →** generalmente se refiere a algún tipo de programa o script. Se corresponde con la capa **controlador** de MVC, definiendo los procedimientos para tratar tanto las información y transformar la petición y respuestas del servidor, pues contiene el código necesario para responder a las acciones que se solicitan en la aplicación. No obstante, no se encarga de manipular directamente datos (lo hace el modelo), ni mostrar ningún tipo de salida (lo hace la vista), sino de servir de enlace/intermediario entre los modelos y vistas. 

También se encarga de enviar órdenes a la visa si se reciben peticiones en la manera de mostrar el modelo (la información). 

- **Tercera capa [servidores de datos *bases de datos, servidores SMTP, etc*] →** proporciona a la segunda los datos que necesita para ejecutarse. Corresponde a la capa **modelo** del MVC, trabaja con la recuperación y almacenamiento propiamente de los datos, pues es la capa en la que se trabaja con los datos, por lo que define mecanismos para acceder a la información y actualizar su estado, a través de funciones que accederán a las tablas de la base de datos. 

Administra todas las peticiones de información, incluyendo consultas y modificaciones; y define los privilegios de acceso que requerirá la lógica de negocio. Envía a la vista a través del controlador, la información solicitada para que pueda ser mostrada al cliente. 

**Ventajas** 

- Las llamadas desde la interfaz de usuario al servidor del nivel medio (controlador) son más flexibles que el diseño de dos niveles porque solo se necesita pasar parámetros al nivel medio. 
- La interfaz no necesita comprender o comunicarse con el destinatario de los datos (modelo), por lo que la estructura de datos se puede modificar sin cambiar la interfaz de usuario en el PC. 
- Si se diseña en un formato modular (como hacemos en Django con Python) , varias aplicaciones pueden reutilizar el código de nivel medio (pues se encuentra separado). Por eso mismo, los roles se pueden dividir en tres capas y una capa se puede reemplazar o modificar fácilmente sin afectar al resto de los módulos. 
- Se decide qué parte lógica de la aplicación procedemos a encapsular en cada uno de nuestros componentes de la misma manera que encapsulamos los componentes en varios niveles. Por lo que permite construir componentes físicos a través de los niveles lógicos. 

**Desventajas**

- Implican un aumento en el tráfico de red y requiere más equilibrio de carga o tolerancia a fallos.
- Los navegadores actuales no son todos iguales y es algo a tener en cuenta. 

-----

**PROTOCOLO HTTP (Hypertext Transfer Protocol)**

Concepto desarrollado por Tim Berners-Lee (CERN, Suiza) que constituye la base de la World Wide Web, así como **HMTL (**lenguaje de marcado de hipertexto que define la estructura de la página web**)** y **URI (**deriva en un **URL**, Uniform Resource Locator que define la ubicación de un recurso, como una página web en Internet**). HTTP** es el código o lenguaje en el que el navegador se comunica con el servidor para indicar la página que quiere ver, y a su vez especifica cómo el servidor envía el recurso al cliente. 

Procedimiento: 

1. El usuario en la barra de direcciones del navegador (cliente) indica la URL. 
1. El navegador envía una solicitud HTTP al servidor web que administra el dominio indicado en la URL. 
1. El servidor web recibe la solicitud HTTP, busca el recurso y envía una cabecera que indica a través de un código de estado los resultados de la búsqueda., así como el recurso en caso de que el cliente no solo haya preguntado por su existencia sino que haya solicitado recibirlo (p.e HTML si se trata de una página web). 
1. El navegador recibe el archivo y lo abre como una página web. 

**Métodos,** permiten identificar la acción que queremos realizar sobre un determinado recurso y utilizar REST**:** 

- **GET →** método que no cambia el estado del recurso, sino que busca obtener información del mismo (pudiendo obtenerla de una caché). Es **idempotente**, ya que puedo solicitar dicha información 20 veces o una vez que siempre voy a tener el mismo resultado; además es **seguro** porque no conlleva la modificación del recurso solicitado. (no lleva cuerpo).

- **POST →** solicita información y se diferencia del GET porque lleva cuerpo y permite llevar información en él, ya que se suele usar para crear un nuevo recurso conociendo la URL de un constructor de recursos, es decir la URL a la que se hace la petición permite la creación de recursos; así pues cambia el estado. **No es** **idempotente,** ya que a diferencia de lo que ocurre con PUT, si se produjese un fallo de timeout (se ha superado el tiempo de espera de respuesta a la petición) y por ende el usuario no supiese si fue creado o no el recurso y repitiera la petición reiteradamente, habría un problema y es que se podrían obtener muchas creaciones de un mismo recurso. Además **no es seguro.** (lleva cuerpo). 

- **PUT →** se enfoca en editar valores del servidor, pues permite actualizar o crear un recurso conocida su URL, así pues cambia el estado del recurso, siendo el cuerpo de la petición donde irá la representación completa del recurso. Es **idempotente** ya que en el caso en que se produjese un fallo de timeout (se supera el tiempo de espera de respuesta a la petición) y el usuario repitiese la petición reiteradamente porque no sabe si fue creado o actualizado el recurso, no habría ningún problema, ya que en el caso de haber creado un recurso, una nueva petición PUT no crearía otro recurso más sino que lo actualiza sin verse afectado el resultado. Además, **no es seguro.** 



- **DELETE →** método que borra un recurso conocida su URL. Es **idempotente,** ya que una vez borrado un elemento si lo borro muchas más veces el resultado es el mismo desde la primera vez que lo hago que es borrarlo; y además **no es seguro** ya que modifica el recurso al borrarlo. 

-----

**ARQUITECTURA JAVA EE**

La plataforma Java EE es un conjunto de especificaciones de API que le permiten crear aplicaciones web. Java EE proporciona un **perfil web** y un **modelo de aplicación estandarizado**, lo que permite la definición de una arquitectura para implementar aplicaciones de varios niveles. En una **aplicación multinivel**, la funcionalidad de la aplicación se divide en varias áreas denominadas **niveles:** 

- **Nivel de cliente →** es el más alto de la arquitectura Java EE, y es el punto en el que los clientes de la aplicación pueden realizar peticiones a un servidor Java EE, normalmente ubicado en otra máquina, en otra zona a pocos kilómetros del servidor Java EE. Asimismo, cuando un cliente envía una solicitud a un servidor, el servidor la recibe, la procesa y devuelve una respuesta basada en la solicitud. 

- **Nivel web →** nivel encargado de gestionar la interacción entre el nivel de cliente y el nivel posterior (**nivel de negocio**). El funcionamiento de este nivel se compone de los siguientes pasos: 

- Recolectar datos ingresados por los clientes. 
- Administrar el flujo de páginas de clientes (y navegación). 
- La información y el estado de los datos de la sesión son mantenidos por el cliente. 
- Obtener resultados de la capa de negocio a partir de los componentes. 
- Presentar al cliente los datos obtenidos de la capa de negocio. 

Si una aplicación web utiliza componentes y servicios Java EE se puede definir en el nivel web de la aplicación como una **aplicación empresarial de tipo Java EE.** 

El **contenedor web (navegador)** es el responsable de implementar todas las especificaciones de la API, además de proporcionar servicios para la gestión y ejecución de componentes web como servlets, JSP, filtros, oyentes, etc. 

**Estructura de una aplicación web Java EE**

Una aplicación web J2EE que utiliza servlets o páginas JSP debe tener una **estructura de archivos y directorios** específica: 

- **Páginas HTML o JSP** se colocan en el **directorio raíz** de la aplicación (también podemos utilizar subdirectorios según sea necesario). 
- **Colgando del directorio principal** de la aplicación hay un directorio **WEB-INF** que contiene información web relacionada con la aplicación. Esta información se divide en: 

- Un **fichero descriptor** de despliegue de la aplicación, se trata de un archivo XML (llamado **web.xml**) que contiene información general sobre la aplicación. 
- **Subdirectorio *classes*** que contiene todas las **clases de Java** (Archivos **.class**) utilizadas en la aplicación, es decir clases fuera de la API de Java para páginas JSP, servlets, etc. Las clases deben mantener la estructura del paquete, es decir si pusieramos la clase paquete1.subpaquete1.Miclase dentro de una clase, quedaría almacenada en el directorio classes/paquete1/subpaquete1/MiClase. 
- **Subdirectorio lib** donde colocaremos las clases de Java empaquetadas en el **archivo JAR**, es decir colocaremos el archivos JAR para nuestra app web y las bibliotecas JSP o servlet requeridas). 
- El resto de **elementos de la app** (imágenes, etc), los podemos estructurar como mejor nos parezca. 

-----

<a name="_na9xy8wfbmgf"></a>**EXTRAS**

**> dynamic →** tipo de datos que permite al compilador diferir la verificación de tipo hasta el tiempo de ejecución en lugar del tiempo de compilación. Esto significa que el tipo se determina en tiempo de ejecución en lugar de estar explícitamente definido en el código fuente. 

Así pues, este tipo de datos permite trabajar con objetos sin conocer su tipo exacto de antemano. Puede acceder a sus propiedades y métodos como si fueran miembros de un objeto estático, y el compilador no verifica el tipo hasta que se ejecuta el programa, es decir no nos salta ese error que no deja compilar. 

Su uso puede ser útil en situaciones en la que no se sabe exactamente el tipo de objeto que se recibirá en tiempo de ejecución (como la comunicación con servidores web, BBDD o sistemas externos). No obstante su uso excesivo puede hacer el código difícil de leer y mantener, por lo que debe usarse con moderación. 

