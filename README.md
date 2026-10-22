# Site — Arranjo para Betel 2028

Site estático em HTML, CSS e JavaScript, pronto para publicar no GitHub Pages. Não precisa de servidor nem de instalação.

## Como publicar no GitHub Pages

1. Entre no GitHub e crie um repositório, por exemplo `arranjo-betel-2028`.
2. Envie os arquivos e pastas deste pacote para a raiz do repositório. A estrutura deve ficar assim:
   - `index.html`
   - `style.css`
   - `script.js`
   - `assets/capa-betel-2028.png`
3. No repositório, acesse **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`; clique em **Save**.
6. Aguarde a publicação. O GitHub mostrará o endereço público do site na mesma página.

## Como personalizar

Abra `index.html` e procure os textos de exemplo, como **“A confirmar”**, **“A definir”** e as instruções que começam com “Informe...”. Substitua pelos dados confirmados da viagem.

- **Data, destino e participantes:** cartões no começo da página.
- **Programação:** seção `id="programacao"`.
- **Checklist:** seção `id="organizacao"`.
- **Custos e pagamentos:** seção `class="costs"`.
- **Dúvidas e contato:** seção `id="duvidas"` e bloco de contato.
- **Imagem de capa:** substitua `assets/capa-betel-2028.png`, mantendo o mesmo nome, ou atualize o caminho no `style.css`.

## Atenção à privacidade

O GitHub Pages publica o site na internet. Evite colocar telefones pessoais, listas nominais de participantes, dados bancários, documentos ou informações privadas sem autorização. O checklist é local ao navegador e não salva respostas num servidor.

## Arquivos

- `index.html` — conteúdo e estrutura
- `style.css` — aparência e adaptação para celular
- `script.js` — menu móvel
- `assets/capa-betel-2028.png` — imagem de capa
