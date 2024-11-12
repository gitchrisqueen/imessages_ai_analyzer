# imessages_ai_analyzer

Collect messages from iMessages and use AI to do an analysis.

## Setup

1. Clone the repository:

    ```sh
    git clone https://github.com/gitchrisqueen/imessages_ai_analyzer.git
    cd imessages_ai_analyzer
    ```

2. Install Poetry if you haven't already:

    ```sh
    curl -sSL https://install.python-poetry.org | python3 -
    ```

3. Install the dependencies:

    ```sh
    poetry install
    ```

4. Create the `.env` file from the `env.example` file and update the paths and information as needed:

    ```sh
    cp env.example .env
    ```

    Edit the `focus_group.env` file to set the correct paths and information.

## Running the Project

1. Activate the virtual environment:

    ```sh
    poetry shell
    ```

2. Run the application:

    ```sh
    python src/cqc_iaa/main.py
    ```

## Testing

To run the tests, use:

```sh
poetry run pytest