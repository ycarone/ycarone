<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Windows-like Login Page</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body, html {
            height: 100%;
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            width: 100%;
        }

        .background {
            background-image: url('https://picsum.photos/1920/1080');
            height: 100%;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .login-container {
    width: 90%; /* Adjusted width to 90% */
    max-width: 400px; /* Limited maximum width */
    margin: 0 auto; /* Center the container horizontally */
    display: flex;
    justify-content: center;
    align-items: center;
}



        .login-card {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 90%; /* Full width of login container */
            height: auto;
        }

        .user-icon {
            font-size: 7rem; /* Increased icon size to 5rem */
            color: #007bff;
            margin-bottom: 20px;
        }

        .welcome-text {
            font-size: 24px;
            margin-bottom: 20px;
            color: #333;
        }

        input[type="email"], input[type="password"] {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 16px;
            box-sizing: border-box;
        }

        button {
            background-color: #0078D7;
            color: white;
            border: none;
            padding: 12px 70px;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #005a9e;
        }

        /* Social login section styles */
        .social-login {
            margin-top: 20px;
            text-align: center;
        }

        .social-login p {
            margin-bottom: 10px;
            color: #666;
        }

        .social-icons {
            display: flex;
            justify-content: center;
        }

        .social-icon {
            margin: 0 10px;
            width: 60px;
            height: 60px;
            background-color: #007bff;
            color: #fff;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            transition: background-color 0.3s ease;
            margin-bottom: 20px;
            
        }

        .social-icon i {
            font-size: 1.5rem;
        }

        .social-icon:hover {
            background-color: #0056b3;
        }

        .time {
            position: absolute;
            bottom: 20px;
            left: 20px;
            color: white;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <div class="background">
        <div class="login-container">
            <div class="login-card">
                <i class="fas fa-user-circle user-icon"></i>
                <div class="welcome-text">Welcome back</div>
                <form>
                    <input type="email" placeholder="Email address" required>
                    <br>
                    <input type="password" placeholder="Password" required>
                    <br>
                    <button type="submit">Sign in</button>
                </form>
                
                <div class="social-login">
                    <p><b>Or sign in with:</b></p>
                    <div class="social-icons">
                        <div class="social-icon">
                            <i class="fab fa-google"></i> <!-- Font Awesome Google icon -->
                        </div>
                        <div class="social-icon">
                            <i class="fab fa-facebook"></i> <!-- Font Awesome Facebook icon -->
                        </div>
                        <div class="social-icon">
                            <i class="fab fa-twitter"></i> <!-- Font Awesome Twitter icon -->
                        </div>
                        
                    </div>
                </div>
                <div>
                  <p>Don't have an account?</p>
                        <a href="#">sign up</a>
                    </div>
            </div>
            
        </div>
    </div>

    
</body>
</html>

