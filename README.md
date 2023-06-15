# PROVA-OTAVIO
KDAKSDKA



function verificarQuadrado() {
  var numero = parseFloat(prompt('Digite um número e vou informar se ele é um quadrado perfeito'));

  if (numero < 0) {
    alert('Números negativos não são quadrados perfeitos');
  } else {
    var raiz = Math.sqrt(numero);

    if (Number.isInteger(raiz)) {
      alert('Esse número é um quadrado perfeito!');
    } else {
      alert('Esse número não é um quadrado perfeito');
    }
  }
}
