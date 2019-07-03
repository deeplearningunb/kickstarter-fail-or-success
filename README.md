# Kickstarter
Projeto/ estudo de Deep Learning para determinar se um projeto cadastrado no Kickstarter tem chances de ser bem sucedido ou falhar.

Para desenvolver o estudo, utilizamos os dados de 2018 [deste dataset](https://www.kaggle.com/kromel/kickstarter-successful-vs-failed).

No projeto, tivemos as seguintes considerações:
- Retiramos os *state* - que dizem se um projeto falhou ou foi bem sucedido - que fossem diferentes de *failed* ou *successful*
- Entendemos também que apenas as categorias (*main_category* e *category*), país (*country*) e a meta em dólares (*usd_goal_real*) tivessem influência nos resultados
- Assim, construímos uma rede neural artificial para tentar prever as chances de sucesso ou falha utilizando estes parâmetros

Outro alvo desejável para o estudo seria tentar estimar os seguintes dados:
- Quantas pessoas devem investir no projeto? (*backers*)
- Quanto o projeto consegue pleitear? (*usd_pledged_real*)