> What software did you use to create your data visualization?
Excel (pivot table)
    > Who is your intended audience? 
    The intended audience is TTC riders and members of the general public who want a simple and familiar visual summary of which stations appear most frequently in delay reports.
    > What information or message are you trying to convey with your visualization? 
    The bar chart shows the top 15 TTC subway stations with the highest number of delay records since 2025. The visualization highlights that delays are not evenly distributed across the system and that some stations appear more frequently in reported delay incidents.
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    A horizontal bar chart was chosen to accommodate long station names and improve readability. Stations were sorted from highest to lowest delay count so rankings were immediately clear. The number of stations was limited to the top 15 to avoid overcrowding, and simple colors and labeling were used to prevent misinterpretation or visual overload.
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Excel does not provide code-based reproducibility in the same way as Python. However, the entired workflow, including data import, PivotTable configuration, sorting, and top 15 selection all have deterministic output. As long as someone else uses the same dataset and following the steps, the same graph should be produced.
    > How did you ensure that your data visualization is accessible?  
    Using a horizontal layout for readability, sufficiently large text, and minimal reliance on color. Clear axis titles and a descriptive chart title help ensure that the visualization can be interpreted by a broad audience.
    > Who are the individuals and communities who might be impacted by your visualization?  
    TTC riders who regularly pass through high-frequency delay stations may be influenced in their route choices or travel planning. Also, City of Toronto and TTC operations staff, who are responsible for scheduling, staffing, and service reliability can identify stations that appear frequently in delay records and prompt further investigation for solution, adding more staffs at specific station to help TTC customers.
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    The Station field was selected because it directly answers the question of where delays occur most frequently. Other variables, such as delay codes or duration, were excluded to keep the message focused and easy to interpret. Limiting the visualization to the top 15 stations improved clarity and comparability.
    > What ‘underwater labour’ contributed to your final data visualization product?Underwater labour included manually prepare a clean station list, verifying station name consistency, PivotTable aggregation, ensuring correct sorting and filtering etc.