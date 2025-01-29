# LH Games - Documentação do Projeto

Este documento descreve a estrutura e o funcionamento do projeto LH Games, que consiste em uma página web para uma loja de jogos.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **public/assets/imgs**: Contém as imagens utilizadas no site, como banners e logos.
- **src/pages**: Contém as páginas HTML do site.
- **src/scripts**: Contém os scripts JavaScript.
- **src/styles**: Contém os arquivos CSS para estilização.

## Passo a Passo do Desenvolvimento

### 1. Estrutura HTML (`index.html`)

- **Cabeçalho (`<head>`)**: Inclui metadados, links para Bootstrap e o arquivo CSS principal.
- **Navegação (`<nav>`)**: Barra de navegação com links para diferentes seções do site e um formulário de busca.
- **Carrossel de Banners**: Utiliza o componente Carousel do Bootstrap para exibir banners promocionais.
- **Seção de Mais Vendidos**: Exibe cards com os jogos mais vendidos.
- **Rodapé (`<footer>`)**: Contém informações de direitos autorais e links úteis.
- **Botão "Voltar ao Topo"**: Botão fixo na parte inferior direita da tela para retornar ao topo da página.

### 2. Estilização CSS (`style.css`, `home.css`, `base.css`, `login.css`)

- **`base.css`**: Reset CSS para garantir consistência entre diferentes navegadores.
- **`home.css`**: Estilos específicos para a página inicial, incluindo o carrossel e a seção de mais vendidos.
- **`login.css`**: Estilos para a página de login, incluindo o formulário de login e cadastro.

### 3. Funcionalidades JavaScript (`script.js`, `jquery.script.js`)

- **`script.js`**:

  - **Função `topo()`**: Rola a página suavemente até o topo.
  - **Evento de Clique no Botão "Comprar"**: Exibe um alerta quando um produto é adicionado ao carrinho.
  - **Validação de Login (`login()`)**: Verifica as credenciais do usuário e redireciona para a página inicial se corretas.
  - **Função `cadastro()`**: Exibe um alerta de sucesso ao cadastrar um novo usuário.

- **`jquery.script.js`**:
  - **Efeito de Esconder/Mostrar Formulário de Cadastro**: Utiliza jQuery para alternar a visibilidade do formulário de cadastro.

### 4. Página de Login (`login.html`)

- **Formulário de Login**: Permite que os usuários façam login com nome de usuário e senha.
- **Formulário de Cadastro**: Permite que novos usuários se cadastrem fornecendo nome de usuário, e-mail e senha.

## Como Executar o Projeto

1. Clone o repositório para o seu ambiente local.
2. Abra o arquivo `index.html` no seu navegador para visualizar a página inicial.
3. Navegue até a página de login clicando no link "Login" na barra de navegação.

## Dependências

- **Bootstrap**: Utilizado para estilização e componentes como o carrossel e a barra de navegação.
- **jQuery**: Utilizado para efeitos de transição no formulário de cadastro.

## Considerações Finais

Este projeto foi desenvolvido com foco em boas práticas de desenvolvimento web, incluindo a organização de arquivos, uso de frameworks e bibliotecas, e documentação clara. Para qualquer dúvida ou sugestão, sinta-se à vontade para entrar em contato.
