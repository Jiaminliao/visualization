> What software did you use to create your data visualization?
Python
    > Who is your intended audience? 
    The intended audience is everyday TTC subway riders (students, commuters, shift workers etc.) who want to understand when delays are more common so they can plan routes and departure times more realistically.
    > What information or message are you trying to convey with your visualization? 
    The heatmap communicates time patterns in delay frequency since 2025. It shows which hours of the day and days of the week have the highest delay records, so riders can anticipate rush hours (e.g., Thursday 4-5 PM).
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    1. I chose to use heatmap as its suitable for patterns across two time dimensions (weekday × hour). 2. I used clear axis labels (hour 0–23, Monday–Sunday), colourbar legend, and a descriptive title so the chart is interpretable without extra explanation. 3. The heatmap has colour gradient by nature so high and low frequency cells stands out. 4. I also re-ordered the Weekdays (Monday to Sunday) so the plot matches how people think about a week.
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    The visualization is reproducible because the entire workflow includes loading the CSV, creating a combined datetime column, extracting hour and weekday, grouping counts, and plotting. Since I did not use random samples but the entire columns, someone else can rerun the code on the same dataset to recreate the heatmap exactly. 
    > How did you ensure that your data visualization is accessible?  
    1. No excessive colours that might cause confusion, no red colour so it's colour-blind friendly. 2. Labels were large enough to read without zooming. 3. The x and y axis should be easily understood.
    > Who are the individuals and communities who might be impacted by your visualization?  
    Riders who rely on the TTC daily are most impacted, especially those with limited flexibility. People living near frequently delayed stations could be indirectly impacted since subway delay usually brings heavy traffic.
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Only features relevant to timing were included, specifically the date and time of each delay record, which were converted into weekday and hour. Other variables, such as delay code and subway number, were excluded since they do not serve the purpose of this visualization and they were hard to understand by audience.
    > What ‘underwater labour’ contributed to your final data visualization product?
    Data collection and processing, handling inconsistent formatting, selecting an appropriate aggregation level, ordering categorical variables correctly...