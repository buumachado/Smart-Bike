# Smart-Bike

## Equipe:
- Bruna Machado Costa - 371783
- Daniel Filho Coelho Ramos - 374921
- Lais Brandão Gadelha - 378606

## Funcionalidade
Como o nome já diz a smart bike será uma bicicleta inteligente que terá como diferencial:
 Medidor de velocidade e distância percorrida integrado a um aplicativo de celular,
 Sensor de luminosidade para ativar automaticamente luzes conectadas a bicicleta,
 Setas que serão acionadas manualmente,
 Conexão com o aplicativo por bluetooth.
        
## Equipamentos Utilizados
- BreadBoard
- Módulo Bluetooth
- 4 leds
- Greenpill
- Sensor LDR 5mm
- ST-Linkv2
- 2 Botões Comutadores simples
- Reed switch
 
## Comunicação com os sensores: 

A leitura do sensor Reed Switch e LDR foi feita pelo ADC, que convertia o valor anlógico passado para digital possibilitando a leitura correta do sensor.
O módulo bluetooth teve sua comunicação feita com a UART.
Os botões para seta foram ligados simplesmente pelo GPIO.

## Sensores/Módulos Principais

Sensor de luminosidade - o modelo utilizado no projeto foi o LDR(Light Dependent Resistor) de 5mm de diâmetro. Este sensor altera a resistência em seus terminais conforme a luminosidade a que é submetido.

Reed Switch - Este pequeno sensor chamado Reed Switch é utilizado para se detectar a presença de um campo magnético. Seu funcionamento é muito simples, quando ele é exposto a um campo magnético os dois filetes de ferro dentro da ampola de vidro são atraídos juntos e o contato se fecha, e quando o campo magnético é removido, os filetes se separam novamente e o contato se abre. Dentro ele foi utilizado para contabilizar a quantidade de voltas que o pneu da bicicleta realiza.

Módulo Bluetooth - utilizado para passar as informações obtidas pelo reed swith para o aplicativo android.



## Smart Bike App:

![app_smart_bike](https://user-images.githubusercontent.com/43276631/50021434-de641880-ffb7-11e8-9df2-6eb3aeffc1cc.jpeg)

