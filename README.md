# 🌿 Ouvir & Cuidar  
### Plataforma Web para ONGs – Experiência Prática III (JavaScript Avançado)

## 🧩 Descrição do Projeto
**Ouvir & Cuidar** é uma plataforma web desenvolvida para auxiliar ONGs a divulgarem seus projetos, gerenciar voluntários e promover doações.  
Nesta terceira entrega, o foco é a implementação de **JavaScript avançado**, transformando o site estático das etapas anteriores em uma aplicação **dinâmica, validada e interativa**.

---

## 🎯 Objetivos da Entrega III
A atividade tem como objetivo aplicar conhecimentos de **JavaScript** para criar uma experiência de navegação fluida e moderna, integrando manipulação de DOM, SPA e validações consistentes.

### ✅ Requisitos Atendidos
- Manipulação avançada do DOM  
- Sistema básico de Single Page Application (SPA)  
- Templates dinâmicos carregados via JavaScript  
- Verificação de consistência de dados em formulários  
- Estrutura modular e código organizado  

---

## 💡 Funcionalidades Implementadas

### 🧭 Navegação SPA (Single Page Application)
O arquivo `js/spa.js` implementa um **roteador SPA** que:
- Intercepta os cliques dos links do menu;
- Carrega o conteúdo das páginas sem recarregar o site;
- Atualiza o histórico de navegação (`pushState`);
- Mantém a responsividade e acessibilidade das páginas.

### 🧾 Máscara e Validação de Formulário
Na página `cadastro.html`, foi implementado um **sistema de consistência de dados**:
- Máscara automática para **CPF**;
- Validação de:
  - Campos obrigatórios;
  - Formato de e-mail;
  - CEP (00000-000);
  - CPF (000.000.000-00);
  - Estado (2 letras);
  - Idade mínima de 18 anos;
  - Datas futuras inválidas.

Mensagens de erro são exibidas dinamicamente, com rolagem automática até o primeiro erro.


---

### 🎨 Feedback Visual (CSS Integrado)
Campos inválidos recebem destaque visual com borda vermelha e texto de aviso, garantindo **acessibilidade e clareza**.

---

## 🧠 Tecnologias Utilizadas
- **HTML5 Semântico**
- **CSS3 Responsivo (Grid e Flexbox)**
- **JavaScript ES6+**
- **DOM Manipulation**
- **Fetch API e History API (para o SPA)**

---

## 🧩 Estrutura Modular do JavaScript

| Arquivo | Função |
|----------|--------|
| `spa.js` | Controla o roteamento, máscaras, validação e integração dinâmica das páginas. |

---
## 🧩 Conclusão

O projeto Ouvir & Cuidar demonstra o uso integrado de HTML5, CSS3 e JavaScript, oferecendo uma base sólida para aplicações web acessíveis e modernas voltadas ao terceiro setor.
Essa etapa final reforça habilidades essenciais de interatividade, modularidade e experiência do usuário.

---

## ✍️ Autoria

Desenvolvido por: Letícia Ferraz


---

## 🧩 Acesse aqui

Parte III [AQUI](https://leticiaferraz00.github.io/Ouvir-Cuidar-III/)
