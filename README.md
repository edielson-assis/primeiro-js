<h1>Conectando o HTML com o JavaScript</h1>
<h2>Instruções do projeto</h2>
<p>Crie um novo projeto com dois arquivos: index.html e script.js. 
  No arquivo HTML, defina a estrutura padrão HTML, e inclua uma tag h1 com o título "Conexão com um arquivo JavaScript". 
  No arquivo JavaScript defina uma função que imprima a mensagem "Conexão feita com sucesso!" no terminal, e execute ela três vezes. 
  Finalmente, conecte ambos arquivos, abra seu projeto no navegador usando a extensão LiveServer e confira se a mensagem foi impressa três vezes no terminal.
</p>

<h3>Código html</h3>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="./script.js" defer></script>
    <title>Primeiro js</title>  
</head>
<body>
    <h1>Conexão com um arquivo JavaScript</h1>
</body>
</html>
```
<h3>Código javascript</h3>

```
const conexao = () => console.log("Conexão feita com sucesso!");

for (let i = 0; i < 3; i++) {
    conexao();
}
```
