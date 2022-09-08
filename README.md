# Por que a responsividade?

Um problema que pode acontecer durante o processo de desenvolvimento de um app é que ao exportar, as diferentes configurações de tela podem trazer comportamentos atípicos como elementos movendo-se para fora da tela, ou sobrepondo-se uns sobre os outros.
Para isso temos 2 remédios:
- Simulação de dispositivos
- Modo prévia de resolução

Abaixo está detalhado com mais detalhes cada uma

## Simulação de dispositivos

Existe um pacote no Unity chamado "Device Simulator" no Unity, que permite que seja emulado uma tela de celular no player (com resolução e limitações físicas, como câmeras). No entanto, até a data que isto está sendo escrito (08/09/22), este pacote está como prévia (incompleto). Então é necessário configurar antes o projeto para receber pacotes em prévia (este processo é necessário pois a premissa é que alguns pacotes em prévia  podem trazer impacto de performance, entre outros fatores)

Para fazer isso, é necessário seguir o seguinte caminho: ``Edit -> Project Settings -> Package Manager``. Segundo o fórum oficial da Unity:
