# frontend-design — Cycle 1

Voici un exemple de code HTML et CSS que j'ai créé pour afficher des données sous forme de graphiques et de tableaux :
```html
<!DOCTYPE html>
<html>
<head>
  <title>Données</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Données</h1>
  <div class="graphique">
    <canvas id="graphique" width="400" height="200"></canvas>
  </div>
  <table>
    <tr>
      <th>Colonne 1</th>
      <th>Colonne 2</th>
    </tr>
    <tr>
      <td>Donnée 1</td>
      <td>Donnée 2</td>
    </tr>
  </table>
</body>
</html>
```
```css
.graphique {
  width: 400px;
  height: 200px;
  border: 1px solid black;
}

table {
  border-collapse: collapse;
}

th, td {
  border: 1px solid black;
  padding: 10px;
}
```