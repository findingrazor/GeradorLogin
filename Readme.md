# Gerador de Login e Senha em Java

## Descrição

Olá! Esse código também foi um exercício da faculdade porém para uma matéria com Java.
Aqui eu ainda não tinha aprendido o conceito de orientação a objeto então é apenas um código
simples que gera um login e uma senha baseado no seu nome. Tem algumas válidações e eu tinha
começado a usar métodos. Talvez tenha alguns comentários no código que se não me engano são
erros que corrigi depois. Para meus códigos em Java eu uso o eclipse, pelo costume que adquiri
na faculdade. 

Vou deixar apenas o enunciado aqui caso alguém se interesse!

### Enunciado

Fazer um programa em Java que receba via teclado a digitação de até 30 nomes de pessoas.

Para cada um dos nomes digitados o programa deverá conter um método para gerar e retornar um Login e uma Senha.
Após gerados o login e senha o programa deverá exibi-los na tela.

O Login será a formado da concatenação da primeira letra de cada nome em maiúsculo. E a senha será formada da concatenação do primeiro dígito do valor ASCII Decimal de cada letra do Login.

Ex: nome digitado: jose maria alves dos santos
Login gerado: JMADS(códigos ASCII decimais: J=74, M=77, A=65, D=68, S=83)
Senha gerada: 77668

Obs: 
Consistir a entrada de dados para que o nome da pessoa digitado:
- Tenha o tamanho mínimo de 15 caracteres;
- Não deve existir caracteres espaço antes do primeiro nome;
- Deve existir pelo menos 1 nome e 1 sobrenome;
- Deve existir apenas 1 espaço entre o nome e sobrenomes;
- Só possua letras em cada nome;
- Criar um FLAG para encerrar a entrada de dados.