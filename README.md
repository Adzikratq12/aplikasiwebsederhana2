
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Adzikra Tazkiya Qurrotaayun_2120225_WPII_2.6C</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f4f4f4;
    }

    .container {
      text-align: center;
    }

    input[type="text"] {
      padding: 8px;
      margin-right: 10px;
    }

    button {
      padding: 8px 16px;
      background-color: #007bff;
      color: #fff;
      border: none;
      cursor: pointer;
    }

    #output {
      margin-top: 20px;
    }
  </style>
</head>

<body>
  <div class="container">
    <input type="text" id="inputText" placeholder="Masukkan teks">
    <button onclick="tampilkanTeks()">Tampilkan</button>
    <div id="output"></div>
  </div>

  <script>
    function tampilkanTeks() {
      var input = document.getElementById('inputText').value;
      var output = document.getElementById('output');
      output.innerHTML = '<p>Teks yang dimasukkan: ' + input + '</p>';
    }
  </script>
</body>

</html>
