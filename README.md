# pokedex.io
<!DOCTYPE html>
<html>

<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pixelify+Sans:wght@400;600&display=swap" rel="stylesheet">



    <meta charset="UTF-8">
    <meta http-equiv="X-UA-compatible" content="IE=edge">
    <meta name="viewport" content="wide=device-width,initial-scale=1.0">
    <link rel=""stylesheet href="style/style.css"></link>
    <title>Pokedex</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Pixelify+Sans:wght@400;500;600&family=Roboto:ital,wght@1,300&display=swap"
        rel="stylesheet">
    <style>
        body {
        
            background-image: url('https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/3a390145-1e80-4c9f-bea4-6f11959496cd/del304o-a42b2fab-d054-4ae3-be0b-dcb50b429172.jpg/v1/fill/w_1280,h_720,q_75,strp/pokeball_wallpaper_by_blackholekun_del304o-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9NzIwIiwicGF0aCI6IlwvZlwvM2EzOTAxNDUtMWU4MC00YzlmLWJlYTQtNmYxMTk1OTQ5NmNkXC9kZWwzMDRvLWE0MmIyZmFiLWQwNTQtNGFlMy1iZTBiLWRjYjUwYjQyOTE3Mi5qcGciLCJ3aWR0aCI6Ijw9MTI4MCJ9XV0sImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl19.uUBZCvo3rUs5zwjD83BHcfVX8H_E70EkJqrgIRqBCaw');
        }
        ul {
            display: flex;
      list-style: none;
        }
        li {
            list-style: none;
        }
        #Pokedex {
            width: 22rem;
            height: 35rem;
            background-color: white;
            border-radius: 8px;
            border: 10px solid white;
            
            background-size: 460px;
        }
        #bulbasaur {
            
           margin: auto;
            color: black;
            font-family: 'Pixelify Sans', sans-serif;
            text-align: center;
            font-size: 200%;
            text-transform: uppercase;
            border: 10px solid black;

            
            

        }
        #bulbasaurimg {
            
            display: flex;
            
            
            
            height: 150px;
        }
        #bulbasaursubstitle {
            justify-content: center;
            margin: auto;
            display: flex;
            font-family: 'Pixelify Sans', sans-serif;
            font-size: 20px;
            font-weight: lighter;
            border: 10px solid black;
            height: 100%;
            font-weight: lighter;
            padding: 3%;
            height: 1cm;
            text-transform: uppercase;
            border-inline-color: green;
            background-color: purple;
            
            
        }
        h1 {
            
            
            font-family: 'Pixelify Sans', sans-serif;
            font-size: 60px;
            text-align: center;
            background-color: white;
            border: 10px solid black;

        }
        p {
            border-top: 10px solid white;
            padding: 0%;
        }
#l1 {
    background-color: white;
    border: 10px solid black;
    border-inline-color: green;
    height: 7,5cm
}
#l2 {
    background-color: white;
    border: 10px solid black;
    border-inline-color: green;
}
        

    </style>
</head>

<body>
    <h1> Pokedex </h1>
    <ul>
    <li id="l1">
   
    <p id="bulbasaur"> bulbasaur </p>
 
    
   
   <img id="bulbasaurimg" src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/1.png" alt="bulbasaurimg">
   <p id="bulbasaursubstitle"> Type: grass, poison </p>
</li>
    <li id="l2">
    <p id="ivysaur"> ivysaur </p>
    <img id="ivysaur" src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/2.png" alt="ivysaur">
    <p id="ivysaursubtitle"> Type: grass, poison</p>
   </li>
</ul>
    
    


</body>

</html>
