<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/f38a62b8-2880-4fd2-82ff-ba263ce97cdb.png"></a>
    <span>Reconhecimento Facial e transformação de imagens em Dados no Azure ML</span>
</h1>

## RCONHECIMENTO DE FACE

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
