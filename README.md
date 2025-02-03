# Guía de Instalación de DeepSeek R1 en local

<p align="center">
<img src="images/deepseek.jpeg"  height=350>
</p>

*Nota:* Este repositorio se terminó de crear el 04/02/2025.

# Índice

* [DeepSeek](#DeepSeek)

* [Instalación con ollama](#Instalación-con-ollama)

* [Conclusión](#Conclusión) 

* [Página DeepSeek](#Página-DeepSeek) 


* [Autor](#Autor)


# DeepSeek

DeepSeek es una empresa china de inteligencia artificial fundada en julio de 2023 por Liang Wenfeng, con sede en Hangzhou, 
China. La compañía se especializa en el desarrollo de modelos de lenguaje de gran escala (LLMs) de código abierto, ofreciendo
 alternativas más accesibles y económicas en comparación con otras soluciones en el mercado.

Uno de sus modelos destacados, DeepSeek-R1, proporciona respuestas comparables a las de modelos avanzados como GPT-4 de OpenAI,
 pero con costos de entrenamiento significativamente menores y requerimientos de computación reducidos. Este enfoque ha permitido
  a DeepSeek ofrecer soluciones de IA de alto rendimiento a una fracción del costo, democratizando el acceso a tecnologías 
  avanzadas de inteligencia artificial. 

La estrategia de DeepSeek de hacer que sus algoritmos y modelos sean de código abierto ha generado un impacto considerable 
en la industria de la IA, desafiando a gigantes tecnológicos establecidos y fomentando una mayor adopción de prácticas abiertas 
en el desarrollo de inteligencia artificial.


## Modelos

Para el modelo R1, hay varios submodelos que varian en la cantidad de parámetros, peso y por ende las capacidades de la maquina
 a utilizar.

* 1.5b pesa 1.1 Gb
* 7b   pesa 4.7 Gb
* 8b   pesa 4.9 Gb
* 14b  pesa 9.0 Gb
* 32b  pesa 20.0 Gb
* 70b  pesa 43.0 Gb
* 671b pesa 404.0 Gb


# Instalación con ollama

1.- ir al siguiente link [ollama](https://ollama.com/download/windows), descargar e instalar el programa. 

<p align="center">
<img src="images/ollama1.jpeg"  height=350>
</p>

2.- Escoger el modelo a descargar en la siguiente [página](https://ollama.com/library/deepseek-r1), escoger el modelo a descargar y 
copiar el comando de descarga que aparece arriba a la derecha ** ollama run deepseek-r1:1.5b ** 

 <p align="center">
<img src="images/ollama2.jpeg"  height=350>
</p>

3 - Ejecutar ollama en un command prompt con el comando ollama 
<p align="center">
<img src="images/ollama3.jpeg"  height=350>
</p>

y luego pegar "ollama run deepseek-r1:1.5b" para descargar
 el modelo más liviano en mi caso.

 <p align="center">
<img src="images/ollama4.jpeg"  height=350>
</p>

4 .- Para usar una interface más amigable se puede descargar el pluging 
[page assist](https://chromewebstore.google.com/detail/page-assist-a-web-ui-for/jfgfiigpkhlkbnfnbobbkinehhfdhndo?pli=1)(link para c)


# Página DeepSeek

[deepseek](https://www.deepseek.com/)

Es necesario registrarse en la pagina. Ya en la pagina se puede acceder al modelo R1 y se pueden obtener las
 credenciales para su api a un precio mas bajo que el OpenAI.


# Conclusión

## Prueba

De esta lista (2 3 4 8 6 7 ) de números cuales son numeros primos?

Si bien es un modelo que aun tiene errores, no deja de ser impresionante el nivel que tiene y que se puede correr en local. 
Esto nos da una pequeña cucharada de lo que nos depara el futuro en modelos de LLM.


 <p align="center">
<img src="images/ollama5.jpeg"  height=500>
</p>





<br>[Volver al Índice](#Índice)

# Autor

José R. Guignan
- Mail: joserguignan@gmail.com
- Linkedin: [https://www.linkedin.com/in/jrguignan/](https://www.linkedin.com/in/jrguignan)
- Portafolio: [https://jrguignan.github.io/](https://jrguignan.github.io/)