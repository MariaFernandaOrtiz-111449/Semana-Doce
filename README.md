# Apuntes_Semana Doce
Apuntes control de movimiento - Tercer Corte - Doceava Semana

Tomás Santiago Sánchez Barrera & María Fernanda Ortíz Velandia & Andrés Felipe Arteaga Escalante

# Indice

1. [Control de Movimiento (Diseño de Transmisión)](#Control-de-Movimiento(Diseño-de-Transmisión))

    1.1. [Conceptos de Transmisión](#Conceptos-de-Transmisión)

2. [Sistema Polea-Correa](#Sistema-Polea-Correa)

    2.1. [Relación de Transmisión](#Relación-de-Transmisión)

    2.2. [Inercia Reflejada](#Inercia-Reflejada)

    2.3 [Torque de Carga](#Torque-de-Carga)

3. [Tornillo Guía](#Tornillo-Guia)

    3.1. [Tornillo Guía Acme](#Tornillo-Guia-Acme)

    3.2. [Tornillo Guía de esfera](#Tornillo-guia-de-esfera)

    3.3. [Relación de Transmisión](#Relacion-de-Transmision)

    3.4. [Inercia Reflejada](#Inercia-Reflejada)

    3.5. [Inercia Reflejada Total](#Inercia-Reflejada-Total)

    3.6. [Torque de Carga](#Torque-de-Carga)

4. [Piñon Cremallera](#Piñon-Cremallera)

    4.1. [Relación de Transmisión](#Relacion-de-Transmision)

    4.2. [Inercia Reflejada](#Inercia-Reflejada)

    4.3. [Torque de Carga](#Torque-de-Carga)

5. [Banda Transportadora](#Banda-Transportadora)

    5.1. [Inercia Reflejada](#Inercia-Reflejada)

    5.2. [Torque de carga](#Torque-de-Carga)

    5.3. [Relación de Transmisión](#Relacion-de-Transmision)

6. [Conclusiones](#Conclusiones)

7. [Ejemplos](#Ejemplos)

8. [Referencias](#Referencias)

# 1. Control de Movimiento (Diseño de Transmisión) <a id="Control-de-Movimiento(Diseño-de-Transmisión)"></a>

## 1.1. Conceptos de Transmisión <a id="Conceptos-de-Transmisión"></a>

El diseño de transmisión mecánica es una disciplina fundamental dentro de la ingeniería, encargada de transferir potencia y movimiento entre distintos componentes de un sistema, utilizando elementos como engranajes, correas, cadenas, piñones, tornillos o bandas. Su objetivo principal es garantizar eficiencia, durabilidad y seguridad en aplicaciones como vehículos, maquinaria industrial, automatización y robótica. Un diseño adecuado no solo optimiza el rendimiento, sino que también reduce el desgaste, minimiza pérdidas de energía y mejora la eficiencia global del sistema. Para lograrlo, combina conocimientos de cinemática, dinámica y resistencia de materiales.

Uno de los sistemas más utilizados es el sistema polea-correa, que permite transmitir movimiento rotacional entre ejes separados mediante una correa flexible. Es común en ventiladores, alternadores y máquinas agrícolas, gracias a su simplicidad, bajo costo y capacidad de amortiguar vibraciones. Para su diseño se debe considerar el tipo de correa (plana, en V o dentada), la alineación precisa entre poleas y la tensión correcta para evitar deslizamientos o desgastes prematuros.

Por otro lado, el sistema tornillo-guía convierte el movimiento rotacional en desplazamiento lineal, siendo esencial en equipos como tornos, fresadoras, impresoras 3D o prensas. Su ventaja radica en la precisión y la capacidad de soportar grandes cargas axiales. El diseño adecuado implica elegir el paso del tornillo según la resolución deseada, prever la fricción del sistema, y aplicar una buena lubricación para garantizar eficiencia y durabilidad.

El piñón-cremallera es un mecanismo que transforma movimiento rotacional en lineal mediante el acoplamiento de un engranaje (piñón) con una barra dentada (cremallera). Se emplea en sistemas de dirección de vehículos, puertas automáticas y elevadores, ofreciendo una transmisión directa, robusta y sin deslizamientos. Su diseño requiere materiales resistentes al desgaste, un análisis de las fuerzas radiales y una correcta lubricación entre dientes.

Finalmente, la banda transportadora es un sistema continuo usado para trasladar materiales de un punto a otro en procesos industriales, logísticos o agrícolas. Está compuesta por una banda que se mueve sobre rodillos impulsados por un motor. Sus ventajas incluyen la automatización del transporte, la reducción del esfuerzo humano y la adaptabilidad a diferentes tipos de carga. Un diseño eficaz debe considerar el tipo de banda (PVC, goma, metálica), el peso del material a transportar, la velocidad requerida y la potencia del motor.

En conjunto, estos sistemas de transmisión pueden integrarse en un solo dispositivo o línea de producción, como en el caso de un robot industrial que utiliza bandas para mover piezas, piñón-cremallera para desplazar su brazo, un tornillo-guía para regular la altura de sus herramientas y correas para transmitir la fuerza de sus motores. Cada sistema aporta características únicas que, combinadas correctamente, permiten crear soluciones mecánicas eficientes, confiables y adaptadas a diversas aplicaciones.

💡 Ejemplo 1: Transmisión Mecánica

* Situación:
Una banda transportadora en una fábrica comienza a moverse más lento de lo normal.

* Posible causa:
La correa de transmisión está floja o desgastada.

* Solución:
Ajustar la tensión de la correa o reemplazarla. También revisar las poleas y lubricar si es necesario.

![Gemini_Generated_Image_5jpm8v5jpm8v5jpm](https://github.com/user-attachments/assets/5a124f0e-a2a3-4ba2-b4a7-a3982123e301)

*Imagen 1. Transmisión Mecánica*

💡 Ejemplo 2: Transmisión eléctrica

* Situación:
En una zona rural, las bombillas parpadean y se observa baja tensión en los electrodomésticos.

* Posible causa:
Caída de voltaje por mala transmisión eléctrica o cableado muy largo sin compensación.

* Solución:
Instalar un transformador reductor en un punto intermedio o usar cables de sección mayor para disminuir la resistencia.

![image](https://github.com/user-attachments/assets/c246e9e1-53c4-4bd2-910b-7e247fdf552e)

*Imagen 2. Transmisión eléctrica*

## 2. Sistema Polea - Correa <a id="Sistema-Polea-Correa"></a>

El sistema de transmisión polea-correa es uno de los métodos más utilizados para transferir movimiento y potencia entre ejes separados en sistemas mecánicos. Este mecanismo se basa en el uso de una o más poleas conectadas entre sí mediante una correa flexible que permite transmitir fuerza desde un eje motriz (activo) hacia uno o varios ejes conducidos (pasivos). Su popularidad se debe a su simplicidad de diseño, bajo costo, funcionamiento silencioso y capacidad de absorber vibraciones. Además, permite trabajar con distancias variables entre ejes, lo que lo hace ideal para aplicaciones en maquinaria agrícola, ventiladores, electrodomésticos y sistemas automotrices. La selección adecuada del tipo de correa (plana, trapezoidal o dentada), junto con una correcta tensión y alineación del sistema, es esencial para garantizar una transmisión eficiente, segura y duradera.

![Gemini_Generated_Image_emfzademfzademfz](https://github.com/user-attachments/assets/c2171736-4ba7-4bcd-96df-ef4280f1c3d9)

*Imagen 3. Sistema de Transmisión Polea-Correa*

### 2.1. Relación de Transmisión <a id="Relación-de-Transmisión"></a>

La relación de transmisión en un sistema polea-correa indica cuántas veces gira una polea en comparación con otra. Es fundamental para controlar la velocidad y el par (torque) que se transmite entre los ejes. Esta relación se determina por el diámetro o número de dientes (en caso de correas dentadas) de las poleas involucradas.

$V_{Tangencial} = W_{ip}R_{ip} = W_{lp}R_{lp}$

La fórmula básica es:

$$Relación de Transmisión (i) = \frac{D_{conducida}}{D_{motora}}$$

La relación de transmisión también se puede expresar como:

$$\frac{N_{motora}}{N_{conducida}} = \frac{D_{conducida}}{D_{motora}}$$

💡 Ejemplo 3: Aumento de velocidad

* Si la motora mide 150 mm y la conducida 75 mm:

$$i = \frac{75}{150} = 0.5$$

La polea conducida gira 2 veces por cada vuelta de la motora. La velocidad aumenta y el torque disminuye.

![image](https://github.com/user-attachments/assets/e4a0c347-32e7-4774-82d8-aa6abe60def1)

*Imagen 4.Aumento de Velocidad*

💡 Ejemplo 4: Reducción de velocidad

* Si la polea motora tiene 100 mm y la conducida tiene 200 mm:

$$i = \frac{200}{100} = 2$$

La polea conducida gira 1 vez por cada 2 vueltas de la motora. La velocidad disminuye y el torque aumenta.

![image](https://github.com/user-attachments/assets/3a740adf-5174-462b-b687-56e3de8b87ad)

*Imagen 5. Reducción de Velocidad*

### 2.2. Inercia reflejada <a id="Inercia-Reflejada"></a>

La inercia reflejada (o inercia equivalente reflejada al motor) es la resistencia al cambio de movimiento angular que experimenta el motor debido a la inercia de las cargas conectadas a través de un sistema de transmisión. En otras palabras, es la forma en que la inercia de la carga se “ve” desde el lado del motor, ajustada por la relación de transmisión del sistema.

Este concepto es fundamental al diseñar sistemas de control de movimiento (como servomotores o motores paso a paso), porque una inercia reflejada mal calculada puede provocar sobrecarga del motor, respuestas lentas o inestabilidad.

Mediante la siguiente fórmula se halla la inercia reflejada:

$J_{trans ref} = J_{IP} + J_{belt -> in} + J_{LP -> in} + J_{load -> in} + J_{C2 -> in}$

Aplicando la relación de los ejes obtenemos la siguiente fórmula:

$J_{trans ref} = J_{IP} + \frac{W_{belt}}{g\eta}r_{ip}^{2} + \frac{L}{\eta*N_{BP}^{2}}(J_{LP} + J_{load} + J_{C2})$

La correa se modela como una masa rotatoria, cuya inercia es $J = mr^{2}$.
Sustituyendo $W_{belt} = mg$ y $r = r_{ip}$ nos da como resultado $J_{belt ->in} = \frac{W_{belt}}{g*\eta}r_{ip}^{2}$

![image](https://github.com/user-attachments/assets/9e616b58-0938-4e76-8807-9fa2c65e6e0e)

*Imagen 6. Inercia Reflejada*

💡 Ejemplo 5: Cálculo de Inercia Reflejada en un Sistema Polea-Correa

* Situación:

Un motor está conectado a una polea de diámetro 100 mm, que transmite movimiento mediante una correa a otra polea de diámetro 300 mm, acoplada a una carga rotativa con una inercia de 1.2 kg·m². Queremos calcular la inercia reflejada al eje del motor.

**Paso 1: Calcular la relación de transmisión**

Usamos la fórmula de relación de transmisión basada en los diámetros:

$$i=\frac{D_{conducida}}{D_{motora}} = \frac{300}{100} = 3$$

**Paso 2: Calcular la inercia reflejada**

Aplicamos la fórmula:

$$J_{r} = \frac{J_{c}}{i^{2}} = \frac{1.2}{3^{2}} = 0.133 kgm^{2}$$

Desde el punto de vista del motor, la carga rotativa se siente como si tuviera una inercia de 0.133 kg·m², lo cual es mucho más fácil de mover y controlar que la inercia real de 1.2 kg·m².

### 2.3. Torque de Carga <a id="Torque-de-Carga"></a>

El torque de carga (también llamado par de carga) es el momento de fuerza que una carga aplica en contra del movimiento generado por un motor o actuador. Es la resistencia que el sistema debe vencer para mantener el movimiento o iniciarlo.

Este torque puede venir de:

* Fricción
* Gravedad (en sistemas verticales)
* Inercia (durante aceleración)
* Cargas externas (como peso de un brazo robótico, fajas transportadoras con carga, etc.)

![image](https://github.com/user-attachments/assets/61dcb8c9-d14c-482a-9c0f-39a12394a7df)

*Imagen 7. Torque de carga*

💡 Ejemplo 6: Torque de carga en una Banda Transportadora

Tenemos una banda transportadora horizontal impulsada por un rodillo de radio 0.1 m, que transporta cajas con un peso total de 80 kg. La banda se mueve a velocidad constante, y se estima una fricción total (banda + rodillos) equivalente a 5% del peso total.

Queremos calcular el torque de carga que el motor debe entregar al eje del rodillo para mover la banda.

**Paso 1: Calcular la fuerza de fricción**

Primero, obtenemos la fuerza de fricción, que es la única oposición en este caso (no hay aceleración ni pendiente):

$$F_{fricción} = 0.05(mg) = 0.05(80*9.81) = 39.24 N$$

**Paso 2: Calcular el torque de carga**

$$T_{C} = Fr = 39.24 * 0.1 = 3.924 N$$

El torque de carga necesario es 3.92 Nm.
Este es el mínimo torque que el motor debe proporcionar (sin contar pérdidas mecánicas adicionales o inercia de arranque).

## 3. Tornillo guía <a id="Tornillo-Guia"></a>

El tornillo guía, también conocido como husillo de avance o husillo de bolas (cuando tiene rodamientos internos), es un mecanismo utilizado para convertir el movimiento rotacional en movimiento lineal, con alta precisión y control.

Es muy común en sistemas como:

* Máquinas CNC
* Impresoras 3D
* Robots cartesianos
* Actuadores lineales

Este sistema está compuesto por un tornillo roscado y una tuerca móvil. Cuando el tornillo gira, la tuerca se desplaza linealmente a lo largo de él (o viceversa, dependiendo del montaje).

![image](https://github.com/user-attachments/assets/b5ab5811-ce14-497b-8364-444f270c2cc6)

*Imagen 8. Tornillo guía*

💡 Ejemplo 7:

Una impresora 3D tipo cartesiana utiliza un tornillo guía en el eje Z (el eje vertical que sube y baja el extrusor o la cama). Durante la impresión, se nota que la boquilla no sube uniformemente al cambiar de capa, lo que provoca que algunas capas se aplasten y otras queden desalineadas.

**Posible causa**

* Acumulación de polvo o residuos plásticos en el tornillo guía que generan fricción.
* Falta de lubricación, lo que impide un movimiento suave.
* Tuerca floja o desgastada, lo que causa holgura y movimientos imprecisos.
* Tornillo guía doblado o mal alineado con los soportes.

**Solución**

* Limpieza completa del tornillo con un paño seco o cepillo suave.
* Aplicar lubricante específico (por ejemplo, grasa ligera o aceite para husillos).
* Verificar el ajuste de la tuerca, reapretar si es necesario o reemplazar si tiene juego.
* Revisar que el tornillo no esté doblado o desalineado; si lo está, se debe reemplazar y realinear el montaje.

### 3.1. Tornillo guía ACME <a id="Tornillo-Guia-Acme"></a>

El tornillo guía ACME es un tipo de tornillo de potencia diseñado para convertir movimiento rotativo en movimiento lineal, utilizado comúnmente en maquinaria, tornos, prensas, impresoras 3D y sistemas de elevación.

Se caracteriza por tener una rosca trapezoidal, con un ángulo de 29° en sus flancos, lo cual lo hace más robusto y resistente al desgaste que una rosca común (como la métrica o la de tornillos de fijación).

![image](https://github.com/user-attachments/assets/3f6c96b3-d70f-4e12-8b0d-8c9944486b47)

*Imagen 9. Tornillo Guía Acme*

### 3.2. Tornillo guía de esfera <a id="Tornillo-guia-de-esfera"></a>

El tornillo guía de esferas es un mecanismo de transmisión lineal de alta precisión que convierte el movimiento rotativo en lineal, al igual que el tornillo ACME, pero con una eficiencia mucho mayor gracias al uso de bolas recirculantes entre el tornillo y la tuerca.

Estas esferas giran en canales especialmente diseñados, lo que reduce drásticamente la fricción y permite movimientos más suaves, rápidos y precisos.

![image](https://github.com/user-attachments/assets/99069899-78f6-42bd-9f43-c06bd3055616)

*Imagen 10. Tornillo guía de esferas*
 
### 3.3. Relación de Transmisión <a id="Relacion-de-Transmision"></a>

La relación de transmisión en un tornillo guía es un concepto fundamental que describe cómo se convierte el movimiento rotacional en movimiento lineal. Esta relación indica cuánta distancia recorre linealmente una tuerca por cada vuelta completa del tornillo.

Este desplazamiento lineal depende directamente del paso del tornillo, que se define como la distancia que avanza la tuerca por cada revolución del tornillo. Por lo tanto, la relación de transmisión puede expresarse como:

$$Relación de transmisión = \frac{1}{paso del tornillo (mm/rev)}$$

![image](https://github.com/user-attachments/assets/c3c21725-a722-4cc2-b88e-2a61f37e78c3)

*Imagen 11. Relación de Transmisión Tornillo Guía*

💡 Ejemplo 8: 
Supón que tienes un tornillo con un paso de 5 mm. Eso quiere decir que por cada vuelta completa, la tuerca se mueve 5 mm en línea recta.

Entonces:

$$RT = \frac{1rev}{5mm} = 0.2 rev/mm$$

En los sistemas de transmisión mecánica mediante tornillos guía, es importante comprender dos conceptos clave: el cabeceo (pitch) y el paso (lead). Ambos están relacionados con la conversión del movimiento rotacional en movimiento lineal, pero representan medidas distintas.

🔹 Cabeceo (Pitch):
El cabeceo indica el número de vueltas que debe realizar el tornillo para que la cápsula o tuerca se desplace una distancia lineal de 1 metro (o 1 pulgada en el sistema inglés). Es una forma de expresar la relación inversa entre la rotación del tornillo y el avance lineal, y se utiliza frecuentemente para calcular relaciones de transmisión.

Por ejemplo, si el cabeceo es de 5 rev/m, significa que el tornillo debe girar 5 veces para que la tuerca avance 1 metro.

🔹 Paso (Lead):
El paso representa la distancia que recorre la cápsula por cada vuelta completa del tornillo, expresado en metros o pulgadas. Es decir, cuántos milímetros (o pulgadas) se mueve la tuerca por una revolución del tornillo.

Por ejemplo, si el paso es de 5 mm, entonces por cada vuelta del tornillo, la tuerca se desplazará 5 mm en línea recta.

A partir del entendimiento técnico surgen las formulas matemáticas como las siguientes: 

$\bigtriangleup \theta = 2\pi p \bigtriangleup X$

$\frac{\bigtriangleup \theta }{\bigtriangleup X} = 2\pi p$

$\frac{\frac{\bigtriangleup \theta }{\bigtriangleup t}}{\frac{\bigtriangleup X}{\bigtriangleup t}} = \frac{velocidad motor}{velocidad carga} = \frac{\theta ^{\cdot }}{x^{\cdot }} = 2\pi P$

![image](https://github.com/user-attachments/assets/c53f3ee1-89f0-456b-9d4c-f454b5685fbb)

*Imagen 12. Relación de Transmisión*

### 3.4. Inercia Reflejada <a id="Inercia-Reflejada"></a>

Es la inercia del sistema lineal (como una carga movida por un tornillo) que se “refleja” o se transfiere al eje rotacional del motor a través del tornillo guía. Esta conversión depende directamente de la relación de transmisión del tornillo, es decir, del paso o lead del tornillo.

![image](https://github.com/user-attachments/assets/1779bffb-c972-4499-9de1-3882b2c6fd5a)

*Imagen 13. Inercia Reflejada Tornillo Guía*

Sabiendo que la carga tiene un movimiento lineal, su energía cinética
sería:

$KE = \frac{1}{2} m{X^{\cdot }}^{2}$

A partir de la relación de transmisión $\frac{\theta ^{\cdot }}{X^{\cdot }} = 2\pi P$ se puede reemplazar

$KE = \frac{1}{2} m \frac{1}{(2\pi P)^{2}} {\theta ^{\cdot }}^{2}$

Ahora se tiene la energía cinética en términos de la velocidad angular,
por lo tanto el término que multiplica la velocidad es la inercia reflejada

$J_{ref} = m \frac{1}{(2\pi P)^{2}}$

$J_{ref} = \frac{m}{{N_{s}}^{2}}$

### 3.5. Inercia Reflejada Total <a id="Inercia-Reflejada-Total"></a>

En sistemas mecatrónicos donde un motor acciona una carga a través de elementos de transmisión (como tornillos guía, engranajes o correas), es fundamental analizar la inercia reflejada total. Esta representa la suma de todas las inercias que el motor “siente” en su eje, es decir, la resistencia que encuentra para acelerar o desacelerar el sistema completo.

A continuación se realizará un análisis matemático frente a las cargas sufridas por el sistema y la respuesta de la inercia del mismo.

$m = \frac{W_{L} + W_{c}}{g}$

$J_{trans ref} = J_{screw} + J_{load -> in} + J_{carriage -> in}$

$J_{trans ref} = J_{screw} + \frac{1}{\eta {N_{s}}^{2}} (\frac{W_{L} + W_{c}}{g})$

### 3.6. Torque de Carga <a id="Torque-de-Carga"></a>

El torque de carga (también conocido como torque resistivo) es el esfuerzo rotacional que el motor debe vencer para mover una carga en un sistema mecánico. Este torque representa todas las fuerzas que se oponen al movimiento del eje del motor debido a la presencia de masas, fricción, gravedad u otras resistencias externas.

![image](https://github.com/user-attachments/assets/afc17e42-2b51-4ecd-96b3-502eb033f06e)

*Imagen 14. Torque de carga*

A continuación se realizará un análisis matemático frente a las cargas sufridas por el sistema y la respuesta de la inercia del mismo.

$F_{ext} = F_{f} + F_{g} + F_{p}$

$F_{f} = \mu (W_{L} + W_{c}) cos\beta$

$F_{g} = (W_{L} + W_{c}) sin\beta$

$F_{ext} = F_{p} + (W_{L} + W_{c})(sin\beta + \mu cos\beta)$

Si está horizontal la fuerza gravitacional es 0

Para calcular el torque de la carga reflejado en el motor, se puede considerar el trabajo realizado por este:

$Work = F_{ext} \frac{1}{(2\pi P)} \bigtriangleup \theta$

$Work = F_{ext} \bigtriangleup X$

$Work = T_{load-> in} \bigtriangleup \theta$

$T_{load-> in} = \frac{F_{ext}}{N_{s}}$

$T_{load-> in} = \frac{F_{ext}}{\eta N_{s}}$

## 4. Piñon cremallera <a id="Piñon-Cremallera"></a>

El sistema piñón-cremallera es un mecanismo de transmisión de movimiento que convierte el movimiento rotatorio de un engranaje (piñón) en movimiento lineal a través de una barra dentada recta (cremallera). Este sistema es ampliamente utilizado en aplicaciones donde se requiere un desplazamiento lineal preciso y robusto, como en sistemas de dirección de vehículos, máquinas CNC, elevadores industriales y equipos automatizados.

Gracias a su diseño simple y directo, el piñón-cremallera ofrece una transmisión mecánica eficiente, con alta rigidez y sin deslizamientos, lo que lo convierte en una alternativa ideal frente a otros mecanismos lineales como husillos o actuadores eléctricos cuando se requiere velocidad y fuerza constantes.

Este tipo de transmisión permite una relación directa entre el giro del piñón y el desplazamiento de la cremallera, lo cual facilita el cálculo del movimiento y del esfuerzo necesario para accionar el sistema. Su mantenimiento relativamente sencillo y su capacidad para operar bajo condiciones exigentes hacen del piñón-cremallera una solución confiable en muchos sistemas industriales y de automatización.

![image](https://github.com/user-attachments/assets/6f4632ef-4ac8-426b-8470-c8fbba7c9cb3)

*Imagen 15. Piñon Cremallera*

💡 Ejemplo 9:
Tenemos un sistema piñón-cremallera utilizado en una máquina para desplazar un cabezal de corte. El piñón tiene un diámetro de paso de 100 mm y está acoplado a un motor que gira a 60 rpm.

Queremos calcular:

* ¿Cuánto se desplaza la cremallera en 1 minuto?

 Cada vuelta del piñón hace avanzar la cremallera una distancia igual al perímetro del piñón.

Si gira 60 veces por minuto:

$Desplazamiento total=60⋅314.16 mm=18849.56 mm=18.85 m$

* ¿Cuál es la velocidad lineal de la cremallera en mm/s?

$V = \frac{desplazamiento total}{tiempo} = \frac{18849.56 mm}{60 s} ≈314.16 mm/s$

### 4.1. Relación de Transmisión <a id="Relacion-de-Transmision"></a>

El sistema piñón-cremallera es un mecanismo ampliamente utilizado para convertir el movimiento rotacional de un engranaje (piñón) en un movimiento lineal de una barra dentada (cremallera). A diferencia de los sistemas de transmisión entre dos engranajes circulares, donde la relación de transmisión se expresa como una razón entre radios o número de dientes, en el sistema piñón-cremallera la relación se establece entre el ángulo de rotación del piñón y la distancia lineal recorrida por la cremallera.

Esta relación depende directamente del diámetro primitivo del piñón (o su paso circular), y se expresa típicamente como:

$$x=r⋅\theta$$

Donde:

* x: desplazamiento lineal de la cremallera
* r: radio del piñón (o $\frac{D}{2}$)
* θ: ángulo de rotación en radianes

La relación de transmisión indica cuánta distancia se desplazará la cremallera por cada vuelta del piñón, lo cual es clave para calcular velocidades lineales, aceleraciones, y seleccionar motores en sistemas de automatización, dirección de vehículos, maquinaria CNC, entre otros.

![image](https://github.com/user-attachments/assets/2884429e-ceaf-40e9-bf32-111559600d2f)

*Imagen 16. Transmisión piñon cremallera*

A partir de la definicón teórica, aplicamos otra deficinión matemática:

$N = \frac{Velocidad motor}{Velocidad carga}$

$V_{rack} = r_{pinion}w_{pinion}$

$N_{RP} = \frac{1}{r_{pinion}}$

💡 Ejemplo 10:
Supongamos que tenemos un piñón con un diámetro primitivo de 80 mm, acoplado a un motor que realiza una rotación completa. Queremos saber:

* ¿Qué distancia lineal recorre la cremallera por cada vuelta del piñón?

Sabemos que el desplazamiento lineal por cada vuelta del piñón es igual a su perímetro primitivo:

$Desplazamiento=\pi⋅D=\pi⋅80 mm≈251.33 mm$

Entonces, por cada vuelta del piñón, la cremallera se moverá 251.33 mm.

* Calcular el desplazamiento total para 10 vueltas

$Desplazamiento total=10⋅251.33 mm=2513.3 mm=2.513 m$

### 4.2. Inercia Reflejada <a id="Inercia-Reflejada"></a>

En sistemas mecánicos como el piñón-cremallera, la inercia reflejada es el efecto que la masa lineal en movimiento (por ejemplo, una carga desplazándose sobre la cremallera) tiene desde el punto de vista del eje del motor que hace girar el piñón.

Aunque la carga se mueve linealmente, su masa equivale a una cierta inercia rotacional reflejada al motor, debido a la relación entre desplazamiento angular del piñón y desplazamiento lineal de la cremallera.

Fórmula general:

$J_{ref} = m*r^{2}$

* $J_{ref}$= inercia reflejada al eje del motor (kg·m²)
* m = masa de la carga lineal (kg)
* r = radio primitivo del piñón (m)

A partir de la definicón teórica, aplicamos otra deficinión matemática:

$J_{trans ref} = J_{pinion} + J_{load->in} + J_{carriage-> in}$

$J_{trans ref} = J_{pinion} + \frac{1}{\eta {N_{RP}}^{2}}(\frac{W_{L} + W_{c}}{g})$

### 4.3. Torque de carga <a id="Torque-de-Carga"></a>

En un sistema piñón-cremallera, el torque de carga es el momento que el motor debe ejercer sobre el piñón para vencer una fuerza lineal (por ejemplo, una carga que se quiere mover) a través del contacto con la cremallera.

Fórmula del torque de carga:

$T=F⋅r$

Donde:

* T = torque de carga (Nm)
* F = fuerza lineal que se aplica sobre la cremallera (N)
* r = radio primitivo del piñón (m)

A partir de la definicón teórica, aplicamos otra deficinión matemática:

$F_{ext} = F_{f} + F_{g} + F_{p}$

$T_{load-> in} = \frac{F_{ext}}{\eta N_{RP}}$

💡 Ejemplo 11:

Supón que tienes:

* Una fuerza de carga $𝐹 = 100 N$ que se requiere para mover la cremallera.
* Un piñón con diámetro primitivo $D=60mm=0.06m$

Entonces:

$T = 100 ⋅ \frac{0.06}{2} = 100 ⋅ 0.03 = 3 Nm$

El motor debe generar al menos 3 Nm de torque para vencer la fuerza de carga sobre la cremallera con ese piñón. Si además hay fricción, inercia, o pendientes, ese torque deberá aumentarse.

## 5. Banda Transportadora plana <a id="Banda-Transportadora"></a>

Una banda transportadora plana es un sistema mecánico utilizado para transportar materiales o productos de un punto a otro de manera continua y eficiente. Está compuesta principalmente por una banda flexible (generalmente de goma, PVC o poliuretano) que se desplaza sobre una estructura plana sostenida por rodillos o una cama deslizante. La banda es impulsada por poleas motrices, y guiada por poleas conducidas y rodillos de retorno.

Este tipo de transportador se emplea ampliamente en industrias como la alimentaria, farmacéutica, manufactura, logística y empaque, ya que permite un flujo constante de productos, optimizando tiempos de producción y reduciendo el esfuerzo humano.

La simplicidad de diseño, facilidad de mantenimiento y adaptabilidad a diferentes longitudes, velocidades y cargas, hacen de la banda plana una solución ideal para el manejo de materiales en procesos automatizados.

**Fórmula General:**

$N= \frac{Velocidad motor}{Velocidad carga}$

$V_{belt} = r_{ip}w_{ip}$

$N_{BD} = \frac{1}{r_{ip}}$

![image](https://github.com/user-attachments/assets/88e7a920-9946-45a6-9efe-feec89a382c4)

*Imagen 17. Banda Transportadora plana*

💡 Ejemplo 12:

Datos del sistema:

* Longitud de la banda: $L=5m$
* Velocidad lineal deseada: $v=0.5m/s$
* Diámetro de la polea motriz: $D=0.2m$
* Masa total transportada sobre la banda: $m=50kg$
* Coeficiente de fricción (rodadura + fricción interna): $\mu=0.04$
* Gravedad: $g=9.81m/s^{2}$

1. Cálculo de la velocidad angular de la polea motriz

$w = \frac{v}{r} = \frac{0.5}{0.1} = 5 rad/s$

Donde $r = \frac{D}{2} = 0.1m$

2. Cálculo del torque necesario en la polea motriz

Primero se calcula la fuerza de fricción que la banda debe vencer:

$f = \mu⋅m⋅g = 0.04⋅50⋅9.81 = 19.62 N$

Luego, el torque requerido en la polea:

$T = f*r = 19.62⋅0.1 = 1.962 Nm$

Para mover una banda transportadora plana de 5 metros con una carga de 50 kg a una velocidad de 0.5 m/s, utilizando una polea de 20 cm de diámetro, se necesita:

* Una velocidad angular de 5 rad/s
* Un torque mínimo de 1.96 Nm en el eje de la polea motriz

### 5.1. Inercia reflejada <a id="Inercia-Reflejada"></a>

La inercia reflejada en una banda transportadora es la forma en que el motor "siente" la resistencia a poner en movimiento la banda, la carga y todo el sistema que esté conectado a ella. Se calcula para entender cuánta fuerza (torque) necesita el motor para mover todo de forma eficiente y segura.

La formula general del sistema es:

$J_{trans ref} = J_{IP} + J_{load-> in} + J_{carriage-> in} + J_{belt-> in} + J_{LP}$

$J_{trans ref} = 2J_{P} + \frac{1}{\eta {N_{BD}}^{2}}(\frac{W_{L} + W_{c} + W_{belt}}{g})$

![image](https://github.com/user-attachments/assets/29dacae2-250c-4235-8d1d-c20de5cd596d)

*Imagen 18. Inercia reflejada banda transportadora*

💡 Ejemplo 13:

Tienes una banda transportadora impulsada por un motor a través de una polea motriz. Los datos del sistema son los siguientes:

* Masa de la banda: 20 kg
* Masa de la carga transportada: 80 kg
* Radio de la polea motriz: 0.15 m
* Relación de reducción (reductor entre el motor y la polea): 10:1

Supón que no hay inercia en los rodamientos, poleas, etc. (para simplificar)

¿Cuál es la inercia reflejada al eje del motor?

**Paso 1: Calcular la inercia total en el eje de la polea**

La inercia de una masa en movimiento lineal que se convierte a inercia rotacional es:

$J = m⋅r^{2}$

Donde:
* m es la masa que se mueve linealmente (la banda + la carga),
* r es el radio de la polea motriz (0.15 m)

Entonces, la masa total que se mueve es:

$m_{total}=20kg+80kg=100kg$

Ahora la inercia equivalente en el eje de la polea:

$J_{Carga} = 100⋅(0.15)^{2} =100⋅0.0225=2.25kgm^{2}$

**Paso 2: Reflejar esta inercia al eje del motor**

Usamos la fórmula:

$J_{reflejada} = \frac{J_{carga}}{R^{2}}$

donde R=10 (relación de reducción).

$J_{reflejada} = \frac{2.25}{10^{2}} = 0.0225kgm^{2}$

La inercia reflejada al eje del motor es $0.0225 kg·m^{2}$.

### 5.2. Torque de carga <a id="Torque-de-Carga"></a>

El torque de carga es la fuerza que el motor debe ejercer para hacer girar la polea de la banda contra las resistencias del sistema. Depende del peso de la carga, fricción, aceleración deseada, y la geometría del sistema.

La formula general del sistema es:

$T_{load-> in} = \frac{F_{ext}}{\eta N_{BD}}$

Además, se aplica la siguiente fórmula cuando la banda tiene un ángulo:

$F_{ext} = F_{P} + (W_{L} + W_{belt})(sin\beta + \mu cos \beta)$

💡 Ejemplo 14:

Se tiene una banda transportadora horizontal con las siguientes características:

* Longitud total de la banda: 4 m
* Carga total sobre la banda: 200 kg
* Masa de la banda transportadora (sin carga): 50 kg
* Aceleración deseada: 0.4 m/s²
* Coeficiente de fricción dinámico total (banda + rodillos): μ = 0.04
* Radio de la polea motriz: r = 0.2 m
* Gravedad: g = 9.81 m/s²

Determinar el torque de carga necesario para mover la banda.

**Paso 1: Calcular masa total del sistema**

$m_{total} = m_{carga} + m_{banda} = 200 + 50 = 250 kg$

**Paso 2: Calcular la fuerza de aceleración**

$F_{inercia} = m_{total} \cdot a = 250 \cdot 0.4 = 100 N$

**Paso 3: Calcular la fuerza de fricción**

$F_{friccion} = \mu \cdot m_{total} \cdot g = 0.04 \cdot 250 \cdot 9.81 = 98.1 N$

**Paso 4: Calcular la fuerza total de resistencia**

$F_{resistencia} = F_{inercia} + F_{friccion} = 100 + 98.1 = 198.1 N$

**Paso 5: Calcular el torque de carga**

$T_{carga} = F_{resistencia} \cdot r = 198.1 \cdot 0.2 = 39.62Nm$

El torque de carga necesario para mover la banda transportadora es de ≈ 39.62 Nm.

### 5.3. Relación de Transmisión <a id="Relacion-de-Transmision"></a>

La relación de transmisión en una banda transportadora es la proporción entre la velocidad de giro del motor y la velocidad de giro de la polea motriz. Se expresa como:

$i = \frac{n_{motor}}{n_{polea}}$

* Si i>1, la polea gira más despacio que el motor y el torque aumenta.
* Si i<1, la polea gira más rápido que el motor y el torque disminuye.

Además, existen varias fórmulas las cuales relacionan la transmición con la inercia reflejada:

$N_{CV} = \frac{1}{r_{DR}}$

$J_{trans ref} = J_{DR} + J_{load-> in} + J_{belt-> in} + J_{ID-> in} + J_{BR-> in}$

$J_{trans ref} = J_{DR} + \frac{1}{\eta {N_{CV}}^{2}}(\frac{W_{L} + W_{belt}}{g}) + \frac{J_{ID}}{\eta (\frac{r_{ID}}{r_{DR}})^{2}} + \frac{J_{BR}}{\eta (\frac{r_{ID}}{r_{DR}})^{2}}$

![image](https://github.com/user-attachments/assets/73ff2c8c-eea1-441b-88e5-2c138c6d6e33)

*Imagen 19. Relación de transmisión banda transportadora*


💡 Ejemplo 15:

* Velocidad de banda deseada: 1 m/s
* Radio polea: 0,2 m

Entonces:

$n_{polea} = \frac{60 \cdot 1}{2\pi \cdot 0.2} \approx  47.7 rpm$

Si el motor gira a 1500 rpm:

$i = \frac{1500}{47.7} \approx 31.5$

Necesitaríamos un reductor (o conjunto de poleas) con relación cercana a 32:1.

Con esta relación ajustamos la velocidad y el torque para que el motor mueva la banda con la fuerza y rapidez adecuadas.

## 6. Conclusiones <a id="Conclusiones"></a>

Los sistemas de transmisión mecánica como polea-correa, tornillo guía, banda transportadora y piñón-cremallera son fundamentales en la automatización y control de movimiento en maquinaria. Cada uno presenta ventajas específicas según el tipo de aplicación:

 * Polea-correa permite una transmisión flexible y económica entre ejes, con cierta tolerancia a deslizamientos.
 * Tornillo guía ofrece alta precisión y capacidad de carga para movimientos lineales lentos.
 * Banda transportadora es eficiente para el transporte continuo de materiales, optimizando el flujo en procesos industriales.
 * Piñón-cremallera proporciona un movimiento lineal directo, rápido y robusto, ideal para sistemas con exigencias de fuerza y exactitud.

## 7. Ejemplos <a id="Ejemplos"></a>



## 8. Referencias <a id="Referencias"></a>

* Shigley, J. E., & Mischke, C. R. (2001). Diseño en Ingeniería Mecánica. McGraw-Hill.
* Thomson Linear. (2020). Guía de tornillos de avance y actuadores lineales.
* CEMA (Conveyor Equipment Manufacturers Association). Belt Conveyors for Bulk Materials.
* HIWIN Technologies. Manual de sistemas de transmisión lineal por piñón-cremallera.
