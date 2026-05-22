# 🔗 PDF Link Editor

Uma aplicação web simples e totalmente client-side para adicionar links invisíveis e clicáveis em arquivos PDF.

O usuário pode carregar um PDF, desenhar visualmente uma área clicável na primeira página e exportar uma nova versão do documento com um link embutido — tudo diretamente no navegador, sem backend.

---

# ✨ Features

* 📄 Upload de arquivos PDF
* 👀 Preview da primeira página
* 🖱️ Seleção visual da área clicável
* 📐 Redimensionamento e movimentação da área
* 🔗 Inserção de links invisíveis
* 💾 Exportação de novo PDF
* ⚡ Funciona 100% no navegador
* 🔒 Sem upload de arquivos para servidores
* 🧩 Sem backend necessário

---

# 🖼️ Preview

> Adicione aqui screenshots do projeto depois

```bash
/assets/preview.png
```

---

# 🚀 Tecnologias Utilizadas

* PDF.js
* pdf-lib
* interact.js
* HTML5
* CSS3
* JavaScript Vanilla

---

# 📦 Como Executar

## 1. Clone o projeto

```bash
git clone https://github.com/seu-usuario/pdf-link-editor.git
```

## 2. Entre na pasta

```bash
cd pdf-link-editor
```

## 3. Rode um servidor local

### Usando Node.js

```bash
npx serve
```

### Ou usando Python

```bash
python -m http.server 8080
```

---

# 🌐 Abra no navegador

```bash
http://localhost:3000
```

ou

```bash
http://localhost:8080
```

---

# 🛠️ Como Usar

1. Selecione um arquivo PDF
2. Aguarde o preview carregar
3. Desenhe uma área clicável na página
4. Ajuste a área se necessário
5. Digite a URL desejada
6. Clique em **Gerar PDF**
7. Baixe o novo arquivo com o link embutido

---

# 📌 Observações Técnicas

* Apenas a primeira página do PDF é suportada atualmente
* Os links são adicionados como anotações reais do PDF
* O PDF original é preservado sem re-renderização
* Compatível com Chrome Desktop
* Todo processamento ocorre localmente no navegador

---

# 📁 Estrutura do Projeto

```bash
.
├── index.html
└── README.md
```

---

# 🔒 Privacidade

Nenhum arquivo é enviado para servidores externos.

Todo processamento acontece localmente no navegador do usuário.

---

# 🧠 Possíveis Melhorias Futuras

* Suporte a múltiplas páginas
* Suporte a múltiplos links
* Remover/editar links existentes
* Zoom no preview
* Snap/grid para seleção
* Histórico de alterações
* Drag & drop de PDFs

---

# 📄 Licença

MIT License

---

# ❤️ Motivação

Esse projeto foi criado para facilitar a inserção rápida de links clicáveis em PDFs sem depender de softwares pesados ou serviços online.

Ideal para:

* contratos
* apresentações
* materiais de estudo
* catálogos
* PDFs interativos

---

# ⭐ Contribuições

Pull requests são bem-vindos.

Se esse projeto te ajudou, considere deixar uma estrela no repositório ⭐
