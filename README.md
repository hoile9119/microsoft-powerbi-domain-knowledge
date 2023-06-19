# Power BI Domain Knowledge

This project aims to provide a comprehensive guide and resources for gaining domain knowledge in Power BI.

## Table of Contents

- [Power BI Domain Knowledge](#power-bi-domain-knowledge)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
    - [Incremental Refresh](#incremental-refresh)
    - [Oracle ODBC](#oracle-odbc)
    - [Impala ODBC](#impala-odbc)
    - [Oracle Native Query](#oracle-native-query)
    - [Power BI Dataflows, Datasets](#power-bi-dataflows-datasets)
    - [REST APIs](#rest-apis)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Installation

### Incremental Refresh
1. Get Data
2. Choose DSN
3. Create parameters
4. Filter data
5. Define policy
6. Save and publish to the service
7. Refresh dataset
8. Tips, Tricks and Notes
    - Trick#1: when filtering param range -> choose short range to get data quickly. (eg: history data from 2020 til now by column `date` -> choose `rangeStart=sysdate - 1` and `rangeEnd = sysdate -2`)
    - Trick#2: create dsn with query from VIEW ( query ). Combine with Trick#1, you can even small the size of data loaded into Power BI desktop file before doing incremental loading. After set up is done, you can update the VIEW you had created whatever you want if it does not change the schema structure

### Oracle ODBC

### Impala ODBC

### Oracle Native Query

### Power BI Dataflows, Datasets

### REST APIs


## Usage
This project provides a collection of guides, tutorials, and examples to help you gain domain knowledge in Power BI. Here are a few usage examples:

Read the Getting Started Guide to understand the basics of Power BI.
Explore the Examples directory to see practical use cases and best practices.
Dive into the Tutorials section to learn how to create custom visuals, perform data modeling, and more.
Check out the Resources directory for links to external blogs, videos, and documentation.
Feel free to explore the project and leverage the resources according to your learning needs.

## Contributing
Contributions are welcome to enhance the project and make it more comprehensive. If you'd like to contribute, please follow these guidelines:

Fork the repository and create a new branch.
Make your changes and improvements.
Test your changes thoroughly.
Submit a pull request, explaining the purpose and changes of your contribution.
Please ensure your contributions align with the project's goals and maintain a high standard of quality.

## License
This project is licensed under the MIT License. Please review the license file for more information.

## Acknowledgments
Special thanks to the contributors and the Power BI community for their valuable resources and insights.

If you have any questions or suggestions regarding this project, please contact leathoi.htt@gmail.com