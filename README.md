# UserAPI
A Simple API for user built in Java.

### Endpoint

`/api/v1/users/`


|          | Get all users | Find a user  | Create a user | Delete a user | Update a user |
| :------: | :-----------: | :----------: | :-----------: | :-----------: | :-----------: |
|  Method  |     `GET`     |    `GET`     |    `POST`     |   `DELETE`  |    `PUT`     |
| Endpoint |    `/all`     | `/find/{id}` |    `/add`     |  `/delete/{id}`  | `/update` |
|   Body   |               |          |      ```{ "username": "Piarre", "password": "Passwd+", "email": "pierre@ideestore.fr"} ``` | | ```{"id": 1, "uuid": "USER UUID","username": "Piarre_", "password": "Passwd++", "email": "pierre@example.com"}``` | 

-------------

# 🔐 License
MIT
