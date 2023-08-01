<!DOCTYPE html>
<html>
<head>
    <title>Box Weight Volume Error Consignment Analysis - RIVIGO</title>
</head>
<body>
    <h1>Box Weight Volume Error Consignment Analysis - RIVIGO</h1>
    <h2>Background</h2>
    <p>Rivigo is a technology-driven logistics company that specializes in transporting consignments across different regions of the country for B2B clients. The company operates through its extensive network of 17 processing centers spread across India.</p>
    <p>The process begins with pick-up agents collecting consignment boxes from clients at their warehouse or business locations. These agents update various consignment details, such as weight, box dimensions, consignee name, address, and pin code, through a mobile application, which generates a consignment note (8-digit unique consignment reference no).</p>
    <p>Human interventions led to an increase in discrepancies in the weights and volume measurements by the agents while collecting the packages.</p>
    <p>Agents mistakenly input incorrect weights or dimensions, such as recording 100 kg instead of 10 kg, or confusing measurement units like 30 x 30 x 20 inches as centimeters.</p>
    <p>These inaccuracies led to improper load planning, inefficient vehicle utilization, and ultimately resulted in revenue loss and extended cash collection cycles (DSO was increased to 60 Days for some of the clients).</p>
    
    <h2>Problem Statement</h2>
    <p>The aim of this project is to develop a logical and construct a model capable of efficiently identifying consignments with inaccurately measured weights and volumes either during or before the load planning stage.</p>
    
    <h2>Dataset</h2>
    <p>Approximately 8000 consignments were picked up daily across India, with more than 2 Lakhs consignments in a month.</p>
    <p>There are more than 1800 active clients spread across 15 major industries, including E-Comm, Pharma, Automobile, etc., and more than 16000 active delivery pincodes. Sample data was taken from clusters where the number of cases of incorrect billing was very high.</p>
    <p>Mumbai and Delhi were major clusters, and the analysis started with 1 month's data of Delhi clusters. For Delhi, the daily average pick-up ranges from 1200-1500 consignments.</p>
    
    <h2>Solution Design</h2>
    <p><strong>Features:</strong> There was no labeled dataset, hence we started analyzing the sample data set with a heuristic approach and developed some logic based on features like - density, length, breadth, heights, weight, types of clients, industry category, number of consignments.</p>
    <p>We have analyzed these features to understand the kind of boxes a client was providing in their consignment.</p>
    <!-- Add more details about solution design here -->
    
    <h2>Tools Used</h2>
    <p>Excel, MySQL, R programming</p>
    
    <h2>Role and Team Structure</h2>
    <p>Data Analyst</p>
    <p>Reporting Manager - Product Manager</p>
    <p>2 Executives for Validation follow-ups and Consignment Corrections</p>
</body>
</html>
