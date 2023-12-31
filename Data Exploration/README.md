```SQL
/* Selecting Top 10 Rows From The Dataset */
SELECT TOP (10)
      rank
      ,Youtuber
      ,subscribers
      ,video_views
      ,category
      ,Title
      ,uploads
      ,Country
      ,Abbreviation
      ,channel_type
      ,video_views_rank
      ,country_rank
      ,channel_type_rank
      ,video_views_for_the_last_30_days
      ,lowest_monthly_earnings
      ,highest_monthly_earnings
      ,lowest_yearly_earnings
      ,highest_yearly_earnings
      ,subscribers_for_last_30_days
      ,created_year
      ,created_month
      ,created_date
      ,Gross_tertiary_education_enrollment
      ,Population
      ,Unemployment_rate
      ,Urban_population
      ,Latitude
      ,Longitude
FROM
      youtube

```

| Rank | Youtuber                          | Subscribers | Video Views | Category           | Title                    | Uploads | Country          | Abbreviation | Channel Type    | Video Views Rank | Country Rank | Channel Type Rank | Video Views for the Last 30 Days | Lowest Monthly Earnings | Highest Monthly Earnings | Lowest Yearly Earnings | Highest Yearly Earnings | Subscribers for Last 30 Days | Created Year | Created Month | Created Date | Gross Tertiary Education Enrollment | Population | Unemployment Rate | Urban Population | Latitude             | Longitude            |
|------|-----------------------------------|-------------|-------------|--------------------|--------------------------|---------|------------------|--------------|-----------------|------------------|--------------|-------------------|----------------------------------|-------------------------|--------------------------|------------------------|------------------------|-------------------------------|--------------|---------------|--------------|---------------------------------------|------------|---------------------|------------------|----------------------|----------------------|
| 1    | T-Series                          | 245,000,000 | 228,000,006,144 | Music              | T-Series                 | 20,082  | India            | IN           | Music           | 1                | 1            | 1                 | 2,257,999,872                    | 564,600                 | 9,000,000                | 6,800,000              | 108,400,000            | 2,000,000                   | 2006         | Mar           | 13           | 28.10                               | 1,366,417,792 | 5.36                | 471,031,520      | 20.5936832427979      | 78.9628829956055    |
| 2    | YouTube Movies                    | 170,000,000 | 0             | Film & Animation   | youtubemovies            | 1       | United States    | US           | Games           | 4,055,159        | 7,670        | 7,423             | 12                               | 0                       | 0                        | 0                      | NULL                   | 2006         | Mar           | 5            | 88.20                               | 328,239,520  | 14.70               | 270,663,040      | 37.0902404785156      | -95.712890625       |
| 3    | MrBeast                           | 166,000,000 | 28,368,842,752 | Entertainment      | MrBeast                  | 741     | United States    | US           | Entertainment   | 48               | 1            | 1                 | 1,348,000,000                    | 337,000                 | 5,400,000                | 4,000,000              | 64,700,000             | 8,000,000                   | 2012         | Feb           | 20           | 88.20                               | 328,239,520  | 14.70               | 270,663,040      | 37.0902404785156      | -95.712890625       |
| 4    | Cocomelon - Nursery Rhymes        | 162,000,000 | 164,000,006,144 | Education          | Cocomelon - Nursery Rhymes | 966     | United States    | US           | Education       | 2                | 2            | 1                 | 1,975,000,064                    | 493,800                 | 7,900,000                | 5,900,000              | 94,800,000             | 1,000,000                   | 2006         | Sep           | 1            | 88.20                               | 328,239,520  | 14.70               | 270,663,040      | 37.0902404785156      | -95.712890625       |
| 5    | SET India                          | 159,000,000 | 147,999,997,952 | Shows              | SET India                | 116,536 | India            | IN           | Entertainment   | 3                | 2            | 2                 | 1,824,000,000                    | 455,900                 | 7,300,000                | 5,500,000              | 87,500,000             | 1,000,000                   | 2006         | Sep           | 20           | 28.10                               | 136,641,779  | 5.36                | 471,031,520      | 20.5936832427979      | 78.9628829956055    |
| 6    | Music                             | 119,000,000 | 0             | NULL               | Music                    | 0       | NULL             | NULL        | Music           | 4,057,944        | NULL         | NULL              | NULL                             | 0                       | 0                        | 0                      | NULL                   | NULL                         | 2013         | Sep           | 24           | NULL                               | NULL         | NULL                | NULL             | NULL                 | NULL                 |
| 7    | ��� Kids Diana Show               | 112,000,000 | 93,247,037,440  | People & Blogs     | ��� Kids Diana Show      | 1,111   | United States    | US           | Entertainment   | 5                | 3            | 3                 | 731,673,984                      | 182,900                 | 2,900,000                | 2,200,000              | 35,100,000             | NULL                         | 2015         | May           | 12           | 88.20                               | 328,239,520  | 14.70               | 270,663,040      | 37.0902404785156      | -95.712890625       |
| 8    | PewDiePie                         | 111,000,000 | 29,058,043,904  | Gaming             | PewDiePie                | 4,716   | Japan            | JP           | Entertainment   | 44               | 1            | 4                 | 39,184,000                       | 9,800                   | 156,700                  | 117,600                | 1,900,000              | NULL                         | 2010         | Apr           | 29           | 63.20                               | 126,226,568  | 2.29                | 115,782,416      | 36.2048225402832      | 138.2529296875      |
| 9    | Like Nastya                       | 106,000,000 | 90,479,058,944  | People & Blogs     | Like Nastya Vlog         | 493     | Russia           | RU           | People          | 630              | 5            | 25                | 48,947,000                       | 12,200                  | 195,800                  | 146,800                | 2,300,000              | 100,000                     | 2016         | Jan           | 14           | 81.90                               | 144,373,536  | 4.59                | 107,683,888      | 61.5240097045898      | 105.318756103516    |
| 10   | Vlad and Niki                     | 98,900,000  | 77,180,166,144  | Entertainment      | Vlad and Niki            | 574     | United States    | US           | Entertainment   | 8                | 5            | 6                 | 580,574,016                      | 145,100                 | 2,300,000                | 1,700,000              | 27,900,000             | 600,000                     | 2018         | Apr           | 23           | 88.20                               | 328,239,520  | 14.70               | 270,663,040      | 37.0902404785156      | -95.712890625       |
