# 📚 Proyecto BibliotecaDuoc

Aplicación web RESTful construida con Spring Boot para gestionar un catálogo de libros. Permite registrar, buscar, actualizar y eliminar libros usando peticiones HTTP.

## 🚀 Tecnologías utilizadas

- Java 17+
- Spring Boot
- Maven
- Lombok
- Postman (para pruebas)
- JDK + IDE compatible (IntelliJ, Eclipse, VSCode)

---

## 📦 Estructura del proyecto

```
src
 └── main
     ├── java
     │   └── com.example.bibliotecaduoc
     │       ├── model         # Clase Libro
     │       ├── repository    # LibroRepository
     │       ├── service       # LibroService
     │       └── controller    # LibroController
     └── resources
         └── application.properties
```

---

## 🧪 Endpoints disponibles

| Método | Endpoint                   | Descripción                       |
|--------|----------------------------|-----------------------------------|
| GET    | `/api/v1/libros`           | Lista todos los libros            |
| POST   | `/api/v1/libros`           | Agrega un nuevo libro             |
| GET    | `/api/v1/libros/{id}`      | Busca un libro por ID             |
| PUT    | `/api/v1/libros/{id}`      | Actualiza un libro existente      |
| DELETE | `/api/v1/libros/{id}`      | Elimina un libro por ID           |

---

## 🔧 Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/profeRuben/bibliotecaduoc.git
   ```

2. En tu IDE, ejecuta la clase `BibliotecaduocApplication.java`.

3. Accede a:
   ```
   http://localhost:8080/api/v1/libros
   ```

---

## 📬 Ejemplos de carga de libros (JSON para POST)

```json
{
  "id": 100,
  "isbn": "842340949X",
  "titulo": "El Método Lean Startup",
  "editorial": "Deusto",
  "fechaPublicacion": 2012,
  "autor": "Eric Ries"
}
```

```json
{
  "id": 101,
  "isbn": "9789569646638",
  "titulo": "Fuego y Sangre",
  "editorial": "Penguin Random House Grupo Editorial",
  "fechaPublicacion": 2018,
  "autor": "George R. R. Martin"
}
```

```json
{
  "id": 102,
  "isbn": "9789563494150",
  "titulo": "Quique Hache: El Mall Embrujado y Otras Historias",
  "editorial": "Sm Ediciones",
  "fechaPublicacion": 2014,
  "autor": "Sergio Gomez"
}
```

```json
{
  "id": 103,
  "isbn": "9781484256251",
  "titulo": "Spring Boot Persistence Best Practices",
  "editorial": "Apress",
  "fechaPublicacion": 2020,
  "autor": "Anghel Leonard"
}
```

```json
{
  "id": 104,
  "isbn": "9789566075752",
  "titulo": "Harry Potter y la piedra filosofal",
  "editorial": "Salamandra",
  "fechaPublicacion": 2024,
  "autor": "J. K. Rowling"
}
```

---

## 👨‍🏫 Autor

- profeRuben  
