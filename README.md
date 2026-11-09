# desenvolvimento-web.3
entregavel de desenvolvimento web semana 3
function classificarNota(nota) {
  if (nota >= 6) return "Aprovado";
  else return "Reprovado";
}
console.log(classificarNota(7), classificarNota(4));

const corSemaforo = "verde";
switch (corSemaforo) {
  case "vermelho": console.log("Pare"); break;
  case "amarelo": console.log("Atenção"); break;
  case "verde": console.log("Siga"); break;
}

for (let i = 1; i <= 10; i++) console.log(`5 x ${i} = ${5 * i}`);

let c = 5;
while (c >= 1) { console.log(c); c--; }

for (let i = 1; i <= 20; i++) console.log(i, i % 2 === 0 ? "par" : "ímpar");

let j = 1;
while (j <= 20) { console.log(j, j % 2 === 0 ? "par" : "ímpar"); j++; }

function diaDaSemana(num) {
  switch (num) {
    case 1: return "Domingo";
    case 2: return "Segunda";
    case 3: return "Terça";
    case 4: return "Quarta";
    case 5: return "Quinta";
    case 6: return "Sexta";
    case 7: return "Sábado";
    default: return "Número inválido";
  }
}
console.log(diaDaSemana(3), diaDaSemana(9));
