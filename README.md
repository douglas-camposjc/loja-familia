# Loja da Família

Prateleira dos apps da família do Douglas: aqui ficam **só os APKs** (nas *Releases*) e o **catálogo** (`catalogo.json`) que o app **Loja da Família** lê para mostrar o que dá para instalar e atualizar.

## Primeira vez num celular

1. No celular, abra este link e baixe a Loja: **[loja-1.0.0.apk](https://github.com/douglas-camposjc/loja-familia/releases/download/loja-1.0.0/loja-1.0.0.apk)**
2. Toque no arquivo baixado e em **Instalar**. Se o Android pedir, libere "instalar apps desconhecidos" para o navegador.
3. Abra a **Loja da Família** e instale os apps que quiser. Daqui para frente, as atualizações (inclusive da própria Loja) aparecem nela.

## Como funciona

- `catalogo.json`: a lista de apps, cada um com a versão mais nova, o link do APK e o SHA-256 (a Loja confere o arquivo antes de instalar).
- *Releases*: um lançamento por versão de cada app (ex.: `controle_tv-1.1.0`).
- O código dos apps fica em outro repositório, privado. Os APKs são assinados com a chave da família: não instale APK com o mesmo nome vindo de outro lugar.
