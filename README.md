<h1 align="center">
  <img alt="Alura Newsletter" src="https://raw.githubusercontent.com/nayarawatanuki/tailwind-css__alura-newsletter/main/img/readme/Alura-newsletter__cover.png"/>
</h1>

### Índice

* [:pencil: Descrição do Projeto](#pencil-descrição-do-projeto)
* [:white_circle: Status do Projeto](#white_circle-status-do-projeto)
* [:hammer: Funcionalidades e Demonstração da Aplicação](#hammer-funcionalidades-e-demonstração-da-aplicação)
* [:open_file_folder: Acesso ao Projeto](#open_file_folder-acesso-ao-projeto)
* [:rocket: Abrir e rodar o projeto](#rocket-abrir-e-rodar-o-projeto)
* [:keyboard: Tecnologias utilizadas](#keyboard-tecnologias-utilizadas)
* [:woman_technologist: Desenvolvedor(a) do Projeto](#woman_technologist-desenvolvedora-do-projeto)

</br>

## :pencil: Descrição do Projeto
O projeto **[Alura Newsletter](https://nayarawatanuki.github.io/tailwind-css__alura-newsletter/)**, é uma proposta de página web de inscrição a Newsletter da Alura, utilizando a estilização toda em Tailwind CSS. 

</br>Desenvolvido para o curso de **TAILWIND CSS - ESTILIZANDO A SUA PÁGINA COM CLASSES UTILITÁRIAS** da platforma [Alura](https://www.alura.com.br/).

</br>

## :white_circle: Status do Projeto
> Projeto concluído :white_check_mark:

</br>

## :hammer: Funcionalidades e Demonstração da Aplicação
A construção/estrutura da página foi pensada e focada mais na parte de estilização `Tailwind CSS`, logo o projeto já foi iniciado com o `HTML` pronto. 
</br></br>

**Estilização Tailwind CSS:**</br>
Foi realizado, utilizado e apredido: 
- Projeto base utilizado para estilizar com Tailwind;

- **O que é Utility First**
  - Abordagem de uso do CSS, que tem como objetivo priorizar a estilização por meio da chamada de 
  **classe utilitárias**, estas por suas vez representam as propriedades do CSS, como font-size, background, color, border etc.
  - **Utility first** (utilitário primeiro) que também é chamado de 
  **Functional CSS** (CSS funcional), compartilha alguns princípios da **programação funcional**, 
  como por exemplo a imutabilidade., composição, previsibilidade e prevenção de efeitos colaterais.
    </br>
    
    Imagine que você tenha em um projeto diversos cards iguais que compartilham de uma mesma classe de estilização, porém, caso você quisesse que um card tivesse um determinado estilo próprio, como você resolveria isso? Se alterar a classe .card, que é usada por todos, irá mudar todos os estilos de uma vez só e não é isso que você deseja. Ah então é só adicionar um outro seletor específico para esse card! Não é bem por aí, pois dessa forma, esse card irá carregar dois seletores, sendo que um deles irá sobrescrever o outro e isso não é o ideal. Solucionamos essa questão com CSS Funcional, onde apenas é atrelado ao elemento, a propriedade que de fato precisa.
    </br>
    
    A ideia de composição traz que as classes são adicionadas uma a uma ao elemento o construindo, compondo com suas características, ao invés de simplesmente herdá-las, o que faz com que praticamente não seja necessário sobrescrever uma propriedade.
    </br>
    
    Quando trabalhamos em um projeto e ele vai se tornando cada vez maior as classes utilitárias podem ser uma grande aliada! Isso porque nós conseguimos mensurar mais facilmente o que exatamente está sendo aplicado em determinado elemento, tornando tudo mais previsível de identificar e realizar manutenções. A atuação desse conceito em conjunto com a abordagem de composição ao invés de herança resulta na prevenção de efeitos colaterais no layout.

  - **Vantagens:**
    1. Não se preocupe com qual nome faz mais sentido para a classe do elemento.
    2. Estilize de forma rápida e sem escrever código CSS.
    3. Faça mudanças mais facilmente e sem efeito colateral.
    4. Construa um layout com ajuda de estilos pré definidos mas que tenham uma leque enorme de possibilidades.

- Início da construção do layout da Alura Newsletter com o Tailwind;
- Como utilizar o Tailwind.config para criar nossas próprias customizações;
- Como esconder um elemento com a classe hidden do Tailwind;

- Flexbox e Grid
  - Como dispor os elementos com utilitários que modificam o display.

- Tipografia
  - Como alinhar, modificar o tamanho, cor e peso dos textos por meio dos utilitários.

- Espaçamento
  - Foi alterado de formas variadas a width, margin e padding com classes utilitárias no Tailwind.
  
- Bordas e sombras:
  - Como estilizar a caixa dos elementos com utilitários que controlam o border-radius.
  - Uso de classes utilitárias que criam sombreamentos nas caixas dos elementos.

- Pseudo-classes e ring:
  - Como estilizar elementos em diferentes estados com o hover e o focus utilizando os utilitários do Tailwind.
  - Classe ring, que cria anéis de contorno com box-shadow.

- Responsividade:
  - Adaptar o layout para diferentes tamanhos de tela utilizando Breakpoint prefix.
  
- Parent state
  - Utilizar o utilitário `group` para aplicar estilo no elemento filho com base na modificação do estado do elemento pai.

- Animation
  - Aplicar a animação ping do Tailwind e também como customizar e criar nossas próprias animações.

</br>

## :open_file_folder: Acesso ao projeto
Você pode acessar o [código fonte do projeto](https://github.com/nayarawatanuki/tailwind-css__alura-newsletter) ou 
[baixá-lo](https://github.com/nayarawatanuki/tailwind-css__alura-newsletter/archive/refs/heads/main.zip).

Caso obte por baixá-lo: 
Após baixar o projeto, você pode abrir com o VS Code. Para isso, abra o explorer (primeiro icone no menu) clique em:
- Abir pasta ou Open folder
- Procure o local onde o projeto está localizado e o selecione (Caso o projeto seja baixado em zip, é necessário extraí-lo antes de procurá-lo)
- Por fim, clique em Selecionar pasta ou Select Folder

</br>

## :rocket: Abrir e rodar o projeto
Caso tenha interesse em visualizar o que foi realizado: [Alura Newsletter](https://nayarawatanuki.github.io/tailwind-css__alura-newsletter/) 

Ou, caso prefira baixá-lo clicando [aqui](https://github.com/nayarawatanuki/tailwind-css__alura-newsletter/archive/refs/heads/main.zip).

> Após baixar o projeto, abra a pasta do projeto (Caso o projeto seja baixado em zip, é necessário extraí-lo antes de abrir), então clique no:
> - Aqruivo **``index.html``**
> - O projeto abrirá em seu navegador padrão (aconselho configurar para o Chrome, se possível)

</br>

## :keyboard: Tecnologias utilizadas
![HTML + CSS + Tailwind](https://raw.githubusercontent.com/nayarawatanuki/tailwind-css__alura-newsletter/main/img/readme/html-css-tailwind.png)</br>

</br>

## :woman_technologist: Desenvolvedor(a) do Projeto
</> [Nayara Watanuki](https://github.com/nayarawatanuki)

</br>

## :star2: Creditos
:mortar_board: [Professor Guilherme](https://github.com/guilhermeonrails)
