## Purpose
Nginx acts as a **public web server** that receives all incoming requests and forwards them to the Flask application running on Gunicorn behind the scenes.

## Benefits
- **Safer** - fewer services exposed to the internet
- **Faster** - Nginx is optimized for handling web traffic
- **More flexible** - easier to scale or make changes later
