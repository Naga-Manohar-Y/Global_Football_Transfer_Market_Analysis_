# Global_Football_Transfer_Market_Analysis

![Visualization GIF](https://github.com/Naga-Manohar-Y/Global_Football_Transfer_Market_Analysis_/blob/main/Report_and_Video/Preview_of_Visualizations.gif)


## Abstract

In this extensive project, our primary focus is on conducting a comprehensive analysis of the football transfer market, particularly within the context of the top 5 global leagues. Over the span of the last decade, we meticulously examine the financial intricacies, strategic decisions, and evolving trends that have shaped the transfer market. Our investigation encompasses an in-depth exploration of the spending behaviors exhibited by the most influential clubs, unraveling the strategic considerations and patterns that underpin their player acquisition strategies.

Furthermore, we shift our attention to individual player transfers, scrutinizing the record-breaking fees associated with these transactions. This involves an examination of the multifaceted factors that drive these deals, including player performance, market demand, and the financial standing of the involved clubs. Our analysis extends to the last 10 years, allowing us to trace the trajectories of financial investments and identify key influencers, such as economic shifts, regulatory changes, and global events.

Diving into the granular details, we explore player values and transfer fees based on various parameters, including position and age. This analysis provides nuanced insights into the market's valuation criteria, shedding light on how these factors influence the financial dynamics of player transfers. The project also concludes with an intriguing investigation into the correlation between financial investments in transfers and on-field success. By examining how money spent translates into competitive achievements, we offer a holistic perspective on the football transfer market's economic, strategic, and competitive dimensions.

## Data Description

The dataset for this project is sourced from the Transfermarkt website, a renowned platform that serves as a comprehensive repository for football-related data, including player transfers, market values, and club information. Transfermarkt has established itself as a reliable and widely-used resource in the football analytics community, providing enthusiasts and analysts with detailed insights into the dynamic world of player movements and financial transactions within the sport.

The focus of this data exploration centers on the transfer data of football players within the top 5 European leagues, namely the Premier League (England), La Liga (Spain), Bundesliga (Germany), Serie A (Italy), and Ligue 1 (France). These leagues represent the pinnacle of European football and are home to some of the most prestigious clubs and talented players globally.

### Dataset Columns

The dataset encompasses a range of crucial columns that capture essential information about each transfer. The key variables include:

- **Club**: The football club involved in the transfer.
- **Name**: The name of the player undergoing the transfer.
- **Age**: The age of the player at the time of the transfer.
- **Nationality**: The player's nationality.
- **Position**: The playing position of the player.
- **Short_Pos**: Abbreviated playing position.
- **Market_Value**: The estimated market value of the player.
- **Dealing_Club**: The club involved in the transfer deal.
- **Dealing_Country**: The country of the dealing club.
- **Fee**: The transfer fee associated with the transaction.
- **Movement**: Indicates whether the transfer is an incoming or outgoing movement.
- **Window**: Specifies the transfer window during which the deal took place.
- **League**: The football league to which the clubs belong.
- **Season**: The season in which the transfer occurred.

These columns collectively provide a comprehensive view of the transfer activities within the top European leagues, allowing for detailed analyses and data visualizations to uncover patterns, trends, and insights into the dynamics of player movements in the world of football.

## Project Structure

```plaintext
.
├── Data_Cleaning_Preprocessing
│   ├── bundesliga_data_cleaned.csv
│   ├── laliga_cleaned.csv
│   ├── ligue_cleaned.csv
│   ├── merged_cleaned_data.csv
│   ├── merged_data_cleaned.ipynb
│   ├── premier-league-cleaned.csv
│   └── serie_a_cleaned.csv
├── Data_Visualizations
│   └── transfers_data_visulizations.ipynb
├── README.md
└── Report_and_Video
    ├── Data_Visualization_Maverick_Report.pdf
    ├── Presentation_Video.mp4
    └── Preview_of_Visualizations.gif

```
- **README.md**: Project overview and instructions.
- **bundesliga_data_cleaned.csv**: Cleaned transfer data for Bundesliga.
- **laliga_cleaned.csv**: Cleaned transfer data for La Liga.
- **ligue_cleaned.csv**: Cleaned transfer data for Ligue 1.
- **merged_cleaned_data.csv**: Merged and cleaned transfer data for all leagues.
- **merged_data_cleaned.ipynb**: Jupyter notebook for data cleaning and merging.
- **premier-league-cleaned.csv**: Cleaned transfer data for Premier League.
- **serie_a_cleaned.csv**: Cleaned transfer data for Serie A.
- **transfers_data_visulizations.ipynb**: Jupyter notebook for data visualization. 

## Services Used

- **Transfermarkt**: Data source for football transfers.
- **Jupyter Notebooks**: For exploratory data analysis and visualization.
- **Python Libraries**: 
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Workflow

### Data Collection:
- Source data from Transfermarkt.
- Store raw data in the respective CSV files.

### Data Cleaning and Merging:
- Clean and merge the data using `merged_data_cleaned.ipynb`.

### Data Visualization:
- Create visual representations of the data using `transfers_data_visulizations.ipynb`.
- Saved the visualizations and added in the [Report.pdf](https://github.com/Naga-Manohar-Y/Global_Football_Transfer_Market_Analysis_/blob/main/Report_and_Video/Data_Visualization_Maverick_Report.pdf).

### Reporting:
- Compile findings into comprehensive report: [Data_Visualization_Maverick_Report.pdf](https://github.com/Naga-Manohar-Y/Global_Football_Transfer_Market_Analysis_/blob/main/Report_and_Video/Data_Visualization_Maverick_Report.pdf)
.
[Video](https://github.com/Naga-Manohar-Y/Global_Football_Transfer_Market_Analysis_/blob/main/Report_and_Video/Presentation_Video.mp4) &[YouTube video](https://youtu.be/O60jRb_fwDI?si=ptlm6BBuk4gfTf6G).

## Conclusion

This project provides a comprehensive analysis of the football transfer market, offering insights into the financial and strategic dimensions of player transfers over the last decade. By leveraging advanced data analysis techniques and visualization tools, we have uncovered key patterns and trends that shape the dynamics of the transfer market. The findings from this project can serve as a valuable resource for football analysts, enthusiasts, and decision-makers in the sports industry.


---

### Additional Info

You can download the files and play with the visualizations, get the data here [transfermarkt-transfers](https://github.com/emordonez/transfermarkt-transfers).