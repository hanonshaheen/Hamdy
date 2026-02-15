# Hamdy
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>رسالة خاصة 💌</title>

<style>
body {
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #ff9ecf, #ffc3e6);
    font-family: 'Tahoma', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    text-align: center;
}

.container {
    background: white;
    padding: 40px;
    border-radius: 20px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    width: 90%;
    max-width: 400px;
}

h1 {
    color: #ff4d88;
}

button {
    background: #ff4d88;
    color: white;
    border: none;
    padding: 15px 25px;
    font-size: 18px;
    border-radius: 30px;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background: #ff1a66;
    transform: scale(1.05);
}

.message {
    margin-top: 20px;
    font-size: 18px;
    color: #444;
    display: none;
    animation: fadeIn 1.5s ease forwards;
}

@keyframes fadeIn {
    from {opacity: 0;}
    to {opacity: 1;}
}
</style>

</head>
<body>

<div class="container">
    <h1>لـ حمدي ❤️</h1>
    <button onclick="showMessage()">اضغط هنا</button>
    <div class="message" id="loveMessage">
        الحقيقة إنك نعمة في حياتي 🤍  
        فخورة بقلبك، باجتهادك، بمحاولاتك الصادقة…  
        وجودك أمان وسند وراحة ليّ.  
        ودايمًا بشوف فيك شخص مميز يستاهل كل خير 💫
    </div>
</div>

<script>
function showMessage() {
    document.getElementById("loveMessage").style.display = "block";
}
</script>

</body>
</html>
