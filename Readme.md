## Estudio Dinámico del Encuentro Cercano de (99942) Apophis
### 1. Introducción y contexto 
"El 13 de abril de 2029, el asteroide (99942) Apophis pasará a una distancia de aproximadamente 31000 km de la superficie terrestre, una altitud inferior a la de los satélites geoestacionarios." Este evento representa una oportunidad excepcional para estudiar la repuesta dinámica de un cuerpo menor ante una pertubación gravitatoria extrema por parte de un planeta. 

Este proyecto tiene como objetivo modelar computacionalmente la trayectoria de Apophis, analizando la transición de su órbita heliocéntrica y cuantificando los cambios en sus elementos orbitales mediante el uso de integradores de $N$-cuerpos

### 2. Pilares Teóricos del Proyecto 
La investigación se fundamenta en los conceptos centrales de la mecánica celeste clásica y computacional vistos en el curso: 
* **El problema de los $N$-Cuerpos**: Modelado de las acelaraciones mutuas entre el Sol, los planetas principales, la Luna y el asteroide.

* **Integración numérica:** Para este encuentro de alta velocidad se implemntan integradores de paso adaptativo (como IAS15) para garantizar la conservación de la energía y el momento angular. 

* **Leyes de conservación y cuadraturas:** Monitoreo del Integral de Jacobi y la energía específica del sistema para validar la precisión del modelo computacional durante el sobrevuelo

### 3. Objetivos de la investigación

1. **Simulación de alta precisión:** Integrar la trayectoria de Apophis utilizando datos de efemérides reales (NASA Horizons) y la librería rebound

2. **Balance energético:** Evaluar el intercambio de energía cinética y potencial durante la aproximación extrema mediante el estudio de las cuadraturas del sistema