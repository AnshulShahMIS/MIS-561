# MIS-561
Portfolio of projects from my Data Visualization class. This will include the completion of assignments in Excel, Tableau, PowerBI, Adobe Express, and various AI tools.

Initial E-Commerce Profitability Analysis, Develop a basic profitability set of dashboards and explain your design, link to published Tableau workbook: https://public.tableau.com/app/profile/misanshulshah/viz/AdvancinginExcelandTableau-Pt_1AnshulShah/ExploratoryDash#2, If I were doing this again, I'd planned earlier and spent time cleaning it up. 

Customer Account Profitability Analysis, Combined and cleaned multi-source retail order data to analyze customer-level profitability and identify accounts requiring pricing review. Built an interactive Tableau dashboard comparing net contributions, revenue, discounts, and cost-to-serve. Link to published Tableau workbook: https://public.tableau.com/views/AdvancinginExcelandTableau-Pt_2AnshulShah/AccountPortfolioDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link If I were doing this again, I'd spend more time refining the dashboard layout and simplifying the presentation for executive users.


Introduction to Power BI, September 27th 2026, https://public.tableau.com/views/PowerBIBusinessIntelligenceTraining_17906109329990/PowerBIStory?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


Introduction to DAX Power BI, October 1st 2026, https://public.tableau.com/views/PowerBIBusinessIntelligenceTraining_17906109329990/PowerBIStory?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


Data Visualization in Power BI, October 12th 2026, https://public.tableau.com/views/PowerBIBusinessIntelligenceTraining_17906109329990/PowerBIStory?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Part 3 text: 
Sarah, when I analyzed Southwest’s 793 accounts, I rolled the order lines up to one row per account in an Excel PivotTable and had to turn on the Data Model just to get a distinct count of orders. In Power BI, that count is a single measure on the line-level table, so it updates on refresh instead of being rebuilt by hand. This course changed how I would show that data. My Account Portfolio dashboard showed each account’s net contribution, but Marcus’s question is which accounts sit in the wrong service tier for what they earn. I would rebuild it as a scatter plot of revenue against cost to serve, colored by tier, so a premium-tier account that costs more than it earns stands out without anyone scanning a table.

At Southwest, I would keep Excel for one-off checks and for cleanup a colleague needs to edit, use Tableau for exploratory analysis and for stories shared outside the company, and use Power BI for recurring reports like Anita’s monthly margin report, where the same source refreshes every month and the losing product lines should be flagged with conditional formatting inside the matrix she already reads. My gap is that I have never published to the Power BI Service or maintained a report other people depend on. To close it, I will rebuild the account analysis in Power BI Desktop from the line-level data, publish it to the Service with scheduled refresh, and keep it running for a month.

*Note: Claude AI was used to help create and improve a draft for part 3
