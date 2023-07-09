# relogio-digital-analogico


Esse projeto é um relógio analógico em JavaScript, HTML e CSS, com a exibição da hora atual em formato digital. O relógio analógico é representado visualmente por ponteiros que se movem para indicar as horas, minutos e segundos.

O arquivo HTML (index.html) contém a estrutura básica da página, com a inclusão dos elementos necessários para o relógio. Os ponteiros são representados por elementos <div> com classes específicas (p_s, p_m e p_h). O elemento digital é representado por uma <div> com a classe digital, onde a hora atual será exibida.

O arquivo CSS (style.css) contém as regras de estilo para os elementos do relógio. Ele define a aparência do relógio analógico, os estilos dos ponteiros, a cor de fundo e o alinhamento dos elementos na página.

O arquivo JavaScript (script.js) contém o código responsável por atualizar o relógio. A função updateClock() obtém a hora atual usando o objeto Date() e calcula os ângulos de rotação para os ponteiros dos segundos, minutos e horas. Em seguida, atualiza a exibição digital com a hora formatada. A função fixTime() adiciona um zero à esquerda para garantir que os valores de hora, minuto e segundo sejam sempre exibidos com dois dígitos.

O projeto pode ser clonado e adicionado ao GitHub seguindo estas etapas:

Crie um novo repositório no GitHub.
Clone o repositório para sua máquina local usando o Git.
Copie os arquivos index.html, style.css e script.js para o diretório do seu repositório local.
Execute os comandos do Git para adicionar, commitar e fazer push dos arquivos para o repositório remoto no GitHub.
Agora o projeto está no GitHub e pode ser compartilhado e versionado. Certifique-se de adicionar um arquivo README.md com informações adicionais sobre o projeto, como descrição, instruções de uso e qualquer outra informação relevante.
