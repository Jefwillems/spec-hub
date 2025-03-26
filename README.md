# GitHub Pages OpenAPI Spec Viewer

This repository hosts a **GitHub Pages** project for displaying OpenAPI specifications using **Jekyll** and **Scalar**.

## Features

- **GitHub Pages**: Easily host and share your OpenAPI specs.
- **Jekyll**: Static site generator for building the project.
- **Scalar**: A lightweight OpenAPI spec viewer.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. Install Jekyll dependencies:
    ```bash
    bundle install
    ```

3. Serve the site locally:
    ```bash
    bundle exec jekyll serve --baseurl=""
    ```

4. Open your browser at `http://localhost:4000`.

## Deployment

This project is automatically deployed via **GitHub Pages**. Ensure the `gh-pages` branch is configured in your repository settings.

## Usage

Place your OpenAPI specification files (e.g., `openapi.yaml`) in the appropriate directory. Scalar will render them automatically.

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for feedback.
