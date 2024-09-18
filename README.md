 raiz {
    --branco-principal: #FFFFFF;
    --cinza-secundario: #C0C0C0;
    --botao-azul: #167BF7;
    --cor-de-fundo: #00030C;
    --fonte-principal: 'Inter';
    --botao-azul-efeito: #3c92fa;
}

corpo {
    background-color: var(--cor-de-fundo);
    cor: var(--branco-principal);
    família de fontes: var(--fonte-principal);
    tamanho da fonte: 16px;
    peso da fonte: 400;
}

* {
    Margem: 0;
    preenchimento: 0;
}

. principal {
    imagem de fundo: url ("img / Background.png");
    background-repeat: sem repetição;
    tamanho do plano de fundo: conter;
    alinhar itens: centro;
    alinhamento de texto: centro;
}

. recipiente {
    Altura: 100VH;
    exibição: grade;
    colunas de modelo de grade: 50% 50%;
}

. container__botao {
    cor de fundo: var (--botao-azul);
    raio da borda: 5px;
    preenchimento: 1em;
    cor: var(--branco-principal);
    exibição: bloco;
    decoração de texto: nenhum;
    margem-fundo: 1em;
}

. botao_secundario {
    cor de fundo: transparente;
    borda: 2px var sólido(--branco-principal)
}

. container__aviso {
    tamanho da fonte: 12px;
    Cor: VAR(--cinza-secundario);
}

. container__titulo {
    tamanho da fonte: 28px;
    peso da fonte: 700;
}

. container__imagem {
    Margem: 1em 0 2em 0;
}

. container__caixa {
    Margem: 0 6em;
}

. secundario__imagem {
    Largura: 80%;
}

. segundo {
    alinhar itens: centro;
    Margem: 0 10em;
}

. descricao__titulo {
    peso da fonte: 700;
    tamanho da fonte: 48px;
    cor: var(--branco-principal);
    margem-fundo: 0.1em;
}

. descricao__texto {
    Cor: VAR(--cinza-secundario);
}

. secundario__botao {
    exibição: bloco embutido;
    Margem superior: 1em;
}

. container__descricao {
    preenchimento: 2em;
}

. dispositivos__lista {
    Display: Flex;
    justificar-conteúdo: centro;
    tipo de estilo de lista: nenhum;
    Margem: 5em 0;
}

. dispositivos {
    alinhamento de texto: centro;
}

. dispositivos__titulo {
    tamanho da fonte: 48px;
    cor: var(--branco-principal);
}

. lista__item {
    tamanho da fonte: 32px;
    cor: var(--branco-principal);
}

. rodape {
    alinhamento de texto: centro;
    margem: 5em 3em;
}

. rodape__lista {
    Display: Flex;
    justificar-conteúdo: centro;
    tipo de estilo de lista: nenhum;
    Margem superior: 1em;
}

. lista__link um{
    decoração de texto: nenhum;
    cor: var(--branco-principal);
    margem-esquerda: 1em;
}

. rodape__texto {
    Margem: 1em 0;
    Cor: VAR(--cinza-secundario);
    tamanho da fonte: 14px;
}

. lista__link um:hover {
    cor: var (--botao-azul);
}

. lista__link a:ativo {
    Cor: Roxo;
}

. container__botao:hover {
    cor de fundo: var(--botao-azul-efeito);
    cor: var(--cor-de-fundo);
}
