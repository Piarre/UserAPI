# UserAPI
A Simple API for user built in Java.

### ⚙️ Setup
See `application.properties` into `userapi/src/main/resources`
and change DB's infos.

### 🖐 Endpoint

`/api/v1/users/`


|          | Get all users | Find a user  | Create a user | Delete a user | Update a user |
| :------: | :-----------: | :----------: | :-----------: | :-----------: | :-----------: |
|  Method  |     `GET`     |    `GET`     |    `POST`     |   `DELETE`  |    `PUT`     |
| Endpoint |    `/all`     | `/find/{id}` |    `/add`     |  `/delete/{id}`  | `/update` |
|   Body   |               |          |      ```{ "username": "", "password": "", "email": ""} ``` | | ```{"id": 1, "uuid": "","username": "", "password": "", "email": ""}``` | 

-------------

# 🔐 License
MIT
