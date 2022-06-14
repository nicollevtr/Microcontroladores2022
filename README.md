# Microcontroladores2022
# **Código do projeto principal**

Projeto principal "sendData".

# **Proposta de projeto** 

Utilização de microcontroladores conectados para o monitoramento das condições de temperatura e umidade no ambiente do Laboratório de Computação.

# **Motivação** 

A eficiência e a garantia do funcionamento do laboratório depende de condições adequadas de temperatura e umidade, uma vez que nele estão armazenados aparelhos e instrumentos que necessitam de estar abrigados de condições ambientes que possam causar danos a sua estrutura física, comprometendo suas funcionalidades.

# **Funcionamento**

O monitoramento será feito a partir de dados obtidos do sensor DHT11 de temperatura e umidade localizado no laboratório, conectados a uma Discovery (STM32F407), a qual comunica-se com um ESP32 via UART para envio dos dados colhidos dos sensores. Este ESP32, estando conectado via Wi-Fi a uma rede a ser determinada, enviará os dados a um servidor online (ThingsSpeak) o qual mostrará gráficos em tempo real dos valores medidos pelo sensor, por meio dos quais será possível acompanhar as condições do ambiente do laboratório.

# **Desenvolvimento**

Para a implementação do projeto, será utilizada a IDE STM32CubeIDE, um kit de desenvolvimento STM32F407VG - STMicroelectronics, um microcontrolador ESP32 e o sensore DHT11 de temperatura e umidade.

![DiagramaBlocos drawio](https://user-images.githubusercontent.com/55112024/172491735-d11222b1-8d1b-40da-b331-bee443a3b8af.png)
![Fluxograma drawio](https://user-images.githubusercontent.com/55112024/169420860-c32dc24a-7b9b-49dc-b0a4-82e51b6c7ea0.png)

# **Links úteis**

Pinagem e comandos para conexão WiFi: https://circuitdigest.com/microcontroller-projects/interfacing-esp8266-with-stm32f103c8-stm32-to-create-a-webserver

Comandos TCP/IP AT https://docs.espressif.com/projects/esp-at/en/latest/esp32/AT_Command_Set/TCP-IP_AT_Commands.html#cmd-start

Leitura do sensor DHT11 com a discovery: https://controllerstech.com/using-dht11-sensor-with-stm32/

Enviar dados via UART da discovery para onectar a ESP32 a rede WiFi e então enviar dados para a webpage: https://controllerstech.com/data-logger-using-stm32-and-esp8266/

STM32F407 User manual https://www.st.com/resource/en/user_manual/dm00039084-discovery-kit-with-stm32f407vg-mcu-stmicroelectronics.pdf

ESP32 reference manual https://www.espressif.com/sites/default/files/documentation/esp32_technical_reference_manual_en.pdf

# **THINGSPEAK**

Link para acessar os dados em tempo real: https://thingspeak.com/channels/1741440

# **Firmware**
Funcionamento do código: 

![firmware_flowchart](https://user-images.githubusercontent.com/55112024/172197054-da6009d7-7fe3-42da-a778-df8585bba426.png)

# **Execução do projeto**
Video ilustrando o funcionamento do projeto:
https://user-images.githubusercontent.com/55112024/172498056-f480e845-2494-4160-b0a0-568178898588.mp4

