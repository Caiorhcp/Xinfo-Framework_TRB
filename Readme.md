# Xinforinfola

## Visão Geral

Xinforinfola é um framework CSS, inspirado no site Alienware.Dell (https://www.dell.com/pt-br/gaming/alienware) foi desenvolvido com SASS, projetado para facilitar a criação de interfaces web modernas e responsivas. Inspirado em frameworks populares como o Bootstrap, o Xinforinfola oferece uma coleção de componentes e estilizações prontos que podem ser integrados rapidamente em qualquer projeto. Nossa missão é simplificar o desenvolvimento front-end, proporcionando um conjunto de ferramentas eficiente e fácil de usar.

## Instruções de Instalação

### Pré-requisitos

Antes de instalar o Xinforinfola, você precisará ter o Node.js e o npm (Node Package Manager) instalados em sua máquina. Caso ainda não os tenha, você pode baixá-los e instalá-los a partir dos links abaixo:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Passos para Instalação

1. **Clone o repositório do Xinforinfola:**

   ```bash
   git clone https://github.com/Caiorhcp/Xinfo-Framework_TRB

2. **Navegue até o diretorio do projeto**
   ```bash 
   cd xinforinfola
   ```

3. **Instale as Dependencias**
   ```bash
   npm install
   ```

4. **Compile os arquivos SASS:**
   ```bash
   npm run sass

   Para compilar continuamente enquanto faz alterações:

   sass --watch xinforinfola_Frameworks/scss/input. scss:xinforinfola_Frameworks/css/output.css
   ```

5. **Inclua o caminho para o css que esta sendo compilado no file html**
   ```bash
   <link rel="stylesheet" href="/Xinforinfola_Frameworks/css/output.css">
   ```

## Exemplos de Uso
1. **Button**

```bash
<button class="xinfo-button1-v1-roxo">Digite algo</button>
```

2. **Card 1**

```bash
   <!--Card 1 exemplo-->
    <div class="xinfo-card1">
    
        <img class="image" src="/images/test.avif" alt="test">
        <!-- classe content texts  -->
        <div class="xinfo-content"> 
        <h2 >  Digite algo </h2>
        <p>Digite algo.</p>
        <!-- classe do botão desejado -->
        <button class="xinfo-button1-v2-laranja">Digite algo</button>
    </div>
    </div> 
    <h1>cards2</h1>
<!--Card 2 exemplo-->
    <div class="xinfo-card2">
    
        <img class="image" src="/images/test.avif" alt="test">
        <!-- classe content texts  -->
        <div class="xinfo-content2"> 
        <h2 >  Digite algo </h2>
        <p>Digite algo.</p>
        <!-- classe do botão desejado -->
        <button class="xinfo-button2-v1-roxo">Digite algo</button>
    </div>
    </div> 

 </div>
 ```

**Os exemplos de uso estam dentro do file index. html, todos interativos.**


**Classes Disponíveis**
```bash
Cabeçalho / Header
.xinfo-site-header
.xinfo-wrapper
.xinfo-site-header__wrapper
.xinfo-nav
.xinfo-nav__toggle
.xinfo-nav__wrapper
.xinfo-nav__item
.xinfo-center
.xinfo-brand
.xinfo-button
.xinfo-button--icon
```

```bash
Botões
.xinfo-button1-v1-roxo
.xinfo-button1-v2-laranja
.xinfo-button1-v3-verde
.xinfo-button1-v4-branco
.xinfo-button1-v5-preto

.xinfo-button2-v1-roxo
.xinfo-button2-v2-laranja
.xinfo-button2-v3-verde
.xinfo-button2-v4-branco
.xinfo-button2-v5-preto

.xinfo-button2-v1-roxo-bgGray
.xinfo-button2-v2-laranja-bgGray
.xinfo-button2-v3-verde-bgGray
.xinfo-button2-v4-branco-bgGray
.xinfo-button2-v5-preto-bgGray
```

```bash
Cards
.xinfo-card1
.xinfo-card2
.xinfo-content
.xinfo-content2
```
```bash
Containers
.xinfo-container1
.xinfo-text-container1
.xinfo-cardsAll
.xinfo-container2
.xinfo-btn-text2
.xinfo-h2-text2
.xinfo-h3-text2
.xinfo-content-2
```

OBS. **Existem presets de estilização disponiveis no arquivo variables.scss**

## Equipe

Este projeto foi desenvolvido por:

- Caio
- Vitor
- Robert

Agradecemos por usar o Xinforinfola! 

UNINASSAU - 2024 - 3°Semestre