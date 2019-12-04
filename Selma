# Metadados

**dc:identifier:** Refere-se ao identificador associado da publicação. Pode ser um UUID, DOI ou ISBN.   
**Atributos:** id (opcional)

**dc:title:** Refere-se ao nome da publicação
**Atributos:** dir, id, xml:lang (opcionais)

```html
<dc:title>Revista .br</dc:title>
```
**dc:language:** Refere-se ao idioma da publicação
**Atributos:** V id (opcional)
```html
<dc:language>pt-br</dc:language>
```
**dcterms:modified:**  Atributo para definir a data da última modificação do documento
```html
<meta property="dcterms:modified">2011-01-21T21:00:00Z</meta>
```
Exemplo:
```html
 <metadata xmlns:dc="http://purl.org/dc/elements/1.1/">
     	<dc:identifier id="isbn-id">urn:isbn:9788560062546</dc:identifier>
        <dc:title>Cartilha de Segurança para Internet</dc:title>
        <dc:language>pt</dc:language>
        <meta property="dcterms:modified">2011-01-01T12:00:00Z</meta>
 </metadata>
```

**Metadados opcionais** (definições pelo W3C)   

**Link (elemento):** Utilizado para relacionar outras fontes ao documento
Atributos: href, rel (obrigatórios) media-type (obrigatório, dependendo do tipo de mídia) id,properties, refines, rel (opcionais) 
```html
<link rel="record" href="front.xhtml#meta-json" media-type="application/xhtml+xml"/>
```

**dc:contributor:** Usado para representar o nome de uma pessoa ou organização que desempenhou um papel secundário na criação do conteúdo de uma publicação do EPUB. Tem o mesmo papel do dc:creator
**Atributos:** dir, id, xml:lang (opcionais)
```html
<dc:contributor id="contributor">Ceweb.br</dc:contributor>
```
**dc:creator:** Representa o nome de uma pessoa ou organização. responsável pela criação do conteúdo
**Atributos:** dir, id, xml:lang (opcionais) 
```html
<dc:creator id="creator">NIC.br</dc:creator>
```
**Possibilidade de mais de um criador:**
```html
<dc:creator id="creator01">NIC.br</dc:creator>
<dc:creator id="creator02">RNP</dc:creator>
```

**dc:date:** Deve ser usado apenas para definir a data de publicação da publicação EPUB.
**Atributos:** id (opcional) 
```html
<dc:date>2011-01-21T21:00:00Z</dc:date>
```
**Definição de data:** 21 de janeiro de 2011, 21:00 UTC
*Outros exemplos de definição de data:*
1963-03-08T14: 07-0600 (8 de março de 1963 às 14:07 no fuso horário seis horas antes do UTC).   

2009-02-20T08: 40Z (20 de fevereiro de 2009 8h40, UTC).    
2018-08-29T15: 19 (15:19, horário local em 29 de agosto de 2018).   
1809-02-12 (em 12 de fevereiro de 1809).   
1906-06 (em junho de 1906).   
1971 (em algum momento do ano de 1971).   
2007-03-01T13: 00: 00Z / 2008-05-11T15: 30: 00Z (algum tempo durante o intervalo entre 1 de março de 2007 13:00 UTC e 11 de maio de 2008 15:30 UTC).   
1900/1909 (algum tempo durante o intervalo entre o início do ano 1900 e o final do ano 1909).   
13-11-2007 / 15 (algum tempo entre 13 de novembro de 2007 e 15 de novembro de 2007).   

**dc:subject:**  identifica o assunto da publicação do EPUB. O valor do elemento DEVE ser o cabeçalho ou rótulo legível por humanos, mas PODE ser o valor do código se a taxonomia em questão não fornecer um rótulo descritivo separado.
**Atributos:** dir, id, xml:lang (opcionais) 
```html
<dc:subject id="subject01">Tecnologia/Interner</dc:subject>
<meta refines="#subject01" property="authority">BISAC</meta>
<meta refines="#subject01" property="term">000000000</meta>
```
**dc:type:** usado para indicar que a publicação EPUB fornecida é de um tipo especializado (por exemplo, anotações ou um dicionário compactado no formato EPUB).
**Atributos:** id (opcional) 
```html
<dc:type>revista</dc:type>
```

# Metadados opcionais (definições pelo Dublin Core)

**dc:description:** Uma conta do recurso. A descrição pode incluir, mas não está limitada a: um resumo, um índice, uma representação gráfica ou texto livre do recurso.
**Atributos:** dir, id, xml:lang (opcionais)
```html
<dc:description>A cartilha de acessibilidade tem como objetivo...</dc:description>
```
**dc:format:** O formato do arquivo, meio físico ou dimensões do recurso.
**Atributos:** id (opcional) 
```html
<dc:format>text/html</dc:format>
```
**dc:publisher:** Uma entidade responsável por disponibilizar o recurso.
**Atributos:** dir, id, xml:lang (opcionais) 
```html
<dc:publisher>Comitê Gestor da Internet no Brasil</dc:publisher>
```
**dc:relation:** Um recurso relacionado.
**Atributos:** dir, id, xml:lang (opcionais) 
```html
<dc:relation>http://cartilha.cert.br/recursos/</dc:relation>
```
**dc:rights:** Informações sobre direitos mantidos no recurso e sobre ele.
**Atributos:** dir, id, xml:lang (opcionais) 
```html
<dc:rights>http://creativecommons.org/licenses/by-nc-nd/3.0/br/</dc:rights>
```
**dc:source:** Um recurso relacionado do qual o recurso descrito é derivado.
**Atributos:** id (opcional) 
```html
<dc:source id="src-id">urn:isbn:9780375704024</dc:source>
```

