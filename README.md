# E-Commerce Simples 🛒

Uma aplicação de e-commerce interativa construída com React e TypeScript. Permite aos usuários navegar por um catálogo de produtos, adicionar itens ao carrinho, ajustar quantidades e concluir a compra com uma página de agradecimento dinâmica.

## Funcionalidades 🚀

- **Navegação Simples**: Catálogo de produtos, carrinho de compras e página de agradecimento.
- **Gerenciamento de Carrinho**:
  - Adicionar itens ao carrinho.
  - Atualizar quantidades de produtos.
  - Remover itens do carrinho.
  - Exibição do total do pedido.
- **Finalização de Compra**: Exibe um resumo detalhado dos itens adquiridos e o total na página de agradecimento.
- **Feedback ao Usuário**: Notificações toast para ações como adicionar itens, atualizar quantidades ou finalizar a compra.

## Tecnologias Utilizadas 🛠️

- **React**: Biblioteca principal para construção da interface.
- **React Router**: Gerenciamento de rotas para navegação entre páginas.
- **React Toastify**: Notificações de feedback para os usuários.
- **TypeScript**: Adiciona tipagem estática para maior segurança no código.

## Estrutura do Projeto 📂

- **`App.tsx`**: Componente principal que gerencia o estado do carrinho e a navegação.
- **`Catalog`**: Exibe o catálogo de produtos com a opção de adicionar ao carrinho.
- **`Cart`**: Lista os itens no carrinho, com opções para atualizar ou remover itens, além de mostrar o total.
- **`CartItem`**: Componente para exibir e gerenciar cada item no carrinho.
- **`Product`**: Exibe os detalhes de cada produto no catálogo e a opção de selecionar quantidade.
- **`ThankYouPage`**: Página de agradecimento após a conclusão da compra.
- **`CheckoutButton`**: Botão para finalizar a compra e redirecionar para a página de agradecimento.
- **Mock de Dados**: Produtos carregados de um arquivo JSON local para simular uma API.

## Como Usar 📖

### Pré-requisitos

- Node.js instalado.

### Passo a Passo

1. Clone o repositório:

   ```bash
   git clone https://github.com/Biazanchin/ecommerce.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd ecommerce
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

5. Acesse no navegador: [http://localhost:5173](http://localhost:5173)

## Funcionalidades Principais 🔄

### Catálogo de Produtos

- Exibe uma lista de produtos com imagem, nome, preço e um seletor de quantidade.
- Permite adicionar produtos ao carrinho com a quantidade escolhida.

### Carrinho de Compras

- Lista todos os produtos adicionados ao carrinho com suas quantidades e preços.
- Permite:
  - Atualizar a quantidade de itens diretamente no carrinho.
  - Remover itens específicos do carrinho.
- Mostra o preço total do pedido.

### Finalização de Compra

- Página de agradecimento que exibe um resumo da compra, incluindo itens, quantidades e preço total.
- Botão para retornar ao catálogo de produtos.

### Feedback em Tempo Real

- Notificações toast para:
  - Confirmar itens adicionados ao carrinho.
  - Informar atualizações de quantidade.
  - Confirmar a remoção de itens.
  - Alertar sobre carrinho vazio ao tentar finalizar a compra.

## Visualização 👀
![image](https://github.com/user-attachments/assets/a72b0918-dd3c-4b68-bee6-637959b73311)
![image](https://github.com/user-attachments/assets/06d71f45-7975-4fc0-8ab6-0e484fa4e5b4)
![image](https://github.com/user-attachments/assets/e4cf6937-8dba-44ca-af4a-b0834852554d)




