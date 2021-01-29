# Shipay-QA-Challenge
Teste para a vaga de Qa na Shipay

# 1.- Quais são os itens que compõem um plano de teste e um caso de teste?
R: São eles os requisito, cenários de testes, definir cronograma das atividades, modelagem de negocio, ferramentas a serem utilizadas.

# 2.- Descreva como você faria para testar e avaliar um serviço de uma API REST (CRUD)?
R: validar documentação de Api, validar que seja retornado os dados corretamentes, se a resposta está de acordo, se o JSON ou xml está correto,  se o content-type alterado, o comportamento continua o mesmo, se quando der erro o status está de acordo com os códigos de erro,  se uma requisição com informações incompleta, qual será o comportamento da requisição

# 3.- Como você lidaria com CAPTCHA em um formulário de Login em testes automatizados de Front-End?
R: Por definição, captcha não pode ser automatizado. Justamente pelo fato de que ele é feito para diferenciar humanos de máquinas
Uma solução é conversar com o dev team pra ter um jeito de testar que seja ativado somente em ambiente não produtivo ou usar serviços que emulam captchas e são específicos para teste. Tipo o http://www.deathbycaptcha.com/

# 4.- Descreva quais seriam os critérios que você utilizaria para definir quais testes automatizar?
R: Testes de funcionalidade mais critica e testes com alta frequencia de uso, que são os testes com cenários repetitivos

# 5.- Descreva quais métricas você considera para avaliar a qualidade de um código?
R: Facilidade de leitura e inteligibilidade de código, cobertura de testes unitários, performance e uso de recursos (banco de dados e processamento)
Existe tb ferramentas voltadas para a verificação de códigos

# 6.- Escreva um teste de aceitação utilizando BDD para validar o atendimento da seguinte "User Story": Como um vendedor, gostaria de consultar preços de produtos (pelo nome) para que eu possa informar o mesmo aos clientes. Considere que a funcionalidade da busca esteja na View principal do sistema, logo após a página de login inicial.
R: Dado que eu acesso a página inicial e informo usuário (xxx) e senha (xxx)
   E entro na página principal
   E seleciono o campo de busca informando o nome do produto desejado
   Então devo ser direcionado para a tela de resultado de busca de produtos
   
# 7.- Você está trabalhando em uma automação de uma aplicação legada que possui funcionalidades críticas para o negócio. Uma atualização do sistema foi aprovada e os desenvolvedores planejam utilizar um software de um terceiro para prover a nova funcionalidade. O software terceiro já foi testado, entretanto a interface existente entre o software existente e o novo software é problemática. A sua automação de testes precisa ser estendida para passar a testar a interface entre os dois produtos. Como você planejaria a abordagem de implementação da melhor solução de automação?

a) Desenvolver a automação de testes para o sistema todo incluíndo o legado e o software terceiro.

b) Investigar se a automação é possível através das APIs utilizadas para integração com o software terceiro. (resposta correta)

c) Desenvolver uma nova automação para testar via a GUI do software terceiro.

d) Investigar se a automação pode ser implementada utilizando a CLI para substituir a automação GUI existente.
