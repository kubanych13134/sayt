<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>You're So Beautiful</title>

<style>
body{
    margin:0;
    overflow:hidden;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:radial-gradient(circle,#260015,#090010);
    font-family:Arial,sans-serif;
}

.scene{
    position:relative;
    width:700px;
    height:700px;
}

.heart{
    position:absolute;
    font-size:24px;
    color:#ff6ab5;
    text-shadow:
        0 0 10px #ff4da6,
        0 0 25px #ff4da6,
        0 0 45px #ff2f92;
    animation:emojiSpin 3s linear infinite;
}

/* Крутятся только смайлики */
@keyframes emojiSpin{
    from{
        transform:rotate(0deg);
    }
    to{
        transform:rotate(360deg);
    }
}

.spark{
    position:absolute;
    width:7px;
    height:7px;
    border-radius:50%;
    background:#ff8bc9;
    box-shadow:
        0 0 10px #ff8bc9,
        0 0 20px #ff5cb1;
    animation:float 4s linear infinite;
}

@keyframes float{
    0%{
        transform:translateY(0) scale(1);
        opacity:1;
    }
    100%{
        transform:
            translateY(-50px)
            scale(0);
        opacity:0;
    }
}

.text{
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    color:#ffe3f0;
    font-size:56px;
    text-align:center;
    font-weight:bold;
    text-shadow:
        0 0 10px #ff69b4,
        0 0 30px #ff2f92,
        0 0 60px #ff2f92;
    animation:pulse 2s infinite;
    z-index:10;
}

@keyframes pulse{
    50%{
        transform:
        translate(-50%,-50%)
        scale(1.05);
    }
}

.qr{
    position:absolute;
    bottom:30px;
    left:50%;
    transform:translateX(-50%);
    width:120px;
    border-radius:16px;
    box-shadow:
        0 0 20px #ff5ca8,
        0 0 40px #ff2f92;
}
</style>
</head>
<body>

<div class="scene" id="scene">

<div class="text">
you’re so<br>beautiful
</div>

<img class="qr"
src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://example.com">

</div>

<script>
const scene=document.getElementById("scene");
const count=120;

for(let i=0;i<count;i++){

    let t=Math.PI*2*i/count;

    // Форма сердца НЕ крутится
    let x=16*Math.pow(Math.sin(t),3);
    let y=-(13*Math.cos(t)
        -5*Math.cos(2*t)
        -2*Math.cos(3*t)
        -Math.cos(4*t));

    x*=16;
    y*=16;

    // Смайлики
    let heart=document.createElement("div");
    heart.className="heart";
    heart.innerHTML="💖";

    heart.style.left=(350+x)+"px";
    heart.style.top=(350+y)+"px";

    // разная скорость вращения смайликов
    heart.style.animationDuration=
        (2+Math.random()*3)+"s";

    scene.appendChild(heart);

    // Розовые штуки/частицы
    for(let j=0;j<2;j++){
        let spark=document.createElement("div");
        spark.className="spark";

        spark.style.left=
            (350+x+
            Math.random()*20-10)+"px";

        spark.style.top=
            (350+y+
            Math.random()*20-10)+"px";

        spark.style.animationDelay=
            Math.random()*4+"s";

        scene.appendChild(spark);
    }
}
</script>

</body>
</html>
