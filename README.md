# HTML-CSS
 Estudos de HTML5 e CSS3

<meta charset="UTF-8">
<table>
<style>
      html, body {
         font-family: Arial, Helvetica, sans-serif;
      }
      table {
         min-width: 500px;
         max-width: 75vw;
         width: 900px;
         padding: 10px;
         text-align: center;
         border-collapse: collapse;
      }
      thead {
         background-color: gray;
         padding: 10px;
      }
      td, th {
         border: 2px solid black;
         height: 25px;
      }
      .feito:hover{
         background-color: rgba(10, 138, 10, 0.747);
      }
      .fazendo:hover {
         background-color: rgba(255, 255, 0, 0.61);
      }
      .vazio > p {
         display: none;
      }
      .vazio:hover {
         background-color: lightgray;
      }
      .vazio:hover > p {
         display: block;
         background-color: lightgray;
      }
      a {
         color: black;
         text-decoration: none;
      }
      a:hover {
         color: white;
      }
      tfoot {
         text-align: center;
         font-weight: bold;
      }
  </style>
<table>
      <thead>
        <th>Modulo 01</th>
        <th>Modulo 02</th>
        <th>Modulo 03</th>
        <th>Modulo 04</th>
        <th>Modulo 05</th>
      </thead>
      <tbody>
        <tr>
          <td class="feito"><a href="modulo01/ex001/index.html">Ex001</a></td>
          <td class="feito"><a href="modulo02/ex001/cor01.html">Ex001</a></td>
          <td class="feito"><a href="modulo03/ex001/fundo01.html">Ex001</a></td>
          <td class="feito"><a href="modulo04/ex001/iframe01.html">Ex001</a></td>
          <td class="vazio" rowspan="15">
            <p>V</p>
            <p>A</p>
            <p>Z</p>
            <p>I</p>
            <p>O</p>
          </td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex002/index.html">Ex002</a></td>
          <td class="feito"><a href="modulo02/ex002/fontes.html">Ex002</a></td>
          <td class="feito"><a href="modulo03/ex002/index.html">Ex002</a></td>
          <td class="fazendo"><a href="modulo04/ex002/index.html">Ex002</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex003/index.html">Ex003</a></td>
          <td class="feito"><a href="modulo02/ex003/fonte01.html">Ex003</a></td>
          <td class="feito"><a href="modulo03/ex003/tabela01.html">Ex003</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex004/index.html">Ex004</a></td>
          <td class="feito"><a href="modulo02/ex004/seletor01.html">Ex004</a></td>
          <td class="vazio" rowspan="12">
            <p>V</p>
            <p>A</p>
            <p>Z</p>
            <p>I</p>
            <p>O</p>
          </td>
          <td class="vazio" rowspan="12">
            <p>V</p>
            <p>A</p>
            <p>Z</p>
            <p>I</p>
            <p>O</p>
          </td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex005/index.html">Ex005</a></td>
          <td class="feito"><a href="modulo02/ex005/index.html">Ex005</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex006/html4.html">Ex006</a></td>
          <td class="feito"><a href="modulo02/ex006/caixa01.html">Ex006</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex007/index.html">Ex007</a></td>
          <td class="feito"><a href="modulo02/ex007/android.html">Ex007</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex008/index.html">Ex008</a></td>
          <td class="vazio" rowspan="8">
            <p>V</p>
            <p>A</p>
            <p>Z</p>
            <p>I</p>
            <p>O</p>
          </td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex009/index.html">Ex009</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex010/index.html">Ex010</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex011/index.html">Ex011</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex012/index.html">Ex012</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex013/index.html">Ex013</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex014/index.html">Ex014</a></td>
        </tr>
        <tr>
          <td class="feito"><a href="modulo01/ex015/index.html">Ex015</a></td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
        <th colspan="5">Estudos HTML5 e CSS3</th>
        </tr>
      </tfoot>
 </table>
</table>