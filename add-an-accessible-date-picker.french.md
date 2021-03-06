---
id: 587d778b367417b2b2512aa8
title: Add an Accessible Date Picker
challengeType: 0
videoUrl: 'https://scrimba.com/c/cD9DJHr'
---

## Description
<section id='description'>
Les formulaires incluent souvent le champ <code>input</code>, qui peut être utilisé pour créer plusieurs contrôles de formulaire différents. L'attribut <code>type</code> sur cet élément indique quel type d'entrée sera créé.
Vous avez peut-être remarqué les types de saisie <code>text</code> et <code>submit</code> dans les défis précédents? Eh bien, HTML5 a introduit une option pour spécifier un champ <code>date</code>. Selon la prise en charge du navigateur, un sélecteur de date apparaît dans le champ <code>input</code> lorsqu'il est en évidence, ce qui facilite le remplissage d'un formulaire pour tous les utilisateurs.
Pour les navigateurs plus anciens, le type sera par défaut <code>text</code>, il est donc utile d'afficher le format de date prévu sur l'étiquette ou sous forme de texte de remplacement au cas où.
En voici un exemple :
<blockquote>&lt;label for=&quot;input1&quot;&gt;Entrez une date :&lt;/label&gt;<br>&lt;input type=&quot;date&quot; id=&quot;input1&quot; name=&quot;input1&quot;&gt;<br></blockquote>
</section>

## Instructions
<section id='instructions'>
Camper Cat est en train d'organiser un tournoi de Mortal Kombat et veut demander à ses concurrents de voir quelle date fonctionne le mieux. Ajouter un tag <code>input</code> avec un attribut <code>type</code> de "date", un attribut <code>id</code> de "pickdate", et un attribut <code>name</code> de "date".
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Your code should add one <code>input</code> tag for the date selector field.
    testString: assert($('input').length == 2, 'Your code should add one <code>input</code> tag for the date selector field.');
  - text: Your <code>input</code> tag should have a <code>type</code> attribute with a value of date.
    testString: assert($('input').attr('type') == 'date', 'Your <code>input</code> tag should have a <code>type</code> attribute with a value of date.');
  - text: Your <code>input</code> tag should have an <code>id</code> attribute with a value of pickdate.
    testString: assert($('input').attr('id') == 'pickdate', 'Your <code>input</code> tag should have an <code>id</code> attribute with a value of pickdate.');
  - text: Your <code>input</code> tag should have a <code>name</code> attribute with a value of date.
    testString: assert($('input').attr('name') == 'date', 'Your <code>input</code> tag should have a <code>name</code> attribute with a value of date.');

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<body>
  <header>
    <h1>Tournaments</h1>
  </header>
  <main>
    <section>
      <h2>Mortal Kombat Tournament Survey</h2>
      <form>
        <p>Tell us the best date for the competition</p>
        <label for="pickdate">Preferred Date:</label>

        <!-- Add your code below this line -->



        <!-- Add your code above this line -->

        <input type="submit" name="submit" value="Submit">
      </form>
    </section>
  </main>
  <footer>&copy; 2018 Camper Cat</footer>
</body>
```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
