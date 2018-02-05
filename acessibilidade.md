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
