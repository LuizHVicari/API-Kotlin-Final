# Exercício: Integração de Autenticação e API REST no Aplicativo Android

Aluno: Luiz Henrique Birck Vicari

## Estrutura do APP:

O aplicativo desenvolvido contém as seguintes páginas:

- Página de Login com SMS
- Página de listagem de carros
- Pagina de detalhe do carro
- Página de criar um carro

Após fazer o Login, o Logout pode ser feito pelo botão presente na TopAppBar com ícone de saída.

As funcionalidades de deletar e atualizar um item estão presentes na tela de detalhes.

Para criar um veículo, é necessário preencher todos os dados e enviar a foto, aguardando que a url da foto no armazenamento seja recuperada.

## Possível Bug

Ao testar o aplicativo, em um emulador ele teve alguns error na tela de criar carro, acredito que possa ser algum uso excessivo de memória na aquisição das imagens, porém não fui capaz de encontrar o problema com os Logs do sistema.

