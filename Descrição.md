# Esta-o-de-Monitoramento-Ambiental-MQTT-P-blico-
Exemplo de trabalho com ESP32
https://wokwi.com/projects/464309328901420033

🌐 Estação de Monitoramento IoT com Telemetria em Nuvem (Tempo Real)
Este projeto apresenta o desenvolvimento de um protótipo funcional para uma Estação de Monitoramento Ambiental IoT utilizando o microcontrolador ESP32. O foco principal deste case é demonstrar uma arquitetura de telemetria ponta a ponta robusta, escalável e de baixo custo, ideal para cenários de Cidades Inteligentes, Agronegócio e Monitoramento de Ativos Industriais.

A solução captura dados de temperatura e umidade e os transmite de forma assíncrona para um Broker MQTT na nuvem, permitindo a visualização dos dados em tempo real em um dashboard interativo.

🚀 Principais Diferenciais e Arquitetura
Conectividade Eficiente: Utilização do protocolo MQTT (Message Queuing Telemetry Transport), o padrão da indústria para IoT devido ao seu baixíssimo consumo de banda e energia.

Prototipagem Ágil & Gêmeo Digital: Integração completa em ambiente simulado de alta fidelidade (Wokwi), permitindo validação lógica e de hardware antes do investimento em componentes físicos.

Independência de Infraestrutura: Comunicação direta com servidores em nuvem utilizando o módulo Wi-Fi nativo do ESP32.

🛠️ Stack Tecnológica
Hardware / Microcontrolador: ESP32 (Sistemas Embarcados)

Sensor: DHT22 (Sensor digital de alta precisão para temperatura e umidade)

Protocolo de Rede: MQTT (Broker Público HiveMQ)

Linguagem de Programação: C/C++ (Ambiente Arduino IDE)

🕹️ Experiência Interativa (Testar em Tempo Real)
Como avaliar este projeto na prática:

Acesse o ambiente de simulação através do Link do Projeto no Wokwi.

Clique no botão "Play" (Iniciar Simulação).

Abra o seu dashboard público ou o HiveMQ Web Client em outra aba do seu navegador (conectando ao broker broker.hivemq.com e assinando os tópicos portfolio/estacao/temperatura e portfolio/estacao/umidade).

Volte na tela do simulador, clique sobre o sensor DHT22 e altere os valores de temperatura ou umidade com o mouse.

O resultado: Veja os gráficos e dados mudarem instantaneamente no painel em nuvem, demonstrando a latência mínima da arquitetura implementada.

💼 Aplicações Comerciais deste Projeto
Esta mesma arquitetura pode ser facilmente adaptada e expandida para clientes que necessitam de:

Controle estrito de temperatura em cadeias de suprimentos e frigoríficos.

Monitoramento climático para estufas automatizadas no setor agrícola.

Sistemas de telemetria industrial (Indústria 4.0) com adição de múltiplos sensores de pressão, vibração ou fluxo.