**dc:coverage:** O tópico espacial ou temporal do recurso. O tópico espacial e a aplicabilidade espacial podem ser um local nomeado ou um local especificado por suas coordenadas geográficas. O tópico temporal pode ser um período, data ou intervalo nomeado. Uma jurisdição pode ser uma entidade administrativa nomeada ou um local geográfico ao qual o recurso se aplica. A melhor prática recomendada é usar um vocabulário controlado, como o Thesaurus de nomes geográficos [TGN]. Onde apropriado, locais ou períodos de tempo nomeados podem ser usados de preferência a identificadores numéricos, como conjuntos de coordenadas ou períodos.
**Atributos:** dir, id, xml:lang (opcionais)
```html
<dc:coverage>Guerra dos browsers; 2000</dc:coverage>
```
**Fontes:**   
https://www.w3.org/publishing/epub3/epub-packages.html   
https://www.dublincore.org/specifications/dublin-core/dcmi-terms/   
http://rs.tdwg.org/dwc/terms/#dcterms:modified   
EPUB 3 Best Practices. Garrish, M., Gylling , M. 2013. O′Reilly; Edição: 1   


**epub:type**
Atributo com o objetivo de estender a semântica do HTML relacionando a áreas da publicação. Os mais comuns são:

**epub:type="frontmatter"**
Material preliminar ao conteúdo principal de uma publicação, como índices, dedicatórias, etc.
```html
<body epub:type="frontmatter">
  <section epub:type="prologue">
    …
  </section>
</body>
</body>


**epub:type="abstract"**
Um breve resumo das principais idéias, conceitos e conclusões do trabalho, ou de uma seção ou trecho dele.
```html
<header>
<h1>A história da Web</h1>
<div epub:type="abstract">
<p>Tim Berners-Lee descreve o processo de concepção da Web …</p>
</div>
</header>
```

**epub:type="acknowledgments"**
Uma passagem contendo agradecimentos às entidades envolvidas na realização do trabalho.
```html
<section epub:type="acknowledgments">
<h1 epub:type="title">Agradecimentos</h1>
<p>Agradecemos a todos os participantes do grupo de revisores do projeto:</p>
<ol>
<li><p>Peter Maltic, pesquisador, Universidade Federal do Rio de Janeiro, Rio de Janeiro Brasil</p></li>
<li><p>Peter Maltic, analista de projetos, NIC.br, São Paulo, Brasil</p></li>
…
</ol>
</section>
```

**epub:type="copyright-page"**
A página de direitos autorais do trabalho.
```html
<section epub:type="copyright-page" aria-label="copyright page">
<p>Creative Comons - Atribuição 4.0 Internacional (CC BY 4.0)</p>
<p>Você tem o direito de:</p>
<p>Compartilhar — copiar e redistribuir o material em qualquer suporte ou formato</p>
<p>Adaptar — remixar, transformar, e criar a partir do material
para qualquer fim, mesmo que comercial.</p>
…
</section>
```

**epub:type="dedication"**
Uma inscrição endereçada a uma ou várias pessoas em particular.
```html
<section>
<h1>Dedicatória</h1>
<section epub:type="dedication">
<p>Para Peter Maltic, por todos os serviços prestados em favor da Internet</p>
</section>
</section>
``

**epub:**type="foreword"
Uma seção introdutória (prefácio) que precede o trabalho, normalmente não escrita pelo autor do trabalho.
```html
<section epub:type="foreword">
        <header>
        <h1>Prefácio</h1>
                <p>Por Peter Maltic</p>
        </header>
<p>A internet mudou a forma como consumimos conteúdo …</p>
…
</section>
```

**epub:** type="halftitlepage"
A meia página de título do trabalho.
```html
<section epub:type="halftitlepage">
<h1 epub:type="halftitle">Microdados</h1>
<p>DÉCIMA EDIÇÃO</p>
</section>
```

**epub:** type="introduction"
Uma seção no início do trabalho, normalmente apresentando ao leitor o escopo ou a natureza do conteúdo do trabalho.
```html
<section epub:type="introduction" aria-label="Introduction">
<p>Nos fascículos anteriores foram apresentados os principais conceitos sobre a acessibilidade na Web. No primeiro conhecemos … </p>
<p>Nesta terceira publicação são apresentados ao leitor de forma mais detalhada os principais beneficiados da Web acessível… </p>
</section>
```

**epub:** type="preface"
Uma seção introdutória que precede o trabalho, normalmente escrita pelo autor do trabalho, diferente do foreword
```html
<section epub:type="preface">
        <span epub:type="pagebreak"/>
<h1>Prefácio</h1>
<p>A internet mudou a forma como as pessoas consomem conteúdo … </p>
…
</section>
```
**epub:** type="seriespage"
Seção usada para listar publicações relacionadas.
```html
<section epub:type="seriespage">
<h1>Publicações relacionadas</h1>
<ul>
<li>Cartilha de Seguranc¸a para Internet, versao 4.0 / CERT.br – S ão Paulo: Comitê Gestor da Internet no Brasil, 2012., ISBN 9788560062058</li>
…
</ul>
</section>
```

