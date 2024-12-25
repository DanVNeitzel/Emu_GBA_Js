GBA.js
======
**Versão 1.1-git — Copyright © 2012 – 2013 Jeffrey Pfau**

GBA.js é um emulador de Game Boy Advance escrito do zero para empregar tecnologias HTML5 como Canvas e Web Audio. Ele não usa plugins e foi projetado para rodar em navegadores de última geração.

## Compatibilidade do navegador
A versão atual do GBA.js funciona nos seguintes navegadores da web:

* Safari 6.0 ou mais recente
* Chrome 22 ou mais recente
* Firefox 25 ou mais recente (lento)

Os seguintes navegadores da web também funcionam, mas terão conjuntos de recursos degradados:

* Firefox 15 ou mais recente (sem som, lento)
* Opera 12.1x ou mais recente (sem som, lento)
* Internet Explorer 10 ou mais recente (sem som, lento, exibição pixelada não funciona)
* Chrome 20, 21 (exibição pixelada não funciona)

Os seguintes navegadores não funcionarão:

* Safari 5.1.x ou mais antigo (sem API de arquivo para carregar jogos em JavaScript)
* Firefox 14 ou mais antigo (sem DataView, usado para memória)
* Internet Explorer 9 ou mais antigo

Todos os outros navegadores não foram testados.

## Compatibilidade de jogos
Consulte a [lista de compatibilidade no wiki do GitHub](https://github.com/endrift/gbajs/wiki/Compatibility-List) para obter uma lista de jogos testados. Observe que o GBA.js é ajustado para jogos comerciais e atualmente não tem um bom suporte para jogos homebrew.

## Lista de recursos
Atualmente, todas as partes do hardware do Game Boy Advance, exceto alguns recursos menos usados ​​e o cabo de link, estão implementados.

O emulador também tem estes recursos:

* Savegames para download e upload
* Capturas de tela
* Pausar a emulação
* Suporte para gamepaks que contêm um relógio em tempo real (por exemplo, Pokemon Ruby e Sapphire)

Recursos que podem ser implementados no futuro incluem:

* Savestates
* Controles remapeáveis
* Suporte para gamepad
* Cabo de link sobre Web Sockets
* Suporte para código de trapaça
* Suporte para tela cheia
* Suporte para gamepaks que têm outros sensores (por exemplo, WarioWare Twisted!, Boktai)

## Licença
Copyright © 2012 – 2013, Jeffrey Pfau
Todos os direitos reservados.

Redistribuição e uso em formas de código-fonte e binário, com ou sem
modificação, são permitidos desde que as seguintes condições sejam atendidas:

* Redistribuições do código-fonte devem manter o aviso de direitos autorais acima, esta
lista de condições e o seguinte aviso legal.

* Redistribuições em formato binário devem reproduzir o aviso de direitos autorais acima,
esta lista de condições e o seguinte aviso de isenção de responsabilidade na documentação
e/ou outros materiais fornecidos com a distribuição.

ESTE SOFTWARE É FORNECIDO PELOS TITULARES DE DIREITOS AUTORAIS E COLABORADORES "NO ESTADO EM QUE SE ENCONTRA"
E QUAISQUER GARANTIAS EXPRESSAS OU IMPLÍCITAS, INCLUINDO, MAS NÃO SE LIMITANDO A,
AS GARANTIAS IMPLÍCITAS DE COMERCIALIZAÇÃO E ADEQUAÇÃO A UM PROPÓSITO ESPECÍFICO
SÃO REJEITADAS. EM NENHUMA HIPÓTESE O TITULAR DOS DIREITOS AUTORAIS OU COLABORADORES SERÃO
RESPONSÁVEIS POR QUAISQUER DANOS DIRETOS, INDIRETOS, INCIDENTAIS, ESPECIAIS, EXEMPLARES OU
CONSEQUENCIAIS (INCLUINDO, MAS NÃO SE LIMITANDO A, AQUISIÇÃO DE
BENS OU SERVIÇOS SUBSTITUTOS; PERDA DE USO, DADOS OU LUCROS; OU INTERRUPÇÃO
DE NEGÓCIOS) INDEPENDENTEMENTE DA CAUSA E EM QUALQUER TEORIA DE RESPONSABILIDADE, SEJA EM
CONTRATO, RESPONSABILIDADE OBJETIVA OU ATO ILÍCITO (INCLUINDO NEGLIGÊNCIA OU OUTRO)
DECORRENTES DE QUALQUER FORMA DO USO DESTE SOFTWARE, MESMO SE AVISADO DA
POSSIBILIDADE DE TAIS DANOS.
