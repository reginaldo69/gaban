# gaban
gaban
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,opsz,wght@0,6..12,200..1000;1,6..12,200..1000&display=swap'){
  "total_pessoas_conectadas": 5.04e9,
  "tempo_medio": 2.38,
  "total_pessoas_mundo": 7.888e9
}async function vizualizarInformacoesGlobais() {
  const res = await fetch(url)
  const dados await res.json()
  console.log(dados.tempo_medio);
}

vizualizarInformacoesGlobais().graficos-container {

}const url = 'https://raw.githubusercontent.com/guilhermeonrails/api/main/dados-globais.json'

async function visualizarInformacoesGlobais() {
  const res = await fetch(url)
  const dados = await res.json()
  const pessoasConectadas = (dados.total_pessoas_conectadas / 1e9)
}

// código omitido{
    "Facebook": 3049,
    "Youtube": 2491,
    "WhatsApp": 2000,
    "Instagram": 2000,
    "Tiktok": 1562,
    "WeChat":1336
}const data = [
  {
    x: 'nomeDasRedes',
    y: quantidadeDeUsuarios,
    type: 'bar',
    marker: {
      color: 'red'
    }
  }
]// código omitido

const layout = {
  plot_bgcolor: getCSS('--bg-color'),
  paper_bgcolor: getCSS('--bg-color'),
  title: {
    text: 'Redes sociais com mais usuários no mundo'
  }
}

// código omitido
