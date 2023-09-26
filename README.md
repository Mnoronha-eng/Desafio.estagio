Desafio estágio IATECAM
- O presente código tem por objetivo servir de parâmetro para
medir meus conhecimentos na área programação pelos 
avaliadores do mesmo instituto.

1. Do projeto
- Trata-se de uma Funcionalidade de cadastro de usuários, onde
o usuário pode fazer seu cadastro inserindo um e-mail válido,
nome, senha e marcar o status do mesmo como ativo ou excluído.
Iniciei o projeto visualizando o modelo a mim provido, e ao
visualizar alguns elementos, decidi iniciar pelo HTML, que é
o que me sinto mais confiante para trabalhar.

1.1 Do HTML
- Iniciei usando as seguintes tags para o HTML: DOCTYPE(tag padrão de HTML),
- <html lang="pt-br"> para definitir que o idioma é português do Brasil,
<head></head> e <body></body> e à partir disso, fui direto para a 
criação das tabelas requeridas onde adicionei os seguintes 
espaços: Nome, e-mail e opções para ser a tela
inicial de cadastro de usuários com um botão com a função NOVO,
que ao clicar, nos leva para outra aba de criação de usuário
com espaços para preenchimento com dados do usuário como 
e-mail, nome, senha e status através da tag lin <a></a>.
No status, decidi utilizar a tag LABEL com as opções de valores
atribuídos excluído e ativo afim de melhorar a experiência do
usuário.

1.2 Do CSS
- Para estilização optei iniciar trabalhando na divisão das caixas
dos botões da interface de cadastro de novo usuário margeando os botões
com padding, adicionando em seguida cor branca, de fundo e bordas
arredondadas afim de contrastar com a cor de fundo que optei por ser
uma cor azul claro utilizando as seguintes tags para CSS:
<style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
Utilizei também o seguinte comando para melhorar a mesma interface:
"}
.formulario{
    display: flex;
    flex-direction: column;
}"
Assim para que as seções de nome, e-mail, senha e status ficassem
em formato de coluna e não na mesma linha.

        
1.3 Do JavaScript
Utilizei a sessão de JavaScript para obter os parâmetros que eu buscava 
na aplicação, preenchimento dos campos do formulário, trabalhar o comportamento
das caixas como inserir nome, e-mail e etc e serem armazenados no próprio código através
do localStorage.setItem('registros', JSON.stringify(registros))" e caso queira excluir,
"row.parentNode.removeChild(row);

APRENDIZADO
  - Durante o desenvolvimento do projeto aprendi muitas coisas como um pouco mais sobre o JavaScript, o qual ainda preciso treinar
  e melhorar bastante e me tornei bem mais confiante com minhas habilidades em HTML e CSS, me sentindo confiante
  até parar criar um projeto igual a esse ou até um pouco mais complexo.
  
