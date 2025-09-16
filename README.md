# Sprint 3 - Edge

# Participantes

Luis Miguel RM561232 <br>
Rafael Joda RM561939 <br>
Davi Alves RM 566279 <br>
Camila de Mendonça RM 565491 <br>
Diego Zandonadi RM 561488 <br>

# Descrição do Projeto

O projeto desenvolvido na sprint é uma bandeira tecnológica com dispositivo IoT (ESP32) que traz inovação para a profissão de árbitro assistente na qual são adicionados botões para habilitar uma comunicação mais fácil e fluída entre toda equipe arbitrária e adicionar mais informações e estatisticas sobre os jogos

# Arquitetura Proposta

A arquitetura inicia com o ESP32 na camada de dispositivo, passa para camada de conectividade com HTTP, a camada de plataforma e análise de dados é tomada pelo thingspeak e o diagrama termina com gráficos na camada de aplicação

# Recursos necessários

O produto foi feito com dispositivo IoT ESP32, Botões para ativamento das sinalizações e uso da plataforma thingspeak.

# Instruções de uso

No wokwi, utiliza o ESP32 normal, conectar os botões ao ESP32 sendo o lado direito conectar ao GND (qualquer um) e o lado esquerdo conectar ao respectivo pino do botão 12, 13, 14 etc. Quando iniciar, clique nos botões e verá as mensagens sendo enviadas. 
Entre no thingspeak, crie a conta, crie o canal, pegue a write api key e coloque na variável apikey, coloque o wifi e senha nas variáveis ssid e password.
O seu produto estará funcionando.

# Script de Configuração da plataforma

field1 = Escanteio
field2 = Lateral
field3 = Impedimento

Api_key = 31HOZMTM3911YQYQ

# Simulação

https://wokwi.com/projects/442197804454616065

