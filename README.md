# Articuno_Assignment

![ezgif com-gif-maker](https://user-images.githubusercontent.com/113454787/213131452-d53b195a-c2c0-4037-ac02-b214a74054db.gif)

command to spin up postgres db using docker :

sudo docker run  --detach      --name container-postgresdb-20     --publish 5432:5432             --env POSTGRES_USER=admin    --env POSTGRES_PASSWORD=admin     postgres:12.1 

![Screenshot from 2023-01-18 14-47-38](https://user-images.githubusercontent.com/113454787/213132402-126ee7fa-dd8c-4ca4-8106-f3272a34521a.png)

command to start the application : python3 ./app.py 
![Screenshot from 2023-01-18 14-49-48](https://user-images.githubusercontent.com/113454787/213132342-9515694b-6177-4de1-a421-50a2ec593955.png)


