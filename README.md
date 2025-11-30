# Gerador de SVG Pro

Uma ferramenta web simples e poderosa para converter imagens (PNG, JPG) em SVG, com funcionalidades avançadas de remoção de fundo e vetorização real.

## Funcionalidades

- **Conversão Simples**: Incorpora a imagem dentro de um arquivo SVG.
- **Remoção de Fundo**: Remove o fundo branco automaticamente, ideal para desenhos e logotipos.
- **Controle de Sensibilidade**: Ajuste fino do nível de remoção do fundo (Threshold).
- **Vetorização Real (Image Tracing)**: Transforma a imagem em vetores (caminhos) reais usando a biblioteca `imagetracerjs`. Isso permite escala infinita sem perda de qualidade.
- **Preview Transparente**: Fundo xadrez para visualizar facilmente as áreas transparentes.
- **Download e Cópia**: Baixe o arquivo `.svg` ou copie o código direto para a área de transferência.

## Como Usar

1.  Abra o arquivo `index.html` no seu navegador (Chrome, Edge, Firefox, etc).
    > **Nota**: Para a vetorização funcionar, você precisa estar conectado à internet na primeira vez para carregar a biblioteca.
2.  Arraste uma imagem para a área pontilhada ou clique em "Escolher imagem".
3.  Ajuste as configurações:
    - **Remover Fundo Branco**: Marque para deixar o fundo transparente.
    - **Sensibilidade**: Deslize para ajustar o quanto de "branco" será removido.
    - **Vetorizar**: Marque para transformar em traços (vetor real). Desmarque para apenas converter o formato.
4.  Clique em **Converter para SVG**.
5.  Veja o resultado no preview e no campo de texto.
6.  Clique em **Baixar SVG** para salvar no computador.

## Tecnologias

- HTML5, CSS3, JavaScript (Vanilla)
- [imagetracerjs](https://github.com/jankovicsandras/imagetracerjs) (para vetorização)

## Autor

Desenvolvido por **Luan Souza de Siqueira**.