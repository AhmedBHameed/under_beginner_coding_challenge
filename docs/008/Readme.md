## تعلم كتابة استمارة معلومات بلغة HTML

> March {docsify-updated}

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <form action="" method="post">
      <fieldset>
        <legend>Personal information:</legend>
        First name:<br />
        <input
          type="text"
          name="firstname"
          value="Mickey"
          placeholder="First Name"
        /><br />
        Last name:<br />
        <input
          type="text"
          name="lastname"
          value="Mouse"
          placeholder="Last Name"
        /><br /><br />
        Favorite car brand:<br />
        <select>
          <option value="volvo">Volvo</option>
          <option value="saab">Saab</option>
          <option value="mercedes">Mercedes</option>
          <option value="audi">Audi</option>
        </select>
        <br />
        <br />
        <textarea name="description"></textarea>
        <br />
        <input type="submit" value="Submit" />
      </fieldset>
    </form>
  </body>
</html>
```
