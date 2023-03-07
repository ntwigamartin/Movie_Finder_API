# Movie_Finder_API

# Description
This is an API built with ruby Sinatra DSL to support a Movie Finder Frontend.

# Using the API
The following endpoints are available;

1. `/users` - register new user.

2. `/authenticate` - login existing user.

3. `/movies` - fetch all movies.

4. `/movies/:id` - edit movie details via PATCH http & delete movie via DELETE http.

The endpoint should be included at the end of the main url `https://sinemazone.onrender.com`. For example to fetch all movies, the url will be `https://sinemazone.onrender.com/movies`.

# Installing the API to local environment
- Step 1: Clone this repo to your local environment.

        git@github.com:ntwigamartin/Movie_Finder_API.git

- Step 2: Navigate to the cloned repository and run the following command to open it on your editor;

        code .

- Step 3: Install the dependencies using;

        Bundle install

- Step 4: Start the application using;

        rake server

NB: You require a code editor(e.g vs code) and an API client(e.g Thunder client or Postman) to run the API locally.

# Author

- Martin Ntwiga