**epub:** type="titlepage"
A página de título do trabalho.
```html
<section epub:type="titlepage">
<h1>Cartilha de Segurança para Internet Versao 4.0</h1>
…
</section>
```
**epub:** type="bodymatter"
O conteúdo principal de uma publicação. 
```html
<body epub:type="bodymatter">
<section epub:type="part">
<h1 epub:type="title">1. Segurança na Internet </h1>
…
</section>
</body>
```

**epub:** type="chapter"
Uma grande divisão estrutural de uma peça de escrita.
```html
<section epub:type="chapter">
<h1>4. Códigos maliciosos ( Malware)</h1>
…
</section>
```

**epub:** type="part"
Uma grande divisão estrutural de uma peça de escrita, tipicamente encapsulando um conjunto de capítulos relacionados.
```html
<body epub:type="bodymatter">
<section epub:type="part">
<h1>Parte 3 - Internet e cidadania</h1>
<section aria-label="Introduction">
<p>Os próximos capítulos contemplam: </p>
<p><a href="#ch04">Capítulo 4</a> responsabilidades governamentais … </p>
<p><a href="file.xhtml#ch05">Capítulo 5</a> responsabilidades do usuário… </p>
</section>
…
</section>
</body>
```

**epub:** type="qna"
Uma seção de perguntas e respostas.
```html
<section epub:type="qna">
        <h1>Questionário:</h1>
        <dl>
             <dt epub:type="question">Quando foi publicada a primeira página Web?</dt>
             <dd epub:type="answer">em 1989</dd>
                …
        </dl>
</section>
```

**epub:** type="volume"
Um componente de uma coleção.
```html
<section epub:type="volume">
        <h1>VOLUME I</h1>
        <section epub:type="part">
                <h1>PARTE I</h1>
<section epub:type="chapter">
                        <h1>Capítulo 1</h1>
                        …
                </section>
        </section>
</section>
```

**epub:** type="backmatter"
Material auxiliar que ocorre após o conteúdo principal de uma publicação, como índices, apêndices etc.
```html
<body epub:type="backmatter">
<section epub:type="credits">
<h1>Créditos</h1>
…
</section>
</body>
```

**epub:** type="afterword"
Uma declaração final do autor ou de uma pessoa importante para a história, geralmente fornecendo informações sobre como a história foi escrita, seu significado ou eventos relacionados que ocorreram desde sua linha do tempo.
```html 
<section epub:type="afterword">
        <h1>Posfácio</h1>
        <p>A internet mudou a forma como consumimos conteúdo …</p>
</section>
```

**epub:** type="appendix"
Informação complementar.
```html
<section epub:type="appendix">
<h1>Appendice D</h1>
<p>Informação complementar … </p>
…
</section>
```

**epub:** type="colophon"
Uma breve descrição geralmente localizada no final de uma publicação, descrevendo notas de produção relevantes para a edição.
```html
<section epub:type="colophon">
        <h1>Notas sobre a publicação</h1>
        <p> Este livro utiliza as fontes…</p>
</section>
```

**epub:** type="conclusion"
Uma seção final que normalmente encerra o trabalho.
```html
<section epub:type="conclusion">
<h1>Conclusão</h1>
<p>A pesquisa detectou os seguintes aspectos comportamentais … </p>
</section>
```

**epub:** type="epigraph"
Uma cotação definida no início do trabalho ou uma seção que estabelece o tema ou define o estado de espírito.
```html
<blockquote epub:type="epigraph">
<p>“No princípio não existia nada”</p>
</blockquote>
```

**epub:** type="bibliography"
Uma lista de trabalhos citados.
Bibliografia deve ser estruturada em listas ordenadas <ol>. Utilize elementos <section> para organizar a bibliografia em seções lógicas. Se a seção não tiver um título <h1>, utilize o atributo aria-label para fornecer informação a tecnologia assistiva.
```html
	<section epub:type="bibliography">
<h1>Referências</h1>
<ol>
<li epub:type="biblioentry">Cartilha de Segurança para Internet, versao 4.0 / CERT.br (2012). … </li>
…
</ol>
</section>
```


**epub:** type="biblioentry"
Uma entrada em uma bibliografia.
```html
<ol>
<li epub:type="biblioentry">Cartilha de Segurança para Internet, versao 4.0 / CERT.br (2012). … </li>
…
</ol>
```

**epub:** type="biblioref"
Uma referência a uma entrada da bibliografia.
```html
<p>Acessibilidade na web é a possibilidade e a condição de alcance, percepção, entendimento e interação para a utilização, a participação e a contribuição, em igualdade de oportunidades, com segurança e autonomia, em sítios e serviços disponíveis na web, por qualquer indivíduo, independentemente de sua capacidade motora, visual, auditiva, intelectual, cultural ou social, a qualquer momento, em qualquer local e em qualquer ambiente físico ou computacional e a partir de qualquer dispositivo de acesso. (<a epub:type="biblioref" href="#ref12">NIC.br, 2013</a>).</p>
```

