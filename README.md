<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>JS</title>
    </head>
    <body>
        <h3> demo non pri data type</h3>
        <script>
            // object creation & init with given value
            var st1=new String("bhumika");
            var n1 = new Number(49);
            let b1 = new Boolean(true);
            let d1 = new Date(15);
            let a1 = [12,23,45,65,2]; //literal


            document.write("st", st1,"<br>");
            document.write("n1", n1,"<br>");
            document.write("b1", b1,"<br>");
            document.write("d1", d1,"<br>");
            document.write("a1", a1,"<br>");

            // object creation with default value

            var st2=new String();
            var n2 = new Number();
            let b2 = new Boolean();
            let d2 = new Date();
            let a2 = []; //literal


            document.write("st", st2,"<br>");
            document.write("n1", n2,"<br>");
            document.write("b1", b2,"<br>");
            document.write("d1", d2,"<br>");
            document.write("a1", a2,"<br>");
        </script>
    </body>
    </html>
