<head>
    <title>{{page.title}}</title>
    <style>
        html,
        body {
            margin: 0;
        }

        * {color: #0f0f0f;}

        nav {
            background: linear-gradient(#00abff, aliceblue, #00abff);
            padding: 2px 5px;
            margin-bottom: 10px;
        }
    </style>
</head>

<body>
    <nav>
        <h2>Shri5ti blog</h2>
    </nav>
    <main>
        {{content}}
        {% if(site.posts) %}
        <h3>Posts</h3>
        <ul>
            {% for post in site.posts %}
            <li>
                <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
            {% endfor %}
        </ul>
        {% endif %}
    </main>
    <footer>
        <div>
            <h4>Footer</h4>
        </div>
    </footer>
</body>