**epub:** type="glossary"
Uma lista alfabética de termos em um domínio específico do conhecimento, com as definições para esses termos.
```html
<dl epub:type="glossary">
  <dt id="glossario">
    <dfn>Glossário</dfn>
  </dt>
```

**epub:** type="glossdef"
A definição de um termo em um glossário.
```html
<body epub:type="glossary">
  <ul>
    <li>
      <span epub:type="glossterm">Spam</span>, 
      <a epub:type="index-locator" href="...">155</a><br/>
      <span epub:type="glossdef">Termo usado para se referir aos e-mails não solicitados, que geralmente são enviados para um grande número de pessoas.</span>
    </li>
```

**epub:** type="glossterm"
Um termo do glossário.
```html
<body epub:type="glossary">
  <ul>
    <li>
      <span epub:type="glossterm">Spam</span>, 
      <a epub:type="index-locator" href="...">155</a><br/>
      <span epub:type="glossdef">Termo usado para se referir aos e-mails não solicitados, que geralmente são enviados para um grande número de pessoas.</span>
    </li>
```


**epub:** type="glossref"
Uma referência a uma definição de glossário.
```html
<p>Também pode ser chamado de <a epub:type="glossref" href="glossario.xhtml#spamzombie">spam zombie</a> quando o bot instalado o transforma em um servidor de e-mails e o utiliza para o envio de spam </p>
```

**epub:** type="case-study"
Uma análise detalhada de um tópico específico.
```html
<aside epub:type="case-study">
<h3>Evidência</h1>
<p>Requisitos Relevantes: R-DataVersion (em inglês)</p>
…
</aside>
```

**epub:** type="help"
Informações que esclarecem ou complementam o conteúdo.
```html
<aside epub:type="help" aria-label="hint">
        <p>Considere a direção de leitura da esquerda para a direita</p>
</aside>
```

**epub:** type="notice"
Informações que requerem atenção especial e que não devem ser ignoradas ou suprimidas. Os exemplos incluem: alerta, aviso, cautela, perigo, importante.
```html
<aside epub:type="notice">
        <img src="alerta.jpg" alt="Alerta"/>
        <p>O uso incorreto dos padrões pode causar problemas de exibição da página.</p>
</aside>
```

**epub:** type="pullquote"
Uma citação do texto que é definido de maneira distinta, como em um tipo de letra maior.
```html
<aside epub:type="pullquote">
<p>“Tornar acessível uma aplicação na Web é responsabilidade de todos no projeto”</p>
</aside>
```

**epub:** type="learning-objective"
Uma designação ou descrição explícita de um objetivo de aprendizado ou uma referência a um objetivo de aprendizado explícito.
```html
<li epub:type="learning-objective">Conceitos detalhados para a compreensão do exercício</li>
```
**epub:** type="learning-objectives"
Uma coleção de objetivos de aprendizagens.
```html 
<section epub:type="learning-objectives">
<header>
<h1>Objetivos de estudo</h1>
</header>
<ol>
<li epub:type="learning-objective">Explicar os conceitos de uso da Web</li>
…
        </ol>
</section>
```

**epub:** type="learning-outcome"
A compreensão ou habilidade que um aluno deve alcançar como resultado de uma lição ou atividade.
```html
<li epub:type="learning-outcomes">Esperamos que o aluno esteja apto a configurar um servidor de forma...</li>
```
**epub:** type="learning-outcomes"
Uma coleção de resultados.
```html
<section epub:type="learning-outcomes">
<header>
<h1>Resultados esperados</h1>
</header>
<p>Ao concluir o curso o aluno estará apto a:</p>
<ol>
<li epub:type="learning-outcome">Configurar um servidor apache</li>
…
</ol>
</section>
```

**epub:** type="learning-resource"
Um recurso fornecido para aprimorar o aprendizado ou uma referência a esse recurso.
```html
<li epub:type="learning-resource"><a href="http://example.com/cs01">Caso de estudo: Configurando uma rede wireless</a></li>
```
**epub:** type="learning-resources"
Uma coleção de recursos de aprendizado.
```html
<section aria-label="learning resources">
   <p>Consulte os links a seguir para mais informações:</p>
   <ul epub:type="learning-resources">
      <li><a href="http://example.com/cs01">Caso de estudo: Configurando uma rede wireless</a></li>
      …
   </ul>
</section>
```

**epub:** type="learning-standard"
Um conjunto formal de expectativas ou requisitos normalmente emitidos por um governo ou um organismo de normas.
```html
<li epub:type="learning-standard">Os alunos devem ser capazes de identificar quem está contando a história no início e no final.</li>
```
**epub:** type="learning-standards"
Uma coleção de padrões.
```html 
<section>
   <h3>Estudo de padrões</h3>
   <ul epub:type="learning-standards">
      <li>Os alunos devem ser capazes de identificar quem está contando a história no início e no final.</li>
      …
   </ul>
</section>
```

**epub:** type="answer"
A resposta a uma pergunta.
```html 
<li epub:type="general-problem">
        <p epub:type="question">...</p>
<p epub:type="answer">O número de pessoas conectadas é de ...</p>
</li>
```

**epub:** type="answers"
Uma coleção de respostas
```html
<ol epub:type="answers">
<li id="ans1">125 mil usuários</li>
<li id="ans2">97 contas ativas</li>
<li id="ans3">987 interações</li>
…
</ol>
```

