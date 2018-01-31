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





# Diretrizes para a construção de um documento em ePub3

As seguintes orientações foram extraídas e adaptadas do documento ePub3 Accessibility Guidelines (https://idpf.github.io/a11y-guidelines/) produzido pelo IDPF com base nas boas práticas de desenvolvimento de um documento Web, para que seja amigável para um documento ePub e considere as recomendações de acessibilidade do W3C.

**Semântica**
**Ordem lógica de leitura**
O objetivo desta orientação é garantir que a marcação do documento obedeça a ordem lógica de leitura do documento. A ordem lógica recomenda o uso de elementos como <figure> para posicionar imagens com suas legendas e <aside> para conteúdos complementares (não necessariamente apenas laterais).
 
Utilize o elemento <figcaption> para a legenda da figura. Considere que o atributo "alt" tem a função de descrever a imagem para uma pessoa que não consegue enxergar a foto e utiliza leitores de tela para ler o conteúdo. A descrição pode ser feita no elemento <figcaption>. É recomendado que o usuário seja informado que a descrição vem a seguir da imagem, como no exemplo abaixo.
 
```
<figure>
<img src="img01.jpg" alt="Descrição da imagem abaixo"/>
   <figcaption>
      Figura 2.2: Vertebrados são animais que posssuem uma coluna vertebral.
   </figcaption>
</figure>
```
 
 **O atributo epub:type**
 Para fazer ebooks acessíveis é necessário considerar que parte do público vai acessar o conteúdo de uma forma não visual, por isso a ordem lógica de leitura deve ser definida na marcação do código. Para facilitar esse trabalho, o EPUB 3 inclui um novo atributo chamado epub:type, que permite que significados mais precisos sejam aplicados às tags genéricas, um processo chamado inflexão semântica.
 
 O atributo epub:type pode ser utilizado em qualquer elemento HTML:
 
 ```
 <section epub:type="dedication">
   …
<section>
```
 
 O valor "dedication" usado no exemplo acima não é apenas uma string aleatória, mas é um valor previsível que os sistemas de leitura podem esperar encontrar em publicações.
 
Embora, em teoria, qualquer semântica possa ser aplicada a qualquer elemento, apenas uma certa semântica faz sentido usar em qualquer tag. Marcando um elemento <aside>, por exemplo,  como uma nota de rodapé é apropriado, mas marcar uma <section> como nota de rodapé nem tanto. O Vocabulário de Semântica Estrutural lista os elementos comuns que cada semântica destina-se a ser usada em conjunto para facilitar esse processo (embora existam exceções à regra).

Você valor do epub:type não se limita a fazer apenas uma declaração no atributo. É possível fazer a declaração de mais de uma referência, separando cada um deles por espaços:

```
<section epub:type="dedication backmatter">
   …
<section>
```
 
Observe que a ordem da semântica não é importante para seu processamento. Entretanto, incluir mais de uma referência semântica pode afetar o estilo do documento. A seguinte regra CSS corresponde ao elemento <section>:
 
 ```
 section[epub|type='dedication'] {
   …
}
```
Uma vez que uma semântica foi definida, a natureza do elemento influencia todo o conteúdo definido nela. Por exemplo, embora o exemplo anterior tenha anexado a semântica de "backmatter" ao elemento que contém "dedication", todas as seções "backmatter" podem ser agrupadas em uma "backmatter" principal da seguinte maneira:

```
<section epub:type="backmatter">
   <section epub:type="dedication">
      …
   </section>
   <section epub:type="index">
      …
   </section>
   …
<section>
```

# Declarando o namespace do epub

Ao usar o atributo epub:type em um documento de conteúdo, o namespace "epub" deve ser declarado no elemento que contém o atributo ou em um de seus antecessores. O namespace normalmente é declarado uma vez no elemento html, como no exemplo a seguir:

```
<html …
     xmlns:epub="http://www.idpf.org/2007/ops">
   …
   <dl epub:type="glossary">
      …
   </dl>
   …
</html>
```


Semântica simples de um documento ePub

Capa:
```
<body epub:type="cover">
   <img class="cover-img" src="cover.jpg" alt="Cover Image"/>
</body>
```
Prefácio (Preface)
```
<section epub:type="preface">
   …
</section>
```
Prefácio (Foreword)
```
<section epub:type="foreword">
   …
</section>
```
Parte
```
<section epub:type="part">
   …
</section>
```
Capítulo
```
<section epub:type="chapter">
   …
</section>
Footnote and reference
<p>lorum ipsum.<a epub:type="noteref" href="#fn01">1</a></p>
<aside id="fn01" epub:type="footnote">
   …
</aside>
```
Nota e referência
```
<p>lorum ipsum.<a epub:type="noteref" href="#en01">1</a></p>
<aside id="en01" epub:type="rearnote">
   …
</aside>
```
Sessão de notas finais
```
<section epub:type="rearnotes">
   <h1>Endnotes</h1>
   
   <section>
      <h2>Chapter 1</h2>
      <aside id="c01-en01" epub:type="rearnote">
         …
      </aside>
      …
   </section>
   …
</section>
```
Anotação e referência
```
<p>
   …ipsum.<a epub:type="annoref" href="#a01">1</a>
</p>
<aside id="a01" epub:type="annotation">
   …
</aside>
```
Barra Lateral
```
<aside epub:type="sidebar">
   <h3>Killer Bee Migration</h3>
   …
</aside>
```
Glossário
```
<dl epub:type="glossary">
   …
</dl>
```
Bibliografia
```
<section epub:type="bibliography">
   …
</section>
```
Índice
```
<section epub:type="index">
   …
</section>
```

# Separação do markup e estilo
A aparência visual de um ebook é bastante considerada por autores, mas é fundamental considerar os leitores que consumirão sua obra de forma não visual, como usuários de displays braille e leitores de tela. Separar o estilo (CSS) do markup não serve somente para a organização do código. Isso representa o quanto a semântica do código é importante e deve transmitir significado para todos os leitores. 

O uso mais eficaz de criar marcações com estruturas significativas específicas para documentos ePub é utilizando o atributo epub:type, criado especificamente para possibilitar a inflexão semântica. 

Esse atributo pode ser utilizado por seletores de CSS para especificar os elementos que receberão os atributos de customização.

Manter o markup separado do estilo é uma boa prática pois facilita a manutenção do código e possibilitar que o leitor possa manipular o estilo e mudar certos parâmetros conforme sua necessidade (por exemplo uma cor diferente para melhorar o nível de contraste). Assim a atualização em apenas um arquivo CSS refletirá em todos os arquivos HTML do documento ePub. É possível ainda colocar múltiplos arquivos CSS, conforme a necessidade da publicação.

Exemplo: 

O seguinte código CSS fará com que um box seja posicionado na lateral direita do conteúdo:
```
@namespace epub 'http://www.idpf.org/2007/ops'
aside[epub|type~='sidebar'] {
   padding: 0.5em;
   margin-left: 2em;
   width: 25%;
   max-width: 15em;
   background-color: rgb(240,240,240);
   border: solid 1px; rgb(0,0,0);
   float: right;
}
```
Ele será aplicado neste código HTML:
```
<aside epub:type="sidebar">
   <h4>UK Prime Ministers</h4>
   <ol>
   	<li>Sir Robert Walpole</li>
   	…
   </ol>
</aside>
```
Para relacionar o arquivo CSS ao código, utilize o elemento "link" da seguinte forma:
```
<html …>
   <head>
      …
      <link
           rel="stylesheet"
           type="text/css"
           href="css/epub3.css"/>
      …
   </head>
   …
</html>
```
É possível ainda definir estilos para dispositivos com tamanhos de tela diferentes (especialmente para dispositivos móveis):
```
<html …>
   <head>
      …
      <link
           rel="stylesheet"
           type="text/css"
           href="css/epub3.css"
           media="screen"/>
      
      <link
           rel="stylesheet"
           type="text/css"
           href="css/epub3-mobile.css"
           media="screen and (max-width:480px)"/>
      …
   </head>
   …
</html>
```
