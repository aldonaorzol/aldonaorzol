## Hi there 👋 

```sql
WITH data_analyst AS (
    SELECT
        'Aldona' AS name,
        'Finance → Data Analytics' AS career_path,
        'Currently transforming data into insights' AS status,
        ARRAY['SQL', 'Power BI', 'Excel', 'Power Query'] AS skills
)
    FULL JOIN 
      'SQL' AS aggregations,
      'Power BI' AS visualizing,
      'Excel' AS pivot_tables,
      'Power Query' AS data_cleaning
FROM binge_coding;
```
