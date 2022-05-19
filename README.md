# Microcontroladores2022
# **Proposta de projeto** 

Utilização de microcontroladores conectados para o monitoramento das condições de temperatura e umidade no ambiente do Laboratório de Computação.

# **Motivação** 

A eficiência e a garantia do funcionamento do laboratório depende de condições adequadas de temperatura e umidade, uma vez que nele estão armazenados aparelhos e instrumentos que necessitam de estar abrigados de condições ambientes que possam causar danos a sua estrutura física, comprometendo suas funcionalidades.

# **Funcionamento**

O monitoramento será feito a partir de dados obtidos do sensor DHT11 de temperatura e umidade localizado no laboratório, conectados a uma Discovery (STM32F407), a qual comunica-se com um ESP32 via UART para envio dos dados colhidos dos sensores. Este ESP32, estando conectado via Wi-Fi a uma rede a ser determinada, enviará os dados a um servidor online (ThingsSpeak) o qual mostrará gráficos em tempo real dos valores medidos pelo sensor, por meio dos quais será possível acompanhar as condições do ambiente do laboratório.

# **Desenvolvimento**

Para a implementação do projeto, será utilizada a IDE STM32CubeIDE, um kit de desenvolvimento STM32F407VG - STMicroelectronics, um microcontrolador ESP32 e o sensore DHT11 de temperatura e umidade. O conjunto será montado de modo compacto e ajustado em um compartimento o qual será alocado em uma posição estrtégica no labortório.
![DiagramaBlocos drawio](https://user-images.githubusercontent.com/55112024/169420858-06cee869-8e8e-402d-8565-bc252f802b86.png)
![Fluxograma drawio](https://user-images.githubusercontent.com/55112024/169420860-c32dc24a-7b9b-49dc-b0a4-82e51b6c7ea0.png)

