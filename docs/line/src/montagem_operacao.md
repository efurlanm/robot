# Instruções de Montagem e Operação

Este documento tenta fornecer um guia básico para a montagem física do robô seguidor de linha e as etapas essenciais para sua operação inicial. A intenção não é ser abrangente ou preciso.

## 1. Montagem do Hardware

### 1.1. Preparação do Chassi

*   Certifique-se de que todas as peças do chassi (ex.: acrílico cortado a laser) estejam limpas e sem rebarbas.
*   Identifique os furos para fixação dos motores, sensores e demais componentes.

### 1.2. Fixação dos Motores e Rodas

*   Encaixe os motores DC com caixa de redução nos suportes do chassi, utilizando parafusos e porcas adequados.
*   Fixe as rodas nos eixos dos motores, garantindo que estejam bem presas.
*   Instale a roda boba na parte frontal ou traseira do chassi, conforme o design, para servir de apoio.

### 1.3. Instalação do Driver de Motor (L298N)

*   Fixe o módulo L298N no chassi, em uma posição que facilite a conexão com o Arduino e os motores.
*   Conecte os terminais de saída do L298N aos motores DC (geralmente, dois fios por motor).

### 1.4. Conexão dos Sensores Infravermelhos (TCRT5000)

*   Monte o módulo TCRT5000 na parte inferior frontal do chassi, de forma que os sensores fiquem a uma distância ideal da superfície (geralmente entre 5mm e 15mm, dependendo do sensor e da pista).
*   Conecte os pinos de saída dos sensores aos pinos analógicos ou digitais do Arduino, conforme a configuração do software.

### 1.5. Conexão do Arduino

*   Fixe a placa Arduino Uno R3 no chassi.
*   Conecte os pinos de alimentação (5V e GND) do Arduino ao L298N e aos sensores.
*   Conecte os pinos de controle do L298N aos pinos digitais do Arduino (para controle de direção e velocidade).

### 1.6. Alimentação

*   Conecte o suporte de pilhas (ou outra fonte de alimentação) ao módulo L298N, respeitando a polaridade.
*   Certifique-se de que a fonte de alimentação seja adequada para os motores e o Arduino.

## 2. Operação Inicial e Calibração

### 2.1. Carregamento do Código

*   Conecte o Arduino ao computador via cabo USB.
*   Abra a Arduino IDE e carregue o código-fonte do robô.
*   Certifique-se de que a placa e a porta serial corretas estejam selecionadas.
*   Compile e faça o upload do código para o Arduino.

### 2.2. Calibração dos Sensores

*   A calibração dos sensores infravermelhos é crucial para o robô diferenciar a linha da superfície da pista.
*   Coloque o robô sobre a pista (parte branca e parte preta da linha).
*   Ajuste os potenciômetros de cada sensor no módulo TCRT5000 (se houver) ou utilize a rotina de calibração no código (se implementada) para que os sensores forneçam leituras distintas para as cores.
*   Monitore as leituras dos sensores através do Serial Monitor da Arduino IDE para verificar a calibração.

### 2.3. Teste de Motores

*   Com o robô suspenso (rodas sem contato com a superfície), teste individualmente cada motor para verificar se giram nas direções corretas (para frente e para trás) e se respondem aos comandos de velocidade.
*   Ajuste as conexões ou o código, se necessário.

### 2.4. Primeiro Teste na Pista

*   Coloque o robô cuidadosamente na linha de partida da pista.
*   Ligue o robô e observe seu comportamento.
*   Faça ajustes finos no código (parâmetros PID, limiares dos sensores) conforme necessário para otimizar o desempenho do robô no percurso.

## 3. Dicas de Solução de Problemas

*   **Robô não se move:** verifique conexões de alimentação, motores, driver de motor e se o código foi carregado corretamente.
*   **Robô não segue a linha:** recalibre os sensores, verifique a iluminação do ambiente, ajuste os limiares no código.
*   **Movimento errático:** ajuste os parâmetros do algoritmo de controle (PID), verifique se as rodas estão bem fixas e se não há atrito excessivo.
*   **Bateria descarrega rápido:** verifique a capacidade da bateria e o consumo de corrente dos componentes.

<br><sub>Last edited: 2025-07-22 22:35:00</sub>
