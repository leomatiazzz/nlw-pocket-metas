# Gerenciador de Metas

## Descrição
Este é um aplicativo de linha de comando para gerenciamento de metas. Ele permite que o usuário cadastre, visualize, marque como concluídas e exclua metas. Os dados são armazenados em um arquivo JSON.

## Tecnologias Utilizadas
- Node.js
- Biblioteca `@inquirer/prompts` para interação com o usuário
- Módulo `fs.promises` para manipulação de arquivos JSON

## Funcionalidades
- Cadastrar novas metas
- Listar metas cadastradas
- Marcar metas como concluídas
- Visualizar metas realizadas
- Visualizar metas pendentes
- Deletar metas

## Instalação
1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado.
2. Clone este repositório ou baixe os arquivos.
3. No terminal, navegue até a pasta do projeto e execute:
   ```sh
   npm install inquirer
   ```

## Como Executar
Para iniciar o programa, execute o seguinte comando no terminal:
```sh
node index.js
```

## Uso
O aplicativo apresenta um menu interativo com as seguintes opções:
1. **Cadastrar meta** - Permite adicionar uma nova meta.
2. **Listar metas** - Exibe a lista de metas e permite marcá-las como concluídas.
3. **Metas realizadas** - Mostra as metas que foram concluídas.
4. **Metas abertas** - Mostra as metas que ainda estão pendentes.
5. **Deletar metas** - Permite excluir metas cadastradas.
6. **Sair** - Fecha o aplicativo.

## Estrutura do Arquivo JSON
As metas são armazenadas no arquivo `metas.json` com o seguinte formato:
```json
[
  {
    "value": "Estudar Node.js",
    "checked": false
  },
  {
    "value": "Criar um projeto pessoal",
    "checked": true
  }
]
```

## Contribuição
Sinta-se à vontade para contribuir com melhorias ou sugerir novas funcionalidades. Basta abrir um pull request ou relatar problemas na seção de issues.

## Licença
Este projeto não tem nenhuma licença, feito apenas para aprendizado pessoal e acadêmico.

