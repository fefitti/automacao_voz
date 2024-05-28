# Sistema de Automação por Meio de Reconhecimento de Voz

Este é um projeto de automação residencial que utiliza reconhecimento de voz para controlar dispositivos eletrônicos. A ideia é criar uma assistente virtual capaz de interpretar comandos de voz e acionar diferentes dispositivos, como lâmpadas, motores e sirenes.

## Instalação

Antes de executar o projeto, é necessário instalar algumas dependências. Você pode fazer isso executando os seguintes comandos:
pip install SpeechRecognition
pip install <caminho do arquivo .whl do PyAudio>


Certifique-se de substituir `<caminho do arquivo .whl do PyAudio>` pelo caminho correto do arquivo PyAudio correspondente ao seu sistema operacional, que pode ser baixado [aqui](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio).

## Como Usar

Para executar o programa, basta rodar o script Python `automacao_voz.py`. Este script irá ativar o microfone do usuário, aguardar um comando de voz e, em seguida, executar a ação correspondente com base no comando reconhecido.

Por exemplo, ao dizer "navegador", o script abrirá o navegador Chrome. Da mesma forma, ao dizer "Excel", o Excel será aberto.

## Contribuições

Contribuições são bem-vindas! Se você tiver ideias de novas funcionalidades ou melhorias para o projeto, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.


