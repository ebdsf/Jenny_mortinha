<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>On The Floor</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:linear-gradient(135deg,#0f172a,#581c87,#db2777);
    min-height:100vh;
    overflow-x:hidden;
    color:white;
}

.hero{
    text-align:center;
    padding:70px 20px 40px;
}

.hero h1{
    font-size:3rem;
}

.hero p{
    margin-top:10px;
    opacity:.8;
}

.card{
    width:min(900px,90%);
    margin:30px auto 60px;
    background:rgba(255,255,255,.12);
    backdrop-filter:blur(12px);
    border-radius:25px;
    padding:30px;
    box-shadow:0 0 30px rgba(0,0,0,.3);
}

button{
    display:block;
    margin:25px auto;
    padding:15px 35px;
    border:none;
    border-radius:50px;
    background:#ff3ea5;
    color:white;
    font-size:18px;
    cursor:pointer;
    transition:.3s;
}

button:hover{
    transform:scale(1.05);
}

#lyrics{
    display:none;
    white-space:pre-wrap;
    line-height:1.7;
    font-size:16px;
}

footer{
    text-align:center;
    padding:30px;
    opacity:.7;
}
</style>
</head>

<body>

<div class="hero">
    <h1>🎉 ON THE FLOOR 🎉</h1>
    <p>Uma página simples, moderna e feita para o GitHub Pages.</p>
</div>

<div class="card">

<button onclick="mostrarMusica()">
Mostrar a letra 🎵
</button>

<div id="lyrics">
J-Lo, ya tú sabes, no hay más na'
It's a new generation
Mr. Worldwide
Of party people
Get on the floor, dale, get on the floor
RedOne
Let me introduce you to my party people in the club, huh
I'm loose (I'm loose)
And everybody knows I get off the chain
Baby, it's the truth (it's the truth)
I'm like Inception
I play with your brain
So don't sleep or snooze (snooze)
I don't play no games so d-don't-d-don't-d-don't
Don't get it confused, no
'Cause you will lose, yeah
Now, now pump-pu-pump-pu-pu-pu-pump it up
And back it up like a Tonka truck
Dale
If you go hard, you gotta get on the floor (hey)
If you're a party freak then step on the floor (yeah)
If you're an animal then tear up the floor
Break a sweat on the floor
Yeah, we work on the floor (dale)
Don't stop, keep it movin', put your drinks up (woo)
Pick your body up and drop it on the floor (hey)
Let the rhythm change your world on the floor
You know we're running sh- tonight on the floor
Brazil, Morocco, London to Ibiza
Straight to LA, New York, Vegas to Africa (dale)
Dance the night away
Live your life and stay young on the floor
Dance the night away
Grab somebody, drink a little more
(Así mismo, así me gusta)
(Así me gusta, así me gusta)
La, la-la-la-la, la-la-la-la-la-la-la-la-la
Tonight we gon' be it on the floor (woo)
La, la-la-la-la, la-la-la-la-la-la-la-la-la
Tonight we gon' be it on the floor (yeah, that's right)
I know you got it, clap your hands on the floor (hey)
And keep on rockin', work it up on the floor (yeah)
If you're a criminal, kill it on the floor
Steal it quick on the floor, on the floor (dale)
Don't stop, keep it movin', put your drinks up (woo)
It's getting ill, it's getting sick on the floor (hey)
We never quit, we never rest on the floor (yeah)
If I ain't wrong, we'll probably die on the floor
Brazil, Morocco, London to Ibiza
Straight to LA, New York, Vegas to Africa (dale)
Dance the night away
Live your life and stay young on the floor
(Dale, así me gusta)
Dance the night away
Grab somebody, drink a little more
(Dale, así me gusta)
(Así me gusta, así me gusta)
La, la-la-la-la, la-la-la-la-la-la-la-la-la
Tonight we gon' be it on the floor (yeah, that's right)
La, la-la-la-la, la-la-la-la-la-la-la-la-la
Tonight we gon' be it on the floor (yeah, that's right)
La, la-la-la-la, la-la-la-la-la-la-la-la-la
Tonight we gon' be it on the floor
La, la-la-la-la, la-la-la-la-la-la-la-la-la
Tonight we gon' be it on the floor
That badonka donk
Is like a trunk full of bass on an old school Chevy
Seven-trey donkey donk (yeah)
All I need is some vodka and some chonky Coke
And watch, shit gon' get Donkey Konged
Baby, if you're ready for things to get heavy
I get on the floor and act a fool if you let me, dale
Don't believe me, just bet me
My name ain't Keith but I see why you sweat me
LA, Miami, New York
Say no more, get on the floor (woo)
Dance the night away
Live your life and stay young on the floor
Dance the night away
Grab somebody, drink a little more
La, la-la-la-la, la-la-la-la-la-la-la-la-la (yeah, that's right)
Tonight we gon' be it on the floor
La, la-la-la-la, la-la-la-la-la-la-la-la-la (yeah, that's right)
Tonight we gon' be it on the floor
La, la-la-la-la, la-la-la-la-la-la-la-la-la (woo)
Tonight we gon' be it on the floor
La, la-la-la-la, la-la-la-la-la-la-la-la-la (yeah, that's right)
Tonight we gon' be it on the floor (woo)
Tonight we gon' be it on the floor
Tonight we gon' be it on the floor


</div>

</div>

<footer>
Feito com HTML, CSS e JavaScript.
</footer>

<script>
function mostrarMusica(){
    const letra = document.getElementById("lyrics");

    if(letra.style.display==="block"){
        letra.style.display="none";
    }else{
        letra.style.display="block";
        letra.scrollIntoView({behavior:"smooth"});
    }
}
</script>

</body>
</html>