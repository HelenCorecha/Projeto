# Programa de Consulta de Signos

Este é um projeto simples em PHP que permite aos usuários consultar informações sobre signos com base em seus dados fornecidos. O programa foi desenvolvido utilizando o servidor XAMPP e uma estrutura de diretórios organizada.

## Funcionalidades

- Enviar dados por meio de um formulário (utilizando o método HTTP POST).
- Processar os dados recebidos para identificar o signo do usuário.
- Exibir informações sobre o signo correspondente.

## Estrutura do Projeto

O projeto segue uma organização em diretórios para facilitar a manutenção e expansão:

- `assets/`: Contém recursos estáticos, como arquivos CSS, JavaScript, imagens e outros.
- `layouts/`: Contém os arquivos relacionados ao layout, como cabeçalhos, rodapés e outras partes reutilizáveis.
- `index.php`: Arquivo principal para exibição do formulário e gerenciamento das requisições.
- `process.php`: Arquivo responsável por processar os dados enviados pelo formulário e retornar o resultado.

## Como Executar o Projeto

1. Certifique-se de que o **XAMPP** está instalado em seu computador.
2. Coloque o diretório do projeto dentro da pasta `htdocs` do XAMPP.
3. Inicie o servidor Apache no painel de controle do XAMPP.
4. Abra o navegador e acesse o projeto por meio do endereço: `http://localhost/nome-do-projeto`.

## Exemplo de Uso

1. Preencha o formulário com os dados necessários (como data de nascimento).
2. Clique em "Enviar".
3. O programa processará as informações e exibirá o signo correspondente e seus detalhes.

## Tecnologias Utilizadas

- **PHP**: Para o desenvolvimento do back-end.
- **HTML**: Para a estrutura do formulário e exibição de informações.
- **CSS**: Para estilizar a interface (armazenado em `assets`).
- **XAMPP**: Para criar um ambiente local de desenvolvimento.

## Melhorias Futuras

- Adicionar suporte para diferentes idiomas.
- Incluir mais informações sobre cada signo.
- Melhorar o design utilizando frameworks como Bootstrap.
- Permitir integração com APIs para obter dados mais completos sobre signos.

---

Sinta-se à vontade para contribuir ou fazer melhorias!
