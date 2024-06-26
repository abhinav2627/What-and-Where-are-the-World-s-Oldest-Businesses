# What-and-Where-are-the-World-s-Oldest-Businesses
What and Where are the World's Oldest Businesses
An important part of business is planning for the future and ensuring that the business survives changing market conditions. Some businesses do this remarkably well and last for hundreds of years. In this project, you’ll explore data from BusinessFinancing.co.uk on the world’s oldest businesses: when were they founded, and which industries do they belong to?

Like many business problems, the data we’ll explore is contained in several different datasets. In order to understand the world’s oldest businesses, we will first need to use joining techniques to merge our data. From there, we can use manipulation tools such as grouping and filtering to answer questions about these historic businesses.

## `CATEGORIES`
| Column | Type |	Meaning |
| :--: | :--: | :--: |
| category_code |	varchar |	Code for the category of the business.|
| category | varchar |	Description of the business category. |

## `COUNTRIES`
| Column | Type | Meaning |
| :--: | :--: | :--: |
| country_code  | varchar | ISO 3166-1 3-letter country code.   |
| country       | varchar | Name of the country.                |
| continent     | varchar | Name of the continent the country exists in. |

## `Businesses`
| Column        | Type    | Meaning                             |
|:-------------:|:-------:|:-----------------------------------:|
| business      | varchar | Name of the business.               |
| year_founded  | int     | Year the business was founded.      |
| category_code | varchar | Code for the category of the business. |
| country_code  | char    | ISO 3166-1 3-letter country code.   |

Let's begin by looking at the range of the founding years throughout the world.
