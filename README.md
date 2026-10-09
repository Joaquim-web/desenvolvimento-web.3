# desenvolvimento-web.3
entregavel de desenvolvimento web semana 3
let pontos = 50;
pontos = pontos + 10;
console.log("Pontos:", pontos);

const MAX_PONTOS = 100;
console.log("MAX_PONTOS:", MAX_PONTOS);

try {
  MAX_PONTOS = 150;
} catch (erro) {
  console.log("Erro ao reatribuir const:", erro.name, "-", erro.message);
}

let texto = "Olá";
let numero = 42;
let booleano = true;
let indefinido;
let nulo = null;

console.log("typeof texto:", typeof texto);
console.log("typeof numero:", typeof numero);
console.log("typeof booleano:", typeof booleano);
console.log("typeof indefinido:", typeof indefinido);
console.log("typeof nulo:", typeof nulo);

let usuario = "Lucas";
let nivel = "Avançado";

let fraseTemplate = `O usuário ${usuario} está no nível ${nivel}.`;
let fraseConcatenada = "O usuário " + usuario + " está no nível " + nivel + ".";

console.log(fraseTemplate);
console.log(fraseConcatenada);
