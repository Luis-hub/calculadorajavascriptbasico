# calculadorajavascriptbasico
Feito em html css e javascript basico
<! DOCTYPE html >
< html  lang = " pt-br " >
    < cabeça >
        < título > </ título >
        < meta  charset = " UTF-8 " >
        < meta  name = " viewport " content = " width = device-width, initial-scale = 1 " >
        < link  href = " style.css " rel = " stylesheet " >
    </ head >
    < corpo >
            < div  class = " fundo " >
                < h1 > LF PROGAMADOR </ h1 >
                < div  class = " Calculadora " >
                   < h1 > Calculadora </ h1 >
                   < p  id = " resultado " > </ p >
                   < mesa >
                       < tr >
                           < td > < button  class = " botao " onclick = " clean () " > C </ button > </ td >
                           < Td > < botão  class = " botao " onclick =" back () " > < </ botão > </ td >
                           < td > < button  class = " botao " onclick = " insert ('/') " > / </ button > </ td >
                           < td > < button  class = " botao " onclick = " insert () " > X </ button > </ td >
                       </ tr >
                       < tr >
                        < td > < button  class = " botao " onclick = " insert ('7') " > 7 </ button > </ td >
                        < td > < button  class = " botao " onclick = " insert ('8') " > 8 </ button > </ td >
                        < td > < button  class = " botao " onclick = " insert ('9') " > 9 </ button > </ td >
                        < td > < button  class = " botao " onclick = " insert ('-') " > - </ button > </ td >
                    </ tr >
                    < tr >
                        < td > < button  class = " botao " onclick = " insert ('4') " > 4 </ button > </ td >
                        < td > < button  class = " botao " onclick = " insert ('5') " > 5 </ button > </ td >
                        < td > < button  class = " botao " onclick = " insert ('6') " > 6 </ button > </ td >
                        < td > < button  class = " botao " onclick = " insert ('+') " > + </ button > </ td >
                    </ tr >
                    < tr >
                        < td > < button  class = " botao " onclick = " insert ('1') " > 1 </ button > </ td >
                        < td > < button  class = " botao " onclick = " insert ('2') " > 2 </ button > </ td >
                        < td > < button  class = " botao " onclick = " insert ('3') " > 3 </ button > </ td >
                        < td  rowspan = " 2 " > < button  class = " botao " style = " height: 106px; " onclick = " calcular () " > = </ button > </ td >
                    </ tr >
                    < tr >
                        < td  colspan = " 2 " > < button  class = " botao " style = " width: 106px; " > 0 </ button > </ td >
                        < td > < button  class = " botao " onclick = " insert ('.') " > . </ botão > </ td >
                        
                    </ tr >
                   </ mesa >
                </ div >








       < script  src = " javascript.js " > </ script >
    </ body >
</ html >
