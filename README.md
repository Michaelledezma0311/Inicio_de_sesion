# Inicio_de_sesion

    var inicioDeSesionRegistrado = "alura";
    var contrasenhaRegistrada = "alura321";



    for(var intentos = 1; intentos <=3 ; intentos++){

        
    var inicioDeSesionIngresado = prompt("Ingrese su usuario");
    var contrasenhaIngresada = prompt("Ingrese su contraseña");

        if( inicioDeSesionRegistrado == inicioDeSesionIngresado && contrasenhaRegistrada == contrasenhaIngresada ) {
        alert("Bienvenido al sistema " + inicioDeSesionIngresado);
        break;
    } 
        else {
        alert("inicio de sesión inválido. Favor intente de nuevo");
    }

    }
