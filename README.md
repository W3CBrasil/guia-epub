# Guia de Boas Práticas em Publicações Digitais
Repositório para a elaboração do "Guia de Boas Práticas em Publicações Digitais" do Brazilian Publishing Community Group. Utilizaremos este repositório para receber sugestões e estruturar o documento base para iniciar o desenvolvimento do documento.

Será utilizada como base a documentação do ePub 3.0 (http://idpf.org/epub/30).

Outras informações sobre o projeto bem como detalhes sobre como participar estão disponíveis na página do Community Group em https://www.w3.org/community/brazilpub/.

Estrutura do documento:
Conforme sugerido na reunião de 20 de outubro de 2017, iniciaremos a estrutura do documento no README e as colaborações, discussões e decisões serão feitas por issues no repositório.

## **Introdução ao ePub**
### O que é o formato ePub
O formato ePub vem impondo-se como formato padrão para os livros digitais, sobretudo por ser fluido, permitindo a adaptação do conteúdo para diferentes tamanhos e formas de telas dos vários aparelhos. Nesse sentido, ele difere do PDF, que é bastante estático, uma vez que representa fielmente a estrutura original da página. O ePub é o complemento ideal para o PDF.
O ePub é um arquivo ZIP compactado (com extensão .epub), que contém alguns arquivos e diretórios, cada um com uma função específica. Cada elemento do arquivo ePub é criado com base em certas normas internacionais estabelecidas pelo W3C.

#### Um pouco de história
Esse formato foi publicado em 2007 pelo International Digital Publishing Forum (IDPF). O IDPF foi uma associação que reúnia os principais operadores no setor da editoria digital e empresas relacionadas a esse mercado. Entre os membros estavam grande empresas (Apple, Google, Sony, IBM, Agfa), editores (Santillana, O'Reilly, McGraw-Hill, HarperCollins), associação de editores (canadense, norte-americana e italiana), livrarias (Barnes & Noble, Simon & Schuster) e fornecedores de serviços (Integra, Aptara, Kobo, Simplíssimo Livros). Uma lista completa é ainda possível obter em: http://idpf.org/membership/members.

O objetivo do consórcio era promover e desenvolver o setor da editoria digital, apoiando e incentivando a adoção de formatos padrões reconhecidos por todos.

O formato ePub é, portanto, o resultado produzido em comum acordo entre os membros do IDPF em 2007, mas tem suas raízes já em 1999 quando o Open E-book Forum — que depois deu origem ao IDPF — lançou uma especificação[1] para livros digitais chamada OEB (Open E-book Publication Structure), o embrião de uma das especificações que compõem o ePub, a OPS.

Em 2017 houve uma mudança nos rumos do formato ePub. O consórcio  IDPF (International Digital Publishing Forum) uniu-se com o W3C (Word Wide Web Platform). 
Esta união tinha sindo anunciada e estudada desde 2016, quando integrantes do IDPF e interessados foram convidados a dar feedback sobre a união e foi disponibilizada uma FAQ sobre a questão, que finalmente no dia 18 de janeiro 2017 foi sancionada em um encontro no Digital Book World (Nova York City). Na prática, o IDPF deixou de existir unindo-se definitivamente ao W3C com o propósito de dar continuidade ao trabalho de produção das especificações do ePub.

A palavra ePub é a composição de Eletronic Publication. A ideia de usar o “eletronic” foi uma escolha ponderada, pois visava a apresentar o ePub como um formato padrão para outros modelos de publicações, além dos livros.

### Tecnologia Web de um ePub
    * HTML
    * CSS
    * SVG
  
## **Passo a passo para a construção de um ePub**
    * Manifesto
    * Marcação semântica
    * Estrutura do documento
    * Caracteristicas e requisitos das lojas
    * ...
  
## **Documentação comentada do ePub3**
    * EPUB 3 Overview
    * EPUB Publications 3.0
      * Package Documents
      * Package Metadata
      * ...
      
    * EPUB Content Documents 3.0
      * EPUB Content Documents
      * EPUB Style Sheets
      * ...
      
    * EPUB Media Overlays 3.0
       * Media Overlay Document Definition
       * Creating Media Overlays
       * ...
       
    * EPUB Open Container Format 3.0
      * OCF Abstract Container
      * OCF ZIP Container
      * ...
      
    * EPUB Canonical Fragment Identiffier Specification
      * EPUB CFI Definition
      * EPUB CFI Processing
      * ...

## Mini Glossário

**Adobe® Digital Edition (ADE)**. Aplicativo gratuito para PC e Mac — além de vir embutido em alguns eReaders — no qual se pode ler e gerenciar livros digitais nos formatos ePub e PDF, com ou sem proteção Adobe DRM.

**Adobe DRM.** Proteção contra cópias para conteúdo digital, em especial os e-books. É o sistema mais adotado para arquivos ePub e PDF, usado por empresas como Barnes & Noble, Kobo, Sony, Cultura, Saraiva, entre outras.

**Aldiko.** Aplicativo com versões gratuitas e pagas para leitura de livros no sistema operacional Android. Lê arquivos ePub e PDF, entre outros.

**Amazon.** Empresa norte-americana que lidera o mercado de venda de e-books e eReaders nos Estados Unidos. É conhecida como loja de venda de diversos objetos, desde livros impressos, eletrônicos, brinquedos até eletrodomésticos.

**Android.** Sistema operacional especial para dispositivos móveis, desenvolvido pela Google. Além de ser usado em muitos modelos de smartphones, também está presente em tablets como Motorola Xoom, Positivo Ypy e os novos Kindle Fire, NOOK Color e Kobo Vox.

**Apple.** Empresa fundada por Steve Jobs que atuava na produção dos computadores pessoais. Com o passar do tempo, ficou conhecida por lançamentos que mudaram o mundo, como o smartphone iPhone e o tablet iPad.

**Arquivo sem proteção.** Um e-book sem qualquer proteção, como a DRM. Esse tipo de arquivo pode ser lido em qualquer plataforma que aceite o ePub.

**Autopublicação (self-publishing)**. Ato de publicação de um livro pelo próprio autor. Essa forma de publicação se tornou extremamente popular com a chegada dos e-books e das mídias sociais.

**AZW.** Formato de livros digitais criado e adotado pela Amazon em sua plataforma Kindle. É similar ao MOBI, mas possui proteção contra cópia.

**Bluefire Reader.** Leitor de livros digitais gratuito para o tablet iPad.

**Calibre.** Aplicativo gratuito para gerenciar bibliotecas digitais. É também conhecido pela conversão de arquivos de MOBI para ePub e vice-versa.

**DAISY.** É um formato de e-book baseado em XML para pessoas com deficiências visuais. Ele pode ser ouvido em um leitor de livros digitais DAISY que converte texto em fala. Para mais informações, consulte o Consórcio DAISY.

**DRM (Digital Rights Management).** Sistema criado para proteger arquivos de e-book de sua distribuição ilegal, bem como empréstimo de obras e cópia não autorizada. Não se pode ler um livro em AZW, no qual se lê um ePub, ou um ePub da Apple, por exemplo, porque cada um deles possui um DRM diferente.

**e-book.** Também conhecido livro digital ou livro eletrônico.

**e-Ink (e-ink, eInk).** Tinta eletroforética. Tipo especial de e-paper, fabricado pela empresa E-Ink Corporation.

**Enhanced e-book.** Livro digital com adicionais, além do texto e de imagens, como áudio e vídeo, entre outros. Permite que o leitor interaja com o conteúdo.

**eReader (e-reader).** Leitor eletrônico, aparelho especialmente projetado para a leitura de e-books, normalmente composto por uma tela de e-paper.

**e-paper (ePaper).** Papel eletrônico, um tipo de tela projetada para imitar o visual e a sensação de leitura do livro em papel. Telas de e-paper não são retroiluminadas como as de LCD, e por isso precisam de luz externa para serem visualizadas.

**ePub** (abreviação de Eletronic Publication — Publicação Eletrônica). É o padrão livre e aberto para conteúdo fluido. Foi criado pelo International Digital Publishing Forum (IDPF), um consórcio formado por várias empresas como Sony e Adobe. O ePub é um formato de arquivo digital de padrão específico para e-books. Os arquivos desse formato possuem a extensão .epub. É projetado para conteúdo fluido, o que significa que a tela de texto pode ser otimizada de acordo com o dispositivo usado para leitura. O padrão é destinado a funcionar como um único formato oficial para distribuição e venda de livros digitais. É suportado por um número crescente de dispositivos e leitores, entre eles o aplicativo gratuito Adobe® Digital Editions e nos eReaders Barnes & Noble NOOK, Sony Reader e Positivo Alfa. É um formato rico baseado em XHTML e CSS, permitindo uma série de diagramações e personalizações. Se adapta às telas, podendo até aumentar e trocar as fontes. A padronização dos e-books facilita na organização de sua coleção com tags e outras informações, é mais compacto que os formatos tradicionais e principalmente por ser multiplataforma, é possível compartilhá-los com outras pessoas, independente do dispositivo que a outra pessoa tenha.

**ePub fixed layout.** É um arquivo ePub especial adotado pela Apple. Permite mais controle na formatação do livro, porém só pode ser lido por dispositivos móveis da Apple.

**iBooks.** Aplicativo gratuito para iPad, iPhone e iPod Touch para ler e comprar livros pela iBookstore.

**iBookstore.** Loja de livros digitais mantida pela Apple.

**iOS.** Sistema operacional presente em dispositivos móveis vendidos pela Apple.

**iPad.** O tablet da Apple, é o mais famoso do mundo.

**Kindle.** Plataforma de livros digitais da Amazon, que inclui uma linha de eReaders, um tablet e também aplicativos para diferentes sistemas operacionais.

**Kobo.** Empresa canadense que possui uma loja virtual de e-books, além de dispositivos de leitura como eReaders e um tablet, junto com aplicativos para diferentes sistemas operacionais.

**MOBI.** Arquivos .mobi são suportados pelo Kindle, da Amazon, pelo Mobipocket Reader, e uma série de outros dispositivos. É um tipo de arquivo ideal para textos corridos, como romances e ficções. Permite pouca personalização, e por isso é mais simples que o ePub. O formato AZW, da Amazon, é uma versão do MOBI com DRM, a proteção antipirataria.

**Nuvem.** Tecnologia que permite armazenar arquivos do usuário em um servidor de um provedor. Permite acessar um arquivo de qualquer aparelho, em qualquer lugar do mundo com acesso à rede.

**PDF (Portable Document Format).** Os arquivos nesse formato são o padrão da indústria para troca de documentos. Uma grande variedade de plataformas e dispositivos oferecem software de leitura de PDF. Com suas fontes incorporadas, rico e cuidadoso layout, imagens de alta resolução e até opções de interatividade, os PDFs são ideais para livros de imagens, viagens e outros. Seu problema reside no fato de não poder ter suas fontes aumentadas e o layout reajustado à tela.

**Tablet.** Aparelho móvel multipropósito com tela LCD colorida, operado por tela de toque.

**Tela de toque (touchscreen).** Tipo de tela eletrônica que permite operar um dispositivo por meio do toque na tela com os dedos.

**Text-to-speech (TTS).** Tecnologia que converte o texto escrito em fala, usando um sintetizador de voz.

**Tinta eletrônica.** Ver e-paper.

## Notas de rodapé
[1] Uma especificação é um documento que lista e descreve as linhas guias para o uso correto e a aplicação de uma tecnologia.