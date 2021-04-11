+++
title = "Big Data Overview"
+++

<!-- Slide 1 -->
<!--: .wrap bg=bg-black bg=aligncenter bgimage=https://images.unsplash.com/photo-1547190027-9156686aa2f0?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1350&q=80 -->

{{< div class="content-center" >}}
# **Big Data Overview**
[{{< svg fa-github >}}Github](https://20100701.github.io/bigdata/)
{{< /div >}}

---
<!-- Slide 2 -->
{{< div class="content-left" >}}
### Avant-propos
*Ce contenu a pour objectif de faire découvrir les concepts de ce que l'on appelle le "Big Data". Certains aspects sont simplifiés dans le but de rester compréhensible par un public voulant appréhender ce sujet sans en devenir des experts.*

### Contexte
Ce contenu a été créé pour les étudiants de la licence <a href="https://uniform.unicaen.fr/catalogue/formation/licences-pro/5236-licence-pro-metiers-informatique---administration-securite-systemes-et-reseaux-parcours-audit-securite-reseaux-sys-info?s=iut-caen&r=1291046129051">Audit et Sécurité des Réseaux et des Systèmes d'Information</a> (aka ASRSI) de l'<a href="http://www.unicaen.fr/">Université de Caen</a>.

### Objectif
Ce contenu doit permettre aux étudiants d'appréhender les concepts du Big Data ainsi que les solutions techniques misent en œuvre.<br>
Il sert donc de support pour un module d'enseignement du Big Data aussi bien pour les parties théoriques que pratiques. Il limite au maximum le temps passé sur la phase de déploiement des environnements afin de laissé le plus de temps possible à la compréhension du Big Data et aux échanges entre étudiants et formateurs.
{{< /div >}}


<figure class="content-right">
  <img alt="Screenshot" src="https://images.unsplash.com/photo-1519452635265-7b1fbfd1e4e0?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=934&q=80">
</figure>

---

<!--: .wrap -->

<!--: .wrap .size-80 ..content-center -->

<!--: .flexblock gallery -->
<!--
- {{< gallery title="Why WebSlides" href="#slide=10" src="https://webslides.tv/static/images/demos-why.png" >}}Why WebSlides{{< /gallery >}}
- {{< gallery title="Landings" href="https://webslides.tv/demos/landings" src="https://webslides.tv/static/images/demos-landings.png" >}}Landings{{< /gallery >}}
- {{< gallery title="Portfolios" href="https://webslides.tv/demos/portfolios" src="https://webslides.tv/static/images/demos-portfolios.png" >}}Portfolios{{< /gallery >}}
- {{< gallery title="Keynote" href="https://webslides.tv/demos/apple" src="https://webslides.tv/static/images/demos-apple.png" >}}Keynote{{< /gallery >}}
-->
---
<!--: .wrap -->

## **More Examples**
<small>Note. None of these slides are currently not ported to Hugo-Webslides...YET.</small>

<!--: .flexblock gallery -->
- {{< gallery title="Netflix's Culture" href="https://webslides.tv/demos/netflix-culture" src="https://webslides.tv/static/images/demos-netflix.png" >}}Netflix{{< /gallery >}}
- {{< gallery title="Longform Articles" href="https://webslides.tv/demos/longforms" src="https://webslides.tv/static/images/demos-longforms.png" >}}Longforms{{< /gallery >}}
- {{< gallery title="Interviews" href="https://webslides.tv/demos/interviews" src="https://webslides.tv/static/images/demos-interviews.png" >}}Interviews{{< /gallery >}}

---
<!-- : .wrap .size-40 -->

### **Configuration**

<!-- : .text-intro -->You can modify WebSlides settings directly from your project config.toml.

~~~toml
[params.webslides]
  banner = false
  slideshow = true
  vertical = false
  autoslide = false
  changeOnClick = false
  disableLoop = false
  minWheelDelta = 40
  disableNavigateOnScroll = false
  scrollWait = 450
  slideOffset = 50
  hideIndex = false
~~~


---
<!-- : .wrap -->

|||v

### **All from one markdown file**

Use three dashes "<code>-</code>" to create a separate slide page.

|||

~~~md

Slide1

---

Slide2

~~~

---
<!-- : .wrap -->


|||

~~~
content
├── home
│   ├── home1.md (weight: 1)
│   └── home2.md (weight: 2)
└── _index.md (initial page)
~~~

|||

### Or not.

You can combine and arrange files with the weight parameter in front matter, and categorize .md files into different folders.

---
<!-- : .aligncenter -->

## Simple Class Assignment

Assign class to a block by using the following notation without quote.

<code><span><!-</span>- : .class -<span>-></span>Content</code>

---
<!-- : .wrap -->

### You can assign class to many elements

<!-- : .flexblock -->
- {{< flexblock "Slides" 6 >}}
<span><!-</span>- : sectionClass .divClass ..subClass -<span>-></span><br>
Content
~~~html
<section class="sectionClass">
  <div class="divClass">
    <div class="subClass">
    Content
    </div>
  </div>
</section>
~~~
{{< /flexblock >}}

- {{< flexblock "Headers and Paragraphs" 6 >}}
<span># <!-</span>- : .hClass -<span>-></span>Header<br>
<span><!-</span>- : .pClass -<span>-></span>Paragraph
~~~html
<h1 class="hClass">Header</h1>
<p class="pClass">Paragraph</p>
~~~
{{< /flexblock >}}

- {{< flexblock "Lists" 6 >}}
<span><!-</span>- : .listClass -<span>-></span><br>
<span>-</span> list1<br>
<span>-</span> list2
~~~
<ul class="listClass">
  <li>list1</li>
  <li>list2</li>
</ul>
~~~
{{< /flexblock >}}
