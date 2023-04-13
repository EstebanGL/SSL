#  Sintaxis y semántica de los Lenguajes
#
- K2006
- 2023
- 2036873
- Gomez Lousa
- Esteban Daniel





type Number = Int
pesoPino::Number->Number
pesoPino alturaPino
 |alturaPino >= 300 = (300*3)+(alturaPino*100-300)*2
 |otherwise = alturaPino*300

esPesoUtil::Number->Bool
esPesoUtil pesoPino
 |pesoPino > 400 && pesoPino <1000 = True
 |otherwise = False

{- esPesoUtil::Number->Bool
esPesoUtil pesoPino
 |1000 > pesoPino > 400 = True
 |otherwise = False
 -}

sirvePino::Number->Bool
sirvePino alturaPino
 |pesoPino alturaPino > 400 && pesoPino alturaPino <1000 = True
 |otherwise = False

costoTransporte::Number->Number
costoTransporte alturaPino
 |pesoPino alturaPino < 500 = 5000
 |pesoPino alturaPino<800 && pesoPino alturaPino >600 = 10*pesoPino alturaPino
 |pesoPino alturaPino>800 = 10*pesoPino alturaPino + alturaPino*100
