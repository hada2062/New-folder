<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Webpage Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #062c3d;
            color: #ffffff;
        }

        header {
            background-color: #054f70;
            text-align: center;
            padding: 10px 0;
        }

        header h1 {
            margin: 0;
            color: #f4b400;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #073850;
            padding: 10px;
        }

        nav a {
            color: #ff7f50;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .search-bar {
            text-align: center;
            margin: 20px 0;
        }

        .search-bar input[type="text"] {
            padding: 5px;
        }

        .search-bar input[type="submit"] {
            padding: 5px 10px;
            background-color: #f4b400;
            border: none;
            cursor: pointer;
        }

        .search-bar input[type="submit"]:hover {
            background-color: #ff7f50;
        }

        main {
            padding: 20px;
        }

        h2 {
            color: #f4b400;
        }

        .subsection {
            border: 2px solid #4cc9ff;
            padding: 10px;
            margin: 20px 0;
        }

        .related {
            color: #f4b400;
        }

        .related a {
            color: #ff0000;
            text-decoration: none;
        }

        .related a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #073850;
            color: #b0b0b0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Header</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Our team</a>
        <a href="#">Projects</a>
        <a href="#">Contact</a>
    </nav>

    <div class="search-bar">
        <input type="text" placeholder="Search query">
        <input type="submit" value="Go!">
    </div>

    <main>
        <h2>Article heading</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec a diam lectus. Set sit amet ipsum mauris. Maecenas congue ligula as quam viverra nec consectetur ant hendrerit. Donec et mollis dolor. Praesent et diam eget libero egestas mattis sit amet vitae augue. Nam tincidunt congue enim, ut porta lorem lacinia consectetur.</p>

        <div class="subsection">
            <h3>Subsection</h3>
            <p>Donec ut libero sed accu vehicula ultricies a non tortor. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ut gravida lorem. Ut turpis felis, pulvinar a semper sed, adipiscing id dolor.</p>

            <p>Pellentesque auctor nisi id magna consequat sagittis. Curabitur dapibus, enim sit amet elit pharetra tincidunt feugiat nisi imperdiet. Ut convallis libero in urna ultrices accumsan. Donec sed odio eros.</p>
        </div>

        <div class="subsection">
            <h3>Another subsection</h3>
            <p>Donec viverra mi quis quam pulvinar at malesuada arcu rhoncus. Cum sociis natoque penatibus et manis dis parturient montes, nascetur ridiculus mus. In rutrum accumsan ultricies. Mauris vitae nisi at sem facilisis semper ac in est.</p>

            <p>Vivamus fermentum semper porta. Nunc diam velit, adipiscing ut tristique vitae sagittis vel odio. Maecenas convallis ullamcorper ultricies. Curabitur ornare, ligula semper consectetur sagittis, nisi diam iaculis velit, is fringilla sem nunc vet mi.</p>
        </div>

        <div class="related">
            <h3>Related</h3>
            <ul>
                <li><a href="#">Oh I do like to be beside the seaside</a></li>
                <li><a href="#">Oh I do like to beside the sea</a></li>
                <li><a href="#">Although in the North of England</a></li>
                <li><a href="#">It never stops raining</a></li>
                <li><a href="#">Oh well...</a></li>
            </ul>
        </div>
    </main>

    <footer>
        &copy;Copyright 2050 by nobody. All rights reversed.
    </footer>
</body>
</html>
