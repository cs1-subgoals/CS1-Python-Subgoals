# Subgoals for Introductory Programming in Python

## Installation Instructions

1. (Optional) Create and activate a new virtual environment for Python to [keep libraries nicely isolated](https://docs.python.org/3/library/venv.html):

    ```sh
    $> virtualenv venv
    ```

    Follow the appropriate activation instructions for your [platform](https://docs.python.org/3/library/venv.html#how-venvs-work). For example, on windows you use `venv/scripts/activate` to activate the virtualenv, or `pretext venv/bin/activate` on most other platforms.

3. Install dependencies (e.g., `pretextbook`):

    ```sh
    $> python3 -m pip install -r requirements.txt
    ```
    
5. Build the `html` output:

    ```sh
    $> pretext build html
    ```

7. View the output in your browser:

    ```sh
    $> pretext view html
    ```

Visit <https://pretextbook.org/documentation.html> to learn more.
