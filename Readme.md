# nginx-uwsgi-pythonflask application
This [**Docker**](https://www.docker.com/) image allows you to create [**Flask**](http://flask.pocoo.org/) web applications in [**Python**](https://www.python.org/) that run with [**uWSGI**](https://uwsgi-docs.readthedocs.org/en/latest/) and [**Nginx**](http://nginx.org/en/) in a single container.

## uwsgi-nginx-flask
**Docker** image with **uWSGI** and **Nginx** for **Flask** applications in **Python** running in a single container. 

## Docker Build and run
Using uWSGI and nginx for production workloads

Docker Build
```
docker build . -t {some tag name}
```

Docker run - Detach mode
```
docker run -d -p 3000:80 {some tag name} 
```

Docker run with interactive mode - recommended for debug
```
docker run -p 3000:80 -it {some tag name}  
```

## sample test
htttp://localhost:3000/
