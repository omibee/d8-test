## Teste prático Drupal 8

Duração prevista: **45 a 60 min**.

 **[OBRIGATÓRIO]** Versiona tudo o que fizeres, mesmo que não tenhas concluído, numa branch `primeiroNome_segundoNome` no repositório a partir do qual vais clonar o projecto.

#### Requisitos
 - Computador com LAMP stack instalada e operacional
 - Skype e microfone pronto para fazer screencast


## Exercício

 1. Clona o repositório em https://git.omibee.com/jmachado/d8-test para o teu ambiente de desenvolvimento
 2. Instala o Drupal
 3. Instala e activa o tema [Bootstrap](https://www.drupal.org/project/bootstrap) para Drupal 8 com o Composer
 4. Cria um content-type "Post" com os campos default.
 5. Acrescenta um campo Media Entity ao content-type "Post", do tipo "Image"
 6. Exporta e versiona a configuração do trabalho feito até agora.
 7. Cria um módulo custom chamado `primeiroNome_ultimoNome_overrides` e usa um hook para acrescentar uma checkbox ao formulário de criação/edição do teu content-type "Post". Essa checkbox deve ter na label o texto "Concordo com a publicação" e a criação do node do tipo "post" só deve acontecer caso essa checkbox esteja marcada.
 8. Descreve (por exemplo no README.txt do teu módulo custom) e implementa uma solução usando um serviço que faça com que os nodes do tipo "Post" sejam automaticamente despublicados uma semana após a sua criação. 

