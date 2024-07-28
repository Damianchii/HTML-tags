
## `<pre>` - tekst w tym znaczniku bierze pod uwage znaki białe
```bash
<p>
<pre>
Lorem ipsum             dolor sit
amet consectetur adipisicing 
elit. Modi, fugit? Corporis in et 
similique animi porro id autem voluptatum! 
Amet.
    </pre>
</p>
```

#### Result
<pre>Lorem ipsum             dolor sit
amet consectetur adipisicing 
elit. Modi, fugit? Corporis in et 
similique animi porro id autem voluptatum! 
Amet.
</pre>



## `<p>` - paragraf
<p>
    Lorem ipsum dolor sit amet consectetur <br>
    adipisicing elit. Architecto animi sit <br>
    adipisci! Maiores iure non iste, <br>
    harum aliquam pariatur vero.
</p>

## `<mark>` - wyróżnia element ze względu na kontekst 
```bash
<p>
    Lorem ipsum dolor sit amet, <mark>consectetur</mark>
    adipisicing elit. <mark>consectetur</mark> Necessitatibus, cumque.
</p>
```
#### Result

<p>
    Lorem ipsum dolor sit amet, <mark>consectetur</mark>
    adipisicing elit. <mark>consectetur</mark> Necessitatibus, cumque.
</p>


<!-- strong - pogrubiony tekst, semantycznie ważny, wyróżniony -->
<p>
    <strong>Kasia Kowalska</strong> - opis tej osoby, Lorem ipsum dolor sit amet.
</p>

<!-- b - tylko pogrubienie -->
<p>
    Lorem <u>ipsum</u> <b>dolor</b> <i>sit</i> amet.
</p>

<!-- em - emfaza, pochylony, semnatycznie znaczący, 
    mniejsza waga niż strong -->
<p>
    Lorem ipsum <em>dolor</em> sit amet.
</p>

<!-- abbr - skrót -->
<p>
    <abbr title="Hyper Text Markup Language">HTML</abbr>
</p>

<!-- zmiany w tekście, ins - dodany tekst, del- sksowany
     sup - indeks górny, sub - indeks dolny,
     s - tylko przekreślony tekst -->
<p>Lorem <ins>insert</ins> dolor sit, amet consectetur
    adipisicing elit. Quo optio fugiat, quam
    ad <sup>quae - indeks górny</sup> iusto! <del>delete</del> deleteur molestiae
    <sub>tenetur - indeks dolny</sub> <s>dolor</s>?
</p>

<!-- q - cytat, element blokowy -->
<q cite="https://developer.mozilla.org/en-US/docs/Web/CSS">
    Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in
    HTML or XML (including XML dialects such as SVG, MathML or XHTML). CSS describes how elements should be rendered on
    screen, on paper, in speech, or on other media.
</q>

<!-- blockquote - cytat, element blokowy, odsunięty id lewej krawędzi okna -->
<blockquote cite="https://developer.mozilla.org/en-US/docs/Web/CSS">
    Cascading <small>Style Sheets </small>(CSS) is a stylesheet language used to describe the presentation of a document
    written in HTML or XML (including XML dialects such as SVG, MathML or XHTML). CSS describes how elements should be
    rendered on screen, on paper, in speech, or on other media.
</blockquote>

<!-- span fragment tekstu do dalszej pracy np z css -->
<p>
    Lorem <span>ipsum</span> dolor
    <span class="bolded-text">sit</span> amet consectetur.
</p>

</body>

</html>
