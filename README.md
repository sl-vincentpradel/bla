# bla
test
<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>
<head>
  <style>
    /* Generally, you should put CSS in a separate file, but for the purpose of this post, I'm including it in the style tag. */
    p, li { text-align: justify; }
    ins { background-color: #A0FFA0; }
    del { background-color: #FFA0A0; }
    .code { background-color: #EEEEEE; }
    .codex { background-color: #FFFFE0; }
    
    .custom-table {
      text-align: center;
      font-family: monospace;
      border-collapse: collapse;
      border-spacing: 0;
    }
    
    th {
      -webkit-transform: rotate(-90deg);
      -moz-transform: rotate(-90deg);
      -ms-transform: rotate(-90deg);
      -o-transform: rotate(-90deg);
      transform: rotate(-90deg);
      width: 95px;
      font-weight: normal;
    }
    td, th {
      border: 1px solid black;
    }
    
    /* Can't eliminate the spacing no matter what I try */
    th:first-child {
      height: 100px;
    }
    th:not(:first-child) {
      height: 10px;
    }
    
    td:nth-child(2), td:nth-child(3), td:nth-child(4) {
      width: 10px;
    }
  </style>
</head>

<body>
  <table class="custom-table">
    <tr>
      <th></th>
      <th>First column</th>
      <th>Second column</th>
      <th>Third column</th>
    </tr>
    <tr>
      <td>First row</td>
      <td>1</td>
      <td>2</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Second row</td>
      <td>2</td>
      <td>4</td>
      <td>6</td>
    </tr>
    <tr>
      <td>Third row</td>
      <td>3</td>
      <td>6</td>
      <td>9</td>
    </tr>
  </table>
</body>
fin
