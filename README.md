# bulletin-editorial-cartoons

This dataset includes a collection of 3,471 full-page editorial cartoons downloaded from issues of *The Bulletin* published between 1886 and 1952. In most cases there is one cartoon per issue. Metadata describing each image is available in a CSV-fromatted file, and in an SQLite database that can be explored using Datasette-Lite. The full collection of high-resolution images can be downloaded as a single 62gb zip file.

These datasets were generated using notebooks in the [trove-journals](https://github.com/GLAM-Workbench/trove-journals/) repository.

For more information and documentation see the [Editorial cartoons from The Bulletin, 1886 to 1952](https://glam-workbench.net/trove-journals/bulletin-cartoons-collection/) section of the [GLAM Workbench](https://glam-workbench.net).

## Dataset summary
- [bulletin-editorial-cartoons.csv](https://github.com/GLAM-Workbench/bulletin-editorial-cartoons/raw/main/bulletin-editorial-cartoons.csv) (1.9 MB, text/csv)
- [bulletin-editorial-cartoons.db](https://github.com/GLAM-Workbench/bulletin-editorial-cartoons/raw/main/bulletin-editorial-cartoons.db) (3.5 MB, db)


## Dataset details

### [bulletin-editorial-cartoons.csv](https://github.com/GLAM-Workbench/bulletin-editorial-cartoons/raw/main/bulletin-editorial-cartoons.csv)

|                |                                                                                                                                                                                                                                                                             |
|:---------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested | 2024-03-19                                                                                                                                                                                                                                                                  |
| file size      | 1.9 MB                                                                                                                                                                                                                                                                      |
| format         | text/csv                                                                                                                                                                                                                                                                    |
| created by     | <a href='https://github.com/GLAM-Workbench/trove-journals/blob/master/Finding_editorial_cartoons_in_the_Bulletin.ipynb'>Finding editorial cartoons in the Bulletin</a> ([documentation](https://glam-workbench.net/trove-journals/finding-editorial-cartoons-in-bulletin/)) |
| number of rows | 3472                                                                                                                                                                                                                                                                        |

#### Columns

| name             | type    | description                                              |
|:-----------------|:--------|:---------------------------------------------------------|
| `id`             | string  | NLA identifier for the page image containing the cartoon |
| `date`           | date    | date the issue was published                             |
| `issue_number`   | string  | publication issue number                                 |
| `issue_id`       | string  | NLA identifier for the issue                             |
| `page`           | integer | number of the page containing the cartoon                |
| `url`            | string  | url to open the page in Trove's digitised object viewer  |
| `download_image` | string  | url to download a high-resolution page image             |
| `text`           | string  | OCRd text extracted from the page                        |

### [bulletin-editorial-cartoons.db](https://github.com/GLAM-Workbench/bulletin-editorial-cartoons/raw/main/bulletin-editorial-cartoons.db)

|                |                                                                                                                                                                                                                                                                             |
|:---------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested | 2024-03-19                                                                                                                                                                                                                                                                  |
| file size      | 3.5 MB                                                                                                                                                                                                                                                                      |
| format         | db                                                                                                                                                                                                                                                                          |
| created by     | <a href='https://github.com/GLAM-Workbench/trove-journals/blob/master/Finding_editorial_cartoons_in_the_Bulletin.ipynb'>Finding editorial cartoons in the Bulletin</a> ([documentation](https://glam-workbench.net/trove-journals/finding-editorial-cartoons-in-bulletin/)) |
| description    | This is an SQLite database formatted for use with Datasette-Lite. As well as metadata from the `bulletin-editorial-cartoons.csv` file it includes a thumbnail column to display the cartoon.                                                                                |

## Examples of use

- [Explore using Datasette](https://glam-workbench.net/datasette-lite/?url=https://github.com/GLAM-Workbench/bulletin-editorial-cartoons/blob/main/bulletin-editorial-cartoons.db&install=datasette-json-html&metadata=https://raw.githubusercontent.com/GLAM-Workbench/bulletin-editorial-cartoons/main/metadata.json#/bulletin-editorial-cartoons/cartoons)
- [Download from Dropbox: 1886 to 1889 (45mb PDF)](https://www.dropbox.com/s/altjl6jixwv5pt0/bulletin-1886-1889.pdf?dl=0)
- [Download from Dropbox: 1890 to 1899 (139mb PDF)](https://www.dropbox.com/s/p15swmact2c9euf/bulletin-1890-1899.pdf?dl=0)
- [Download from Dropbox: 1900 to 1909 (147mb PDF)](https://www.dropbox.com/s/0rivg50s8qam2et/bulletin-1900-1909.pdf?dl=0)
- [Download from Dropbox: 1910 to 1919 (153mb PDF)](https://www.dropbox.com/s/pdsj6xjot0l928w/bulletin-1910-1919.pdf?dl=0)
- [Download from Dropbox: 1920 to 1929 (159mb PDF)](https://www.dropbox.com/s/64x9y5nvgez1q3o/bulletin-1920-1929.pdf?dl=0)
- [Download from Dropbox: 1930 to 1939 (151mb PDF)](https://www.dropbox.com/s/8mytp5qhqcrctt3/bulletin-1930-1939.pdf?dl=0)
- [Download from Dropbox: 1940 to 1949 (146mb PDF)](https://www.dropbox.com/s/go3vyuqq0td6oqd/bulletin-1940-1949.pdf?dl=0)
- [Download from Dropbox: 1950 to 1952 (42mb PDF)](https://www.dropbox.com/s/klcv0gyjs81c0pm/bulletin-1950-1952.pdf?dl=0)


----
Created by [Tim Sherratt](https://timsherratt.au) for the [GLAM Workbench](https://glam-workbench.net)