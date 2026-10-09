# Emmet-инструкции для страниц сайта

Для каждой HTML-страницы приведена одна комбинированная Emmet-инструкция. Она отражает фактическую структуру страницы и основные классы/идентификаторы, используемые в проекте.

## 1. Главная страница — `index.html`

```text
html:5>body#top.home-page>header.site-header>div.container.header-inner>a.logo>span^nav.main-nav>ul>li*7>a^^^^main>section.hero>div.container.hero-layout>div.hero-content>p.eyebrow+h1#hero-title+p.hero-text+div.hero-actions>a.button+a.button.button-secondary^^div.hero-metrics>div*3>strong+span^^^figure.hero-visual>img+figcaption>span+strong^^^^section.section.container.intro-grid>article>h2#city-short+p*3+p.note>mark^^aside.fact-card>h3+dl>dt+dd+dt+dd+dt+dd+dt+dd^^details>summary+p^^^^section#gallery.section.section-soft>div.container>div.section-heading>p.eyebrow+h2#gallery-title+p^div.gallery-grid>figure*7>img+figcaption^^^^section.section.container>div.section-heading>p.eyebrow+h2#events-title^div.cards.three-cols>article.news-card*3>time+h3+p+a^^^^section.section.callout>div.container.callout-inner>div>h2+p^a.button^^^^footer.site-footer>div.container.footer-grid>div>strong+br+small^address+a^^a.to-top
```

## 2. История города — `history.html`

```text
html:5>body#top.history-page>header.site-header>div.container.header-inner>a.logo>span^nav.main-nav>ul>li*7>a^^^^main.page-main>section.page-hero>div.container>p.eyebrow+h1+p^^section.section.container>article.prose>h2+p+blockquote>p+cite^^div.table-wrap>table.history-table>caption+thead>tr>th*3^^tbody>tr*12>td>time^td+td^^^^section.section.section-soft>div.container.timeline-notes>article>h2+p>strong^^aside>h3+ol>li*5^^^^footer.site-footer>div.container.footer-grid>div>strong+br+small^address+a^^a.to-top
```

## 3. Инфраструктура города — `infrastructure.html`

```text
html:5>body#top.infrastructure-page>header.site-header>div.container.header-inner>a.logo>span^nav.main-nav>ul>li*7>a^^^^main.page-main>section.page-hero>div.container>p.eyebrow+h1+p^^section.section.container.split-layout>article>h2+p>strong^p+hr+p>abbr+abbr^^aside.geo-card>h3+ul>li*4^meter+small^^^section.section.section-soft>div.container>div.section-heading>p.eyebrow+h2#map-title^iframe.city-map+p.map-caption>a^^^section.section.container>div.section-heading>p.eyebrow+h2^div.district-grid>article*4>data+h3+p^^^^section.section.section-dark>div.container.transport-grid>article>h2+p>strong^p^^aside>h3+ul.transport-list>li*4>span^^^^footer.site-footer>div.container.footer-grid>div>strong+br+small^address+a^^a.to-top
```

## 4. Культура и искусство — `culture.html`

```text
html:5>body#top.culture-page>header.site-header>div.container.header-inner>a.logo>span^nav.main-nav>ul>li*7>a^^^^main.page-main>section.page-hero>div.container>p.eyebrow+h1+p^^section.section.container.culture-lead>figure.culture-photo>img+figcaption^article>h2+p*2+details>summary+p^^^section.section.section-soft>div.container>div.section-heading>p.eyebrow+h2^div.cards.three-cols.culture-cards>article*3>h3+p^^^^section.section.container>div.section-heading>p.eyebrow+h2#people-title^div.people-list>article>h3>small^p+p>q^^article>h3>small^p^^^^section.section.callout>div.container.callout-inner>div>h2+p^a.button^^^^footer.site-footer>div.container.footer-grid>div>strong+br+small^address+a^^a.to-top
```

## 5. О разработчике — `about.html`

```text
html:5>body#top.about-page>header.site-header>div.container.header-inner>a.logo>span^nav.main-nav>ul>li*7>a^^^^main.page-main>section.page-hero>div.container>p.eyebrow+h1+p^^section.section.container.developer-section>figure.developer-figure>img.developer-photo^article.developer-bio>h2+p.lead+p*2^^section.section.section-soft>div.container.skills-section>div.section-heading>p.eyebrow+h2+p>code^^div.skills-chart>div.skill-row*5>div.skill-label>span+strong^progress^^^^section.section.container.tools-section>h2+ul.tag-list>li*6>code^^p>kbd^^^footer.site-footer>div.container.footer-grid>div>strong+br+small^address+a^^a.to-top
```

## 6. Обратная связь — `contact.html`

```text
html:5>body#top.contact-page>header.site-header>div.container.header-inner>a.logo>span^nav.main-nav>ul>li*7>a^^^^main.page-main>section.page-hero>div.container>p.eyebrow+h1+p^^section.section.container.contact-layout>article>h2+p>span.required-star+code^^form.contact-form>fieldset>legend+label>span.required-star^^input#name+small+label>span.required-star^^input#email+label+input#phone^^fieldset>legend+label+select#topic>option*4^^label+input#district+datalist#districts>option*4^^label>span.required-star^^textarea#message+label.checkbox-row>input+span>span.required-star^^^div.form-actions>button*3^^^^aside.validation-card>h3+ol>li*4>code^^p>code*5^^^^footer.site-footer>div.container.footer-grid>div>strong+br+small^address+a^^a.to-top
```

## 7. South Park — `southpark.html`

```text
html:5>body#top.southpark-root>header.site-header>div.container.header-inner>a.logo>span^nav.main-nav>ul>li*7>a^^^^main.page-main.southpark-page>section.page-hero>div.container>p.eyebrow+h1+p^^section.section.container.css-character-layout>article.css-character-info>p.eyebrow+h2+p>code*3^^p+div.character-tech-list>span*5^^aside.note-card.character-note>h3+p>strong+code^^^div.cartman-showcase>div.cartman-scene>div.css-cloud.cloud-a+div.css-cloud.cloud-b+div.css-mountain.mountain-a+div.css-mountain.mountain-b+div.css-ground+div.cartman-figure>div.cartman-shadow+div.cartman-legs>span.cartman-leg.leg-left+span.cartman-leg.leg-right^^div.cartman-body>span.cartman-coat-line+span.cartman-button.button-one+span.cartman-button.button-two+span.cartman-button.button-three+div.cartman-arm.arm-left>span.cartman-mitten^^div.cartman-arm.arm-right>span.cartman-mitten^^div.cartman-head>div.cartman-ear.ear-left+div.cartman-ear.ear-right+div.cartman-eye.eye-left>span.cartman-pupil+span.cartman-lid^^div.cartman-eye.eye-right>span.cartman-pupil+span.cartman-lid^^span.cartman-nose+span.cartman-mouth+span.cartman-chin^^div.cartman-hat>span.cartman-hat-band+span.cartman-pom^^^div.scene-label>span.live-dot^^p.showcase-tip^^^footer.site-footer>div.container.footer-grid>div>strong+br+small^address+a^^a.to-top
```
