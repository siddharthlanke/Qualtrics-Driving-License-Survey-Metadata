# Qualtrics Driving License Survey Metadata

This repository contains a dataset and metadata for a survey conducted on driving licenses. The dataset was created as part of an assignment for the subject **Understanding Data and their Environment** during my MSc Data Science course at the University of Manchester.

## Project Overview

This assignment focuses on learning how to create metadata for a dataset. The survey was conducted using **Qualtrics**, and the metadata adheres to the **Mapping to Dublin Core (DDI Version 2)** standard. The main objective of this assignment is to understand the structure and importance of metadata in database management.

## Files in the Repository

- **survey_dataset.xlsx**: Contains the raw survey data.
- **metadata.xlsx**: Contains the metadata for the dataset, following the Dublin Core (DDI Version 2) format.

## Metadata Standard

This assignment focuses on learning how to create metadata for a dataset. The survey was conducted using **Qualtrics**, and the metadata adheres to the **Mapping to Dublin Core (DDI Version 2)** standard. The specific DC elements included in the metadata are:

- **Title** (`<titl>` 2.1.1.1)
- **Creator** (`<AuthEnty>` 2.1.2.1)
- **Subject** (`<keyword>` 2.2.1.1, `<topcClas>` 2.2.1.2)
- **Description** (`<abstract>` 2.2.2)
- **Publisher** (`<producer>` 2.1.3.1)
- **Contributor** (`<othId>` 2.1.2.2)
- **Date** (`<prodDate>` 2.1.3.3)
- **Type** (`<dataKind>` 2.2.3.10)
- **Format** (`<fileType>` 3.1.5)
- **Language** (`<language>`)
- **Relation** (`<othrStdyMat>` 2.5)
- **Coverage** (`<timePrd>` 2.2.3.1, `<nation>` 2.2.3.3, `<geogCover>` 2.2.3.4)
- **Rights** (`<copyright>` 2.1.3.2)

## How to Use

1. Download the **survey_dataset.xlsx** file to explore the dataset.
2. Open **metadata.xlsx** to view the associated metadata, which provides context for understanding and analyzing the dataset.

## License

This repository is licensed under the [MIT License](LICENSE).

## Acknowledgments

- University of Manchester for guidance on this project.
- The group members of the **Turquoise Team** for their collaboration.
