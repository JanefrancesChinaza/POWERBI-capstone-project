Previous Tournament Goals = 
CALCULATE(
    [Total Goals Scored],
    DATEADD(Dim_Date[Year], -4, YEAR)
)
