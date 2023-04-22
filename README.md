# Impesion-en-FuncionFor
estecodigo demuestra el uso del codigo For, similar al while 
<meta charset="UTF-8">
<h1>JUEGO</h1>
<script>
  function saltoLinea()  {
    document.write("<br>");
    document.write("<br>");
}
  function imprimir(frase) {
    document.write(frase);  
    saltoLinea();
  }
var texto = (prompt("ingrese un caracter:"));
 var ingresa = parseInt(prompt("Ingrese las lineas a repetir:"));
 var ingresa2 = parseInt(prompt("ingresa el numero de columnas a repetir:")); 
 for ( lineas = 1; lineas <= ingresa; lineas++) {
    for (var columnas = 1; columnas <= ingresa2; columnas++) {
      document.write(texto);
    }
    saltoLinea();
  }
 

  imprimir("fin :)");
</script>
