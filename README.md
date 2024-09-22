## Desenvolvimento de Interfaces Web

## Feedback Lab 1

Olá! Excelente trebalho. 

Alguns pontos a melhorar:

1. As imagens devem sempre conter um texto alternativo. Isto permite mostrar um texto alternativo quando a imagem não consegue ser carregada e melhora a acessibilidade do nosso website. Permite, por exemplo, que pessoas invisuais consigam perceber o está na imagem.

```html
<img src="images/diw.svg" alt="">
```

2. Devemos sempre colocar um título na nossa página, de forma a que utilizador consiga identificar o website nas tabs abertas e no seu histórico.

```html
<head>
    <title>Document</title>
</head>
```

## Feedback Lab 2

1. Excelente uso do elemento figure!

2. No multimedia.html:

a. Podemos utilizar o elemento section para ter um HTMl melhor estruturado.


```html
<h2>Multimédia</h2>
<p><a href="#fotografias">Fotografias</a>
<a href="#video">Vídeo</a>
<a href="#poema">Poema</a></p>

<h3 id="fotografias">Fotografias</h3>
<p><a href="images/bergen2_grande.jpg" target="_blank"><img src="images/bergen2_pequeno.jpg" alt="Bergen Noite"></a>
<a href="images/bergen3_grande.jpg" target="_blank"><img src="images/bergen3_pequeno.jpg" alt="Auroras Bergen"></a>
<a href="images/bergen4_grande.jpg" target="_blank"><img src="images/bergen4_pequeno.jpg" alt="Teleférico Bergen"></a></p>

<h3 id="video">Vídeo</h3>
<iframe width="560" height="315" src="https://www.youtube.com/embed/gENJ8nqPfVs?si=jhHxOjFU2_jhhNqN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<h3 id="poema">Poema</h3>
<pre>Entre montanhas e o mar,
    Bergen encanta ao luar.
    Fiordes que o vento abraça,
    Bryggen, história que passa.
    
    Nas ruas, o tempo flui,
    Onde o céu com o mar se dilui.
    Cores vibrantes, barcos no cais,
    Beleza que nunca se desfaz.
    </pre>
```

```html
<h2>Multimédia</h2>

<p>
    <a href="#fotografias">Fotografias</a>
    <a href="#video">Vídeo</a>
    <a href="#poema">Poema</a>
</p>

<section>
    h3 id="fotografias">Fotografias</h3>
    <p>
        <a href="images/bergen2_grande.jpg" target="_blank"><img src="images/bergen2_pequeno.jpg" alt="Bergen Noite"></a>
        <a href="images/bergen3_grande.jpg" target="_blank"><img src="images/bergen3_pequeno.jpg" alt="Auroras Bergen"></a>
        <a href="images/bergen4_grande.jpg" target="_blank"><img src="images/bergen4_pequeno.jpg" alt="Teleférico Bergen"></a>
    </p>
</section>


(...)
```

b. Temos de formatar o código HTML de forma correta. Na próxima aula vou mostrar alguns exemplos.

3. A tabela está incompleta