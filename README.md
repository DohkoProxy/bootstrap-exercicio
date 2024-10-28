/* no bootstrap os itens de uma coluna sao divididos em 12 partes da pagina. Para definirmos quantas partes cada elemento irá usar, definimos dentro da própria tag.
ex.: 
            <div class="col-4">
                Coluna #2
            </div>              -> para usar 4 espaços independente da tela

                        <div class="col-sm-4">
                Coluna #2
            </div>              -> para usar 4 espaços em telas pequenas como de dispositivos móveis (small)

                        <div class="col-lg-4">
                Coluna #2
            </div>              -> para usar 4 espaços em telas grandes (large)

    Por padrao, as colunas tembem vem com padding proprio do bootstrap. Para remover, ou alterar usamos o g-.
    ex.:
            <div class="col-sm-12 col-lg-8 g-0"> 
                Coluna #2
            </div>              -> neste caso, removemos o padding com o valor 0.*/




/* podemos facilitar nossa criacao no Visual studio, com comandos direito. Veja o exemplo onde criaremos várias colunas, com imagens e um h3 dentro de cada uma:

.container>.row>.col*5>img+h3

definimos que teremos uma div (container), dentro uma linha (row), dentro 5 colunas (col*5), dentro imagens e uma h3 (img+h3) */




/* para customizar as fontes, podemos usar as classes. Como:

- colocando uma classe de h1 em qualquer texto, com um p (<p class="h1">)
- colocando uma classe de display em qualquer elemento de texto, com um display (<h1 class="display-1">) */




/* o mesmo serve para adicionarmos as customizacoes do bootstrap em uma tabela, acrescemtamos a classe table. <table class="table">
também podemos estilar elementos com uma estilizacao da classe, como por exemplo:

- <table class="table table-primary">
- <table class="table table-secondary">
- <table class="table table-sucess">
- <table class="table table-danger">
- <table class="table table-warning">
- <table class="table table-info">
- <table class="table table-light">
- <table class="table table-dark"> */



/* as classes também sao aplicadas, na criacao de botoes, veja os exemplos:

- <button class="btn"> -- padrao
- <button class="btn btn-primary">
- <button class="btn btn-secondary">
- <button class="btn btn-sucess">
- <button class="btn btn-danger">
- <button class="btn btn-warning">
- <button class="btn btn-info">
- <button class="btn btn-light">
- <button class="btn btn-dark">
- <button class="btn btn-link">

também podemos customizar somente a borda do botao, veja:

- <button class="btn btn-outline-primary"> -- incluindo todas as variacoes acima

também podemos customizar o tamanho do botao, com uma nova classe, exemplo:

- <button class="btn btn-outline-primary btn-sm"> -- small, para um botao pequeno (sm)
- <button class="btn btn-outline-primary btn-md"> -- medium, para um botao medio (md)
- <button class="btn btn-outline-primary btn-lg"> -- large, para um botao grande (lg) */




/* accordions, estrutura básica:

<div class="accordion">
        <div class="accordion-item">
            <div class="accordion header">
                <button class="accordion-button" data-bs-toggle ="collapse" data-bs-target="#resposta1">Pergunta</button>
            </div>
            <div id="resposta1" class="accordion-collapse collapse show">
                <div class="accordion-body">
                    Resposta da Pergunta
                </div>
            </div>
        </div>
</div> */




/* collapse - neste exemplo de colapse está o modelo de um botao que esconde e mostra uma preço oculto. Vejamos:

<button class="btn btn-dark" data-bs-toggle="collapse" data-bs-target="#preco">
    Ver preço
</button>
<div id="preco" class="collapse collapse-vertical">
    <p>R$ 788,99</p>
</div>

neste caso, o collapse, a aparicao do item será na vertical, mas se quiser na horizontal, basta mudar a segunda classe.*/




/* alertas - a criacao de alertas com bootstrap também é muito intuitiva, criada pelas classes.

- <div class="alert¨></div> - padrao
- <div class="alert alert-primary"></div> -- junto com todas as variacoes como, secondary, sucess, danger, info, dark, etc...

entretanto, todo alerta deve poder ser fechado pelo usuario, uma vez que tomou conheciimento, o padrao para se fazer isso seria:

    <div class="alert alert-info alert-dismissible">
        <button class="btn-close" data-bs-dismiss="alert"></button>
        Mensagem de alerta!!!
    </div>
*/