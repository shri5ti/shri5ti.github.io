<head>
    <title>{{page.title}}</title>
    <style>
        html,
        body {
            padding: 0;
            margin: 0;
            background: linear-gradient(#000,#545454,#777777,#545454,#000);
            color: white;
        }

        main {
            margin: 0 auto;
            width: 90%;
            border: 1px solid white;
            min-height: 80%;
            background-color: white;
            color: black;
            padding: 10px;
        }
    </style>
</head>

<body>
    <main>
        {{content}}
    </main>
    <footer>
        <div style="background-color: beige;">
            <h4>Footer</h4>
        </div>
    </footer>
</body>