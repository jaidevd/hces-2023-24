# Microdata from the Household Consumption and Expenditure Survey (HCES) 2023-24

This repository contains section and questionnaire-wise microdata from HCES
2023-24.

The datasets are broadly organized in two categories:
* one for the metadata, demographic and other details of the households and their members.
* the other for the item-wise consumption and expenditure data.

Each table contains the responses to one section of one questionnaire.
Please see the tables below for the descriptions of the different datasets.

## Metadata

| Section | Questionnaire | File                                 | Description                                 |
|---------|---------------|--------------------------------------|---------------------------------------------|
| 1       | HCQ           | [Download](data/sec-1-HCQ.parquet)   | State, district, sector of household        |
| 3       | HCQ           | [Download](data/sec-3-HCQ.parquet)   | Details of household members                |
| 4       | HCQ           | [Download](data/sec-4-HCQ.parquet)   | Household characteristics                   |
| 4.1     | FDQ           | [Download](data/sec-4.1-FDQ.parquet) | General information on purchase and payment |
| 4.2     | CSQ           | [Download](data/sec-4.2-CSQ.parquet) | General information on purchase and payment |
| 4.3     | DGQ           | [Download](data/sec-4.3-DGQ.parquet) | General information on purchase and payment |

## Consumption and Expenditure Datasets

| Section | Questionnaire | File                                  | Description                                          | Period            |
|---------|---------------|---------------------------------------|------------------------------------------------------|-------------------|
| 5.1     | FDQ           | [Download](data/sec-5.1-FDQ.parquet)  | Cereals [^1]                                         | in the last month |
| 5.2     | FDQ           | [Download](data/sec-5.2-FDQ.parquet)  | Pulses [^1]                                          | in the last month |
| 5.3     | FDQ           | [Download](data/sec-5.3-FDQ.parquet)  | Sugar and salt [^1]                                  | in the last month |
| 6.1     | FDQ           | [Download](data/sec-6.1-FDQ.parquet)  | Milk and milk products [^1]                          | in the last week  |
| 6.2     | FDQ           | [Download](data/sec-6.2-FDQ.parquet)  | Vegetables [^1]                                      | in the last week  |
| 6.3     | FDQ           | [Download](data/sec-6.3-FDQ.parquet)  | Fresh fruits [^1]                                    | in the last week  |
| 6.4     | FDQ           | [Download](data/sec-6.4-FDQ.parquet)  | Dry fruits [^1]                                      | in the last week  |
| 6.5     | FDQ           | [Download](data/sec-6.5-FDQ.parquet)  | Eggs, fish, and meat [^1]                            | in the last week  |
| 6.6     | FDQ           | [Download](data/sec-6.6-FDQ.parquet)  | Edible oil [^1]                                      | in the last week  |
| 6.7     | FDQ           | [Download](data/sec-6.7-FDQ.parquet)  | Spices [^1]                                          | in the last week  |
| 6.8     | FDQ           | [Download](data/sec-6.8-FDQ.parquet)  | Beverages [^1]                                       | in the last week  |
| 7.1     | FDQ           | [Download](data/sec-7.1-FDQ.parquet)  | Served processed food [^1]                           | in the last week  |
| 7.2     | FDQ           | [Download](data/sec-7.2-FDQ.parquet)  | Packaged processed food                              | in the last week  |
| 8.1     | CSQ           | [Download](data/sec-8.1-CSQ.parquet)  | Energy (fuel & light) [^2]                           | in the last month |
| 9.1     | CSQ           | [Download](data/sec-9.1-CSQ.parquet)  | Toilet articles [^2]                                 | in the last month |
| 9.2     | CSQ           | [Download](data/sec-9.2-CSQ.parquet)  | Other household consumables [^2]                     | in the last month |
| 10.1    | CSQ           | [Download](data/sec-10.1-CSQ.parquet) | Education [^2]                                       | in the last year  |
| 10.2    | CSQ           | [Download](data/sec-10.2-CSQ.parquet) | Medicine & hospitalization [^2]                      | in the last year  |
| 10.3    | CSQ           | [Download](data/sec-10.3-CSQ.parquet) | Medicine and non-hospitalization [^2]                | in the last year  |
| 11.1    | CSQ           | [Download](data/sec-11.1-CSQ.parquet) | Conveyance [^2]                                      | in the last month |
| 11.2    | CSQ           | [Download](data/sec-11.2-CSQ.parquet) | Consumer services (excluding conveyance) [^2]        | in the last month |
| 11.3    | CSQ           | [Download](data/sec-11.3-CSQ.parquet) | Entertainment [^2]                                   | in the last month |
| 11.4    | CSQ           | [Download](data/sec-11.4-CSQ.parquet) | Rent and other taxes & cesses [^2]                   | in the last year  |
| 12.1    | CSQ           | [Download](data/sec-12.1-CSQ.parquet) | _Pan_ [^1]                                           | in the last week  |
| 12.2    | CSQ           | [Download](data/sec-12.2-CSQ.parquet) | Tobacco [^1]                                         | in the last week  |
| 12.3    | CSQ           | [Download](data/sec-12.3-CSQ.parquet) | Intoxicants [^1]                                     | in the last week  |
| 13.1    | DGQ           | [Download](data/sec-13.1-DGQ.parquet) | Clothing [^2]                                        | in the last year  |
| 13.2    | DGQ           | [Download](data/sec-13.2-DGQ.parquet) | Footwear [^2]                                        | in the last year  |
| 13.3    | DGQ           | [Download](data/sec-13.3-DGQ.parquet) | Bedding [^2]                                         | in the last year  |
| 14.1    | DGQ           | [Download](data/sec-14.1-DGQ.parquet) | Personal goods [^2][^3]                              | in the last year  |
| 14.2    | DGQ           | [Download](data/sec-14.2-DGQ.parquet) | Transport equipment  [^2][^3]                        | in the last year  |
| 14.3    | DGQ           | [Download](data/sec-14.3-DGQ.parquet) | Sports goods [^2][^3]                                | in the last year  |
| 14.4    | DGQ           | [Download](data/sec-14.4-DGQ.parquet) | Medical equipment [^2][^3]                           | in the last year  |
| 14.5    | DGQ           | [Download](data/sec-14.5-DGQ.parquet) | Cooking & household appliances  [^2][^3]             | in the last year  |
| 14.6    | DGQ           | [Download](data/sec-14.6-DGQ.parquet) | Crockery & utensils [^2][^3]                         | in the last year  |
| 14.7    | DGQ           | [Download](data/sec-14.7-DGQ.parquet) | Furniture & fixtures [^2][^3]                        | in the last year  |
| 14.8    | DGQ           | [Download](data/sec-14.8-DGQ.parquet) | Goods for recreation [^2][^3]                        | in the last year  |
| 14.9    | DGQ           | [Download](data/sec-14.9-DGQ.parquet) | Residential building, land & other durables [^2][^3] | in the last year  |

[^1]: _Consumption of_
[^2]: _Expenditure on_
[^3]: Including purchase, construction, repair & maintenance


## Acknowledgements

This repository builds on the [original microdata](https://github.com/advaitmoharir/hces_2023/) cleaned, processed and published by
@vijayshree-jayaraman and @advaitmoharir. This fork adds an extra layer of
readability by ensuring that:

1. Section-wise responses are separated
2. Item names accompany item codes
3. States and districts are named alongside their codes to avoid 3rd
   party lookups.
