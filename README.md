# And
<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Block Blast</title>

<style>
body{
    margin:0;
    background:#111827;
    color:white;
    font-family:Arial;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    flex-direction:column;
}

h1{
    color:#facc15;
    margin-bottom:20px;
}

#game{
    display:grid;
    grid-template-columns:repeat(8,60px);
    grid-template-rows:repeat(8,60px);
    gap:5px;
}

.cell{
    width:60px;
    height:60px;
    background:#1f2937;
    border-radius:10px;
    cursor:pointer;
    transition:0.2s;
}

.cell:hover{
    transform:scale(1.05);
}

.active{
    background:#22c55e;
}

.info{
    margin-top:20px;
    font-size:24px;
}

button{
    margin-top:20px;
    padding:12px 25px;
    border:none;
    border-radius:15px;
    background:#facc15;
    font-weight:bold;
    cursor:pointer;
}
</style>
</head>
</html>
