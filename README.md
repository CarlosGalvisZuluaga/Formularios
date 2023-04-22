<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="description" content="Esta pagina web se basara en informacion personal y la creacion de tres formularios distintos">
        <meta name="author" conten="Carlos Galvis">



    </head>
    <body>
        <h1> Biografia</h1>
        <p>Mi nombre es Carlos Alberto Galvis Zuluaga, soy de la ciudad de Cartagena-Bolivar, naci un 17 de marzo de 2004.
           Me gradue de bachiller y alcance a cursar dos semestres universitarios en la Universidad Tecnologica de Bolivar 
           en la carrera de Administracion de Empresas, lo que mas me gusta hacer en mis tiempos libres es jugar futbol y videojuegos.
           Tome este curso para poder aprender y disfrutar de la programacion, y si es posible vivir de ello.
           Vivo con mis padres, mi hermano y Tengo 4 perros</p>
        <img src="Foto.jpeg">
        <h2>Comidas favoritas</h2>
        <ul>
            <li><a href="https://cartagenateamo.com/wp-content/uploads/2021/02/WhatsApp-Image-2021-02-11-at-12.23.58-PM-1.jpeg" target="_BLANK">Mojarra Frita</a></li>
            <li><a href="https://recetasdecolombia.com/wp-content/uploads/2022/02/mote-de-queso--500x375.jpg" target="_BLANK">Mote de queso</a></li>
            <li><a href="https://media-cdn.tripadvisor.com/media/photo-p/0c/8e/29/36/queso-frito-con-tajadas.jpg" target="_BLANK">Platano verde con queso</a></li>
        </ul>
        <h2>Cancion Favorita</h2>
        <audio src="Audio.mp3" controls></audio>
        <main>
            <h2>Formulario</h2>
            <h3>Informacion personal</h3>
            <section id="">
              <form>
                <div>
                    <label for="Nombre">Nombre</label>
                    <input type="text" id="Nombre" class="" name="Nombre" placeholder="Escriba aqui" required>
                </div>
                
                <div>
                    <label for="SegundoNombre">Segundo Nombre</label>
                    <input type="text" id="SegundoNombre" class="" name="SegundoNombre" placeholder="Escriba aqui">
                </div>
                
                <div>
                    <label for="PrimerApellido">Primer Apellido</label>
                    <input type="text" id="PrimerApellido" class="" name="PrimerApellido" placeholder="Escriba aqui" required>
                </div>

                <div>
                    <label for="SegundoApellido">Segundo Apellido</label>
                    <input type="text" id="SegundoApellido" class="" name="SegundoApellido" placeholder="Escriba aqui" required>
                </div>
                
                <div>
                    <label for="Edad">Edad</label>
                    <input type="number" id="Edad" class="" name="Edad" placeholder="Escriba aqui" required>
                </div>

                <div>
                    <label for="Correo">Correo</label>
                    <input type="email" id="Correo" class="" name="Correo" placeholder="Escriba aqui" required pattern="[a-z0-9.,_-+%]+[a-z0-9.-]+\.[a-z]{2,}$">
                </div>

                <div>
                    <label for="Telefono">Telefono</label>
                    <input type="number" id="Telefono" class="" name="Telefono" placeholder="Escriba aqui" required>
                </div>

                <h3>Informacion Fisica</h3>
            <section id="">
              <form>
                <div>
                    <label for="Sexo">Sexo</label>
                    <input type="radio" id="Sexo" class="" name="Sexo"  value="M" required> <label>Masculino</label>
                    <input type="radio" id="Sexo" class="" name="Sexo"  value="F" required> <label>Femenino</label>
                </div>
                
                <div>
                    <label for="Estatura">Estatura</label>
                    <input type="text" id="Estatura" class="" name="Estatura" placeholder="Escriba aqui">
                </div>
                
                <div>
                    <label for="Peso">Peso</label>
                    <input type="Number" id="Peso" class="" name="Peso" placeholder="Escriba aqui" required>
                </div>

                <div>
                    <label for="Deporte">Deporte</label>
                    <input type="text" id="Deporte" class="" name="Deporte" placeholder="Escriba aqui" required>
                </div>

                <div>
                    <label for="FrecuenciaDeActividadFisica">Frecuencia de actividad fisica</label>
                    <input type="text" id="FrecuenciaDeActividadFisica" class="" name="FrecuenciaDeActividadFisica" placeholder="Escriba aqui" required>

                    <h3>Informacion Alimenticia</h3>
                    <section id="">
                      <form>
                        <div>
                            <label for="Desayuna">Desayuna</label>
                            <input type="radio" id="Desayuna" class="" name="Desayuna"  value="Si" required> <label>Si</label>
                            <input type="radio" id="Desayuna" class="" name="Desayuna"  value="No" required> <label>No</label>
                        </div>
                        
                        <div>
                            <label for="Almuerza">Almuerza</label>
                            <input type="radio" id="Almuerza" class="" name="Almuerza"  value="Si" required> <label>Si</label>
                            <input type="radio" id="Almuerza" class="" name="Almuerza"  value="No" required> <label>No</label>
                        </div>
                        
                        <div>
                            <label for="Cena">Cena</label>
                            <input type="radio" id="Cena" class="" name="Cena"  value="Si" required> <label>Si</label>
                            <input type="radio" id="Cena" class="" name="Cena"  value="No" required> <label>No</label>
                        </div>
                        
                        <div>
                            <label for="ComidasAlDia">Comidas al Dia</label>
                            <input type="number" id="ComidasAlDia" class="" name="ComidasAlDia" placeholder="Escriba aqui" required>
                        </div>
        
                </div>
              </form>
        </main>
    </body>
</html>
