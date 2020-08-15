# Name day list

## What is a name day?

A name day is a tradition in some countries in Europe and America, and Roman Catholic and Eastern Orthodox countries in general. It consists of celebrating a day of the year that is associated with one's given name. The celebration is similar to a birthday.

*Source: [https://en.wikipedia.org/wiki/Name_day](https://en.wikipedia.org/wiki/Name_day)*

## About project

This repository aims to publish list of name days for several countries in computer-readable for, so they can be used in various software projects. Feel free to include this list in any project of yours.

As name days are usually not standardized in the particular country, there isn't just single valid list. The goal of this project is to contain most used and most popular names.

## Format

Each list is in one file:
- CSV format
- UTF-8 encoding
- 366 lines, with one day on each line
- First part is date in MM-DD format, seconds part is name, parts are separated by semicolon `;`
- There can be several names in one day (separated by comma), or no name at all (usually during significant public holidays)

For example, line `11-27;Milan` means that on 27 November, name "Milan" celebrates the name day.

Special file `-list.csv` contains list of all lists with description localized in the offical language of that particular country.

## Current lists

- Croatia (croatia.csv)
- Czech Republic (czechia.csv)
- Hungary (hungary.csv)
- Poland (poland.csv)
- Slovakia (slovakia.csv)
- Spain (spain.csv)

All current lists are based on the data available on English Wikipedia.

## How to contribute

If you want to fix a list, or add new list for a country that hasn't been added yet, **feel free to create a pull request**.
