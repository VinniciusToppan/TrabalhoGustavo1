# TrabalhoGustavo1
READ ME

# Projeto de Cadastro de Motos

Este é um projeto web simples para o cadastro, visualização, edição e exclusão de motocicletas. A interface é responsiva, moderna e permite visualizar as motos cadastradas por meio de um botão que exibe/oculta os cards de forma elegante.

## estrutura do projeto

---

##  Funcionalidades

### 1. *Cadastro de Motos*
- O usuário pode adicionar novas motos preenchendo um formulário com:
  - Marca
  - Modelo
  - Ano
  - Preço
  - Imagem
- As motos cadastradas são exibidas em formato de *card responsivo*.

### 2. *Listagem de Motos*
- Um botão no topo da página chamado *"Motos Cadastradas"* exibe/oculta dinamicamente a seção de cards.
- Os cards contêm:
  - Imagem da moto
  - Informações básicas (marca, modelo, ano, preço)
  - Botões de edição e exclusão

### 3. *Edição*
- Ao clicar em "Editar", os dados da moto selecionada aparecem no formulário.
- O usuário pode modificar os dados e salvar as alterações.

### 4. *Exclusão*
- O botão "Excluir" remove imediatamente o card da moto.

---

##  Layout e Estilo

- Utiliza *CSS puro* com uma paleta escura moderna.
- Imagem de fundo translúcida.
- Estilo responsivo para celulares e desktops.
- Animações suaves ao exibir/ocultar os cards.

---

##  Tecnologias Utilizadas

- *HTML5*: Estrutura da página
- *CSS3*: Estilização do site (layouts, responsividade, transições)
- *JavaScript Vanilla (puro)*: Funcionalidades (CRUD)

---

##  Como Usar

1. Baixe ou clone o repositório.
2. Abra o arquivo index.html em qualquer navegador moderno.
3. Use o botão *"Cadastrar Moto"* para abrir o formulário.
4. Cadastre uma nova moto preenchendo os campos e clicando em *Salvar*.
5. Clique no botão *"Motos Cadastradas"* para exibir ou esconder os cards.
6. Edite ou exclua motos diretamente nos cards.

---

##  Observações

- Os dados não são persistidos após o recarregamento da página, pois não há backend.
- O projeto pode ser facilmente adaptado para usar localStorage, um banco de dados ou API.

---

##  Melhorias Futuras

- Integração com backend (Node.js, Firebase, etc.)
- Upload real de imagens
- Filtros de busca e ordenação
- Paginação para muitos cadastros

---

##  Autor

Desenvolvido por [Seu Nome].

---
