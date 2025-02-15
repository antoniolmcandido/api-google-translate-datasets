# 📜 Projeto de Tradução de Posts com Google Translate API 🇬🇧➡️🇧🇷
> Transformando o mundo em um lugar mais conectado, uma tradução de cada vez! 🌍💬

Este projeto utiliza a API do Google Translate para traduzir 29.604 posts de usuários do inglês para o português de forma automatizada. Imagine conseguir compreender o conteúdo compartilhado por pessoas ao redor do mundo, superando a barreira do idioma! 💡

## 🎯 Objetivo
O principal objetivo deste projeto é traduzir posts de usuários, originalmente escritos em inglês, para o português, utilizando a API do Google Translate. Isso possibilita que uma vasta quantidade de conteúdos seja acessada e compreendida de maneira rápida e eficiente, contribuindo para a inclusão digital e intercâmbio de ideias entre culturas. 🌐

## 🚀 Tecnologias Utilizadas
- Python 🐍: Linguagem de programação principal para o desenvolvimento do script.
- Google Translate API 🌍: Serviço de tradução automática da Google, que foi utilizado para realizar as traduções dos posts.
- Requests 📡: Biblioteca Python para fazer requisições HTTP, essencial para a interação com a API.
- JSON 🧩: Formato utilizado para armazenar e manipular os dados dos posts traduzidos.
- Pandas 📊: Para organização e processamento dos dados em formato tabular, facilitando a análise e exportação.

## 💡 Como Funciona
1. Coleta dos Posts: O projeto começa com a coleta de posts de usuários que estão no idioma inglês.
2. Envio para a API: Para cada post, o conteúdo é enviado para a Google Translate API, onde a tradução é realizada de maneira automática.
3. Armazenamento dos Dados: Após a tradução, os dados são armazenados e organizados com o auxílio de Pandas.
4. Exportação: O resultado pode ser exportado em diferentes formatos, como XLSX, CSV ou JSON, para posterior análise ou uso em outras aplicações.

## ⚙️ Como Rodar o Projeto
Para executar este projeto, basta seguir os passos abaixo:

### 1. Clonar o Repositório
```bash
git clone https://github.com/antoniolmcandido/google-api-translate-datasets.git
```
### 2. Instalar Dependências
Instale todas as dependências necessárias utilizando o pip:
```bash
pip install pandas numpy tqdm googletrans
```
## 3. Rodar o Script de Tradução
Com tudo configurado, basta rodar o script para realizar a tradução dos posts, para isso utilize o jupyter notebook.

## 4. Obter os Resultados
O script irá gerar um arquivo posts_traduzidos.xlsx com os posts traduzidos. Você pode abrir esse arquivo no Excel ou outro editor de sua preferência para visualizar os resultados.

## 🎨 Exemplo de Resultado
Aqui está um exemplo de como um post traduzido se pareceria:

| **Post Original**                           | **Post Traduzido**                             |
|---------------------------------------------|-----------------------------------------------|
| "I love exploring new places!"              | "Eu adoro explorar novos lugares!"            |
| "The weather today is just perfect."        | "O clima hoje está simplesmente perfeito."    |
| "Can't wait for the weekend to arrive!"     | "Mal posso esperar para o fim de semana chegar!" |


## 🔧 Como Personalizar
Você pode personalizar o projeto conforme suas necessidades! Algumas opções de personalização:

- Alterar o idioma de tradução (ex: de inglês para francês, espanhol, etc.).
- Modificar a forma de armazenamento dos dados, exportando para outros formatos ou integrando com bancos de dados.
- Configurar o número de posts a ser traduzido para adaptar ao seu projeto específico.

## 📋 Licença
Este projeto é licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## 💬 Contribuições
Contribuições são bem-vindas! Se você tiver alguma melhoria ou correção, sinta-se à vontade para abrir um pull request. Vamos juntos melhorar a acessibilidade e a troca de informações no mundo! 🌍

## 💻 Instalação Rápida - Passo a Passo Visual
1. Clone o Repositório.
2. Instale as Dependências.
3. Execute o Script.

## 🙋‍♂️ Precisa de Ajuda?
Se você tiver alguma dúvida ou precisar de ajuda para configurar o projeto, não hesite em abrir uma issue no repositório. Eu vou responder assim que possível! 😄

## 🎉 Agradecimentos
Este projeto foi inspirado na potencialidade das APIs modernas e na facilidade de acesso a dados de diversas fontes. Obrigado ao time da Google Cloud pela incrível API de tradução, e ao Python pela sua flexibilidade e poder! 🙌

Vamos juntos transformar a comunicação no mundo! 🌍✨

## Documentação Biblioteca Googletrans Python
[https://pypi.org/project/googletrans](https://pypi.org/project/googletrans)
