### Django Notes Notepad Application

This repository contains a Dockerized Django Notes Notepad application, available on Docker Hub as `nadunb96/notes-app:dj`. It utilizes MySQL for data storage, Django for backend development, and Jinja for templating.

#### Usage

1. **Pull the Docker image from Docker Hub:**

    ```bash
    docker pull nadunb96/notes-app:dj
    ```

2. **Run the Docker container:**

    ```bash
    docker run -d -p 8000:8000 --name notes-app nadunb96/notes-app:dj
    ```

3. **Access the application in your web browser at** `http://localhost:8000`.

#### Features

- Create, read, update, and delete notes.
- Secure user authentication and authorization.
- MySQL database integration for data storage.
- Dockerized for easy deployment and scalability.

#### Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

#### License

This project is licensed under the [MIT License](LICENSE).

#### Acknowledgements

Special thanks to the Django and Docker communities for their valuable contributions and support.
