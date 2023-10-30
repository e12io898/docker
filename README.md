## **Задание 1:**
Из папки `nginx`:
> `sudo docker build -t my_nginx:v1 -f nginx_dockerfile .`
> 
> `sudo docker run -p 8000:80 my_nginx:v1`
> 
> [http://localhost:8000/](http://localhost:8000/)

## **Задание 2:**
Из папки `stocks_products`:
> `sudo docker build -t stock_products:v1 -f py_dockerfile .`
> 
> `sudo docker run -d -p 8000:8000 stock_products:v1`
> 
> [http://localhost:8000/api/v1/](http://localhost:8000/api/v1/)


