
# Wiki de Jogos com Retorno Dinâmico utilizando ChatGPT

Este é um projeto de aplicação web que permite a criação de uma wiki de jogos, com um retorno dinâmico utilizando ChatGPT como ferramenta, utilizando as API's da OpenAI como base. A aplicação permitirá que os usuários adicionem informações sobre jogos e consultem informações sobre jogos já existentes.



## Funcionalidades

Algumas das funcionalidades da aplicação incluem:

+ Adicionar informações sobre jogos: os usuários poderão adicionar informações sobre jogos que já jogaram, como títulos, plataformas, gêneros, sinopses, datas de lançamento, etc.

+ Consultar informações sobre jogos: os usuários poderão pesquisar informações sobre jogos já existentes na wiki, utilizando a ferramenta ChatGPT para obter respostas dinâmicas.

+ Moderação de conteúdo: os usuários poderão denunciar conteúdo ofensivo ou inadequado, e a equipe de moderação poderá remover esse conteúdo da plataforma.
## Tecnologias Utilizadas

Algumas das tecnologias utilizadas na aplicação incluem:

+ Python: a linguagem de programação utilizada para escrever a aplicação.
+ Flask: um framework web para Python utilizado para construir a aplicação.
+ ChatGPT: uma ferramenta de processamento de linguagem natural que será utilizada para obter respostas dinâmicas sobre jogos na wiki.
+ API's da OpenAI: as API's da OpenAI serão utilizadas como base para a implementação do ChatGPT na aplicação.
+ Banco de Dados: um banco de dados será utilizado para armazenar as informações sobre os jogos adicionados pelos usuários.


## Instalação

Para instalar e executar a aplicação, siga as instruções abaixo:

1. Clone este repositório para sua máquina local.
2. Instale as dependências do projeto utilizando o gerenciador de pacotes pip:

```
pip install -r requirements.txt

```

3. Crie um arquivo .env na raiz do projeto e adicione as seguintes variáveis de ambiente:

```makefile
 FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=sua_chave_secreta_aqui
OPENAI_API_KEY=sua_api_key_aqui

```
4. Crie o banco de dados utilizando o comando abaixo:

```csharp
flask db init
flask db migrate
flask db upgrade
```

5. Execute a aplicação utilizando o comando abaixo:

```arduino
flask run

```

6. Acesse a aplicação no seu navegador utilizando o endereço http://localhost:5000.



## Contribuição

Para contribuir com o projeto, siga as instruções abaixo:

1. Faça um fork do repositório.

2. Crie um novo branch para sua contribuição:

```css
git checkout -b minha_contribuicao
```

3.  Faça suas alterações e commit as mudanças:
```sql
git commit -m "Minha contribuição"
```

4. Envie seu branch para o repositório forkado:
```pearl
git push origin minha_contribuicao
```

5. Crie um pull request.
## Licença

Este projeto é distribuído sob a licença MIT. Para mais informações, leia o arquivo LICENSE.
