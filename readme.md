# Basic HTML site

## HTML Snippets

Semantic tags help with acessibility, SEO (machine learning), performance and collaboration.

<details name="html">
<summary>Common Structure</summary>

```htm
<!DOCTYPE html>
<html lang="en">
<head></head> 

<body>  

    <header> <header>

    <main> 

        <section></section>
        <article></article>

    </main>

     <aside></aside> <!-- Remove if there's no sidebar -->
        
    <footer> </footer>

</body> 
</html>

```
**Notes:** 

```<aside>``` content indirectly related to the main content like a sidebar.

```<section>``` a standalone section of a document that should comtain a heading.

```<article>``` a self-contained content that can be distributed or reused. 

```<div>``` a generic container used to define a division. It has no sematic meaning and is primarily used to group elements for styling with CSS. 

```<!-- my comment  -->``` comments are notes in the code that are hidden from the page view.

</details>


<details name="html">
<summary>Head Section</summary>

```htm

<head>
    
    <meta charset="UTF-8">     
    <meta name="viewport" content="width=device-width, initial-scale=1.0">     
    <title>Company Name - we do this Max 65 charactors</title>
    <link rel="stylesheet" href="/css/style.css">
    <meta name="description" content="This is has no SEO value but can be shown in search listing. Treat as sales copy.">
        
</head>
```
**Notes:** 

Use this [Favicon Generator](https://realfavicongenerator.net/).


</details>

<details name="html">
<summary>Most used tags</summary>


```htm
<!-- Heading h1 - h6 -->

<h1>Main heading - only use one per page</h1>
<h2>Next level heading. Never skip a level</h2>


<!-- Text -->

<p>This is my paragraph text.</p>
<p>My text with a <strong>bolded</strong> word and an <em> italic</em> word.</p>
<small>My small text.</small>


<!-- Image (remove loading='lazy' if the image is the viewport when on load) -->

<img src="/image" loading="lazy" alt="describe the image" width="300"height="150">


<!-- Links -->

<a href="https://another-website.com">Another website </a>
<a href="/about">My about page</a>

```

**Notes:** 
</details>

## Resources:

