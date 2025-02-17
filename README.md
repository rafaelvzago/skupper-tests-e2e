# Skupper Tests End to End Repository

This repository contains end-to-end (e2e) tests for the Skupper.io tool, specifically for version 2. Each e2e test is organized into its own folder, containing all necessary files and scripts to run the test.

## Repository Structure

- `LICENSE`: Contains the Apache License, Version 2.0 under which this project is licensed.
- `README.md`: This file, providing an overview of the project.
- `tests/`: Directory containing folders for each e2e test. Each folder is named after the test it contains.

## E2E Tests

Each e2e test is located in its own folder within the `tests/` directory. The folder name corresponds to the name of the test. Inside each folder, you will find all the necessary files and scripts to run the test.

## Test Collection

The tests in this repository use the following collection: [Skupper Tests](https://github.com/rafaelvzago/skupper-tests).

## Prerequisites

To run the tests in this repository, you will need to have the following prerequisites installed on your system:

- Skupper V2 installed on the cluster(s) you will be testing.
- If you are willing to test in a namespace level, you will need to have it installed prior to running the tests.


## E2E Tests Structure

* Each e2e test is organized into its own folder within the `tests/` directory. The folder name corresponds to the name of the test. Inside each folder, you will find all the necessary files and scripts to run the test.
* Inside the tests/YOUR_TEST folder you will need to follow:

```
tests/
└── YOUR_TEST/
  ├── requirements.txt
  └── test.yml
```
```
* `requirements.txt`: List of dependencies required to run the test.
* `test.yml`: Configuration file for the test.
```

A virtual environment is recommended to run the tests. To create a virtual environment.

## Running the Tests

To run the tests, follow the instructions provided in each test folder. Generally, you will need to have Skupper.io tool version 2 installed and configured on your system.

## License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or new tests to add.

## Contact

For any questions or issues, please open an issue in this repository.
