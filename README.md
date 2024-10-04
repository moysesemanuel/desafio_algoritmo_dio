# Desafio surpresa

<img width="651" alt="shapes (2)" src="https://github.com/user-attachments/assets/6eb3a62c-04f7-452c-930d-ff572f630a55">

<b>#O QUE PRECISAVA SER FEITO ?</b>

Criar um código para armazenar o máximo de informações possível dos pokemon da imagem abaixo e ao final, para cada um, exiba uma mensagem de saída escrita o nome do pokemon concatenado com "Cadastrado com sucesso"

<img width="1104" alt="shape_1g-y-1bRKuJKEDAE_-Ga5" src="https://github.com/user-attachments/assets/f80b0997-f79d-4391-8083-605e6ca39579">

EXEMPLO:
"DRAGONITE Cadastrado com sucesso"

<b>O meu foi feito em JavaScript</b>

``` JavaScript
const frase = "cadastrado com sucesso"
let nomesPokemon = ["Poochyena" , "Zigzagoon" , "Dragonite" , "Wurwple"]
let timePokemon = [
  ["Poochyena", 2 , "M", "Hp 13/13"],
  ["Zigzagoon", 2 , "F", "Hp 13/13"],
  ["Dragonite", 5 , "M", "Hp 25/25"],
  ["Wurwple", 2 , "M", "Hp 7/14"]
]


console.log(timePokemon[3][0] + " " + frase)
```
