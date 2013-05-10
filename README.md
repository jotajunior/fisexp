fisexp
======

Como utilizar?
--------------
Bem, existe o campo equação, e embaixo uma área para texto.<br />
Digamos que você tem que calcular o seguinte:
<br />
__Experimento sobre resistência elétrica__<br />
**R = V/I**<br />
Onde você tem **V = (5,1 +- 0,2)V** e **I = (23 +- 3)mA**<br />
E tem que encontrar R, com sua incerteza.<br />
Para o fisexp resolver isso, é só digitar no campo equação: <br />
**v/i**<br />
E no campo abaixo, colocar as variaveis da seguinte forma:<br />
**v = 5.1 +- 0.2**<br />
**i = 23 +- 3**<br />
Não se esqueça de pular linha entre uma equação e outra, e **colocar +- (nunca -+ )**.<br />
<br /><br />
Limitações
----------
- **Só pode ter um sinal de divisão na equação**<br />
- **Ainda tenho que arrumar para aceitar as mesmas variaveis no numerador e denominador (mas tenho que dormir)**<br />
- **Como já disse, por enquanto utilize para incerteza só +-. -+ vai dar erro.**<br />
- **Não está ajustado para levar em conta só número significativos**<br /><br/>

Bem, fiz essa noite, tem muita coisa pra melhorar. Mas já ajuda... E fiz em JavaScript
para rodar nos computadores do laboratório sem precisar instalar nada.<br /><br />

Quem quiser contribuir... Só mandar os commits!<br /><br />

"Facilitando a vida da "alegria" de sexta-feira"
