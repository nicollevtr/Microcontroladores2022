# Microcontroladores2022
# **Proposta de projeto** 

Utilização de microcontroladores conectados para o monitoramento das condições de temperatura e umidade no ambiente do Laboratório de Computação.

# **Motivação** 

A eficiência e a garantia do funcionamento do laboratório depende de condições adequadas de temperatura e umidade, uma vez que nele estão armazenados aparelhos e instrumentos que necessitam de estar abrigados de condições ambientes que possam causar danos a sua estrutura física, comprometendo suas funcionalidades.

# **Funcionamento**

O monitoramento será feito a partir de dados obtidos de sensores de temperatura e umidade localizados no laboratório, conectados a um ESP32, o qual poderá se comunicar com um segundo ESP32 via rede Wi-Fi. Este enviará os dados constantemente atualizados via comunicação serial com um STM32F407, conectado a um notebook, por meio do qual será possível acompanhar as condições do ambiente do laboratório.

# **Desenvolvimento**

Para a implementação do projeto, será utilizada a IDE STM32CubeIDE, um kit de desenvolvimento STM32F407VG - STMicroelectronics, dois microcontroladores ESP32 e os sensores de temperatura e umidade (modelos a serem definidos).
