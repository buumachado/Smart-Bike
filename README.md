## Smart-Bike

Equipe:
- Bruna Machado Costa - 371783
- Daniel Filho Coelho Ramos - 374921
- Lais Brandão Gadelha - 378606

Como o nome já diz a smart bike será uma bicicleta inteligente que terá como diferencial:
- Medidor de velocidade e distância percorrida integrado a um aplicativo de celular,
- Sensor de luminosidade para ativar automaticamente luzes conectadas a bicicleta,
- Setas que serão acionadas manualmente,
- Conexão com o aplicativo por bluetooth.
        
Equipamentos Utilizados
- BreadBoard
- Módulo Bluetooth
- 4 leds
- Greenpill
- Sensor LDR 5mm
- ST-Linkv2
- 2 Botões Comutadores simples
- Reed switch
 
Comunicação com os sensores: 

A leitura do sensor Reed Switch e LDR foi feita pelo ADC, que convertia o valor anlógico passado para digital possibilitando a leitura correta do sensor.
O módulo bluetooth teve sua comunicação feita com a UART.
Os botões para seta foram ligados simplesmente pelo GPIO.


App:

<img width="274" alt="captura de tela 2018-12-06 as 22 26 18" src="https://user-images.githubusercontent.com/8231241/49622080-d5b38700-f9a6-11e8-99c8-5a59e7476a1e.png">
