# Decodificador_BCD
Gael Cumplido Mendoza - A01029238

📌 Descripción

Entradas: 10 switches para numero binario, salida: 4 Displays para numero en decimal.
Este proyecto implementa y prueba compuertas lógicas en un FPGA utilizando Quartus y Verilog, lo que se espera son 10 entradas que forman un numero binario (Num. max: 1023) y de salida aparecerá el numero decimal en 4 displays (Como el numero maximo es 1023 cada display agarra las 4 secciones del numero, los miles, las centenas, las decenas y las unidades). Para las entradas se utilzan los 10 switches del FPGA, y para las salidas se utilizan 4 displays de 7 segmentos  igual integrados en el FPGA.

⚙️ Requisitos

Quartus Prime (Intel FPGA)

FPGA compatible (Ejemplo: Cyclone IV, MAX10), En este proyecto se utilizó FPGA Intel DE10-Lite

Cable de programación JTAG

📂 Estructura del Proyecto

/decodificador_BCD

│── BCD.v # Módulo principal para decodificador

│── display.v # Modulo para el display de 7 segmentos

│── BCD_tb.v # Testbench para simulación

│── decodificador_BCD.qpf # Archivo del proyecto en Quartus

│── decodificador_BCD.qsf # Archivo de configuración del FPGA

│── README.md # Este archivo
