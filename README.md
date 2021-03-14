# Login-Responsivo
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sing Up Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <main>
        <h1>Create a Account</h1>
        <div class="social-media">
            <a href="#">
                <img src="images/facebook.png" alt="Facebook">
            </a>

            <a href="#">
                <img src="images/google.png" alt="Google">
            </a>

            <a href="#">
                <img src="images/Linkedin.png" alt="Linkedin">
            </a>
        </div>

        <div class="alternative">
            <span>OR</span>
        </div>

        <form action="">

            <label for="name">
                <span>Nome</span>
                <input type="text" id="name" name="name">
            </label>

            <label for="Email">
                <span>Email</span>
                <input type="email" id="email" name="email">
            </label>

            <label for="Password">
                <span>Password</span>
                <input type="password" id="password" name="password">
            </label>
             
            <input type="submit" value="Sing Up" >
        </form>
    </main>

    <section class="image">
        <img src="images/mobile.svg" alt="Mobile">
        <div class="circle"></div>
    </section>
    
</body>
</html>
