1. Which of these html is an acceptable hierarchy for a newspaper article?

a) html > body > article > footer

2. In the example, which element is the child and which is the parent?

a) Head is the parent, title is the child

3. Which is the correct list of responsibilities for HTML and CSS:

b) HTML: data, CSS: presentation

4. Which tag wraps text content into a paragraph?

d) <p>

5. Given the following image, which of the following HTML matches the design? Explain your reasoning.

a)

  <header>
    <nav></nav>
    <h1></h1>
    <h5></h5>
  </header>
  <section>
    <article>
      <img>
      <ul></ul>
      <h2></h2>
    </article>
  </section>

6. What is the purpose of the alt attribute?

c) Provide a description of the image for screen readers and search engines

7. What will a browser do if HTML is invalid?

c) Do the best it can, but the page might not look the way it is intended

8. What is the definition of a void tag:

b) A void tag has no content

9. Which of the following is the correct syntax to apply multiple classes to an element?

b) <div class="large important sparkly"></div>

10. In the following HTML, what is the article's relationship to the aside?

b) sibling

Exercises

1.

The above HTML wouldn’t be syntactically correct because the <body> tag is inside of the <head> tag. Usually the <head> tag just contains data about the page (which won’t display in the browser) and goes in between the <html> and <body> tags. The <body> tag is suppose to exist outside of the <head> tag as a sibling, not a child, with <html> being the parent tag. 
‘Will I be seen?’ will show in the browser because it’s placed inside of the <body> tag, which makes up the contents of an HTML file.