# Front-end Challenge - Doc88

A necessidade é desenvolver o projeto "Pastel de Ideias", onde o usuário pode criar um cardápio para sua pastelaria. #DeuFome

## Instruções para entrega

* Versione, com git, e hospede seu código em algum serviço de sua preferência: github, bitbucket, gitlab ou outro.
* Crie um README com instruções claras sobre como executar sua obra.
* Envie um email com o link do seu repositório para bruno.cesar@doc88.com.br
* Dúvidas podem ser enviadas para o mesmo email acima.

## Layout e Material

Todos os assets necessários para o desenvolvimento estão disponíveis para download em https://xd.adobe.com/spec/855f4c8d-dd32-45f7-784b-3b38f80782fa-f36e/

![Captura de Tela (1)](https://user-images.githubusercontent.com/1139893/66259052-0c9f2880-e783-11e9-9cde-6dfe432ebd8a.png)

## Requisitos

* Implemente o HTML/CSS da tela com base no layout disponível em https://xd.adobe.com/view/4bdff275-a804-4a06-5f3a-5197149e261f-3dee/screen/493ba0b0-f711-4e85-86dc-e8deadd7d02b/Web-1920-4?fullscreen
* O projeto deve ser uma *single page application (SPA)* escrita utilizando Vue ou Nuxt.
* Campos "título do pedido" e "sabor" devem ser: obrigatorios, do tipo texto, mínimo de 3 e máximo de 60 caracteres.
* Campo "preço" deve ser: obrigatorio e do tipo numero.
* Campo "descrição" deve ser do tipo texto. 
* Campo "imagem" deve mostrar um preview da imagem ao fazer o upload e aceitar apenas arquivos no formato .jpg ou .png. 
* Campo "comida para bebida", ao alterar deve manter informações no formulário.
* Ao clicar no botão "Limpar" todos os campos devem ficar vazios, inclusive a imagem.
* Ao clicar no botão "Cadastrar" os dados do item devem ir para lista de pedidos, sendo que o último pedido cadastrado deverá ir para o topo.
* Na lista de pedidos, caso não tenha imagem cadastrada, usar uma padrão.
* Não é preciso se preocupar com persistência dos dados. É esperado que o itens cadastrados sejam perdidos com o recarregamento da página (F5).

## Requisitos Opcionais

* Tornar o layout responsivo.
* Desenvolvimento de testes unitários no Javascript.
* Padronização do código: seguir algum styleguide de Javascript e/ou CSS.
* Aplicação das animações de transição.
* Upload de imagem com drag and drop (Arrasta e solta).
* Efeito paralax no pastel que está desfocado. Algo como o aplicado no site https://buffalowax.com
* E qualquer outra sugestão sua

## Critérios de avaliação

* Fidelidade ao layout solicitado;
* Fidelidade às funcionalidades solicitadas;
* Componentização e extensibilidade dos componentes Javascript;
* Clareza de nomenclatura do CSS;
* HTML estruturado de forma semântica;
* Requisitos Opcionais
