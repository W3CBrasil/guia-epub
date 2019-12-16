# Acessibilidade
Esta sessão foi construída com base nas principais diretrizes de acessibilidade para ePub. São eles:
  * **WCAG 2.0** (https://www.w3.org/Translations/WCAG20-pt-br/): É o principal documento com orientações e diretrizes sobre acessibilidade na Web.
  * **EPub Accessibility 1.0** (http://www.idpf.org/epub/a11y/): Documento que orienta sobre a acessibilidade direcionada a documentos em formato ePub.
  * **Epub 3 Accessibility Guidelines** (https://idpf.github.io/a11y-guidelines/): Complemento ao documento sobre acessibilidade em ePub com foco no ePub3.
  * **EPUB Accessibility Techniques 1.0** (http://www.idpf.org/epub/a11y/techniques/techniques.html): Documento que aponta as técnicas de acessibilidade para uso em um documento ePub.
  
  Acessibilidade de um documento ePub deve ir de encontro com os níveis de conformidade das WCAG 2.0. Ela deve estar em conformidade com o nível A de conformidade, mas o recomendado é atingir o nível AA.
  
  Os níveis de conformidade do WCAG 2.0 são definidos com base no impacto que as recomendações tem no acesso de pessoas com deficiência e seu grau de dificuldade de implementação. Cada diretriz de acessibilidade tem em sua descrição o nível de conformidade, sendo o nível A o o mais baixo e o nível AAA o mais elevado.
  
  As diretrizes de nível A e AA consideradas para este guia são as seguintes:
  
[1.1.1 Conteúdo Não Textual](https://www.w3.org/TR/WCAG21/#text-alternatives): Todo o conteúdo não textual que é exibido ao usuário tem uma alternativa textual que serve a um propósito equivalente, exceto para as situações indicadas abaixo. (Nível A)
  
  [1.2.1 Apenas Áudio e apenas Vídeo (Pré-gravado)](https://www.w3.org/TR/WCAG21/#audio-only-and-video-only-prerecorded):Para as mídias de apenas áudio | pré-gravados e mídias de vídeo (sem áudio) | pré-gravados as regras seguintes são verdadeiras, exceto quando o áudio ou o vídeo é uma mídia alternativa para o texto e está claramente identificado como tal: (Nível A). 
  
  [1.2.2 Legendas (Pré-gravadas)](https://www.w3.org/TR/WCAG21/#captions-prerecorded)): São fornecidas legendas para todo conteúdo de áudio | pré-gravado em mídia sincronizada, exceto quando a mídia for uma alternativa para texto e for claramente identificada como tal. (Nível A)
  
  [1.2.3 Audiodescrição ou Mídia Alternativa (Pré-gravada)](https://www.w3.org/TR/WCAG21/#audio-description-or-media-alternative-prerecorded))): Uma alternativa para mídia com base em tempo ou uma audiodescrição do conteúdo em vídeo | pré-gravado é fornecida para mídia sincronizada, exceto quando a mídia é uma alternativa ao texto e for claramente identificada como tal. (Nível A)
  
  [1.2.4 Legendas (Ao Vivo)](https://www.w3.org/TR/WCAG21/#captions-live): São fornecidas legendas para todo o conteúdo do áudio | ao vivo existente em mídia sincronizada. (Nível AA)   
  
  [1.2.5 Audiodescrição (Pré-gravada)](https://www.w3.org/TR/WCAG21/#audio-description-prerecorded): É fornecida audiodescrição para todo o conteúdo de vídeo | pré-gravado existente em mídia sincronizada. (Nível AA)
  
  [1.3.1 Informações e Relações](https://www.w3.org/TR/WCAG21/#info-and-relationships): As informações, a estrutura e os relacionamentos transmitidos através de apresentação podem ser determinados por meio de código de programação ou estão disponíveis no texto. (Nível A)
  
  [1.3.2 Sequência com Significado](https://www.w3.org/TR/WCAG21/#meaningful-sequence): Quando a sequência na qual o conteúdo é apresentado afeta o seu significado, uma sequência de leitura correta pode ser determinada por meio de código de programação. (Nível A)
  
  [1.3.3 Características Sensoriais](https://www.w3.org/TR/WCAG21/#sensory-characteristics): As instruções fornecidas para compreender e utilizar o conteúdo não dependem somente das características sensoriais dos componentes, tais como forma, tamanho, localização visual, orientação ou som. (Nível A)
  
  [1.4.1 Utilização de Cores](https://www.w3.org/TR/WCAG21/#use-of-color): A cor não é utilizada como o único meio visual de transmitir informações, indicar uma ação, pedir uma resposta ou distinguir um elemento visual. (Nível A)
  
  [1.4.2 Controle de Áudio](https://www.w3.org/TR/WCAG21/#audio-control): Se qualquer áudio em uma página web tocar automaticamente durante mais de 3 segundos, deve estar disponível um mecanismo para fazer uma pausa ou parar o áudio, ou um mecanismo para controlar o volume do áudio, independentemente do nível global de volume do sistema deve disponibilizar. (Nível A)
  
  [1.4.3 Contraste (Mínimo)](https://www.w3.org/TR/WCAG21/#contrast-minimum): A apresentação visual de texto e imagens de texto tem uma relação de contraste de, no mínimo, 4.5:1, exceto para o seguinte: (Nível AA)
  
  [1.4.4 Redimensionar texto](https://www.w3.org/TR/WCAG21/#resize-text): Exceto para legendas e imagens de texto, o texto pode ser redimensionado sem tecnologia assistiva até 200 por cento sem perder conteúdo ou funcionalidade. (Nível AA)
  
  [1.4.5 Imagens de Texto](https://www.w3.org/TR/WCAG21/#images-of-text): Se as tecnologias que estiverem sendo utilizadas puderem proporcionar a apresentação visual, é utilizado texto para transmitir informações em vez de imagens de texto, exceto para o seguinte: (Nível AA)
  
  [2.1.1 Teclado](https://www.w3.org/TR/WCAG21/#keyboard): Toda a funcionalidade do conteúdo é operável através de uma interface de teclado sem requerer temporizações específicas para digitação individual, exceto quando a função subjacente requer entrada de dados que dependa da cadeia de movimento do usuário e não apenas dos pontos finais. (Nível A)
  
  [2.1.2 Sem Bloqueio do Teclado](https://www.w3.org/TR/WCAG21/#no-keyboard-trap): Se o foco do teclado puder ser movido para um componente da página utilizando uma interface de teclado, então o foco pode ser retirado desse componente utilizando apenas uma interface de teclado e, se for necessário mais do que as setas do cursor ou tabulação ou outros métodos de saída normalmente utilizados, o usuário deve ser informado sobre o método para retirar o foco. (Nível A)
  
  [2.2.1 Ajustável por Temporização](https://www.w3.org/TR/WCAG21/#timing-adjustable): Para cada limite de tempo definido pelo conteúdo, no mínimo, uma das seguintes afirmações é verdadeira: (Nível A)
  
  [2.2.2 Colocar em Pausa, Parar, Ocultar](https://www.w3.org/TR/WCAG21/#pause-stop-hide): Para informações em movimento, em modo intermitente, em deslocamento ou em atualização automática, todas as seguintes afirmações são verdadeiras: (Nível A)
  
  [2.3.1 Três Flashes ou Abaixo do Limite](https://www.w3.org/TR/WCAG21/#three-flashes-or-below-threshold): As páginas web não incluem nenhum conteúdo que pisque mais de três vezes no período de um segundo, ou o flash encontra-se abaixo dos limites de flash universal e flash vermelho. (Nível A)
  
  [2.4.1 Ignorar Blocos](https://www.w3.org/TR/WCAG21/#bypass-blocks): Um mecanismo está disponível para ignorar blocos de conteúdo que são repetidos em várias páginas web. (Nível A)   
  
  [2.4.2 Página com Título](https://www.w3.org/TR/WCAG21/#page-titled): As páginas web têm títulos que descrevem o tópico ou a finalidade. (Nível A)
  
  [2.4.3 Ordem do Foco](https://www.w3.org/TR/WCAG21/#focus-order): Se uma página web puder ser navegada de forma sequencial e as sequências de navegação afetarem o significado ou a operação, os componentes que podem ser focados recebem o foco em uma ordem que preserva o significado e a operabilidade. (Nível A)
  
  [2.4.4 Finalidade do Link (Em Contexto)](https://www.w3.org/TR/WCAG21/#link-purpose-in-context): A finalidade de cada link pode ser determinada a partir do link sozinho ou a partir do texto do link em conjunto com seu respectivo contexto do link determinado por meio de código de programação, exceto quando a finalidade do link for ambígua para os usuários em geral. (Nível A)
  
  [2.4.5 Várias Formas](https://www.w3.org/TR/WCAG21/#multiple-ways): Está disponível mais de uma forma para localizar uma página web em um conjunto de páginas web, exceto quando a Página Web for o resultado, ou uma etapa, de um processo. (Nível AA)
  
  [2.4.6 Cabeçalhos e Rótulos](https://www.w3.org/TR/WCAG21/#headings-and-labels): Os cabeçalhos e os rótulos descrevem o tópico ou a finalidade. (Nível AA)
  
  [2.4.7 Foco Visível](https://www.w3.org/TR/WCAG21/#focus-visible): Qualquer interface de usuário operável por teclado dispõe de um modo de operação onde o indicador de foco do teclado está visível. (Nível AA)
  
[3.1.1 Idioma da Página](https://www.w3.org/TR/WCAG21/#language-of-page): O idioma humano pré-definido de cada página web pode ser determinado por meio de código de programação. (Nível A)

  [3.2.1 Em Foco](https://www.w3.org/TR/WCAG21/#on-focus): Quando qualquer componente recebe o foco, não inicia uma alteração de contexto. (Nível A)
  
  [3.2.2 Em Entrada](https://www.w3.org/TR/WCAG21/#on-input): Alterar a definição de um componente de interface de usuário não provoca, automaticamente, uma alteração de contexto, a menos que o usuário tenha sido avisado sobre esse comportamento antes de utilizar o componente. (Nível A)
  
  [3.2.3 Navegação Consistente](https://www.w3.org/TR/WCAG21/#consistent-navigation): Os mecanismos de navegação que são repetidos em múltiplas páginas web dentro de um conjunto de páginas web ocorrem na mesma ordem relativa a cada vez que são repetidos, a menos que seja iniciada uma alteração pelo usuário. (Nível AA)
  
  [3.2.4 Identificação Consistente](https://www.w3.org/TR/WCAG21/#consistent-identification): Os componentes que têm a mesma funcionalidade em um conjunto de páginas web são identificados de forma consistente. (Nível AA)
  
  [3.3.1 Identificação do Erro](https://www.w3.org/TR/WCAG21/#error-identification): Se um erro de entrada for automaticamente detectado, o item que apresenta erro é identificado e o erro é descrito para o usuário em texto. (Nível A)
  
  [3.3.2 Rótulos ou Instruções](https://www.w3.org/TR/WCAG21/#labels-or-instructions): Rótulos ou instruções são fornecidos quando o conteúdo exigir a entrada de dados por parte do usuário. (Nível A)
  
  [3.3.3 Sugestão de Erro](https://www.w3.org/TR/WCAG21/#error-suggestion): Se um erro de entrada for automaticamente detectado e forem conhecidas sugestões de correção, então as sugestões são fornecidas ao usuário, a menos que coloque em risco a segurança ou o propósito do conteúdo. (Nível AA)
  
  [3.3.4 Prevenção de Erros (Legal, Financeiro, Dados)](https://www.w3.org/TR/WCAG21/#error-prevention-legal-financial-data): Para páginas web que façam com que ocorram responsabilidades jurídicas ou transações financeiras para o usuário, que modificam ou eliminam dados controláveis pelo usuário em sistemas de armazenamento de dados, ou que enviem respostas de teste do usuário, no mínimo, uma das seguintes afirmações é verdadeira: (Nível AA)
  
  [4.1.1 Análise](https://www.w3.org/TR/WCAG21/#parsing): No conteúdo implementado utilizando linguagens de marcação, os elementos dispõem de tags completas de início e de fim, os elementos são aninhados de acordo com as respectivas especificações, os elementos não contêm atributos duplicados, e quaisquer IDs são exclusivos, exceto quando as especificações permitem estas características. (Nível A)
  
  [4.1.2 Nome, Função, Valor](https://www.w3.org/TR/WCAG21/#name-role-value): Para todos os componentes de interface de usuário (incluindo, mas não se limitando a: elementos de formulário, links e componentes gerados por scripts), o nome e a função podem ser determinados por meio de código de programação; os estados, as propriedades e os valores, que possam ser definidos pelo usuário, podem ser definidos por meio de código de programação; e a notificação sobre alterações destes itens está disponível para os agentes de usuário, incluindo as tecnologias assistivas. (Nível A)  





# Diretrizes para a construção de um documento em ePub3

As seguintes orientações foram extraídas e adaptadas do documento ePub3 Accessibility Guidelines (https://idpf.github.io/a11y-guidelines/) produzido pelo IDPF com base nas boas práticas de desenvolvimento de um documento Web, para que seja amigável para um documento ePub e considere as recomendações de acessibilidade do W3C.

## Ordem lógica de leitura
O objetivo desta orientação é garantir que a marcação do documento obedeça a ordem lógica de leitura do documento. A ordem lógica recomenda o uso de elementos como ```<figure>``` para posicionar imagens com suas legendas e ```<aside>``` para conteúdos complementares (não necessariamente apenas laterais).
 
Utilize o elemento ```<figcaption>``` para a legenda da figura. Considere que o atributo ```alt``` tem a função de descrever a imagem para uma pessoa que não consegue enxergar a foto e utiliza leitores de tela para ler o conteúdo. A descrição pode ser feita no elemento ```<figcaption>```. É recomendado que o usuário seja informado que a descrição vem a seguir da imagem, como no exemplo abaixo.
 
```
<figure>
<img src="img01.jpg" alt="Descrição da imagem abaixo"/>
   <figcaption>
      Figura 2.2: Vertebrados são animais que posssuem uma coluna vertebral.
   </figcaption>
</figure>
```
 Referências e padrões de conformidade
* EPUB 3 — [O atributo ```epub:type```](http://idpf.org/epub3/latest/contentdocs#sec-xhtml-content-type-attribute)
* WCAG 2.0 — [H88: Utilizar HTML conforme a especificação](http://www.w3.org/TR/WCAG20-TECHS/H88.html)
 
## O atributo epub:type
 Para fazer ebooks acessíveis é necessário considerar que parte do público vai acessar o conteúdo de uma forma não visual, por isso a ordem lógica de leitura deve ser definida na marcação do código. Para facilitar esse trabalho, o EPUB 3 inclui um novo atributo chamado ```epub:type```, que permite que significados mais precisos sejam aplicados às tags genéricas, um processo chamado inflexão semântica.
 
 O atributo epub:type pode ser utilizado em qualquer elemento HTML:
 
 ```
 <section epub:type="dedication">
   …
<section>
```
 
 O valor ```dedication``` usado no exemplo acima não é apenas uma string aleatória, mas é um valor previsível que os sistemas de leitura podem esperar encontrar em publicações.
 
Embora, em teoria, qualquer semântica possa ser aplicada a qualquer elemento, apenas uma certa semântica faz sentido usar em qualquer tag. Marcando um elemento ```<aside>```, por exemplo,  como uma nota de rodapé é apropriado, mas marcar uma ```<section>``` como nota de rodapé nem tanto. O Vocabulário de Semântica Estrutural lista os elementos comuns que cada semântica destina-se a ser usada em conjunto para facilitar esse processo (embora existam exceções à regra).

Você valor do ```epub:type``` não se limita a fazer apenas uma declaração no atributo. É possível fazer a declaração de mais de uma referência, separando cada um deles por espaços:

```
<section epub:type="dedication backmatter">
   …
<section>
```
 
Observe que a ordem da semântica não é importante para seu processamento. Entretanto, incluir mais de uma referência semântica pode afetar o estilo do documento. A seguinte regra CSS corresponde ao elemento ```<section>```:
 
 ```
 section[epub|type='dedication'] {
   …
}
```
Uma vez que uma semântica foi definida, a natureza do elemento influencia todo o conteúdo definido nela. Por exemplo, embora o exemplo anterior tenha anexado a semântica de ```backmatter``` ao elemento que contém ```dedication```, todas as seções ```backmatter``` podem ser agrupadas em uma ```backmatter``` principal da seguinte maneira:

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

## Declarando o namespace do epub

Ao usar o atributo ```epub:type``` em um documento de conteúdo, o namespace ```epub``` deve ser declarado no elemento que contém o atributo ou em um de seus antecessores. O namespace normalmente é declarado uma vez no elemento ```<html>```, como no exemplo a seguir:

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

## Separação do markup e estilo
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
Para relacionar o arquivo CSS ao código, utilize o elemento ```link``` da seguinte forma:
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
## Idioma do documento
Especificar o idioma padrão de um documento - bem como quaisquer alterações no documento, como instâncias de termos de idioma estrangeiro, diálogo ou passagens em outro idioma - ajuda a garantir que as tecnologias de suporte possam renderizar corretamente o texto (por exemplo, para que os caracteres de braille corretos sejam apresentados, ou que uma voz seja capaz de renderizar o idioma usado).

Para definir o idioma padrão para um documento XHTML, os atributos ```lang``` e ```xml:lang``` language devem ser inseridos no elemento html de conteúdo. O código de idioma definido nesses atributos deve coincidir com um dos códigos de idioma especificados em um elemento dc:lang na seção de metadados do documento do pacote.

Quando anexado a elementos dentro do elemento ```<body>```, os atributos identificam o idioma do conteúdo de texto desse elemento (para identificar uma mudança de idioma).

```
<html … lang="en" xml:lang="en">
   …
   <body>
      …
      <p>
         Harsh gargoyle face that warred against me 
         over our mess of hash of lights in 
         <span xml:lang="fr" lang="fr">rue 
         Saint-André-des-Arts</span>. In words of
         words for words, palabras. Oisin with
         Patrick. Faunman he met in Clamart woods,
         brandishing a winebottle.
         <i xml:lang="fr" lang="fr">C'est 
         vendredi saint!</i> Murthering Irish.
         His image, wandering, he met. I mine. I 
         met a fool i'the forest.
      </p>
      …
   </body>
</html>
```
## Número de páginas

Se um ebook for produzido a partir do mesmo fluxo de trabalho que um documento impresso, os marcadores de paginação de impressão devem ser mantidos no documento. Esses marcadores beneficiam os leitores em ambientes mistos de impressão/digital, como uma sala de aula, pois os números de página permitem um ponto de referência comum entre as duas edições.

Os locais de quebra de página podem ser adicionados à marcação usando tags ```span``` e ```div``` com um atributo de tipo ```epub:type``` para o valor do número da página.

```
<p>
   …
   <span
         epub:type="pagebreak"
         id="page24"
         title="24"/>
   …
</p>
```


Quando incluir as referências da página de impressão, os metadados do documento do pacote também devem incluir um elemento ```dc:source``` que identifica a fonte de impressão.

```
<package…>
   …
   <metadata
      xmlns:dc="http://purl.org/dc/elements/1.1/">
      …
      <dc:source id="src-id">
         urn:isbn:9780375704024
      </dc:source>
   </metadata>
</package>
```

## Quadros em linha (iframe)

Os quadros em linha (iframe) geralmente se integram bem com as tecnologias assistivas, mas as seguintes considerações de acessibilidade sempre devem ser respeitadas ao usá-las:

* Cada ```iframe``` deve incluir um título explicativo que indique claramente a finalidade do conteúdo incorporado (em um atributo de ```title``` no elemento ```<iframe>```).
* Ao definir a altura e a largura do ```iframe``` utilize unidades relativas, como porcentagem ou ems, a fim de facilitar o redimensionamento.
* O deslocamento deve ser definido como automático para que ele ainda possa ser acessado se for maior do que o espaço disponível (especialmente se o usuário redimensionar o conteúdo do ```iframe```).
* O elemento ```iframe``` deve fornecer conteúdo embutido para sistemas de leitura que não suportem ```iframe``` (por exemplo, um link direto para o arquivo de conteúdo).
* Se o quadro não contiver conteúdo para o leitor, indique como vazio no atributo ```title```, defina sua propriedade de exibição de CSS como ```display:none```, e altura e largura em 0. Para garantir que os leitores não possam ser tabulados no elemento, defina o atributo ```tabindex``` para ```-1``` .

Exemplo de ```iframe``` acessível
```
<iframe
        href="quiz01.xhtml"
        title="Quiz 1"
        class="quiz">
   Your reading system does not support
   inline frames. Please follow <a 
   href="quiz01.xhtml">this link</a> 
   to open the associated content document.
</iframe>
```
Exemplo de ```iframe``` invisível
```
<iframe
        href="script.xhtml"
        title="empty"
        tabindex="-1"
        height="0"
        width="0"
        class="hidden">
</iframe>
```
## Negrito e itálico

Textos em negrito e itálico são freqüentemente usados para meros elementos de estilo, mas eles carregam vários tipos de informações pertinentes ao texto: pontos de ênfase, mudanças de tom ou localização, nomes especiais, etc. A não ser que a marcação semântica correta seja usada para aplicar esta formatação, no entanto, a mesma informação não pode ser transmitida para leitores não visuais.

A lista abaixo descreve como aplicar os vários métodos em HTML5 e CSS para negrito e itálico:

* **```<em>```**:  
O elemento ```em``` indica que o texto deve ser estressado verbalmente.
* **```<strong>```**:  
O elemento ```strong``` indica importância, como quando faz declarações imperativas ou usa palavras-sinal como 'aviso' e 'alerta'.
* **```<i>```**:  
O elemento ```i``` é usado quando o uso de itálico indica uma mudança de tom ou voz. Um exemplo fornecido na especificação HTML5 é uma seqüência de sonhos estendidos, mas poderia ser qualquer divergência semelhante da narrativa principal em pensamento ou lembrança. O elemento ```i``` também é usado sempre que há significância semântica por trás da ênfase (por exemplo, as palavras em itálico indicam um termo técnico, palavras estrangeiras, etc.).
* **```<b>```**:  
O elemento ```b``` é usado sempre que o negrito transmite significado semântico, semelhante ao uso de ```i``` para marcação semântica (por exemplo, palavras-chave).
* **```font-style: itálico e font-weight: bold ```**:  
As propriedades CSS para negrito e itálico devem ser usadas sempre que o uso de negrito e itálico é de apresentação (por exemplo, em títulos e palavras-chave). A formatação CSS não possui semântica, portanto a ênfase não será notada por tecnologias assistivas.

Exemplo de uso do elemento ```<em>``` para estressar a vocalização
```
<p>
   … There was nothing so <em>very</em> remarkable
   in that; nor did Alice think it so <em>very</em>
   much out of the way to hear the Rabbit say to
   itself, <q>Oh dear! Oh dear! I shall be 
   late!</q> …
</p>
<p>
   … 'Really this is what is meant by the Fourth
   Dimension, though some people who talk about the 
   Fourth Dimension do not know they mean it. It is 
   only another way of looking at Time. <em>There 
   is no difference between Time and any of the 
   three dimensions of Space except that our 
   consciousness moves along it</em>. …
</p>
```
Exemplo de uso do elemento ```<strong>``` para indicar importância
```
<p>
   <strong>Warning</strong>, all features should 
   be considered unstable …
</p>
<p>
   <strong>Do not feed the bears!</strong> 
</p>
```
Exemplo de uso do elemento ```<i>``` para indicar termos em latim
```
<p>
   When hybrids are able to breed <i>inter se</i>, 
   they transmit …
</p>
<p>
   Among the sea-shells, the most abundant was the 
   <i>Patella deaurat</i> …
   ```
   
</p>

## Hiperlinks
O uso de hiperlinks em um ebook deve ser considerado cuidadosamente para evitar que seu uso atrapalhe a experiência de leitura do usuário.

A navegação por tecnologia assistiva vai fazer foco em cada um dos links, o que pode causar dificuldade para o usuário navegar pela publicação. Outro problema do seu uso excessivo é que leitores de tela costumam ler o termo "link" antes da palavra marcada para informar o usuário. Esse tipo de interrupção na leitura pode atrapalhar a experiência de leitura do usuário.

Remover links redundantes e fazer uso de forma consciente é a melhor recomendação para seu uso em um ebook. 

É importante também garantir que o usuário consiga perceber e distinguir links do restante do texto. Remover o sublinhado não é proibido, mas recomenda-se que exista um contraste adequado e diferença na forma de exibição, seja ele sublinhado, em caixa ou de outra forma que diferencie um link do restante do texto.

Exemplo de um hiperlink:
```
<a href="…">Espeficicação de um ePub</a>
```
Exemplo de link em negrito (especificado no CSS):
```
a {
	text-decoration: underline;
	font-weight: bolder;
	color: rgb(51,102,204);
}
```

## Trabalhos publicados
Ao incluir uma lista de trabalhos adicionais de um autor (por exemplo, na página de título da série), use listas ordenadas ```<ol>``` ou não ordenadas ```<ul>``` para detalhar as entradas.

Se a lista de trabalhos transmitir informações que se perderiam se reordenadas (por exemplo, uma listagem cronológica por data de publicação), use uma lista ordenada. Se a ordem dos títulos não tiver qualquer significado particular (por exemplo, alfabética), use uma lista desordenada.

Exemplo de uma lista simples de trabalhos publicados
```
<html …
      epub:prefix="daisy:
      http://www.daisy.org/z3998/2012/vocab/structure/">
   …
   <section epub:type="daisy:published-works">
      <h2>Also by the author</h2>
      <ul class="works">
         <li>The Tempest</li>
         <li>Henry IV, Part 2</li>
         <li>King Lear</li>
      </ul>
   </section>
```
Exemplo de uma lista complexa de trabalhos publicados
```
<html …
      epub:prefix="daisy:
      http://www.daisy.org/z3998/2012/vocab/structure/">
   …
   <section epub:type="daisy:published-works">
      <h2>Also by the author</h2>
         
      <section>
         <h3>Comedies</h3>
         <ul>
            <li>The Tempest</li>
         </ul>
      </section>
         
      <section>
         <h3>Histories</h3>
         <ul>
            <li>Henry IV, Part 2</li>
         </ul>
      </section>
         
      <section>
         <h3>Tragedies</h3>
         <ul>
            <li>King Lear</li>
         </ul>
      </section>
   </section>
   …
</html>
```
## Índice
Embora o documento de navegação do EPUB forneça recursos de navegação para a publicação como um todo, a incorporação de índices dentro do corpo pode facilitar ainda mais a compreensão e a navegação.

Se você incorporar outras tabelas de conteúdo no corpo da sua publicação, tente construí-las da mesma maneira que o documento de navegação - usando o elemento ```<nav>``` e as listas ordenadas ```<ol>```. As listas simplificam o acesso, pois as tecnologias assistivas geralmente fornecem atalhos de teclado para movê-los de forma mais eficaz.

Exemplo de reutilização da navegação do índice no elemento ```<spine>```
```
<package …>
   …
   <manifest>
      …
      <item id="htmltoc"
      	    properties="nav"
      	    media-type="application/xhtml+xml"
      	    href="bk01-toc.xhtml"/>
      …
   </manifest>
   …
   <spine>
      …
      <itemref idref="htmltoc" linear="yes"/>
      …
   </spine>
</manifest>
```

Exemplo de inserção de um índice no corpo da publicação
```
<section epub:type="toc">
   <h1>Table of Contents</h1>
   <nav id="pub-toc">
      <ol class="toc">
         <li>
            <a href="ch01.xhtml">1. Introduction</a>
         </li>
         <li>
            <a href="ch02.xhtml">2. Building a 
               Better EPUB: Fundamental
               Accessibility</a>
         </li>
         <li>
            <a href="ch03.xhtml">3. It’s Alive:
               Rich Content Accessibility</a>
         </li>
         <li>
            <a href="ch04.xhtml">4. Conclusion</a>
         </li>
      </ol>
   </nav>
</section>
```
Exemplo de um mini índice no início de uma sessão
```
<section>
   <header>
      <h2>
         3. It’s Alive: Rich Content Accessibility
      </h3>
      <nav id="ch3-toc">
         <ol>
            <li>
               <a href="#s01">The Sound and 
               the Fury: Audio and Video</a>
            </li>
            <li>
               <a href="#s02">Talk to Me: 
               Media Overlays</a>
            </li>
            <li>
               <a href="#s03">Tell It Like 
               It Is: Text-to-Speech (TTS)</a>
            </li>
            <li>
               <a href="#s04">The Coded Word:
               Scripted Interactivity</a>
            </li>
            <li>
               <a href="#s05">A Little Help:
               WAI-ARIA</a>
            </li>
            <li>
               <a href="#s06">A Blank Slate:
               Canvas</a>
            </li>
         </ol>
      </nav>
   </header>
   …
</section>
```

## Listas de ilustrações
Para facilitar a navegação do conteúdo, as publicações devem incluir uma lista para todas as ilustrações que eles contêm. Sem esses links rápidos, muitas vezes não há um caminho fácil para os leitores localizarem as ilustrações novamente. Se esse recurso não está disponível os leitores devem navegar pelo conteúdo do livro até chegarem ao local.

O documento de navegação EPUB pode ser usado para fornecer esta funcionalidade. Uma lista de ilustrações pode ser definida do mesmo modo que o índice, mas usando um elemento de navegação com um atributo de tipo ```epub:type``` com o valor ```loi``` (veja o Exemplo 1). O ```loi nav``` deve conter apenas uma única lista ordenada de entradas, com cada entrada ligando a uma figura ou ilustrações.

Observe que, embora este tipo de auxílio de navegação não seja formalmente definido na especificação do EPUB, os documentos de navegação foram extensíveis para esse fim. Ao criar uma ```loi nav```, você também deve incorporar o documento de navegação como conteúdo dentro da publicação, já que sistemas de leitura podem não fornecer acesso especializado a ele.

Exemplo de uma lista de ilustrações
```
<nav epub:type="loi">
   <h2>List of Illustrations</h2>
   <ol>
      <li>
         <a href="ch01.html#fig01">Figure 1.1</a>
      </li>
      <li>
         <a href="ch01.html#fig02">Figure 1.2</a>
      </li>
      …
   </ol>
</nav>
```
Referenciando imagens por marcas na navegação
O ```landmarks nav``` pode referenciar elementos no mesmo arquivousando um atributo ```href``` que faz referência ao ```ID``` da lista:
```
<nav epub:type="loi" id="illustrations">
   …
</nav>
<nav epub:type="landmarks">
   …
   <li>
      <a href="#illustrations" epub:type="loi">List of 
      Illustrations</a>
   </li>
   …
</nav>
```
## Listas de tabelas
Para facilitar a navegação do conteúdo, as publicações devem incluir uma lista para todas as tabelas que eles contêm. Sem esses links rápidos, geralmente não há um caminho fácil para os leitores localizarem as tabelas novamente. Eles têm que navegar pelo conteúdo do livro até chegarem ao local.

A lista de tabelas segue a mesma orientação utilizada para criar a lista de imagens.

Exemplo de uma lista de tabelas
```
<nav epub:type="lot">
   <h2>List of Tables</h2>
   <ol>
      <li><a href="ch01.html#tbl01">Table 1</a></li>
      <li><a href="ch01.html#tbl02">Table 2</a></li>
      …
   </ol>
</nav>
```
Referenciando tabelas por marcas na navegação
O ```landmarks nav``` pode referenciar elementos no mesmo arquivousando um atributo ```href``` que faz referência ao ```ID``` da lista:
```
<nav epub:type="lot" id="tables">
   …
</nav>
<nav epub:type="landmarks">
   …
   <li>
      <a href="#tables" epub:type="lot">List of
      Tables</a>
   </li>
   …
</nav>
```
## Seções
O elemento ```<section>``` é usado para encapsular seções de conteúdo primário e estabelecer a hierarquia estrutural da publicação. Claramente, agrupar e identificar conteúdos permite uma melhor navegação por parte de qualquer pessoa que lê usando uma tecnologia assistiva.

Um atributo ```epub:type``` deve ser inserido em cada seção para indicar a natureza específica do conteúdo, quando aplicável. Veja o [Vocabulário de semântica estrutural EPUB3](https://idpf.github.io/epub-vocabs/structure/) para a lista de valores permitidos que podem ser usados com o atributo.

Quando o atributo epub:type não é especificado, uma natureza genérica de seção/subseção é assumida com base no nível de aninhamento.

Uma seção não deve ter mais de um título.

Se uma seção não tiver um título, considere incluir um atributo de ```aria-label``` na seção para identificar seu objetivo.
Exemplo de sessão definida por cabeçalhos
```
<section epub:type="chapter" id="c01">
   <h1 id="c01h01">Chapter 1. Loomings.</h1>
   <p>Call me Ishmael. … </p>
   …
</section>
```
Exemplo de sessão definida por atributos
Atributo title
```
<section epub:type="chapter" title="chapter" id="c01">
   <p>It was a dark and stormy night … </p>
   …
</section>
```
Atributo aria-label
```
<section epub:type="chapter" aria-label="chapter" id="c01">
   <p>It was a dark and stormy night … </p>
   …
</section>
```
No caso de sessões mais complexas ou que necessitam ser separadas, a hierarquia de cabeçalhos deve ser seguida.
```
<body>
   <section epub:type="part">
      <h1>Part I</h1>
      <section epub:type="chapter">
         <h2>Chapter I</h2>
      </section
   </section>
</body>
```
## Cabeçalhos
Os cabeçalhos continuam a ser um dos principais meios de navegação para usuários de tecnologia assistiva.

Cada seção deve ter um título numerado (por exemplo, ```<h1>```) que reflete seu nível na hierarquia de documentos, pois os títulos numerados permitem que tecnologias assistivas, independentemente do suporte para HTML5, navegem na estrutura do documento.

Cada elemento de cabeçalho deve representar um único cabeçalho. Não quebre um cabeçalho em tags separadas para formatação visual. Se você precisa incluir subtítulos, incorporá-los no título principal ou incluí-los em um parágrafo subseqüente, use uma tag de cabeçalho para encapsular o título completo (o Exemplo 2 mostra ambos os exemplos de uso).

Se uma seção de texto não tiver um título, inclua um título em um atributo de ```aria-label``` no elemento envolvente. As tecnologias assistivas anunciarão este rótulo e alertarão os usuários de que uma nova seção está começando.

> **Nota:**
> Não use elementos de cabeçalho dentro da ```<figure>```, ```<blockquote>``` e outros elementos raiz de seção HTML5. Embora esses recursos possam ter cabeçalhos, o uso de elementos de cabeçalho forçará os usuários a navegar por eles para encontrar a próxima seção.

Evite utilizar múltiplos ```<h1>``` na ublicação. Sistemas de leitura e tecnologias assistivas não suportam o algoritmo de estrutura de tópicos definido em HTML5. Se você usa um título ```<h1>``` para cada seção, todos aparecerão como títulos de nível superior para um usuário, impedindo sua capacidade de navegar.

Exemplo de cabeçalhos numerados
```
<section epub:type="division">
  <h1>Book One: 1805</h1>
      <section epub:type="chapter">
         <h2>Chapter 1</h2>
```
Exemplo de cabeçalhos e subtítulos
```
<section epub:type="chapter">
   <h1><span epub:type="title">ORIGIN OF THE WORLD.—FIRST DYNASTY.</span>
   <span epub:type="subtitle">URANUS AND GÆA. (Cœlus and Terra.)</span></h1>
```
Utilizando o elemento ```<header>```
```
<section epub:type="chapter">
   <header>
      <h1>ORIGIN OF THE WORLD.—FIRST DYNASTY.</h1>
      <p epub:type="subtitle">URANUS AND GÆA. (Cœlus and Terra.)</p>
   </header>
```
Sessões sem cabeçalhos
Utilizando o atributo ```title``` 
```
<section epub:type="preamble" title="preamble">
   <p>
      How these papers have been placed in sequence 
      will be made manifest in the reading of them.
      …
   </p>
</section>
```
Utilizando o atributo ```aria-label``` 
```
<section epub:type="preamble" aria-label="preamble">
```

> ## Tabelas
> Fazer a revisão do documento https://idpf.github.io/a11y-guidelines/content/xhtml/tables.html

## Listas
As listas são muitas vezes ignoradas como um recurso de acessibilidade, mas a capacidade de se mover de forma rápida e eficaz através de longas listas é uma necessidade chave de leitura. 

Para facilitar a navegação das listas, marque sempre os itens no conjunto usando o elemento de lista ordenada ```<ol>``` ou não ordenado ```<ul>``` apropriada. Não use elementos ```<br>``` para exibir itens visualmente em linhas separadas ou use técnicas de estilo para configurar a aparência visual de uma lista, pois impedirá a navegação.

Usar o tipo de lista correta também é importante, pois pode ser a única orientação para o leitor se a ordem dos itens é significativa. 

O elemento da lista de definições ```<dl>``` serve para listas de nomes/valores. Estes podem incluir dicionários, glossários, perguntas frequentes e similares. O elemento não deve ser usado para diálogo de personagens, conforme observado na especificação HTML5. Repetir nomes de personagens em elementos ```<dt>```, puramente para indicar quem está falando, quebra esta semântica. Embora a formatação automática que acompanha o tipo de lista pode caber em certos formatos, como peças, cada elemento ```<dt>``` deve definir um valor exclusivo.

Os elementos da lista não devem ser usados para propósitos puramente de apresentação (por exemplo, usando listas ```<dl>``` para fazer cabeçalhos em negrito com parágrafos recuados).

Exemplo de lista desordenada
```
<ul>
   <li>Credit, consumer, 164</li>
   <li>Cross-functional contact, 10-11</li>
   <li>Culture
      <ul>
         <li>buyer behavior and, 85</li>
         <li>defined, 85, 98, 118</li>
         …
      </ul>
   </li>
   …
</ul>
```
Exemplo de uma lista de definição
```
<dl>
   <dt><def>Exchange function</def></dt>
   <dd>
      Sales of the product to the various members 
      of the channel of distribution.
   </dd>
   <dt><def>Physical distribution function</def></dt>
   <dd>
      Moves the product through the exchange 
      channel, along with title and ownership.
   </dd>
   <dt><def>Marketing channel</def></dt>
   <dd>
      Sets of independent organizations involved
      in the process of making a product or 
      service available for use or consumption 
      as well as providing a payment mechanism 
      for the provider.
   </dd>
   …
</dl>
```
Referências e padrões de conformidade
* HTML5 — [O elemento ```<ol>```](http://www.w3.org/TR/html5/grouping-content.html#the-ol-element)
* HTML5 — [O elemento  ```<ul>```](http://www.w3.org/TR/html5/grouping-content.html#the-ul-element)
* HTML5 — [O elemento ```<dl>```](http://www.w3.org/TR/html5/grouping-content.html#the-dl-element)
* WCAG 2.0 — [H40: Utilizando listas de definição](http://www.w3.org/TR/WCAG20-TECHS/H40.html)
* WCAG 2.0 — [H48: Utilizando ```<ol>```, ```<ul>``` e ```<dl>``` para listas ou grupo de links](http://www.w3.org/TR/WCAG20-TECHS/H48.html)

## Descrições
Há muitas razões pelas quais a descrição do conteúdo aumenta sua acessibilidade para todos os leitores. Embora muitas vezes se considere útil apenas para leitores não visuais, as descrições facilitam a compreensão e fornecem contexto para os leitores com uma ampla gama de necessidades. 

Os hiperlinks simples são a maneira mais acessível de fornecer um link para uma descrição.
```
<figura>
    <img src = "crime-map.jpg" alt = "Crime em Gotham City">
    <a href="crime-desc.xhtml"> Descrição </a>
</ figura>
```
A vantagem principal dos hiperlinks é que eles estão expostos a todos os usuários, ao contrário do atributo ```aria-describedby``` descrito na próxima seção. A principal desvantagem é que eles são sempre visíveis, e os editores geralmente são impedidos de adicionar qualquer conteúdo visível por seus acordos com os autores.

Observe que um hiperlink nem sempre precisa fazer referência a uma descrição em outro documento. As descrições podem ser incluídas no final de uma seção, como notas de rodapé.

O atributo ```aria-describedby```  pode ser usado para adicionar uma descrição a qualquer elemento HTML5, não apenas ```<img>```. Esse atributo não é bem suportado e pode não é útil para descrições de imagens complexas, pois o texto que ele faz referência é resumido a uma seqüência de texto simples.

Referências e padrões de conformidade
* WAI - [WAI-ARIA 1.0 - ```aria-describedby```](http://www.w3.org/TR/wai-aria/states_and_properties#aria-describedby)

## Figuras
O elemento ```<figure>``` do HTML5 permite que uma tecnologia assistiva ignore o conteúdo secundário, permitindo que os leitores continuem a ler a narrativa primária ininterrupta. Como as figuras são intercaladas dentro do corpo, como em elementos ```<aside>```, o leitor seria constantemente interrompido nos pontos em que elas ocorressem.

O elemento ```<figure>``` pode ser usado para encapsular imagens, tabelas, fragmentos de código e outros conteúdos com uma legenda relacionada, descrição e/ou elementos de conteúdo associados. O elemento só deve ser usado para conteúdo secundário que pode ser lido separadamente da narrativa principal.

Ser capaz de determinar programaticamente a legenda de uma figura é outra característica útil introduzida no HTML5. Como as legendas são freqüentemente colocadas sob o conteúdo da figura, os leitores no passado muitas vezes não tiveram contexto para a figura até chegar ao texto descritivo que seguiu a imagem ou a tabela.

O elemento ```<figcaption>``` agora pode ser usado para marcar a legenda. Esse elemento deve ser o primeiro ou o último na figura a ser válido para a definição HTML5.

Exemplo de imagem com legenda e descrição
```
<figure>
   <img src="images/blob.jpeg" alt="the blob"
           aria-describedby="img01-desc"/>
   <figcaption>
      Figure 3.7 — The blob is digesting Steve 
      McQueen in this unreleased ending to the 
      classic movie.
      <aside class="hidden id="img01-desc">
         <p>
            In the photo, Steve McQueen can be seen
            floating within the gelatinous body of 
            the blob as it moves down the main
            street …
         </p>
      </aside>
   </figcaption>
</figure>
```
Exemplo de imagem com descrição em link
```
<figure>
   <p><a href="blob-desc.xhtml">Description</a></p>
   <img src="images/blob.jpeg" alt="the blob"/>
   <figcaption>
      Figure 3.7 — The blob is digesting Steve 
      McQueen in this unreleased ending to the 
      classic movie.
   </figcaption>
</figure>
```
Tabela com descrição utilizando ```<figcaption>```
Note that the table caption element should not be used when a table is included in a figure. Including both a figcaption and caption will cause both to be rendered.
```
<figure>
   <figcaption>
      Characteristics with positive and 
      negative sides.
      <aside class="hidden" id="tbl01-summary">
         <p>Summary</p>
         <p>
            Characteristics are given 
            in the second column…
         </p>
      </aside>
   </figcaption>
   <table aria-describedby="tbl01-summary">
      …
   </table>
</figure>
```
Referências e padrões de conformidade
* HTML5 — [O elemento ```<figure>```](http://www.w3.org/TR/html5/grouping-content.html#the-figure-element)
* HTML5 — [O elemento ```<figcaption>```](http://www.w3.org/TR/html5/grouping-content.html#the-figcaption-element)
* WCAG 2.0 — [G73: Forneça uma descrição linga em outro local com um link para ele próximo ao conteúdo não textual](http://www.w3.org/TR/WCAG20-TECHS/G73.html)

## Imagens
Imagens que são fundamentais para a compreensão de uma publicação devem incluir sempre uma alternativa de texto em seu atributo alt. No caso de imagens complexas, uma descrição detalhada também deve ser adicionada.

Se a imagem for puramente decorativa, o atributo ```alt``` deve ficar vazio. Para melhorar, a acessibilidade, um atributo de ARIA ```role``` com o valor ```presentation``` também deve ser anexado.

> **Nota**:
> Se uma imagem é importante para a publicação, mas não é obrigatória para ser lida no ponto de inserção (ou seja, não é parte da ordem de leitura lógica), use o elemento ```<figure>``` para anexá-la.

Exemplo de imagem simples significativa (não é necessária nenhuma descrição)
```
<img
     src="covers/9781449328030_lrg.jpg"
     alt="First Edition" />
```

Exemplo de imagem complexa significativa (descrição é necessária)
```
<figure>
   <img
        id="fig01"
        src="graphics/water-cycle.jpg"
        aria-describedby="water-cycle-desc"
        alt="The hydrologic cycle, showing the 
          circular nature of the process as water 
          evaporates from a body of water and 
          eventually returns to it"/>
   <figcaption>
      The hydrologic cycle
      <a href="#water-cycle-desc">
         <img src="images/desc.gif"
             alt="Click for description"/>
      </a>
   </figcaption>
</figure>
…
<aside id="water-cycle-desc">
   <p>
      Figure 1 - The diagram shows the processes
      of evaporation, condensation, 
      evapotranspiration, water storage 
      in ice and snow, and precipitation. 
      A large body of water …
   </p>
   <p><a role="doc-backlink" href="#fig01">
      <img src="#fig01" alt="Return to figure"/>
      </a></p>
</aside>
```
Exemplo de imagem decorativa
```
<img
     src="graphics/gothic-border.png"
     role="presentation"
     alt=""/>
```
Referências e padrões de conformidade
* HTML5 - [O elemento ```<img>```](http://www.w3.org/TR/html5/embedded-content-0.html#the-img-element)
* WCAG 2.0 - [H37: usando atributo ```alt``` em elementos ```<img>```](http://www.w3.org/TR/WCAG20-TECHS/H37.html)
* WCAG 2.0 - [H67: usando texto alternativo nulo e nenhum atributo de título em elementos ```<img>``` para imagens que a Tecnologia Assistiva deve ignorar](http://www.w3.org/TR/WCAG20-TECHS/H67.html)
* WCAG 2.0 - [G15: usando uma ferramenta para garantir que o conteúdo não viole o limite geral do flash ou o limiar de flash vermelho](http://www.w3.org/TR/WCAG20-TECHS/G15.html)
* WCAG 2.0 - [G19: garantindo que nenhum componente do conteúdo pisque mais de três vezes em qualquer período de 1 segundo](http://www.w3.org/TR/WCAG20-TECHS/G19.html)
* WCAG 2.0 - [G73: fornecendo uma descrição longa em outro local com um link que seja imediatamente adjacente ao conteúdo não-textual](http://www.w3.org/TR/WCAG20-TECHS/G73.html)
* WCAG 2.0 - [G74: fornecendo uma descrição longa no texto perto do conteúdo não-textual, com uma referência à localização da descrição longa na breve descrição](http://www.w3.org/TR/WCAG20-TECHS/G74.html)
* WCAG 2.0 - [G92: fornecendo uma descrição longa para conteúdo que não seja de texto que atende o mesmo propósito e apresenta a mesma informação](http://www.w3.org/TR/WCAG20-TECHS/G92.html)
* WCAG 2.0 - [G94: Fornecer alternativas de texto curto para conteúdo que não seja de texto que tenha o mesmo propósito e apresenta a mesma informação que o conteúdo não-textual](http://www.w3.org/TR/WCAG20-TECHS/G94.html)
* WCAG 2.0 - [G100: fornecendo uma alternativa de texto curto, que é o nome aceito ou um nome descritivo do conteúdo não-textual](http://www.w3.org/TR/WCAG20-TECHS/G100.html)
* WCAG 2.0 - [G103: Fornecer ilustrações, imagens e símbolos visuais para ajudar a explicar ideias, eventos e processos](http://www.w3.org/TR/WCAG20-TECHS/G103.html)
* WCAG 2.0 - [G111: usando cores e padrões](http://www.w3.org/TR/WCAG20-TECHS/G111.html)
* WCAG 2.0 - [C9: usando CSS para incluir imagens decorativas](http://www.w3.org/TR/WCAG20-TECHS/C9.html)
* WCAG 2.0 - [C18: usando margem CSS e regras de preenchimento em vez de imagens de espaçador para design de layout](http://www.w3.org/TR/WCAG20-TECHS/C18.html)
* WCAG 2.0 - [C30: Usando CSS para substituir texto com imagens de texto e fornecendo controles de interface de usuário para alternar
Adicional](http://www.w3.org/TR/WCAG20-TECHS/C30.html)

## Áudio
Ao incluir clipes de áudio, assegure-se de que os controles do sistema nativo de leitura sejam ativados por padrão (ou seja, configurando o atributo ```controls``` no elemento ```<audio>```). Esta prática garante que o controle seja acessível, mesmo que o script não esteja disponível. Se os controles personalizados forem fornecidos e suportados pelo sistema de leitura, os controles nativos podem ser desabilitados pelo JavaScript.

Embora o elemento ```<audio>``` permita o acesso de conteúdo descendente, esse conteúdo não se destina a servir como uma alternativa acessível. Só está disponível para o leitor se o elemento de áudio não for suportado pelo sistema de leitura, que normalmente ocorre apenas nos sistemas de leitura EPUB 2.

Os seguintes métodos para tornar o conteúdo de áudio acessível são recomendados na especificação HTML5:

* Fornecer navegação usando o elemento ```<track>```.
* Fornecer um link para uma transcrição.
* Se as legendas ou um vídeo de lingua de sinais estiverem disponíveis, o elemento de vídeo pode ser usado para reproduzir de forma síncrona o clipe.

Exemplo de ativação dos controles padrão do sistema de leitura
```
<audio src="audio/clip01.mp3" controls="controls"/>
```
Exemplo de inserção de transcrição do áudio
```
<div>
   <audio src="audio/01.mp3" controls="controls"/>
   <a href="transcript01.html">Transcript</a>
</div>
```
Exemplo de inserção de uma mensagem de retorno de erro
```
<audio src="audio/clip12.mp3" controls="controls">
   <div class="err">
      <p>
         Sorry, it appears your system 
         does not support audio playback.
      </p>
   </div>
</audio>
```

Referências e padrões de conformidade
* HTML5 - [O elemento ```<audio>```](http://www.w3.org/TR/html5/embedded-content-0.html#the-audio-element)
* HTML5 - [O elemento ```<track>```](http://www.w3.org/TR/html5/embedded-content-0.html#the-track-element)
* WCAG 2.0 - [G78: fornecendo uma segunda faixa de áudio selecionável pelo usuário que inclui descrições de áudio](http://www.w3.org/TR/WCAG20-TECHS/G78.html)
* WCAG 2.0 - [G81: Fornecer um vídeo sincronizado do intérprete de lingua de sinais que pode ser exibido em uma janela/viewport diferente ou sobreposto na imagem pelo tocador](http://www.w3.org/TR/WCAG20-TECHS/G81.html)
* WCAG 2.0 - [G87: Fornecendo legendas](http://www.w3.org/TR/WCAG20-TECHS/G87.html)
* WCAG 2.0 - [G93: fornecendo legendas abertas (sempre visíveis)](http://www.w3.org/TR/WCAG20-TECHS/G93.html)

## Vídeo
Ao incluir clipes de vídeo, assegure-se de que os controles do sistema nativo de leitura sejam ativados por padrão (ou seja, configurando o atributo ```controls``` no elemento ```<video>```). Esta prática garante que o controle seja acessível, mesmo que o script não esteja disponível. Se os controles personalizados forem fornecidos e suportados pelo sistema de leitura, os controles nativos podem ser desabilitados pelo JavaScript.

Embora o elemento de vídeo permita o conteúdo descendente, esse conteúdo não se destina a servir como uma alternativa acessível. Só está disponível para o leitor se o elemento de vídeo não for suportado pelo sistema de leitura, o que geralmente ocorre apenas nos sistemas de leitura EPUB 2.

Os seguintes métodos para tornar o conteúdo de vídeo acessível são recomendados na especificação HTML5:

* Usar o elemento ```<track>``` para incluir legendas, legendas e descrições.
* Incorpore legendas diretamente no vídeo.
* Forneça navegação por cena usando o elemento ```<track>```.
* Forneça um link para uma transcrição.

O elemento de ```<video>``` também inclui o atributo ```poster``` para permitir que uma imagem padrão seja configurada para exibição enquanto nenhum dado estiver disponível. Atualmente, não existe nenhuma maneira de descrever esta imagem, no entanto, textos de retorno (fallback) são recomendados.

O acordo sobre o suporte universal para um codec e um contêiner de vídeo não pôde ser alcançado em HTML5 e é uma questão similar para EPUB 3. Embora a especificação EPUB 3 permita tecnicamente qualquer formato (sem retorno), o IDPF recomenda um ou ambos os formatos MP4 e WebM. Embora isso não pareça ser uma questão de acessibilidade, considere que isso significa que muitos outros leitores podem estar confiando em recursos que você pode antever antecipadamente.

Habilitando controles nativos com o atributo ```controls```
```
<video
   src="video/the_general.webm"
   controls="controls">
   …
</video>
```
Incluindo mais de uma opção de vídeo usando o elemento de ```<source>```
```
<video controls="controls">
   <source
       src="video/the_general.webm"
       type="video/webm"/>
   <source
       src="video/the_general.mp4"
       type="video/mp4"/>
   …
</video>
```
Incluindo faixas cronometradas
```
<video controls="controls">
       src="video/big-hollywood-blockbuster.mp4"
       controls="controls">
   <track
       kind="subtitles"
       src="subtitles.en.vtt"
       srclang="en"
       label="English"/>
   <track
       kind="captions"
       src="captions.en.vtt"
       srclang="en"
       label="English"/>
</video>
```
Incluindo uma imagem de fundo ao vídeo
```
<video
   src="video/the_general.mp4"
   poster="graphics/the_general.jpg"
   controls="controls">
   …
</video>
```
Incluindo uma mensagem de erro
```
<video
       src="video/the_general.mp4"
       controls="controls">
   …
   <div class="err">
      <p>
         Sorry, it appears your system 
         either does not support video 
         playback or cannot play the 
         MP4 format provided.
      </p>
   </div>
</video>
```


Referências e padrões de conformidade
* HTML5 - [O elemento ```<video>```](http://www.w3.org/TR/html5/embedded-content-0.html#the-video-element)
* HTML5 - [O elemento ```<track>```](http://www.w3.org/TR/html5/embedded-content-0.html#the-track-element)
* WCAG 2.0 - [G15: usando uma ferramenta para garantir que o conteúdo não viole o limite geral do flash ou o limiar de flash vermelho](http://www.w3.org/TR/WCAG20-TECHS/G15.html)
* WCAG 2.0 - [G19: garantindo que nenhum componente do conteúdo pisque mais de três vezes em qualquer período de 1 segundo](http://www.w3.org/TR/WCAG20-TECHS/G19.html)
* WCAG 2.0 - [G78: fornecendo uma segunda faixa de áudio selecionável pelo usuário que inclui descrições de áudio](http://www.w3.org/TR/WCAG20-TECHS/G78.html)
* WCAG 2.0 - [G81: Fornecer um vídeo sincronizado com intérprete de lingu de sinais que pode ser exibido em uma janela/viewport diferente ou sobreposto na imagem pelo tocador de mídia](http://www.w3.org/TR/WCAG20-TECHS/G81.html)
* WCAG 2.0 - [G87: Fornecendo legendas](http://www.w3.org/TR/WCAG20-TECHS/G87.html)
* WCAG 2.0 - [G93: fornecendo legendas abertas (sempre visíveis)](http://www.w3.org/TR/WCAG20-TECHS/G93.html)





## Notas e notas de rodapé
As notas de rodapé e as notas finais provaram um impedimento para a experiência de leitura porque interrompem o fluxo narrativo. Quando as notas de rodapé são colocadas imediatamente após o parágrafo que as referencia, os usuários precisavam navegar manualmente por cada uma, pois normalmente são indistinguíveis do conteúdo do texto. Mesmo as notas de fim, agrupadas no final da seção, exigem que o usuário passe por elas.

Os elementos estruturais do HTML5, juntamente com o atributo ```role```, fornecem um meio de aliviar esse problema, marcando claramente notas de rodapé, notas de rodapé individuais e seções. Isso não apenas permite que os agentes acessíveis ignorem as notas, exceto quando seguidos de suas referências, mas permite que qualquer agente os trate de forma mais inteligente (por exemplo, como pop-ups).

As anotações colocadas na narrativa principal devem ser marcadas usando o elemento HTML5 ```aside```. Esse uso garante que, mesmo que sua semântica não seja reconhecida, as notas ainda serão tratadas como conteúdo secundário devido à natureza do elemento HTML5 ```aside```.

As notas agrupadas no final de uma seção não precisam ser marcadas individualmente como ```aside```, mas devem ser agrupadas usando as notas de rodapé semânticas apropriadas. As listas são um meio eficaz de representar grupos de notas nessas seções, pois permitem que os usuários as movam com mais eficiência (por exemplo, cada número de item da lista normalmente corresponde sequencialmente ao número da nota contida, e os usuários devem ter a capacidade de pular mais de um item da lista por vez, quando houver muitas anotações).

**Notas em tabelas**

Se ocorrerem notas em uma tabela, evite colocá-las em um elemento ```tfoot```, pois ele se destina a resumos das colunas. 

**Nota Referências**

As referências de notas devem ser marcadas usando o elemento ```a``` do HTML5.
Não use o elemento ```sup``` para substituir referências de notas, pois é uma marcação de apresentação redundante. A propriedade CSS ```vertical-align``` pode ser definida para substituir os elementos ```a```.

**Referenciamento para retorno**

Embora não seja especificamente necessário estar acessível, é uma boa prática vincular grupos de notas aos locais de referência no texto. Se um usuário estiver pesquisando as notas, os links na referência permitirão encontrar rapidamente o texto ao qual a nota se refere.

**Exemplos**

Exemplo de nota de rodapé no corpo da página

```
<p>
   In that
   year<a href="#ft2f" role="doc-noteref" epub:type="noteref">2</a>
   there were 67 mills engaged in the manufacture of
   cotton goods …
</p>
<aside id="ft2f" role="doc-footnote" epub:type="footnote">
   <p>
     2 The manufacturing statistics for 1900 which
     follow are not those given in the Twelfth
     Census, but are taken from the 
     <em>Census of Manufactures</em> …
   </p>
</aside>
<p>…</p>
```

Grupo de notas no final de sessão
```
<section epub:type="endnotes" role="doc-endnotes"> 
   <h2>End Notes</h2>
   <ol>
     <li role="doc-endnote">
       According to the usual nomenclature, the
       branch flowing S.W. is called the Chattooga;
       this unites with the Tallulah to form the 
       Tugaloo, which …
     </li>
     …
   </ol>   
</section>
```

CSS para subescrever notas de referências
```
a[role~='doc-noteref'] {
   vertical-align: super;
   line-height: normal;
   font-size: smaller;
}
```
Link de retorno na nota de rodapé
```
<aside role="doc-footnote">
   <p><a href="#ref" role="doc-backlink" title="Go to note reference">1.</a> 
   According to the usual nomenclature, the …</p>
</li>
```
Link de retorno na nota de fim
```

The backlink follows the note text to avoid any conflicts with automatic list numbering. 
The link is placed in its own element so that the user does not have to listen to the 
note before being able to activate it.

<li role="doc-endnote">
   <p>According to the usual nomenclature, the …</p>
   <p><a href="#ref" role="doc-backlink">Go to note reference</a></p>
</li>
```

Referências e padrões de conformidade
* DPUB-ARIA — [```doc-footnote```](https://www.w3.org/TR/dpub-aria-1.0/#doc-footnote)
* DPUB-ARIA — [```doc-endnote```](https://www.w3.org/TR/dpub-aria-1.0/#doc-endnote)
* DPUB-ARIA — [```doc-endnotes```](https://www.w3.org/TR/dpub-aria-1.0/#doc-endnotes)