**epub:** type="assessment"
Um teste ou outra atividade que ajude a medir a compreensão do aluno sobre o que está sendo ensinado.
```html
<section epub:type="assessment">
<h1>Estudo de padrões</h1>
<ol>
<li epub:type="general-problem">
<div epub:type="question">
<p>Qual o padrão mais adequado para a implementação de recursos de acessibilidade?</p>
</div>
</li>
…
</ol>
</section>
```

**epub:** type="assessments"
Uma coleção de avaliações.
```html
<section epub:type="assessments">
        <h1>Avaliações</h1>
 <section epub:type="assessment">
 <h2>Padrões</h2>
                …
        </section>
        <section epub:type="assessment">
                <h2>Boas práticas</h2>
                …
        </section>
</section>
```


**epub:** type="feedback"
Instruções úteis para o leitor com base no resultado de uma avaliação.
```html
<div epub:type="feedback" id="quiz01" aria-live="assertive">
        <!--feedback escrito dinamicamente -->
</div>
```

**epub:** type="fill-in-the-blank-problem"
Um problema que exige que o leitor insira uma resposta em texto para completar uma frase, afirmação ou similar.
```html
<div epub:type="fill-in-the-blank-problem">
<div epub:type="question">
O padrão para a estrutura de páginas é o _____.
</div>
</div>
<div epub:type="fill-in-the-blank-problem">
<div epub:type="question">
As _____ servem para definir o estilo de uma página.
</div>
</div>
```

**epub:** type="general-problem"
Um problema com uma solução de forma livre.
```html
<div epub:type="general-problem">
<div epub:type="question">
Qual seria uma descrição melhor do realismo ingênuo,
“Ver é acreditar” ou “acreditar é ver”?
</div>
</div>
```

**epub:** type="match-problem"
Um problema que requer que o leitor combine o conteúdo de uma lista com os itens correspondentes em outra lista.
```html
<div epub:type="match-problem">
<p> Combine os itens da lista da esquerda com os itens da lista da direita </p>
<div epub: type = "question">
<ol>
<li> O ponto em que, se vencido, vence a partida para um jogador </li>
<li> A área entre a rede e a linha de serviço </li>
<li> Bater na bola antes que ela salte </li>
                 ...
         </ol>
<ol>
<li> ace </li>
<li> retrocesso </li>
<li> linha de serviço central </li>

…
</ol>
</div>
</div>
```

**epub:** type="multiple-choice-problem"
Um problema com um conjunto de respostas em potencial para escolher - algumas, todas ou nenhuma delas podem estar corretas.
```html
<div epub:type="multiple-choice-problem">   
<p epub:type="question">Which New Yorker author also wrote children's books?</p>
<ol>
<li>James Thurber</li>
<li>E.B White</li>
<li>Dorothy Parker</li>
</ol>
</div>
```

**epub:** type="practice"
Um exercício de revisão ou amostra.
```html
<section epub:type="practice">
<h1>Chapter 1</h1>
<ol>
<li epub:type="general-problem">
<p epub:type="question">Which would be a better description of naive realism, “seeing is believing” or “believing is seeing”?</p>
</li>
<li epub:type="true-false-problem">
<p epub:type="question">Shakespeare's last play was The Tempest.</p>
</li>
…
        </ol>
</section>
```

**epub:** type="practices"
Uma coleção de práticas.
```html
<section epub:type="practices">
<h1>Learning Activities</h1>
<section epub:type="practice">
<h1>Chapter 1</h1>
…
        </section>
<section epub:type="practice">
<h1>Chapter 2</h1>
…
        </section>   
        …
</section>
```

**epub:** type="question"
Uma declaração que solicita informações ou testa um problema. Normalmente encontrados emparelhados com uma ou mais respostas - ou possíveis respostas - em problemas de autoavaliação, entrevistas com perguntas e respostas e perguntas freqüentes, embora uma resposta não seja necessária.
```html
<li epub:type="general-problem">
        <p epub:type="question">...</p>
<p epub:type="answer">The riddle refers to time, as it devours all …</p>
</li>
```

**epub:** type="true-false-problem"
Um problema com uma resposta verdadeira ou falsa.
```html
<ol>
<li epub:type="true-false-problem">
<p epub:type="question">There will be an increase in the number sof both elementary and secondary teachers in each year from 1998 through 2004.
</li>
<li epub:type="true-false-problem">
<p epub:type="question">The number of additional elementary teachers added each year from 1998 through 2004 will be larger in the years at the beginning of this time period than in the years toward the end.</p>
</li>
…
</ol>
```

**epub:** type="footnote"
Uma nota que aparece na parte inferior de uma página.
```html
<aside epub:type="footnote" id="fn01">
<a href="#footnoteref01">1</a> The CDA requirements are roughly equivalent to one year of college.
</aside>
```

**epub:** type="footnotes"
Uma coleção de notas que aparecem na parte inferior de uma página.
```html
<aside epub:type="footnotes">
        <p id="fn01" epub:type="footnote"><a href="#fnref01">1</a>. The original
wording of this paragraph suggested the author …</p>
        <p id="fn02" epub:type="footnote"><a href="#fnref02">2</a>. Most of this
paragraph was lost to bookworms.</p>
</aside>
```

