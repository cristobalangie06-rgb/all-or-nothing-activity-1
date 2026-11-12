# all-or-nothing-activity-1
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Savoria Restaurant</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Georgia, "Times New Roman", serif;
            background: #f8f3ec;
            color: #33261f;
            line-height: 1.6;
        }

        /* =========================
           NAVIGATION
        ========================= */

        header {
            position: sticky;
            top: 0;
            z-index: 1000;
            background: rgba(255, 250, 244, 0.97);
            box-shadow: 0 3px 15px rgba(70, 40, 20, 0.12);
        }

        nav {
            max-width: 1200px;
            margin: auto;
            padding: 18px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            color: #8b3f2f;
            font-size: 28px;
            font-weight: bold;
            letter-spacing: 1px;
        }

        .logo span {
            color: #c89552;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 28px;
        }

        nav a {
            text-decoration: none;
            color: #49362b;
            font-family: Arial, sans-serif;
            font-weight: bold;
            font-size: 14px;
            transition: 0.3s;
        }

        nav a:hover {
            color: #b2643d;
        }

        /* =========================
           HERO
        ========================= */

        .hero {
            min-height: 88vh;
            display: flex;
            align-items: center;
            padding: 60px 8%;

            background:
                linear-gradient(
                    rgba(35, 18, 12, 0.60),
                    rgba(35, 18, 12, 0.48)
                ),
                url("https://images.unsplash.com/photo-
