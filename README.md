MangaUpdates

Dataset folder includes all the data I scraped from mangaupdates.com
- big_publisher_title.csv: All manga titles published the four biggest English manga publishers: Viz Media, Yen Press, Seven Seas Entertainment and Kodansha USA. Updated on 17/8/2020
- josei_title_full.csv: All scanlated and licensed josei manga titles. Updated on 24/8/2020
- big_publisher_josei_year: All josei titles published by the four biggest English manga publisher with the year they were published in English. Updated on 24/8/2020
- scanlation_all_chapter.csv: Number of chapters of each group by year. Updated on 25/9/2020
- seinen_title_full.csv: All scanlated and licensed seinen manga titles. Updated on 29/9/2020
- seinen_publisher_year.csv: All seinen titles published by the four biggest English manga publisher with the year they were published in English. Updated on 29/9/2020
- scanlator_not_duplicated.csv: around 10.000 scanlation group's information. Updated on 7/8/2020
- title_no_duplicate.csv: information of all licensed manga titles. Updated on 17/8/2020

Script to scrape and analyze the data: 
- Scrape Manga Updates.ipynb: scripts that I scrape all the scanlation group's, licensed titles', josei titles' and seien titles' information
- Scrape number of chapter.ipynb: script that I scrape number of chapters that each group scanlated by year 
- Request delist google.ipynb: Analyzing the google copyright removal requests data. Data was downloaded from https://transparencyreport.google.com/copyright/explore?hl=en_GB
- Analyzing scraped data, combine scanlation chapter.ipynb: Script to analyze most of the data that I scraped