**epub:** type="noteref"
Uma referência a uma nota, geralmente aparecendo um símbolo sobrescrito no corpo principal do texto.
```html
<p>Another important aspect of this book is that it follows an iterative style. In the computing education community, a well-known educational design pattern exists that states that important concepts should be taught early and often.<a epub:type="noteref" href="#endnote1">1</a> … </p>
```
**epub:** type="rearnotes"
Uma nota que aparece na parte traseira (contra-capa) da obra ou no final de uma seção.
```html
<section epub:type="rearnotes">
        <h2>Notes</h2>
<p id="endnote1" epub:type="rearnote"> … </p>
<p id="endnote2" epub:type="rearnote"> … </p>
…
</section>
```

**epub:** type="rearnotes"
Uma coleção de notas que aparecem na parte traseira (contra-capa) da obra ou no final de uma seção.
```html
<section>
        <h2>Notes</h2>
<ol epub:type="rearnotes">
<li id="endnote1"><a href="chap01.xhtml#fnref01">1</a>. A study of
the mentioned species reveals …</li>
<li id="endnote2"><a href="chap01.xhtml#fnref02">2</a>. During an
excavation of the area …</li>
…
</ol>
</section>
```

**epub:** type=”referrer”
Um link para o local inicial em um relacionamento de link bidirecional.
```html
<aside epub:type="rearnote" id="fn01">
<p>
<a href="#ref1" epub:type=”referrer”>
<span epub:type=”ordinal”>1</span>
</a>
The CDA requirements are roughly equivalent to one year of college.
</p>
</aside>
```

**epub:** type="label"
O rótulo do texto que precede um ordinal no título de um componente (por exemplo, 'Capítulo', 'Parte', 'Figura', 'Tabela').
```html
<h1>
<span epub:type="label">Chaper</span>
<span epub:type="ordinal">1</span>
</h1>
```

**epub:** type="ordinal"
Um especificador ordinal para um componente em uma sequência de componentes (por exemplo, '1', 'IV', 'B-1').
```html
<ul>
        <li><span epub:type="ordinal">LO.1a</span> … </li>
        <li><span epub:type="ordinal">LO.1b</span> … </li>
        …
</ul>
```

**epub:** type="subtitle"
Um título explicativo ou alternativo.
```html
<section>
<header>
<h1>Geopolitics</h1>
<p epub:type="subtitle">Mountains as Walls</p>
</header>
…
</section>
```

**epub:** type="title"
O nome principal de uma obra, seção ou componente.
```html
<h1>
<span epub:type="label">Chaper</span>
<span epub:type="ordinal">1</span>
<span epub:type="title">Single-Cell Organisms</span>
</h1>
```

**epub:** type="pagebreak"
Um separador (às vezes com valor) que indica a posição antes da qual ocorre uma quebra entre duas páginas contíguas em uma mídia paginada estaticamente.
```html 
<span epub:type="pagebreak" id="pg302" title="302"/>
```
```html <span epub:type="pagebreak" id="pg302" title="302"/>

**epub:** type="keyword"
Uma palavra-chave ou frase.
```html 
<p>A <b epub:type="keyword">capital gain</b> is realized when … </p>
```
**epub:** type="keywords"
Uma coleção de palavras-chave.
```html
<section>
<h1>Key Terms</h1>
<ol epub:type="keywords">
<li>Benefit</li>
<li>Capital</li>
<li>Economic model</li>
</ol>
</section>
```

**epub:** type="credit"
Um reconhecimento da fonte do conteúdo citado ou de uma contribuição ao trabalho.
```html 
<p epub:type="credit">Page <a href="C03.xhtml#ch03table01">62</a>, <a href="C03.xhtml#ch03table01">Table 3.1</a> from <cite>“Economic Foundations of Cost-Effectiveness Analysis”</cite> by A. M. Garber and C. E. Phelps, <cite>Journal of Health Economics</cite> 16(1):1–31, 1997. Reprinted by permission of Elsevier Science.</p>
```

**epub:** type="credits"
Uma coleção de créditos.
```html
<section epub:type="credits">
<h1>Credits</h1>
<section>
<h1>Chapter 1</h1>
<p epub:type="credit">Page <a 
href="C03.xhtml#ch03table01">62</a>, <a
href="C03.xhtml#ch03table01">Table 3.1</a> from
<cite>“Economic Foundations of Cost-Effectiveness Analysis”</cite>
by A. M. Garber and C. E. Phelps, <cite>Journal of Health
Economics</cite> 16(1):1–31, 1997. Reprinted by permission of
Elsevier Science.</p>
…
</section>
</section>
```

**epub:** type="loa"
Uma lista de clipes de áudio incluídos no trabalho.
```html
<nav epub:type="loa">
        <h2>List of Audio</h2>
        <ol>
                <li><a href="c01.html#c01audio01">Roosevelt Infamy Speech</a></li>
                <li><a href="c01.html#c01audio02">Kennedy Inauguration
Address</a></li>
                …
        </ol>
</nav>
```

**epub:** type="loi"
Uma lista de ilustrações incluídas no trabalho.
```html
<nav epub:type="loi">
        <h2>List of Illustrations</h2>
        <ol>
                <li><a href="c01.html#c01fig01">Figure 1 - The Brain</a></li>
                <li><a href="c01.html#c01fig02">Figure 2 - The Heart</a></li>
                …
        </ol>
