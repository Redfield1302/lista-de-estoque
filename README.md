# lista-de-estoque
Lista de Itens com Armazenamento Local  Este projeto é uma aplicação web simples para gerenciar uma lista de itens com quantidade. Os itens podem ser adicionados, editados e removidos. Os dados são armazenados no localStorage para persistência entre as sessões do navegador.
Funcionalidades

    Adicionar Itens: Permite adicionar novos itens à lista com um nome e uma quantidade.
    Editar Itens: Permite editar a quantidade de um item existente.
    Remover Itens: Permite remover um item da lista.
    Persistência: Os itens são armazenados no localStorage do navegador, garantindo que a lista persista entre as sessões.

Tecnologias Utilizadas

    HTML: Estrutura básica da página.
    CSS: Estilos para a apresentação visual (se aplicável).
    JavaScript: Lógica para manipulação da lista e armazenamento dos itens no localStorage.
    Como Funciona

    Carregar Itens: Ao carregar a página, a função carregarItens é chamada para recuperar e exibir itens previamente armazenados no localStorage.
    Adicionar Itens: O usuário pode adicionar um item à lista preenchendo os campos de nome e quantidade e clicando no botão "Adicionar". O item é então adicionado à lista e salvo no localStorage.
    Editar Itens: Ao clicar no botão "Editar" de um item, o usuário pode modificar a quantidade do item. As mudanças são salvas automaticamente no localStorage.
    Remover Itens: Ao clicar no botão "Remover" de um item, o item é removido da lista e o estado atualizado é salvo no localStorage.
