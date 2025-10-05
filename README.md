<div align="center">
<h1>Tarea 7</h1>
  <p>
    Ingeniería Electrónica · Universidad Santo Tomás
    <br>
    <b>Didier Posse</b>
    <br>
    <em>Primer punto</em>
  </p>
</div>

<hr>

<div align="center">
  <h2>Diferencia en algunos comandos de Ubuntu</h2>
</div>

<h2><code>htop</code></h2>
<div align="center">
  <p><img width=850 src="https://github.com/user-attachments/assets/b04a9229-4d06-4e9a-bda4-548e0e87078d"/></p>
</div>

<p>
El comando <code>htop</code> se utiliza para <b>monitorear en tiempo real</b> el uso de los recursos del sistema.  
En la parte superior muestra el <b>uso de los núcleos del CPU</b>, indicando el porcentaje de actividad de cada uno.  
Debajo de esto se encuentra el <b>uso de la memoria RAM</b> y de la <b>memoria SWAP</b>, expresado en gigabytes.  
Más abajo aparece una lista con los <b>procesos en ejecución</b>, mostrando información como el consumo de CPU, el uso de memoria, el tiempo que llevan corriendo, entre otros detalles.  
Finalmente, en la parte inferior, se incluyen <b>opciones para gestionar los procesos</b>, como finalizar tareas, filtrar, buscar procesos o cambiar su prioridad.  
</p>

<p>
En resumen, <code>htop</code> es una <b>versión más visual e interactiva</b> del clásico comando <code>top</code>, ideal para analizar el rendimiento del sistema de forma clara y dinámica.
</p>

<h2><code>glances</code></h2>
<div align="center">
  <p><img width=850 src="https://github.com/user-attachments/assets/89172a53-c318-4656-9180-99bbc0b983bf"/></p>
</div>

<p>
El comando <code>glances</code> se utiliza para <b>monitorear el uso de los recursos del sistema</b>, pero de una forma <b>más completa y detallada</b> que <code>htop</code>. 
Muestra información sobre el <b>uso del CPU</b>, la <b>memoria RAM</b>, la <b>memoria SWAP</b> y también incluye datos más específicos, como el <b>rendimiento de la GPU</b> y el <b>load average</b> del sistema. 
Toda esta información se presenta de forma ordenada y precisa, lo que permite tener una visión general más técnica del estado del equipo.
</p>

<p>
En la parte inferior, <code>glances</code> muestra los <b>procesos en ejecución</b> de manera organizada, distribuyéndolos mejor y mostrando sus valores con <b>unidades reales</b> (como MB o KB) en lugar de porcentajes. 
En resumen, <code>glances</code> ofrece una <b>visión más detallada y completa</b> del sistema, mientras que <code>htop</code> se enfoca en una <b>representación más visual e interactiva</b> de los recursos.
</p>

<h2><code>ifconfig</code></h2>
<div align="center">
  <p><img width=850 src="https://github.com/user-attachments/assets/a5c658a7-692b-4d39-9599-dcc4f60d8db3"/></p>
</div>

<p>
El comando <code>ifconfig</code> se utiliza para <b>visualizar y gestionar la configuración de red</b> del sistema. 
Permite ver las <b>direcciones IP</b> del dispositivo, tanto <b>públicas como privadas</b>, además de mostrar información de <b>IPv4</b> e <b>IPv6</b>. 
A diferencia de <code>htop</code> y <code>glances</code>, que monitorean recursos y procesos del sistema, este comando se enfoca en el <b>estado de la red</b>, mostrando detalles sobre la <b>conectividad</b> y el <b>tráfico</b> de las interfaces.
</p>

<p>
También es posible ver información como el nombre de cada interfaz, la cantidad de paquetes enviados o recibidos y posibles errores de transmisión. 
El comando <code>ifconfig</code> es una herramienta clásica de red, aunque actualmente ha sido reemplazada en muchos sistemas modernos por los comandos <code>ip a</code> o <code>ip addr</code>, que ofrecen una forma más actualizada y completa de monitorear las interfaces de red.
</p>

<h2><code>nmap</code></h2>
<div align="center">
  <p><img width=850 src="https://github.com/user-attachments/assets/7b5ec7f2-c0aa-406f-903f-08c5a602f8d6"/></p>
</div>

<p>
El comando <code>nmap</code> es una herramienta muy completa que se utiliza para <b>explorar redes, detectar equipos y analizar puertos</b>. 
A diferencia de los demás comandos, <code>nmap</code> cuenta con <b>múltiples opciones y parámetros</b> que permiten realizar búsquedas más específicas según lo que se quiera analizar. 
Un uso común es <code>nmap &lt;ip&gt;</code>, el cual muestra los <b>dispositivos activos</b> en la red a la que se está conectado.
</p>

<p>
Este comando es muy utilizado en el campo de la <b>ciberseguridad</b>, ya que permite identificar <b>puertos abiertos o cerrados</b>, así como conocer los servicios que se están ejecutando en cada dispositivo. 
A diferencia de <code>ifconfig</code>, que solo muestra la configuración de red del propio equipo, <code>nmap</code> permite <b>visualizar todos los dispositivos conectados</b> a la red, ofreciendo una visión mucho más completa del entorno.
</p>

<h2><code>lshw</code></h2>
<div align="center">
  <p><img width=850 src="https://github.com/user-attachments/assets/3b553bd8-293a-46be-9a18-fb9232e19981"/></p>
</div>

<p>
El comando <code>lshw</code> se utiliza para <b>mostrar información detallada del hardware</b> del sistema. 
Ofrece un resumen muy completo que incluye datos como el <b>fabricante</b>, las <b>características técnicas</b>, los <b>identificadores</b> y el <b>nombre completo</b> de cada componente detectado por el equipo. 
Esta herramienta resulta muy útil para conocer a fondo la estructura física y las especificaciones del hardware instalado.
</p>

<p>
A diferencia de <code>htop</code> y <code>glances</code>, que se enfocan en el <b>uso de los recursos</b> en tiempo real, 
<code>lshw</code> se centra en las <b>características físicas y técnicas</b> del hardware. 
En pocas palabras, mientras los otros comandos muestran cómo se está usando el hardware, <code>lshw</code> muestra exactamente <b>qué hardware tiene tu equipo</b>.
</p>

<hr>

<div align="center">
  <p>
    <em>Segundo Punto</em>
  </p>
</div>

<hr>

<h2><b>IPv4</b></h2>
<p>
El <b>IPv4</b> (Internet Protocol version 4) es un protocolo utilizado para <b>asignar direcciones únicas a los dispositivos electrónicos</b> dentro de una red o subred. 
Estas direcciones permiten <b>identificar cada dispositivo</b> para que pueda <b>enviar y recibir información</b> correctamente a través de la red.  
</p>

<p>
El formato de <b>IPv4</b> está compuesto por <b>32 bits</b> divididos en <b>4 secciones de 8 bits</b> cada una, separadas por puntos. 
El formato más común es: <code>192.168.x.x</code>, y el rango posible va desde <code>0.0.0.0</code> hasta <code>255.255.255.255</code>.  
Este tipo de direcciones es el <b>más utilizado en la mayoría de las redes</b>, aunque actualmente está siendo reemplazado de forma gradual por <b>IPv6</b> debido a la limitación en la cantidad de direcciones disponibles.
</p>


<h2>IPv6</h2>
<p>
El IPv6 (Internet Protocol version 6), 
</p>
