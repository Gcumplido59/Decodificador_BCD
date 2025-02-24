# Decodificador_BCD

📌 Descripción
Entradas: 10 switches para numero binario, salida: 4 Displays para numero en decimal.
Este proyecto implementa y prueba compuertas lógicas en un FPGA utilizando Quartus y Verilog, lo que se espera son 10 entradas que forman un numero binario (Num. max: 1023) y de salida aparecerá el numero decimal en 4 displays.

⚙️ Requisitos

Quartus Prime (Intel FPGA)

FPGA compatible (Ejemplo: Cyclone IV, MAX10), En este proyecto se utilizó FPGA Intel DE10-Lite

Cable de programación JTAG

📂 Estructura del Proyecto

/Decodificador_BCD

│── BCD.v # Módulo principal con compuertas lógicas

│── BCD_tb.v # Testbench para simulación

│── BCD.qpf # Archivo del proyecto en Quartus

│── BCD.qsf # Archivo de configuración del FPGA

│── README.md # Este archivo
