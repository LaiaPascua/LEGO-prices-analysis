# LEGO prices analysis
This is an analysis of the LEGO Sets available on LEGO webpage on 20/3/2024. We want to see what parts those sets contain and analize what sets are more valuable


## DATA SOURCES

|File               |Source      |Link                                                  |Notes                            |
|-------------------|------------|------------------------------------------------------|---------------------------------|
|colors             |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|elements           |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|inventories        |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|inventory_minifigs |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|inventory_parts    |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|inventory_sets     |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|minifigs           |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|part_categories    |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|parts              |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|sets               |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|themes             |Rebrickable |https://rebrickable.com/downloads/                    |                                 |
|parts_volume       |Bricklink   |https://www.bricklink.com/catalogDownload.asp         |                                 |
|pickabrik_price_new|Webscrapping|https://www.lego.com/en-us/pick-and-build/pick-a-brick|see WebScrapping notebook + combination with elements dataset |
|web_catalog_price  |Webscrapping|https://www.lego.com/en-us/categories/price           |see WebScrapping notebook                                     |
|sets_with_price    |Combination |sets dataset + web_catalog_price dataset              |made in excel                    |
|inventories_price  |Combination |sets_with_price dataset + inventories dataset         |made in excel                    |
|whole_price_dataset|Combination |Several datasets + Machine Learning                   |see LEGO_data_processing notebook|



## DATA CONTEXT
### What is a Lego set?
