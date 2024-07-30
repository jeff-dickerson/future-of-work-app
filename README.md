Metaknowledge app
# Future of Work App

## Overview

This app helps professionals upskill using domain expertise, digital skills, and agentic workflows. It includes user authentication, domain knowledge input, skills taxonomy, second brain, digital twin, and agentic workflows features.

## Setup Instructions

1. Clone the repository.
2. Create a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Initialize the database:
    ```bash
    python src/auth/auth.py
    ```
5. Run the application:
    ```bash
    python src/main.py
    ```
6. Run the tests:
    ```bash
    python -m unittest discover tests
    ```

## Usage

1. Register and login via the authentication module.
2. Input domain knowledge.
3. Add skills to the taxonomy.
4. Capture new skill abstractions in the second brain.
5. Create a digital twin.
6. Develop and manage workflows.

## Project Structure

- `src/auth/auth.py`: Handles user authentication processes.
- `src/domain/domain_input.py`: Manages domain knowledge input.
- `src/skills/taxonomy.py`: Creates and maintains skills taxonomy.
- `src/brain/second_brain.py`: Captures and organizes new skill abstractions.
- `src/twin/digital_twin.py`: Builds a digital twin of the user.
- `src/workflows/agentic_workflows.py`: Develops workflows using digital skills and domain knowledge.
- `src/main.py`: Integrates all modules and runs the application.
- `tests/`: Contains tests for all modules.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License.
