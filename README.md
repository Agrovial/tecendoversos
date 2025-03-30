# Tecendo Versos

Este é o site oficial do projeto **Tecendo Versos**, desenvolvido com [Jekyll](https://jekyllrb.com/) e hospedado via [GitHub Pages](https://pages.github.com/).

📍 Acesse o site aqui: [https://agrovial.github.io/tecendoversos/](https://agrovial.github.io/tecendoversos/)

---

## 🔧 Como rodar localmente

### Pré-requisitos:
- Ruby instalado
- Bundler (`gem install bundler`)

### Instalar dependências:
```bash
bundle install

## ✅ Pré-requisitos

1. **Ruby** instalado (recomenda-se 2.7 ou superior)
2. **Bundler** instalado:

```bash
gem install bundler
```

---

## 📦 Instalar dependências

Navegue até a pasta do projeto:

```bash
cd /Users/nathan.virgilio/Documents/tecendoversos/tecendoversos
```

Instale as dependências com:

```bash
bundle install
```

---

## 🚀 Rodar o servidor local com baseurl

Como o site é hospedado em uma subpasta no GitHub Pages, use o comando com `--baseurl`:

```bash
bundle exec jekyll serve --baseurl "/tecendoversos"
```

---

## 🌐 Acessar no navegador

Abra em:

```
http://localhost:4000/tecendoversos/
```

---

## 🛑 Parar o servidor

Use `Control + C` no terminal.

---

## 🔁 Atalho opcional (alias)

Adicione isso ao final do seu arquivo `~/.zshrc`:

```bash
alias tecendo='cd /Users/nathan.virgilio/Documents/tecendoversos/tecendoversos && bundle exec jekyll serve --baseurl "/tecendoversos"'
```

Depois basta digitar `tecendo` no terminal para iniciar o servidor automaticamente.

---
