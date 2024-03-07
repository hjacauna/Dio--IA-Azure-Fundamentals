<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/f38a62b8-2880-4fd2-82ff-ba263ce97cdb.png"></a>
    <span>Reconhecimento Facial e transformação de imagens em Dados no Azure ML</span>
</h1>

## RECONHECIMENTO DE FACE

Utilizando esse recurso, é possível reconhecer um rosto. Ele verifica a delimitação dos pontos do rosto dentro de um retângulo e verifica se a pessoa está usando ou não máscara.

Para realizar o experimento, utilizamos o gerador de imagem do Bing com uma grande quantidade de indivíduos para verificar se havia um limite no reconhecimento de rostos. Os resultados obtidos foram os seguintes:

- Todos os rostos foram reconhecidos.
- Devido à qualidade da imagem, borrões foram erroneamente reconhecidos como máscaras.
- Também foi detectado que não estava sendo feita a cobertura adequada do nariz e da boca.
- O experimento foi divertido! Seria interessante testar outras combinações para verificar como a IA se comporta e, se possível, até mesmo desafiá-la.

### Entrada

Imagem gerada pelo bing.

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/input/30%20pessoas.jpeg?raw=true" width=""/>

### Saída

Resultados da IA

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/output/detectou%20mascara.png?raw=true" width=""/>

## Gerar legendas para uma imagem

As Legendas de Imagem no Azure Vision Studio permitem que você gere descrições automáticas para imagens com base em seu conteúdo visual. Essa funcionalidade é parte da Análise de Imagem 4.0 e oferece duas opções:

- Legenda: Gera uma descrição concisa de uma única frase para todo o conteúdo da imagem.
- Legendas Densas: Fornece descrições mais detalhadas, gerando frases de até dez regiões específicas da imagem, além de descrever a imagem como um todo. As Legendas Densas também retornam coordenadas de caixas delimitadoras para as regiões descritas.

### Gerador de legendas

No exemplo a seguir foi descrito em uma frase o cenario da imagem.

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/output/%20Legenda%20pato%20na%20lua.png?raw=true" width=""/>

Nesse outro exemplo foi detectado o personagem animado pela IA.

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/output/Legenda%20pato%20astro.png?raw=true" width=""/>

### Gerado de legendas densas

No gerador de licenças densas, vários objetos foram encontrados mas nem todos tivem 100% de acertividade.

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/output/legenda%20densa%20astro.png?raw=true" width=""/>

Descrição de outros objetos na proxima imagem.

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/output/legenda%20densa%20pato.png?raw=true" width=""/>

## Marcando imagem

Nessa funcionalidades podemos verificar a quantidade de objetos reconhecidos pela IA. Aqui, a pontuação de confiança é a probabilidade de o texto do atributo detectado descrever o que realmente está na imagem.

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/output/marcando%20img.png?raw=true" width=""/>

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/output/marcando%20img%202.png?raw=true" width=""/>

## Detectando objetos

A detecção de objetos detecta e extrai caixas delimitadoras com base em milhares de objetos e seres vivos reconhecíveis.

Na primeira iamgem tem uma acertividade de 85% de que se trata de uma ave.

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/output/detectando%20objeto.png?raw=true" width=""/>

Na proxima imagem, conseguimos enganar a ia, ela detectou o astrouna "pato" como uma pessoa.

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/output/detectando%20obj%20quebrei.png?raw=true" width=""/>

## Extrair texto de imagens

Nessa etapa utilizamos uma imagem gerada pela IA do bing a mesma trouxe uma cidade futuristica com caracteres em chines, e a IA consegui identificar o letreiro desemprego, algo muito surpreendente.

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/output/ocr%20desemprego.png?raw=true" width=""/>

# Considerações finais.

O Azure Machine Learning se destaca como uma plataforma completa e poderosa para tarefas de visão computacional, oferecendo uma gama de recursos que permitem explorar diferentes aplicações com grande potencial. As considerações finais apresentadas servem como um guia para os próximos passos na jornada de aprendizado e utilização da plataforma.
