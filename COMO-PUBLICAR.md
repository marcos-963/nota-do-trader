# Como colocar a calculadora no ar (GitHub Pages, gratuito)

Esta pasta é a **Edição do Leitor** da Nota do Trader:

- **Funciona em qualquer celular ou computador,** sem login e sem depender do Claude.
- **Sem o "Pergunte ao Claude":** o assistente só funciona dentro do Claude. O resto é igual à sua versão: Operação, Preço médio, Onde está o preço, Cenários, Exemplos, "Enviar e corrigir" e os botões de apagar.
- **Não coleta nada:** sem cadastro, sem e-mail, sem formulário. Os números ficam só no navegador do leitor.

## Arquivos

| Arquivo | Para quê |
|---|---|
| `index.html` | A calculadora (é a página que abre no endereço) |
| `qrcode-nota-do-trader.png` / `.svg` | QR code para o livro, que aponta para `https://marcos-963.github.io/nota-do-trader/` |
| `PAGINA-FINAL-DO-LIVRO.md` | Texto pronto para a página "Ferramenta de apoio" |

## Antes de publicar: links dos livros

No fim do `index.html` há três links com o texto `LINK_AMAZON_LIVRO_1`, `_2` e `_3`. Troque cada um pelo link do livro **na Amazon**, por exemplo `https://www.amazon.com.br/dp/XXXXXXXXXX`, usando o ASIN de cada livro. Não use links de outras lojas: a regra do KDP proíbe.

## Publicar

1. No GitHub, crie um repositório **público** chamado `nota-do-trader`.
2. Envie os arquivos desta pasta para ele.
3. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em 1 ou 2 minutos, a calculadora abre em `https://marcos-963.github.io/nota-do-trader/`.
5. Teste o QR code com o celular antes de colocar no livro.

**Se escolher outro nome de repositório ou um domínio próprio,** o endereço muda e o QR code precisa ser gerado de novo.

## Atualizar depois

Para mudar a calculadora, envie um `index.html` novo para o mesmo repositório. O endereço e o QR code continuam os mesmos, então os livros já vendidos continuam funcionando.