</nav>
```

**epub:** type="lot"
Uma lista de tabelas incluídas no trabalho.
```html 
<nav epub:type="lot">
        <h2>List of Tables</h2>
        <ol>
                <li><a href="c01.html#c01tbl01">Table 1.1 - Population
Growth</a></li>
                <li><a href="c01.html#c01tbl02">Table 1.2 - Historical
Unemployment Rates</a></li>
                …
        </ol>
</nav>
```

**epub:** type="lov"
Uma lista de videoclipes incluídos no trabalho.
```html
<nav epub:type="lov">
        <h2>List of Video</h2>
        <ol>
                <li><a href="c01.html#c01vid01">Hindenburg Disaster</a></li>
                <li><a href="c01.html#c01vid02">Space Shuttle Challenger
Disaster</a></li>
                …
        </ol>
</nav>
```

**epub:type="toc"**
Um índice, normalmente aparecendo no frontmatter da obra ou no
início de uma seção.
```html
<nav role="doc-toc" epub:type="toc" id="toc">
<h2>Table of Contents</h2>
<ol>
  <li>
	<a href="s01.xhtml">A simple link</a>
  </li>
  …
</ol>
</nav>
```

**epub:type="toc-brief"**
Uma versão reduzida e/ou especializada do índice.
```html
<nav epub:type="toc-brief" id="toc-brief">
 <h1>Brief Table of contents</h1>
 <ol>
   <li>
     <p><a href="chap1.xhtml">Chapter 1 ‒ Introduction</a></p>
      <p>A brief history of the evolution of scientific thinking.</p>
    </li>
   <li>
     <p><a href="chap2.xhtml">Chapter 2 ‒ The Greeks</a></p>
      <p>Archimedes, Aristotle, Euclid and Pythagoras</p>
   </li>
 </ol>
</nav>
```

**epub:type="index"**
Um auxílio à navegação que fornece uma lista detalhada de links para assuntos importantes, nomes e outros tópicos importantes abordados no trabalho.
```html
<body epub:type="index">
		<h2>Simplest index</h2>
		<ul epub:type="index-entry-list">
		<!-- epub:type index-entry is implied for all li's, due to ancestor with epub:type of index-entry-list -->
			<li><span epub:type="index-term">abbreviations</span>, 
				<a epub:type="index-locator" href="...">52</a></li>
			<li><span epub:type="index-term">accents</span>, 
				<a epub:type="index-locator" href="...">20</a></li>
			<li><span epub:type="index-term">blogs</span>, 
				<a epub:type="index-locator" href="...">98</a></li>
			<li><span epub:type="index-term">cold calling</span>, 
				<a epub:type="index-locator" href="...">68</a></li>
			<li><span epub:type="index-term">Facebook</span>, 
				<a epub:type="index-locator" href="...">viii</a>, 
				<a epub:type="index-locator" href="...">96</a></li>
			<li><span epub:type="index-term">inversion</span>, 
				<a epub:type="index-locator" href="...">53</a></li>
			<li><span epub:type="index-term">Twitter</span>, 
				<a epub:type="index-locator" href="...">37-42</a></li>
		</ul>
	</body>
```

**epub:type="index-headnotes"**
Narrativa ou outro conteúdo para ajudar os usuários a usar o índice.
```html
<header epub:type="index-headnotes">
	<h1>Subject Index</h1>
	<p>This is an index to the main text of the book; content in the appendices has not been indexed.  
	References are to section and paragraphs. The number preceding the colon is the number of the section; 
	the number following the colon is the paragraph number within the section.</p>
	<p>Alphabetization is word-by-word: New York comes before Newtown.</p>
</header> 
```

**epub:type="index-legend"**
Lista de símbolos, abreviações ou formatação especial usada no índice e seus significados.
```html
<header epub:type="index-headnotes">
	<p>The following abbreviations are used in this index.</p>
	<dl epub:type="index-legend">
		<dt>Civ. R.</dt><dd>Civil Rule</dd>
		<dt>Crim. R.</dt><dd>Criminal Rule</dd>
		<dt>§</dt><dd>Statute</dd>
	</dl>
	<p>The following formatting conventions are used in this index-</p>
	<dl epub:type="index-legend">
		<dt>bold text</dt><dd>main discussion/definition of topic</dd>
		<dt>italic text</dt><dd>indicates figure</dd>
		<dt>'t' following a locator</dt><dd>indicates table</dd>
	</dl>
</header> 
```

**epub:type="index-group"**
Coleção de entradas principais consecutivas que compartilham uma característica comum, por exemplo, a letra inicial das entradas principais.
```html
<section epub:type="index">
	...
	<section epub:type="index-group">
		<h1>A</h1>
		...[entries beginning with "A"]
	</section>
	<section epub:type="index-group">
		<h1>B</h1>
		...[entries beginning with "B"]
	</section>
</section>
```

**epub:type="index-entry-list"**
Coleção de entradas principais ou subentradas consecutivas.
```html
<ul epub:type="index-entry-list">
	<li epub:type="index-entry">
		<span epub:type="index-term">Black, John</span>
		<ul epub:type="index-entry-list">
			<li epub:type="index-entry">
				<span epub:type="index-term">birth</span>
				<a epub:type="index-locator">¶75</a>
			</li>
			<li epub:type="index-entry">
				<span epub:type="index-term">death</span>
				<a epub:type="index-locator">¶78</a>
			</li>
		</ul>
	</li>
