# Apuntes_Semana Doce
Apuntes control de movimiento - Tercer Corte - Doceava Semana

Tomás Santiago Sánchez Barrera & María Fernanda Ortíz Velandia & Andrés Felipe Arteaga Escalante

# 1. Control de Movimiento (Diseño de Transmisión)

**Conceptos de Transmisión**

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

## 2. Sistema Polea - Correa

El sistema de transmisión polea-correa es uno de los métodos más utilizados para transferir movimiento y potencia entre ejes separados en sistemas mecánicos. Este mecanismo se basa en el uso de una o más poleas conectadas entre sí mediante una correa flexible que permite transmitir fuerza desde un eje motriz (activo) hacia uno o varios ejes conducidos (pasivos). Su popularidad se debe a su simplicidad de diseño, bajo costo, funcionamiento silencioso y capacidad de absorber vibraciones. Además, permite trabajar con distancias variables entre ejes, lo que lo hace ideal para aplicaciones en maquinaria agrícola, ventiladores, electrodomésticos y sistemas automotrices. La selección adecuada del tipo de correa (plana, trapezoidal o dentada), junto con una correcta tensión y alineación del sistema, es esencial para garantizar una transmisión eficiente, segura y duradera.

![Gemini_Generated_Image_emfzademfzademfz](https://github.com/user-attachments/assets/c2171736-4ba7-4bcd-96df-ef4280f1c3d9)

*Imagen 3. Sistema de Transmisión Polea-Correa*

### 2.1. Relación de Transmisión

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

💡 Ejemplo 3: Reducción de velocidad

* Si la polea motora tiene 100 mm y la conducida tiene 200 mm:

$$i = \frac{200}{100} = 2$$

La polea conducida gira 1 vez por cada 2 vueltas de la motora. La velocidad disminuye y el torque aumenta.

![image](https://github.com/user-attachments/assets/3a740adf-5174-462b-b687-56e3de8b87ad)

*Imagen 5. Reducción de Velocidad*

### 2.2. Inercia reflejada

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

💡 Ejemplo 4: Cálculo de Inercia Reflejada en un Sistema Polea-Correa

* Situación:

Un motor está conectado a una polea de diámetro 100 mm, que transmite movimiento mediante una correa a otra polea de diámetro 300 mm, acoplada a una carga rotativa con una inercia de 1.2 kg·m². Queremos calcular la inercia reflejada al eje del motor.

**Paso 1: Calcular la relación de transmisión**

Usamos la fórmula de relación de transmisión basada en los diámetros:

$$i=\frac{D_{conducida}}{D_{motora}} = \frac{300}{100} = 3$$

**Paso 2: Calcular la inercia reflejada**

Aplicamos la fórmula:

$$J_{r} = \frac{J_{c}}{i^{2}} = \frac{1.2}{3^{2}} = 0.133 kgm^{2}$$

Desde el punto de vista del motor, la carga rotativa se siente como si tuviera una inercia de 0.133 kg·m², lo cual es mucho más fácil de mover y controlar que la inercia real de 1.2 kg·m².

### 2.3. Torque de Carga

El torque de carga (también llamado par de carga) es el momento de fuerza que una carga aplica en contra del movimiento generado por un motor o actuador. Es la resistencia que el sistema debe vencer para mantener el movimiento o iniciarlo.

Este torque puede venir de:

* Fricción
* Gravedad (en sistemas verticales)
* Inercia (durante aceleración)
* Cargas externas (como peso de un brazo robótico, fajas transportadoras con carga, etc.)

![image](https://github.com/user-attachments/assets/61dcb8c9-d14c-482a-9c0f-39a12394a7df)

*Imagen 7. Torque de carga*

💡 Ejemplo 5: Torque de carga en una Banda Transportadora

Tenemos una banda transportadora horizontal impulsada por un rodillo de radio 0.1 m, que transporta cajas con un peso total de 80 kg. La banda se mueve a velocidad constante, y se estima una fricción total (banda + rodillos) equivalente a 5% del peso total.

Queremos calcular el torque de carga que el motor debe entregar al eje del rodillo para mover la banda.

**Paso 1: Calcular la fuerza de fricción**

Primero, obtenemos la fuerza de fricción, que es la única oposición en este caso (no hay aceleración ni pendiente):

$$F_{fricción} = 0.05(mg) = 0.05(80*9.81) = 39.24 N$$

**Paso 2: Calcular el torque de carga**

$$T_{C} = Fr = 39.24 * 0.1 = 3.924 N$$

El torque de carga necesario es 3.92 Nm.
Este es el mínimo torque que el motor debe proporcionar (sin contar pérdidas mecánicas adicionales o inercia de arranque).

## 3. Tornillo guía

El tornillo guía, también conocido como husillo de avance o husillo de bolas (cuando tiene rodamientos internos), es un mecanismo utilizado para convertir el movimiento rotacional en movimiento lineal, con alta precisión y control.

Es muy común en sistemas como:

* Máquinas CNC
* Impresoras 3D
* Robots cartesianos
* Actuadores lineales

Este sistema está compuesto por un tornillo roscado y una tuerca móvil. Cuando el tornillo gira, la tuerca se desplaza linealmente a lo largo de él (o viceversa, dependiendo del montaje).

![image](https://github.com/user-attachments/assets/b5ab5811-ce14-497b-8364-444f270c2cc6)

*Imagen 8. Tornillo guía*

💡 Ejemplo 6:

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

### 3.1. Tornillo guía ACME

El tornillo guía ACME es un tipo de tornillo de potencia diseñado para convertir movimiento rotativo en movimiento lineal, utilizado comúnmente en maquinaria, tornos, prensas, impresoras 3D y sistemas de elevación.

Se caracteriza por tener una rosca trapezoidal, con un ángulo de 29° en sus flancos, lo cual lo hace más robusto y resistente al desgaste que una rosca común (como la métrica o la de tornillos de fijación).

![image](https://github.com/user-attachments/assets/3f6c96b3-d70f-4e12-8b0d-8c9944486b47)

*Imagen 9. Tornillo Guía Acme*

### 3.2. Tornillo guía de esfera

El tornillo guía de esferas es un mecanismo de transmisión lineal de alta precisión que convierte el movimiento rotativo en lineal, al igual que el tornillo ACME, pero con una eficiencia mucho mayor gracias al uso de bolas recirculantes entre el tornillo y la tuerca.

Estas esferas giran en canales especialmente diseñados, lo que reduce drásticamente la fricción y permite movimientos más suaves, rápidos y precisos.

![image](https://github.com/user-attachments/assets/99069899-78f6-42bd-9f43-c06bd3055616)

*Imagen 10. Tornillo guía de esferas*
 
### 3.3. Relación de Transmisión




## 4. Concepto Transmisión Polea-Correa

El sistema de transmisión por polea y correa es un mecanismo ampliamente utilizado para transferir movimiento y potencia entre dos ejes separados. Este tipo de transmisión se basa en el uso de una correa flexible que conecta dos poleas: una motriz (conectada al motor) y otra conducida (conectada a la carga). Al girar la polea motriz, la correa transmite ese movimiento a la polea conducida, permitiendo modificar la velocidad y el torque de salida según el diámetro de las poleas involucradas.

Entre sus ventajas destacan la simplicidad mecánica, el bajo costo, el funcionamiento silencioso y la capacidad de absorber vibraciones. Además, permite transmisiones a distancia y cierta flexibilidad en la alineación de los ejes. Sin embargo, también presenta desventajas como el posible deslizamiento de la correa, la necesidad de mantenimiento periódico (ajuste de tensión y reemplazo de la correa) y una eficiencia menor comparada con sistemas más rígidos como engranajes.

**Puntos claves:**

* *Relación de transmisión:* Se determina por el cociente entre los diámetros de las poleas. Esto permite adaptar la velocidad y el torque entre el motor y la carga.

* *Tensión adecuada:* Es fundamental mantener la correa con la tensión correcta para evitar deslizamientos y asegurar una transmisión eficiente y duradera.

### 4.1. Relación de Transmisión

La relación de transmisión en un sistema de polea-correa indica cómo se modifica la velocidad de rotación entre la polea motriz (la que transmite el movimiento) y la polea conducida (la que recibe el movimiento). Esta relación depende directamente del tamaño de las poleas, y se calcula como:

Relación de transmisión (i) = $$\frac {Diámetro de la polea conducida}{Diámetro de la polea motriz}$$

Este valor también puede expresarse usando las velocidades de rotación:

$$i: \frac{Velocidad de la polea motriz}{Velocidad de la polea conducida}$$

### 4.2. Inercia Reflejada

En un sistema de polea-correa, la inercia reflejada se refiere a cómo la inercia de la carga (conectada a la polea conducida) se “ve” desde el motor (polea motriz), tomando en cuenta la relación de transmisión. Este concepto es clave en el diseño de sistemas de control de movimiento, ya que afecta directamente la respuesta dinámica del motor.

La inercia reflejada $J_{ref}$ al eje del motor se obtiene mediante la siguiente fórmula:

$$J_{ref}: \frac{J_{carga}}{i^{2}}$$

Donde:
* $J_{carga}$ es la inercia real de la carga.
* 𝑖
i es la relación de transmisión (diámetro polea conducida / diámetro polea motriz).

### 4.3. Torque de Carga

El torque de carga en un sistema de transmisión por polea-correa es el torque que debe entregar el motor para mover la carga conectada a la polea conducida. Este torque depende de la relación de transmisión, el tipo de carga y la eficiencia del sistema.

**Relación entre torque del motor y torque de la carga:**

$$T{motor}: \frac{T_{carga}}{i*n}$$

Donde:

* $T{motor}$ es el torque que debe generar el motor
* $T_{carga}$ es el torque requerido por la carga
* $i$ es la relación de transmisión (diámetro polea conducida / diámetro polea motriz)
* $n$ es la eficiencia del sistema (entre 0 y 1)

## 5. Ejercicios

### Una carga tiene una inercia de 0.05 kg·m² y se conecta a un motor a través de una relación de transmisión de 4:1.
* Calcula la inercia reflejada al motor.

$$J_{r}=\frac{J_{L}}{N^{2}}$$

$J_{r}=\frac{0.05}{4^{2}}$

$J_{r}=\frac{0.05}{16}$

$J_{r}=0.003125 Kg*m^{2}$

* Si el torque requerido por la carga es de 2 Nm, ¿cuánto torque reflejado sentirá el motor?

$$T_{r}= \frac{T_{L}}{N}$$

$T_{r}=\frac{2}{4}$

$T_{r}=0.5 Nm$


### Un motor eléctrico proporciona un torque constante de 3 Nm a una velocidad de 1500 rpm.

* Calcular la potencia mecánica entregada por el motor en watts.

$$P=T*\omega$$

$T=3 Nm$

$\omega = 2\pi * \frac{rpm}{60}$

$\omega=2\pi* \frac{1500}{60}$

$\omega=2\pi * 25$

$\omega = 157.08 rad/s$

$P=3*157,08$

$P=471,24 W$

### Un sistema de transmisión tiene una eficiencia del 85%. Si el motor entrega una potencia de 500 W:

*  Calcular la potencia útil disponible en la carga.

$$P_{util}=\eta*P_{entrada}$$

$P_{util}=0.85*500$

$P_{util}= 425 W$

## 6. Conclusiones

* El diseño correcto de sistemas de transmisión mecánica (engranajes, correas, cadenas) es esencial para garantizar eficiencia, precisión, seguridad y durabilidad en sistemas automatizados y mecatrónicos.
* Una correcta elección del motor y su relación con la transmisión y la carga permite alcanzar un funcionamiento óptimo. Esto requiere asegurar el torque necesario, una relación de inercia adecuada y el cumplimiento de criterios como el costo, precisión y tiempos de ciclo.
* La inercia y el torque reflejados al eje del motor deben calcularse para anticipar el esfuerzo que el motor debe realizar. Esto es vital para evitar sobrecargas, mejorar el rendimiento dinámico y permitir un control más preciso.
* La relación entre engranajes afecta directamente la velocidad y el torque transmitido. Además, mantener alta eficiencia en el sistema minimiza pérdidas energéticas, mejora la vida útil del equipo y reduce el consumo energético.
* La relación define el equilibrio entre la inercia de la carga y la del motor. Mantenerla en rangos adecuados asegura un control estable y eficiente. Una mala relación puede llevar a inestabilidad, sobreesfuerzo del motor o pérdida de precisión.

## 7. Referencias

* Mecatrónica Integrada (2023). Motores eléctricos: Torque, potencia y eficiencia. Universidad Cooperativa de Colombia – Facultad de Ingeniería Mecatrónica. Material de estudio.

* González, J. (2019). Principios de máquinas eléctricas y transformadores. McGraw-Hill.

* Universidad Nacional de Colombia (2022). Laboratorio de máquinas eléctricas: prácticas con motores de inducción y corriente continua. Facultad de Ingeniería Eléctrica.

* Universidad Cooperativa de Colombia – Facultad de Ingeniería Mecatrónica. (2023). Motores eléctricos: Torque, potencia y eficiencia. Material de estudio interno.
