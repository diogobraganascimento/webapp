
# Jogo Teca

>## Sobre
> O projeto consiste na criação de uma aplicação chamada JogoTeca, onde o site exiba as seguintes informações:
>* Lista de Jogos
>* Cadastrar novos jogos
>* fazer Login 
>* Restringir acesso


### Bibliotecas utilizadas
* [Python](python.org) == 3.9
* [Flask](https://flask.palletsprojects.com/en/2.0.x/) == 2.0.3

***
### JINJA2
 * É o *motor* de templates do **Flask**. 
Ele nos ajuda com diversos helpdes enquanto 
projetamos nossos HTML de forma mais dinâmica.
> Filtros que podemos utilizar no arquivo HTML. Ex: { { titulo | title } }
>> * upper: colocar os caracteres em caixa alta;
>> * round: arredondar números;
>> * trim: remover espaços do início e do fim do texto;
>> * default ('texto exibido por padrão') - quando queremos mostrar algo, caso a variável esteja vazia ou nula.

> Tipos de delimitadores do Jinja2:
>> * { % ... % }: usado para inserir estrutura Python dentro de um arquivo html;
>> * { { ... } }: usado para facilitar a exibição de código python como um output em um template html. Alternativa { % print( ... ) % }
>> * { # ... # }: usado para adicionar comentários que não serão exibidos no *output* do template HTML.