# Websocket example


1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop)
2. Run `docker-compose up -d --build` in the root of the project
3. Open `http://localhost:8000` in your browser
4. Edit `templates/` directory and see the changes in the browser
5. Run `docker-compose down` to stop the server
6. Enjoy!

### if you want to add css and js from separate files use static folder

when you add css and js files in static folder you can use them in your html file like this
```html
<!-- load static should be at the top of the file -->
{% load static %}

<link rel="stylesheet" href="{% static 'path/to/file' %}">

<script src="{% static 'path/to/file' %}"></script>
```

