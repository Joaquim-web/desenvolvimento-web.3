# desenvolvimento-web.3
entregavel de desenvolvimento web semana 3


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
