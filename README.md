# Cardápio Interativo

Este projeto foi desenvolvido para a matéria de Programação para Dispositivos Móveis. O objetivo do aplicativo é fornecer uma plataforma interativa para visualizar e gerenciar um cardápio de pratos de um restaurante, facilitando o acesso e a organização das informações dos clientes.

## Funcionalidades do Aplicativo

### Tela de Restaurantes
A tela de Restaurantes exibe uma lista de restaurantes disponíveis. Cada item na lista apresenta informações básicas sobre o restaurante, como nome e localização. Ao tocar em um restaurante, o usuário é direcionado para a tela de pratos específicos desse restaurante.

![Tela Restaurantes](https://github.com/eduardolopesx02/Cardapio-Interativo-Trabalho-Mobile/assets/143762383/fb2220a3-8e17-4adc-bc7a-601857b16d90)

### Tela de Pratos
A tela de Pratos exibe uma lista de pratos disponíveis no restaurante selecionado. Cada prato é apresentado com seu nome, descrição e preço. Ao tocar em um prato, o usuário é direcionado para a tela de detalhes do prato.

![Tela Pratos](https://github.com/eduardolopesx02/Cardapio-Interativo-Trabalho-Mobile/assets/143762383/429a1550-92dc-43bf-9b5f-2c5d1827c82d)

### Tela de Produto
A tela de Produto exibe informações detalhadas sobre um prato específico, incluindo uma imagem do prato, seu nome, descrição, e preço. Além disso, há um botão para adicionar o prato aos favoritos.

![Tela Produto](https://github.com/eduardolopesx02/Cardapio-Interativo-Trabalho-Mobile/assets/143762383/c7c45f7d-b6b6-48cc-b239-6d8c7bc605fb)

### Tela de Favoritos
A tela de Favoritos exibe uma lista dos pratos que o usuário marcou como favoritos. O usuário pode visualizar rapidamente todos os seus pratos favoritos e gerenciar essa lista, removendo pratos quando necessário.

![Tela Favoritos](https://github.com/eduardolopesx02/Cardapio-Interativo-Trabalho-Mobile/assets/143762383/80dc1f97-65f8-4ed8-81da-bba0e9f2a77d)

## Tecnologias Utilizadas

- **Flutter:** Framework utilizado para o desenvolvimento da aplicação.
- **Dart:** Linguagem de programação utilizada com o Flutter.
- **JSON:** Utilizado para armazenar e acessar os dados dos pratos de forma estática ("mock").
- **Visual Studio Code:** IDE escolhida para o desenvolvimento, oferecendo recursos avançados de edição e depuração.

## Descrição das Telas

### Tela de Restaurantes
Esta tela apresenta uma lista de todos os restaurantes disponíveis. Os dados são recuperados e exibidos em um formato de lista, permitindo que o usuário selecione um restaurante para ver mais detalhes sobre seus pratos.

### Tela de Pratos
Após selecionar um restaurante, esta tela mostra uma lista de pratos disponíveis no restaurante selecionado. Cada prato na lista pode ser selecionado para visualizar detalhes mais específicos na tela de Produto.

### Tela de Produto
Nesta tela, são exibidos detalhes completos sobre um prato específico, incluindo uma imagem do prato, descrição detalhada, e preço. Há também um botão que permite ao usuário adicionar o prato aos seus favoritos.

### Tela de Favoritos
Esta tela agrega todos os pratos que o usuário marcou como favoritos, facilitando o acesso rápido aos pratos preferidos. O usuário pode gerenciar sua lista de favoritos, removendo itens conforme necessário.
