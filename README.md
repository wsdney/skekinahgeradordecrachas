# 🎟️ Gerador de Crachás Personalizados

Um sistema web simples e flexível para criar crachás de eventos de forma
rápida.\
Permite personalizar fundo, textos, imagens, bordas, e gerar crachás
automaticamente a partir de uma lista de nomes.

👉 [Acesse aqui no GitHub
Pages](https://wsdney.github.io/skekinahgeradordecrachas/)

------------------------------------------------------------------------

## 🚀 Recursos

-   Adicionar **textos** livres com manipulação (mover, redimensionar,
    girar, mudar fonte, cor e tamanho).\
-   Inserir **imagens** e posicionar livremente dentro do crachá.\
-   Definir **dimensões do crachá** (largura e altura).\
-   Alterar **cor de fundo** ou aplicar **gradiente**.\
-   Ativar/Desativar **borda do crachá**, escolhendo **espessura e
    cor**.\
-   Criar crachás automaticamente para uma lista de nomes.\
-   **Gerar PDF** pronto para impressão, ocupando várias páginas se
    necessário.\
-   Salvar e carregar **configurações** em arquivos `.json` (facilita
    reutilizar layouts para eventos futuros).

------------------------------------------------------------------------

## 🖊️ Como usar

### Criar o layout do crachá

1.  Defina as dimensões do crachá (ex.: `10x7 cm` ou `10x14 cm`).\
2.  Escolha **fundo sólido** ou **gradiente**.\
3.  Clique em **➕ Texto** ou **➕ Imagem** para adicionar elementos.
    -   Arraste, redimensione e personalize livremente.\
4.  Se desejar, ative a **borda**, escolha cor e espessura.

------------------------------------------------------------------------

### Inserir nomes automaticamente nos crachás

1.  Clique em **➕ Texto**.\

2.  Um texto genérico aparecerá:

        Seu Texto {{NAME}}

3.  Clique e edite, deixando somente:

        {{NAME}}

4.  Posicione o `{{NAME}}` onde deseja que o nome apareça.\

5.  Na caixa **Lista de nomes**, insira um nome por linha:

        Maria Silva
        João Pereira
        Ana Souza

6.  Configure margens, espaçamento e orientação (paisagem ou retrato).\

7.  Clique em **Gerar PDF**.

    -   O sistema substituirá `{{NAME}}` por cada nome.\
    -   O PDF conterá um crachá para cada nome da lista.

------------------------------------------------------------------------

### Salvar e carregar configurações

-   Clique em **Salvar Configuração** → gera um arquivo `.json`.\
-   Para reutilizar, clique em **Carregar Configuração** e selecione o
    `.json`.\
-   Isso permite ter **modelos prontos para cada evento**.

------------------------------------------------------------------------

## 🖨️ Gerar PDF

-   O PDF é gerado com base no layout definido.\
-   O sistema ajusta os crachás para caber na folha A4.\
-   Se os crachás não couberem em uma página, o sistema cria várias
    páginas automaticamente.

------------------------------------------------------------------------

## 🛠️ Tecnologias utilizadas

-   **HTML + CSS (Tailwind)**\
-   **JavaScript (Fabric.js, jsPDF, FileSaver.js)**
