
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html>
<head>
   <title>Ejemplo 4.</title>
<style type="text/css">
   h1 { font-family: verdana; text-align: center; color: purple; }
   p { font: 1.2em arial; color: navy; padding:0.3em 3em  }
</style>
</head>
<body>
   <h1>Presentaci&oacute;n con javascript</h1>
   <script language="javascript">
      var presentacion = "Hola, bienvenido a mi p&aacute;gina"
      var pregunta =  "&#191;C&oacute;mo te llamas?"
      alert(presentacion)
      var a = prompt(pregunta)
      document.write("<p>hola " + a + "</p>")
   </script>
   <p>Encantado de conocerte</p>
</body>
</html>

