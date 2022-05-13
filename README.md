Clone the repository to the Go src directory

Install gorilla-mux using "go get -u github.com/gorilla/mux"

Run "go build", then "go run main.go" to serve the API.

endpoints are "localhost:8000/movies" for all movies, and "localhost:8000/movie/{id}" for getting movies by id.

GET works for "localhost:8000/movies", while CRUD works for "localhost:8000/movie/{id}".

Structs were used instead of a database, will fix that later.
