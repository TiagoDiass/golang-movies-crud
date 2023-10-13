# golang-movies-crud
That's my first CRUD using the Go programming language

It's a webserver that exposes some endpoints

- Get movies - *GET* - `http://localhost:8000/movies`
- Get movie by id - *GET* - `http://localhost:8000/movies/{id}`
- Create movie - *POST* - `http://localhost:8000/movies`
- Delete movie - *DELETE* - `http://localhost:8000/movies/{id}`
- Update movie - *PUT* - `http://localhost:8000/movies/{id}`

Used a package called Gorilla Mux to deal with some parts about http servers.
