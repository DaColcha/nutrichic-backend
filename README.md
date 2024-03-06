# NutriChic backend

## Entradas Blog
#### Objeto:
    {
        "categoria": 4,
        "titulo": "título entrada",
        "contenido": " contenido "
    }

- **GET** /blog
- **POST** /blog , envías el objeto
- **DELETE** /blog/{id}
- **PATCH** /blog/editar/{id} , envías el objeto
## Mensajes Contacto

#### Objeto:
    {
        "nombresPaciente": " nombres completos",
        "emailPaciente": " email ",
        "telefonoPaciente": " no debe tener más de 10 caracteres",
        "horario": 2,
        "mensaje": " contenido mensaje"
    }

- **GET** /contacto
- **POST** /contacto, envías el objeto