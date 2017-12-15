# Acessibilidade
Esta sessão foi construída com base nas principais diretrizes de acessibilidade para ePub. São eles:
  * **WCAG 2.0** (https://www.w3.org/Translations/WCAG20-pt-br/): É o principal documento com orientações e diretrizes sobre acessibilidade na Web.
  * **EPub Accessibility 1.0** (http://www.idpf.org/epub/a11y/): Documento que orienta sobre a acessibilidade direcionada a documentos em formato ePub.
  * **Epub 3 Accessibility Guidelines** (https://idpf.github.io/a11y-guidelines/): Complemento ao documento sobre acessibilidade em ePub com foco no ePub3.
  * **EPUB Accessibility Techniques 1.0** (http://www.idpf.org/epub/a11y/techniques/techniques.html): Documento que aponta as técnicas de acessibilidade para uso em um documento ePub.
  
  Acessibilidade de um documento ePub deve ir de encontro com os níveis de conformidade das WCAG 2.0. Ela deve estar em conformidade com o nível A de conformidade, mas o recomendado é atingir o nível AA.
  
  Os níveis de conformidade do WCAG 2.0 são definidos com base no impacto que as recomendações tem no acesso de pessoas com deficiência e seu grau de dificuldade de implementação. Cada diretriz de acessibilidade tem em sua descrição o nível de conformidade, sendo o nível A o o mais baixo e o nível AAA o mais elevado.
  
  As diretrizes de nível A e AA consideradas para este guia são as seguintes:
  
  1.1.1 Conteúdo Não Textual: Todo o conteúdo não textual que é exibido ao usuário tem uma alternativa textual que serve a um propósito equivalente, exceto para as situações indicadas abaixo. (Nível A)
  1.2.1 Apenas Áudio e apenas Vídeo (Pré-gravado):Para as mídias de apenas áudio | pré-gravados e mídias de vídeo (sem áudio) | pré-gravados as regras seguintes são verdadeiras, exceto quando o áudio ou o vídeo é uma mídia alternativa para o texto e está claramente identificado como tal: (Nível A). 
  1.2.2 Legendas (Pré-gravadas): São fornecidas legendas para todo conteúdo de áudio | pré-gravado em mídia sincronizada, exceto quando a mídia for uma alternativa para texto e for claramente identificada como tal. (Nível A)
  1.2.3 Audiodescrição ou Mídia Alternativa (Pré-gravada): Uma alternativa para mídia com base em tempo ou uma audiodescrição do conteúdo em vídeo | pré-gravado é fornecida para mídia sincronizada, exceto quando a mídia é uma alternativa ao texto e for claramente identificada como tal. (Nível A)
  1.2.4 Legendas (Ao Vivo): São fornecidas legendas para todo o conteúdo do áudio | ao vivo existente em mídia sincronizada. (Nível AA)
  1.2.5 Audiodescrição (Pré-gravada): É fornecida audiodescrição para todo o conteúdo de vídeo | pré-gravado existente em mídia sincronizada. (Nível AA)
  1.3.1 Informações e Relações: As informações, a estrutura e os relacionamentos transmitidos através de apresentação podem ser determinados por meio de código de programação ou estão disponíveis no texto. (Nível A)
  1.3.2 Sequência com Significado: Quando a sequência na qual o conteúdo é apresentado afeta o seu significado, uma sequência de leitura correta pode ser determinada por meio de código de programação. (Nível A)
  1.3.3 Características Sensoriais: As instruções fornecidas para compreender e utilizar o conteúdo não dependem somente das características sensoriais dos componentes, tais como forma, tamanho, localização visual, orientação ou som. (Nível A)
  1.4.1 Utilização de Cores: A cor não é utilizada como o único meio visual de transmitir informações, indicar uma ação, pedir uma resposta ou distinguir um elemento visual. (Nível A)
  1.4.2 Controle de Áudio: Se qualquer áudio em uma página web tocar automaticamente durante mais de 3 segundos, deve estar disponível um mecanismo para fazer uma pausa ou parar o áudio, ou um mecanismo para controlar o volume do áudio, independentemente do nível global de volume do sistema deve disponibilizar. (Nível A)
  1.4.3 Contraste (Mínimo): A apresentação visual de texto e imagens de texto tem uma relação de contraste de, no mínimo, 4.5:1, exceto para o seguinte: (Nível AA)
  1.4.4 Redimensionar texto: Exceto para legendas e imagens de texto, o texto pode ser redimensionado sem tecnologia assistiva até 200 por cento sem perder conteúdo ou funcionalidade. (Nível AA)
  1.4.5 Imagens de Texto: Se as tecnologias que estiverem sendo utilizadas puderem proporcionar a apresentação visual, é utilizado texto para transmitir informações em vez de imagens de texto, exceto para o seguinte: (Nível AA)
  2.1.1 Teclado: Toda a funcionalidade do conteúdo é operável através de uma interface de teclado sem requerer temporizações específicas para digitação individual, exceto quando a função subjacente requer entrada de dados que dependa da cadeia de movimento do usuário e não apenas dos pontos finais. (Nível A)
  2.1.2 Sem Bloqueio do Teclado: Se o foco do teclado puder ser movido para um componente da página utilizando uma interface de teclado, então o foco pode ser retirado desse componente utilizando apenas uma interface de teclado e, se for necessário mais do que as setas do cursor ou tabulação ou outros métodos de saída normalmente utilizados, o usuário deve ser informado sobre o método para retirar o foco. (Nível A)
  2.2.1 Ajustável por Temporização: Para cada limite de tempo definido pelo conteúdo, no mínimo, uma das seguintes afirmações é verdadeira: (Nível A)
  2.2.2 Colocar em Pausa, Parar, Ocultar: Para informações em movimento, em modo intermitente, em deslocamento ou em atualização automática, todas as seguintes afirmações são verdadeiras: (Nível A)
  2.3.1 Três Flashes ou Abaixo do Limite: As páginas web não incluem nenhum conteúdo que pisque mais de três vezes no período de um segundo, ou o flash encontra-se abaixo dos limites de flash universal e flash vermelho. (Nível A)
  2.4.1 Ignorar Blocos: Um mecanismo está disponível para ignorar blocos de conteúdo que são repetidos em várias páginas web. (Nível A)
  2.4.2 Página com Título: As páginas web têm títulos que descrevem o tópico ou a finalidade. (Nível A)
  2.4.3 Ordem do Foco: Se uma página web puder ser navegada de forma sequencial e as sequências de navegação afetarem o significado ou a operação, os componentes que podem ser focados recebem o foco em uma ordem que preserva o significado e a operabilidade. (Nível A)
  2.4.4 Finalidade do Link (Em Contexto): A finalidade de cada link pode ser determinada a partir do link sozinho ou a partir do texto do link em conjunto com seu respectivo contexto do link determinado por meio de código de programação, exceto quando a finalidade do link for ambígua para os usuários em geral. (Nível A)
  2.4.5 Várias Formas: Está disponível mais de uma forma para localizar uma página web em um conjunto de páginas web, exceto quando a Página Web for o resultado, ou uma etapa, de um processo. (Nível AA)
  2.4.6 Cabeçalhos e Rótulos: Os cabeçalhos e os rótulos descrevem o tópico ou a finalidade. (Nível AA)
  2.4.7 Foco Visível: Qualquer interface de usuário operável por teclado dispõe de um modo de operação onde o indicador de foco do teclado está visível. (Nível AA)
3.1.1 Idioma da Página: O idioma humano pré-definido de cada página web pode ser determinado por meio de código de programação. (Nível A)
  3.2.1 Em Foco: Quando qualquer componente recebe o foco, não inicia uma alteração de contexto. (Nível A)
  3.2.2 Em Entrada: Alterar a definição de um componente de interface de usuário não provoca, automaticamente, uma alteração de contexto, a menos que o usuário tenha sido avisado sobre esse comportamento antes de utilizar o componente. (Nível A)
  3.2.3 Navegação Consistente: Os mecanismos de navegação que são repetidos em múltiplas páginas web dentro de um conjunto de páginas web ocorrem na mesma ordem relativa a cada vez que são repetidos, a menos que seja iniciada uma alteração pelo usuário. (Nível AA)
  3.2.4 Identificação Consistente: Os componentes que têm a mesma funcionalidade em um conjunto de páginas web são identificados de forma consistente. (Nível AA)
  3.3.1 Identificação do Erro: Se um erro de entrada for automaticamente detectado, o item que apresenta erro é identificado e o erro é descrito para o usuário em texto. (Nível A)
  3.3.2 Rótulos ou Instruções: Rótulos ou instruções são fornecidos quando o conteúdo exigir a entrada de dados por parte do usuário. (Nível A)
  3.3.3 Sugestão de Erro: Se um erro de entrada for automaticamente detectado e forem conhecidas sugestões de correção, então as sugestões são fornecidas ao usuário, a menos que coloque em risco a segurança ou o propósito do conteúdo. (Nível AA)
  3.3.4 Prevenção de Erros (Legal, Financeiro, Dados): Para páginas web que façam com que ocorram responsabilidades jurídicas ou transações financeiras para o usuário, que modificam ou eliminam dados controláveis pelo usuário em sistemas de armazenamento de dados, ou que enviem respostas de teste do usuário, no mínimo, uma das seguintes afirmações é verdadeira: (Nível AA)
  4.1.1 Análise: No conteúdo implementado utilizando linguagens de marcação, os elementos dispõem de tags completas de início e de fim, os elementos são aninhados de acordo com as respectivas especificações, os elementos não contêm atributos duplicados, e quaisquer IDs são exclusivos, exceto quando as especificações permitem estas características. (Nível A)
  4.1.2 Nome, Função, Valor: Para todos os componentes de interface de usuário (incluindo, mas não se limitando a: elementos de formulário, links e componentes gerados por scripts), o nome e a função podem ser determinados por meio de código de programação; os estados, as propriedades e os valores, que possam ser definidos pelo usuário, podem ser definidos por meio de código de programação; e a notificação sobre alterações destes itens está disponível para os agentes de usuário, incluindo as tecnologias assistivas. (Nível A)
  
