# Parcial2MenaEdgar
Examen

Este Repositorio Contiene un codigo para 5 marcas de telefono y despues usando array push se agregan 2 marcas 
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title></title>
</head>
<body>
<?php 
$telefonos = [
    ["Iphone Pro Max", 8000],
    ["Samsung", 5000],
    ["Xiomi", 3000],
    ["Motorola", 10000],
    ["Ghi", 1500]
];

echo "<h1>Teléfonos</h1>";

foreach ($telefonos as $telefono) {
    echo "<li>{$telefono[0]} \${$telefono[1]}</li>";
}



array_push($telefonos, ["ZTE", 2200]);
array_push($telefonos, ["Nokia", 2700]);

echo "<h1>Dos Nuevas Marcas De Teléfonos</h1>";

foreach ($telefonos as $telefono) {
    echo "<li>{$telefono[0]} \${$telefono[1]}</li>";
}

?>
</body>
</html>

