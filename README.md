# PokemonC
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap-theme.min.css">
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/js/bootstrap.min.js"></script>
    <title>charmander</title>
    <style>
        
        body {
            background-color: #f2882c;
    
        }
        .pokeimg1 {
            position: absolute;
        }
        .pokeImg {
            width: 150px;
            height: 150px;
            position: absolute;
            top: 299px;
            left: 155px;
            
        }
        button {
            width: 50px;
            height: 50px;
            background-color: rgb(16, 3, 126);
            border-color: rgb(204, 200, 198);
            border-radius: 50px;
            position: absolute;
            left: 65px;
            top: 540px;
        }
        .placeholder {
            width: 145px;
            height: 68px;
            position: absolute;
            top: 609px;
            left: 120px;
            font-size: 25px;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            border-radius: 10px;
            background-color: transparent;
            text-align: center;
            text-shadow: 1px;
    
        }
        .grafica {
            width: 300px;
            height: 300px;
            position: absolute;
            top: 294px;
            left: 527px;
            opacity: 100%;
        }
    </style>

</head>
<body>
    <div style="margin: 10px;">
        <nav class="navbar navbar-light" style="background-color: rgb(186, 191, 197);">
         <div class="container">
           <a class="navbar-brand" href="index.html" style="color: black;                                                                     font-family: 'Maputo', sans-serif;
           ; font-size: xx-large;">Inicio</a>
           <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <style>
              @import url('https://fonts.cdnfonts.com/css/maputo');
            </style>
  
            
            <ul class="nav navbar-nav">
               <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink"
                 data-toggle="dropdown"
                 aria-haspopup="true"
                 aria-expanded="false">Unidad 1</a>
                <div class="dropdown-menu"
                aria-labelledby="navbarDripdownMenuLink">
                
                <a class="dropdown-item"
                href="perfil.html">Perfil</a><br>
                
                <a class="dropdown-item"
                href="calculadora.html">Calculadora</a><br>
                
                <a class="dropdown-item"
                href="tienda.html">Tienda </a><br>
            </div></a>
               </li>


               <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink"
                 data-toggle="dropdown"
                 aria-haspopup="true"
                 aria-expanded="false">Unidad 2</a>
                <div class="dropdown-menu"
                aria-labelledby="navbarDripdownMenuLink">
                
                <a class="dropdown-item"
                href="primavera.html">primavera</a><br>
                
                <a class="dropdown-item"
                href="tienda pedido.html">Tienda pedido</a><br>
            </div></a>
               </li>


               <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink"
                 data-toggle="dropdown"
                 aria-haspopup="true"
                 aria-expanded="false">Unidad 3</a>
                <div class="dropdown-menu"
                aria-labelledby="navbarDripdownMenuLink">
                
                <a class="dropdown-item"
                href="base de datos.html">Base de Datos</a><br>
                
                <a class="dropdown-item"
                href="peliculas
                .html">Peliculas</a><br>

                <a class="dropdown-item"
                href="pokemond.html">Pokedex</a><br>
            </div></a>
                 
               </li>
            </ul>
           </div>
         </div>
        </nav>

    </div>

    <img src="pokedex,.jpg" alt="Pokedex" width="900px">
    <input type="text" placeholder="charmander" id="pokeName" class="placeholder">
    <img src="Pokebola.png" alt="Pokebola" id="pokeImg" width="300px" class="pokeImg">

    <div id="pokename" class="pokeimg1" style="left: 900px; top: 290px; font-size: 15px; color: rgb(7, 7, 10);"></div>
    <div id="pokeHe" class="pokeimg1" style="left: 900px; top: 320px; font-size: 15px; color: rgb(234, 245, 245);"></div>
    <div id="pokeWe" class="pokeimg1" style="left: 900px; top: 350px; font-size: 15px; color: rgb(55, 55, 48);"></div>
    <div id="poketype" class="pokeimg1" style="left: 900px; top: 380px; font-size: 15px; color: rgb(66, 194, 194);"></div>
    <div id="pokeitem" class="pokeimg1" style="left: 900px; top: 410px; font-size: 15px; color: rgb(99, 112, 131);"></div>
    <div id="pokemove1" class="pokeimg1" style="left: 900px; top: 440px; font-size: 15px; color: rgb(10, 245, 100);"></div>
    <div id="pokemove2" class="pokeimg1" style="left: 900px; top: 470px; font-size: 15px; color: rgb(119, 18, 252);"></div>
    <div id="pokemove3" class="pokeimg1" style="left: 900px; top: 500px; font-size: 15px; color: rgb(11, 19, 73);"></div>
    <div id="pokemove4" class="pokeimg1" style="left: 900px; top: 530px; font-size: 15px;color: rgb(12, 163, 143);"></div>

    <div id="pokeid" class="pokeimg1" style="left: 215px; top: 290px; font-size: 17px; color: black;"></div>
    <div id="pokeorder" class="pokeimg1" style="left: 500px; top: 300px; font-size: 15px; color: beige;"></div>

    <button onclick="fetchPokemon()" class="button"></button>
    <div class="grafica">
        <canvas id="miCanvas"></canvas>
    </div>

    <script>
        const fetchPokemon = () => {
            const pokeNameInput = document.getElementById("pokeName");
            let pokeName = pokeNameInput.value.toLowerCase();
            const url = https://pokeapi.co/api/v2/pokemon/${pokeName};

            fetch(url)
                .then(res => {
                    if (!res.ok) {
                        throw new Error('Network response was not ok');
                    }
                    return res.json();
                })
                .then(data => {
                    console.log(data);

                    let pokeImgSrc = data.sprites.front_default;
                    document.getElementById('pokeImg').src = pokeImgSrc;

                    let name = document.getElementById('pokename');
                    name.innerHTML = Name; ${data.forms[0].name};

                    let element1 = document.getElementById('pokeHe');
                    element1.innerHTML = Height: ${data.height};

                    let element2 = document.getElementById('pokeWe');
                    element2.innerHTML = Weight: ${data.weight};

                    let element3 = document.getElementById('pokeorder');
                    element3.innerHTML = Order: #${data.order};

                    let element4 = document.getElementById('pokeid');
                    element4.innerHTML = Id: #${data.id};

                    let element5 = document.getElementById('pokeitem');
                    element5.innerHTML = Ability: ${data.abilities[0].ability.name};

                    let element6 = document.getElementById('poketype');
                    element6.innerHTML = Type: ${data.types[0].type.name};

                    let element7 = document.getElementById('pokemove1');
                    element7.innerHTML = Move 1: ${data.moves[0].move.name};

                    let element8 = document.getElementById('pokemove2');
                    element8.innerHTML = Move 2: ${data.moves[1].move.name};

                    let element9 = document.getElementById('pokemove3');
                    element9.innerHTML = Move 3: ${data.moves[2] ? data.moves[2].move.name : ''};

                    let element10 = document.getElementById('pokemove4');
                    element10.innerHTML = Move 4: ${data.moves[3] ? data.moves[3].move.name : ''};

                    const miCanvas = document.getElementById("miCanvas").getContext("2d");
                    if (window.miCanva !== undefined) {
                        window.miCanva.destroy();
                    }
                    window.miCanva = new Chart(miCanvas, {
                        type: "bar",
                        data: {
                            labels:["HP", "Attack", "Defense", "Special-A", "Special-D", "Speed"],
                            datasets:[{
                                label: data.forms[0].name,
                                backgroundColor: 'rgba(54,162,235,1)',
                                data:[
                                    data.stats[0].base_stat,
                                    data.stats[1].base_stat,
                                    data.stats[2].base_stat,
                                    data.stats[3].base_stat,
                                    data.stats[4].base_stat,
                                    data.stats[5].base_stat
                                ],
                                borderColor: [
                                    'rgba(255, 99, 132, 1)',
                                    'rgba(54, 162, 235, 1)',
                                    'rgba(255, 206, 86, 1)',
                                    'rgba(75, 192, 192, 1)',
                                    'rgba(153, 102, 255, 1)',
                                    'rgba(255, 159, 64, 1)'
                                ],
                                backgroundColor: [
                                    'rgba(255, 99, 132, 0.5)',
                                    'rgba(54, 162, 235, 0.5)',
                                    'rgba(255, 206, 86, 0.5)',
                                    'rgba(75, 192, 192, 0.5)',
                                    'rgba(153, 102, 255, 0.5)',
                                    'rgba(255, 159, 64, 0.5)'
                                ]
                            }]
                        }
                    });
                })
                .catch(error => {
                    console.error('There has been a problem with your fetch operation:', error);
                    alert('Error fetching Pokemon data. Please try again.');
                });
        }
    </script>
    <script src="charmander.jpg"></script>
</body>
</html>
