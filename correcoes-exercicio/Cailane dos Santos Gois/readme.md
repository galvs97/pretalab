Oi Cailane, tudo bem? <br>

Arrasou muito na indentação, organização de código e nomenclatura das classes. Gostei de ver, viu? <br><br>
Mas vamos aos pontos de correção: <br>
    - Faltou a barra no fechamento das tags de quebra de linha, lembra que são selfclosing ( </> )? <br>
    - O posicionamento do botão de enviar no formulário está sobressaindo e tomando espaço do footer,
    isso acontece porque no css (form textarea, linha 161) voce está definindo um tamanho pro text area e
    nesse caso seria melhor definir o tamanho do elemento pai (< form>) com as configurações que deseja, 
    uma vez que, elementos de input sempre ocupam o espaço total disponível para ele.
<br><br>
Parabéns pela entrega! ;)