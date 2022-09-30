# CASH-TESTER

Implementar una solución viable a la problemática que más de 595.288 personas sufren en el país al no poder identificar eficazmente la denominación de las monedas de referencia colombiana.

El diseño se compone de:

•	Un sensor (transductor) el cual es una resistencia sensible a la fuerza (FSR - FlexiForce A101). 

•	Circuito de acondicionamiento de señal usando un puente de wheatstone asi como también un amplificador de instrumentación y un filtro pasa bajos

•	La señal proveniente del filtro pasa bajos pasada por un circuito detector de picos el cual se encarga de retardar/ampliar la duración del pico de voltaje

•	La señal proveniente del detector de picos es enviada a un comparador para clasificar y crear un voltaje DC.

•	El voltaje DC proveniente del comparador ingresa a un VCO el cual producirá una variación en frecuencia. 

•	La frecuencia proveniente del VCO es usada para producir un sonido con el cual es posible identificar el valor de la moneda.

