# Сборка образа
 docker build . --tag=my_new 
# Запуск контейнера
 docker run --name my_1 -d -p 8000:8000 my_new
