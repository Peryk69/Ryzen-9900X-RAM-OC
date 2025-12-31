# Ryzen-9900X-RAM-OC
Ryzen 9 9900X &amp; DDR5 6000MHz | Daily Stable OC 
🔧 System SpecsCPU: AMD Ryzen 9 9900X (Zen 5).MB: MSI MAG B650 TOMAHAWK WIFI (BIOS 1.00 / AGESA 1.2.0.3e).RAM: Team Group T-Force Delta RGB 32GB (2x16) @ 6000MT/s (Hynix).🧠 CPU Optimization (PBO + Curve Optimizer)Configuración para reducir voltajes y mejorar frecuencias efectivas:PBO: Advanced / Limits: Motherboard.Curve Optimizer: Negative 15-25 (All Core).FCLK: 2100 MHz (Optimizado para 9900X).Max CPU Boost: +100/200 MHz.Resultado: Frecuencia estable de ~5.6GHz con menor huella térmica.⚡ RAM Timings (Stable Daily / Summer Profile)Perfil ajustado para mantener latencia sub-70ns con seguridad térmica para los chips Hynix:ParameterValueParameterValueSpeed6000 MT/stREFI65535tCL30tRFC480tRCD / tRP36 / 36tRC84tRAS48PowerDownDisabledUCLKMCLK (1:1)VDD/VDDQ1.35V
(Ryzen 9 9900X), ya que en la arquitectura Zen 5, el rendimiento de la memoria y el procesador van de la mano.

Aquí tienes el bloque de texto para añadir a tu README.md o crear un archivo nuevo llamado CPU_OPTIMIZATION.md:

⚡ AMD Ryzen 9 9900X CPU Optimization (PBO + Curve Optimizer)
Para maximizar el rendimiento del 9900X junto con la RAM optimizada, se han aplicado ajustes de Precision Boost Overdrive (PBO). El objetivo es permitir que el procesador alcance frecuencias más altas (hasta 5.6GHz+) manteniendo temperaturas controladas.

⚙️ Configuración en BIOS MSI
Parámetro	Valor	Objetivo
PBO (Precision Boost Overdrive)	[Advanced]	Desbloquea los límites de energía de fábrica.
PBO Limits	[Motherboard]	Permite que el 9900X use la robusta entrega de corriente de la B650 Tomahawk.
Precision Boost Overdrive Scalar	[Manual] - 1X	Mantiene el voltaje seguro para uso diario.
CPU Boost Clock Override	[+100MHz / +200MHz]	Aumenta el techo de frecuencia máxima.
Curve Optimizer	[Per Core] o [All Core]	El ajuste más importante para eficiencia.

Exportar a Hojas de cálculo

📉 Ajuste de Curve Optimizer (Undervolt)
El 9900X se beneficia enormemente de reducir el voltaje por núcleo:

All Core Curve Optimizer Sign: [Negative]

All Core Curve Optimizer Magnitude: [15 a 25]

Nota: Empezar en -15 para estabilidad total. Si es estable, subir a -25 para mejores temperaturas y más frecuencia.

🚀 Resultados obtenidos
Frecuencia efectiva: ~5.63 GHz en cargas ligeras.

Mejora térmica: Reducción de ~5-8°C en carga máxima comparado con el PBO por defecto.

Sincronía: Al optimizar el CPU, el controlador de memoria (IMC) sufre menos estrés térmico, permitiendo que la latencia de la RAM sea más estable a 69.5 ns.

¿Cómo integrarlo en GitHub?
Te sugiero añadir una sección final en tu README titulada "Synergy: CPU + RAM":

"La clave de este sistema es la sinergia. Al aplicar un Negative Curve Optimizer al Ryzen 9 9900X, liberamos margen térmico que permite al FCLK de 2100MHz y a la memoria DDR5 6000 trabajar con una latencia más baja y consistente, evitando el 'thermal throttling' del controlador de memoria interno."

¿Te gustaría que te redacte también los pasos específicos para encontrar estas opciones dentro del menú de Overclocking de tu placa MSI?
<img width="662" height="625" alt="image" src="https://github.com/user-attachments/assets/c0b00cbb-969f-47ef-bf07-7e905ed6247e" />
<img width="470" height="695" alt="Captura de pantalla 2025-12-31 201258" src="https://github.com/user-attachments/assets/b37005c4-6746-4b6b-a8b1-56724aa6ae5e" />![IMG_20251231_140814](https://github.com/user-attachments/assets/ef89e670-26f7-424a-b3e8-7b21c9b06654)
![IMG_20251231_140804](https://github.com/user-attachments/assets/baefd6f5-f69c-4225-855e-4873527180a2)

<img width="499" height="881" alt="image" src="https://github.com/user-attachments/assets/181a7c89-3df4-44bb-88be-1a3ce3ab0b4f" />[Ryzen 9 9900x Zen 5 – Daily Tuning Guide.pdf](https://github.com/user-attachments/files/24397452/Ryzen.9.9900x.Zen.5.Daily.Tuning.Guide.pdf)