</ul>
```

**epub:type="index-entry"**
Um termo com qualquer subentrada, localizador, referência cruzada e / ou nota editorial do atendente.
 ```html
<ul epub:type="index-entry-list">
	<li epub:type="index-entry">
		<span epub:type="index-term">Heston, Charlton</span>
		<a epub:type="index-locator" href="...">53</a>
		<a epub:type="index-locator" href="...">76-79</a>
	</li>
	<li>
		<span epub:type="index-term">Howard, Leslie</span>
		<a epub:type="index-locator" href="...">62</a>
	</li>
</ul>
```

**epub:type="index-term"**
Palavra, frase, string, glifo ou imagem representando o conteúdo indexável.
 ```html
<ul epub:type="index-entry-list">
	<li epub:type="index-entry">
		<span epub:type="index-term">Heston, Charlton</span>
		<a epub:type="index-locator" href="...">53</a>
		<a epub:type="index-locator" href="...">76-79</a>
	</li>
	<li>
		<span epub:type="index-term">Howard, Leslie</span>
		<a epub:type="index-locator" href="...">62</a>
	</li>
</ul>
```


**epub:type="index-editor-note"**
Nota editorial referente a uma única entrada.
 ```html
<ul>
	<li>
		<span epub:type="index-term">Heston, Charlton</span>
		<span epub:type="index-editor-note">Charlton Heston (1923-2008), actor in numerous American films.</span>
	</li>
</ul> 
```

**epub:type="index-locator"**
Uma referência a uma ocorrência do conteúdo indexado na publicação.
	```html
	<a epub:type="index-locator"><img alt="phone" src="phone-icon.png"/></a>
	...
	<a epub:type="index-locator">35</a>
	...
	<a epub:type="index-locator">II:14</a> 
	```

**epub:type="index-locator-list"**
Coleção de localizadores sequenciais ou intervalos de localizadores.
 ```html
<ul epub:type="index-locator-list">
	<li>
		<ul class="...">
			<!-- epub:type value index-locator is implied for all a elements due to ancestor with epub:type value locator-list -->
			<li><a href="...">3:5</a></li>
			<li><a href="...">9</a></li>
			<li><a href="...">14</a></li>
		</ul>
	</li>
	<li>
		<ul class="...">
			<li><a href="...">5:7</a></li>
			<li><a href="...">9</a></li>
		</ul>
	</li>
</ul> 
```

**epub:type="index-locator-range"**
Um par de localizadores que conecta um termo a um intervalo de conteúdo, em vez de um único ponto. 
 ```html
<ul epub:type="index-locator-list">
	<li epub:type="index-locator-range">
<a href="chap2.xhtml#p076">76-79</a>
</li>
</ul>
```

**epub:type="index-xref-preferred"**
Referência de um termo a um ou mais termos ou categorias preferenciais em um índice (análogo a "Ver xxx").
 ```html
<!-- note id attribute beij -->
<li epub:type="index-entry" id="beij">
	<span epub:type="index-term">Beijing</span>
	<a epub:type="index-locator">113-120</a>
</li>
...
<li epub:type="index-entry">
	<span epub:type="index-term">Peking</span>
	<span epub:type="index-xref-preferred">See 
		<!-- note href attribute #beij -->
		<a epub:type="index-term" href="#beij">Beijing</a>
	</span>
</li>
```

**epub:type="index-xref-related"**
Referência de um termo a um ou mais termos ou categorias de termos relacionados em um índice (análogo a "Consulte também xxx").
 ```html
<li epub:type="index-entry">
	<span epub:type="index-term">sweet potatoes</span>
	<span epub:type="index-xref-related">See also 
		<!-- note href attribute #yams -->
		<a epub:type="index-term" href="#yams">yams</a>
	</span>
</li>
```

**epub:type="index-term-category"**
Palavra, frase, string, glifo ou imagem representando uma categoria de termos no índice.
 ```html
<li epub:type="index-entry">
	<span epub:type="index-term">battles</span>
	<span epub:type="index-xref-preferred">See 
		<a epub:type="index-term-category" href="nav.xhtml#battles">names of specific battles</a>
	</span>
</li> 
```

**epub:type="index-term-categories"**
Wrapper para uma lista das categorias de termos pertencentes a um índice.

```html
<nav epub:type="index-term-categories" hidden="">
<!-- hidden attribute prevents term categories from being rendered in the content flow -->
<ul>
	<li id="battles">battles
		<ol>
			<!-- a's pointing to all terms in this term category -->
			<li><a href="index.xhtml#chan">Chancellorsville</a></li> 
			<li><a href="index.xhtml#man1">First Manassas</a></li>
			<li><a href="index.xhtml#gett">Gettysburg</a></li>
		</ol>
	</li>
	...
	<!-- more than one term category may be included -->
	<li id="generals">Confederate generals
		<ol>
			<li><a href="index.xhtml#grant">Grant, Ulysses S.</a></li>
			<li><a href="index.xhtml#lee">Lee, Robert E.</a></li>
			<li><a href="index.xhtml#pick">Pickett, George</a></li>
		</ol>
	</li>
</ul> 
