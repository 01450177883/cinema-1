//condicionais - if - else
//menores de 18 anos -> menor de idade(meia)
//entre 18 e 60-> adultos(meia apenas com carteirinha)
//maiores de 60 anos -> idoso(meia)


//inteira - adulta e não tem carteirinha
//meia - o resto
const idade= 15
const temCarteirinha = false

const ehAdulta = idade >= 18 && idade <= 60
if (ehAdulta && temCarteirinha === false) {
  console.log("inteira")
} else {
  console.log("meia")
}
