# Semana 1 - Deploy estatico (GitHub Pages) 
## Links 
- Repositorio: https://github.com/LucasRMarchetti/nuvem-semana1-lucas-marchetti 
- Site (GitHub Pages): https://lucasrmarchetti.github.io/nuvem-semana1-lucas-marchetti/ 
## O que foi feito 
- Criei index.html, style.css e script.js pelo navegador 
- Ativei GitHub Pages (main / root) 
 
# Semana 2 - (GET + POST)
## O que foi feito 

Nesta parte do projeto foi implementado o consumo de APIs públicas utilizando JavaScript (fetch), mantendo o modelo sem Node
POST:
{
  "fonte": "jsonplaceholder.typicode.com",
  "resposta": {
    "turma": "Serviços em Nuvem",
    "atividade": "Semana 2",
    "timestamp": "2026-03-02T11:58:13.792Z",
    "id": 101
  }
}

# Semana 2 - BÔNUS (API/FETCH
## O que foi feito 
Adicionamos APIs públicas usando fetch() no JavaScript, essas APIs permitem que o usuário digite o nome de uma cidade e clique em “Buscar clima”. O sistema então realiza duas requisições em sequência: primeiro converte o nome da cidade em latitude e longitude, e depois utiliza essas coordenadas para buscar dados de clima, como temperatura e velocidade do vento, através das APIs geocoding e forecast. Também adicionamos um "histórico" pelo LocalStorage 
