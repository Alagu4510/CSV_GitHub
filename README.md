# GitHub Repository Info Fetcher
This program fetches information about GitHub repositories using the GitHub API and processes a CSV file containing repository information.

## Requirements

- Python 3.x
- `requests` library (can be installed with `pip install requests`)

## Usage

1. Clone the repository or download the files.
2. Install the required dependencies using the command: `pip install requests`.
3. Prepare a CSV file containing information about GitHub repositories. The file should have two columns: "Repo Name" and "User Name".
4. Run the program using the command: `python main.py`.
5. Enter the path to the input CSV file when prompted.
6. Enter the path to the output folder where the output CSV file and log file will be saved.
7. The program will fetch information about each repository, save the results in an output CSV file, and create a log file.

## Test

The GitHub Repository Info Fetcher includes unit tests using the pytest framework. To run the tests, follow these steps:

1.Ensure you have pytest installed. If not, you can install it using the following command:
2.Copy code
3.pip install pytest
4.Open a terminal or command prompt and navigate to the directory where the code is located.
5.Run the following command to execute the tests:
6.Copy code
7.pytest -v

The tests will be executed, and the test results will be displayed in the console.
