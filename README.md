# Pet-List

PetList é um App desenvolvido com o framework Ionic para o projeto de estágio Veloz do grupo Ser Educacional.

O App possui em suas funções o armazenamento de uma lista retirada de uma API REST do seguinte site "http://petstore-demo-endpoint.execute-api.com/petstore/pets" onde há
existência de três botões cujo a função de cada é organizar a lista a partir das variáveis da lista: Id, Type e Price.

![image](https://user-images.githubusercontent.com/88844519/185764089-db2219e9-a98e-4afe-8617-530872e9bab1.png)

Para a instalação das dependências, é necesssário utilizar os seguintes comandos no terminal da pasta ou progama:

```npm install --local```

```npm audit --fix --force```

Caso o aplicativo não funcione por problemas de CORS(Cross-Origin Resource Sharing), aconselho desativar o CORS do navegador ou substituir a API utilizada em "src/app/home/home.page.ts" para "https://demo1287829.mockable.io/".
