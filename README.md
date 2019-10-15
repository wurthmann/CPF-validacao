# CPF-validacao
Validação de CPF via JavaScript e HTML

A validação de CPF é um processo essencial para qualquer web site atualmente, visando evitar fraldes e manter o registro de usuários correto.

Primeiramente vamos entender como funciona o CPF:

O CPF é um documento válido em território nacional e é composto por 11 digitos sendo os dois últimos chamados de digitos validadores, pois são responsáveis por validar os 9 primeiros digitos que compoem o documento.

para que possamos encontrar o primeiro digito validador devemos realizar a multiplicação de cada digito por sua posição e na sequência somar todos:

O segundo digito segue a mesma maneira, porém no calculo é utilizado o primeiro digito encontrado.

O codigo desenvolvido visa assim encontrar os digitos validadores e comparar se são os mesmos informados pelo usuário.
