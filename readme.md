# Notes

## HTML 

Use of semantic tags help with acessibility, SEO (machine learning), performance and collaboration.

Some research suggests over 92.8% of websites rely heavily on non-semantic, ```<div>```-based layouts. "Bloat-heavy" builders such as Wix, Squarespace, Elementor and Divi prioritize ease of use resulting in the extreme nesting of non-semantic tags.

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
