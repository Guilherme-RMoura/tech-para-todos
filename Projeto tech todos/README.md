# Tech para Todos - Plataforma Web de Inclusão Digital

Projeto acadêmico desenvolvido para a disciplina de **Desenvolvimento Front-End Para Web** (Bacharelado em Engenharia de Software).

---

## 📌 Sobre o Projeto
O **Tech para Todos** é uma plataforma web criada para apoiar uma organização não governamental fictícia focada em democratizar o ensino de programação e infraestrutura de TI para jovens de escolas públicas. A aplicação oferece presença digital profissional, divulgação de cursos, captação de recursos e captação de voluntários.

---

## 🗂️ Estrutura de Diretórios
O repositório está organizado de forma limpa e modular:

```text
tech_para_todos/
├── index.html              # Página Inicial (Institucional, Missão/Visão/Valores, Eixos e Contato)
├── projetos.html           # Cursos Práticos, Cronograma Geral, Voluntariado e Como Doar
├── cadastro.html           # Formulário de Cadastro e Voluntariado com Máscaras e Validação
├── README.md               # Documentação técnica do projeto
├── css/
│   └── style.css           # Estilização completa em CSS3 (sem frameworks externos)
└── img/
    ├── modulo1_html_css.jfif
    ├── modulo2_JS.jfif
    ├── modulo3_JS2.jfif
    ├── modulo1_manutencao.jfif
    ├── modulo2_manutencao.jfif
    └── modulo3_manutencao.jfif
```

---

## 🚀 Tecnologias Empregadas
- **HTML5 Semântico**: Uso de tags semânticas estruturantes (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<fieldset>`, `<legend>`, `<table>`, `<footer>`) em conformidade com as diretrizes do W3C.
- **CSS3 Moderno**: 
  - Layout totalmente responsivo utilizando **Flexbox** e **CSS Grid**.
  - Variáveis de tema (CSS Custom Properties) para padronização de cores e tipografia.
  - Breakpoints para dispositivos móveis e desktops.
  - Sem uso de bibliotecas externas (Bootstrap, Tailwind, etc.), atendendo ao escopo da disciplina.
- **JavaScript Nativo (Vanilla JS)**:
  - Máscaras dinâmicas de preenchimento em tempo real para **CPF**, **Telefone/WhatsApp** e **CEP**.
  - Validação nativa com métodos e atributos de restrição HTML5.

---

## 📋 Páginas do Sistema
1. **Home (`index.html`)**:
   - Apresentação da ONG, missão, visão e valores.
   - Eixos de atuação com imagens ilustrativas.
   - Informações completas de contato (endereço, telefone, e-mails e horários).

2. **Projetos Sociais (`projetos.html`)**:
   - Cards detalhados dos 6 módulos práticos (Trilhas de Desenvolvimento Web e Manutenção de Hardware).
   - Tabela responsiva de cronograma de turmas com datas de início e término.
   - Seção explicativa sobre **Como Doar** (doação de equipamentos e apoio via PIX).
   - Chamada para voluntariado.

3. **Cadastro (`cadastro.html`)**:
   - Formulário categorizado por perfis (Voluntário, Doador, Aluno e Visitante).
   - Campos com validações nativas: Nome Completo, E-mail, CPF, Telefone, Data de Nascimento, CEP, Logradouro, Número, Bairro, Cidade e Estado.

---

## 💻 Como Executar
1. Clone o repositório ou baixe o código fonte:
   ```bash
   git clone https://github.com/SEU-USUARIO/tech-para-todos.git
   ```
2. Abra a pasta do projeto no seu editor de código (ex: VS Code).
3. Abra o arquivo `index.html` em qualquer navegador web (Google Chrome, Firefox, Edge, etc.) ou utilize a extensão **Live Server**.

---

## 👨‍💻 Autor
- **Guilherme Moura**
- Curso: Engenharia de Software
- Disciplina: Desenvolvimento Front-End Para Web
