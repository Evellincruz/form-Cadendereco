# Cadastro de Endereços

## Descrição

O Cadastro de Endereço é uma aplicação web interativa projetada para facilitar o registro de endereços através do uso de CEPs. Com uma interface simples e intuitiva, os usuários podem inserir um CEP e automaticamente visualizar os dados relacionados ao endereço, como rua, número, bairro, cidade e estado, poupando tempo e evitando erros manuais.

## Tecnologias Utilizadas

HTML5: Para a estruturação semântica da página.

CSS3: Para estilização e design responsivo (index.css).

JavaScript ES6: Para funcionalidades interativas e manipulação de dados (java.js).

## Funcionalidades
Entrada de CEP: Campo para o usuário inserir seu CEP.

Preenchimento Automático: Os campos de endereço são preenchidos automaticamente com base no CEP fornecido.

Validação de CEP: O sistema verifica se o CEP possui 8 dígitos e se contém apenas números.

Limpeza de Formulário: Campos são automaticamente limpos antes de um novo preenchimento.

Mensagens de Alerta: O usuário é notificado se o CEP inserido for inválido ou se não for encontrado.

## Como Funciona
Limpeza do Formulário: Ao iniciar a busca, todos os campos de endereço são limpos para evitar confusão com dados anteriores.

Validação do CEP: O CEP deve ser composto por exatamente 8 dígitos numéricos. A aplicação utiliza expressões regulares para garantir essa validação.

Consulta: Após a validação, o CEP é usado para fazer uma chamada de dados. Se o CEP for válido, os dados do endereço são retornados.

Preenchimento dos Campos: Se retornar dados válidos, os campos de endereço são preenchidos automaticamente. Caso contrário, uma mensagem de alerta é exibida.

Acessibilidade: A aplicação é projetada para ser acessível e responsiva, funcionando em diferentes tamanhos de tela.

## Como Usar
Clone o repositório:

Copiar código
git clone <https://github.com/Evellincruz/form-Cadendereco.git> 

Abra o arquivo index.html em um navegador de sua escolha.

Insira o CEP desejado no campo apropriado e pressione "Enter" ou clique fora do campo para acionar a busca.

Visualize os dados preenchidos automaticamente nos campos de endereço.
