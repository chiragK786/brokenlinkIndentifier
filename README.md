# brokenlinkIndentifier





# Broken Link Identifier with Selenium and Java

This repository contains a project that identifies broken links on a web page using Selenium and Java. It identifies broken links by checking the HTTP status code of the link and comparing it to the expected status code (200).

## Requirements

* Java 8+
* Maven
* Selenium

## Installation

To install the project, clone the repository using the following command:

```
git clone https://github.com/chiragK786/broken-link-identifier.git
```

Then, navigate to the project directory and run the following command:

```
mvn install
```

## Usage

To use the project, run the following command:

```
java -jar target/broken-link-identifier-1.0.0-SNAPSHOT-jar-with-dependencies.jar <URL>
```

Where `<URL>` is the URL of the web page to be checked.

The output of the command will be a list of broken links on the web page, if any.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License.
