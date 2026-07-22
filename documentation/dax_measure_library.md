Previous Tournament Goals = 
CALCULATE(
    [Total Goals Scored],
    DATEADD(Dim_Date[Year], -4, YEAR)
)
Total Draws = SUM(Fact_Tournament_Performance[Draw])

Total Games Played = SUM(Fact_Tournament_Performance[Games Played])

Total Goal Difference = [Total Goals Scored] - [Total Goals Conceded]

Total Goals Conceded = SUM(Fact_Tournament_Performance[Goals Against])

Total Goals Scored = SUM(Fact_Tournament_Performance[Goals For])

Total Loss = SUM(Fact_Tournament_Performance[Loss])

Total Points = ([Total Wins] * 3) + ([Total Draws] * 1)

Total Teams = DISTINCTCOUNT(Fact_Tournament_Performance[Team])

Total Wins = SUM(Fact_Tournament_Performance[Win])

YoY Goal Growth % = 
VAR CurrentGoals = [Total Goals Scored]
VAR PriorGoals = [Previous Tournament Goals]
RETURN
DIVIDE(CurrentGoals - PriorGoals, PriorGoals, 0)
Total Teams = DISTINCTCOUNT(Fact_Tournament_Performance[Team])
