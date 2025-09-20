# Tela de Login - HTML & CSS

Este projeto é uma **tela de login responsiva** criada usando HTML e CSS puro. A interface possui campos para usuário e senha, botão de login, e uma seção ilustrativa ao lado da tela principal.

---

## 🛠 Estrutura do Projeto

- **index.html**  
  Arquivo HTML que contém a estrutura da página, incluindo:
  - Seções da tela de login (`left-login` e `right-login`).  
  - Card central com campos de entrada (`usuario` e `senha`).  
  - Botão de login.  
  - Elemento `<img>` para exibição de imagem ilustrativa.

- **style.css**  
  Arquivo CSS que define o estilo da página, incluindo:
  - Layout principal usando **Flexbox**.  
  - Cores, sombras, e bordas arredondadas.  
  - Estilização de inputs, labels e botão de login.  
  - Responsividade para telas menores usando media queries.  
  - Fonte personalizada importada do Google Fonts (`Noto Sans`).

- **financias.svg**  
  Imagem ilustrativa usada no lado esquerdo da tela de login.

---

## 🎨 Design e Layout

- Tela dividida em duas partes:
  - **Left-login**: área de apresentação com título e imagem.  
  - **Right-login**: área de interação com o card de login.
- **Card-login**: container centralizado que contém:
  - Título "LOGIN"
  - Campos de entrada (usuário e senha)
  - Botão de login estilizado
- **Estilo visual**:
  - Cores escuras de fundo com contrastes em verde neon (`#00ff88`).  
  - Bordas arredondadas (`border-radius`) e sombras (`box-shadow`) para profundidade.  
  - Tipografia clara e moderna com fonte **Noto Sans**.

---

## 📱 Responsividade

- Para telas menores que 950px: o card de login ocupa 85% da largura.  
- Para telas menores que 600px:
  - Layout muda para coluna (`flex-direction: column`).  
  - Título da esquerda é escondido para otimizar espaço.  
  - Card e imagem ajustam largura proporcional ao tamanho da tela.

---

## ⚙️ Funcionalidades

- Campos de entrada de usuário e senha.  
- Botão de login com efeito visual de clique (`cursor: pointer` e sombra).  
- Layout responsivo que se adapta a diferentes tamanhos de tela.

---

## 💡 Possíveis melhorias

- Adicionar **validação de formulário** com JavaScript.  
- Implementar **conexão com backend** para autenticação real.  
- Adicionar **mensagens de erro** para usuário e senha incorretos.  
- Animações mais avançadas para transição de tela e interação com inputs.

---

## 🔗 Referências

- [Google Fonts - Noto Sans](https://fonts.google.com/specimen/Noto+Sans)  
- Documentação oficial de [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)  
- Princípios de **UI/UX** para telas de login modernas.
