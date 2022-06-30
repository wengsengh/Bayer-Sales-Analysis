# Bayer Pesticide Sales Analysis

## 1.0 Project Background & Product Line
1.1 Company Introduction: Bayer's official flagship store (Bayer, headquartered in Leverkusen, Germany, has 750 stores in 200 locations on six continents)
Production plant; with 120,000 employees and 350 branches, almost all over the world. Polymers, medicine and health care, chemicals and agriculture are the company's four pillar industries. The company's product categories exceed 10,000).<p>
1.2 Project Goal: Identify market opportunities for business growth.<p>
1.3 Product Line:<p>
![image](https://user-images.githubusercontent.com/24800888/176578273-bb788168-6d98-458d-aa1b-c4132dabb7e6.png)

## 2.0 Dataset
Bayer's official flagship store online sales data in the Years 2015-2018:<p>
![image](https://user-images.githubusercontent.com/24800888/176578397-4faf7401-365e-4352-af41-9ea35e5ad381.png)
<p>
Rodenticide niche market:<p>
- Cockroach<p>
- Insect<p>
- Mite<p>
- Lice<p>
- Rodent

## 3.0 Data Cleansing and Filling the Gaps
3.1 Since the time column is from November 2015 to October 2018, we need the complete data for each month from 2016 to 2018.
This is because it is convenient to analyze the product from the perspective of annual change.<p>
3.2 We can use linear regression to predict that for each sub-category market, use the sales amount in November/December of 2015, 2016, and 2017 to predict the corresponding month of 2018.

## 4.0 Result
4.1.1 Overall Market <p>
![image](https://user-images.githubusercontent.com/24800888/176580799-1d93ae52-b096-4532-9642-ebcb77d4a7dc.png)
<p>In the past three years, there has been a growth trend, and the entire market tends to grow and mature. <p>
4.1.2 Sub-categories Market

![image](https://user-images.githubusercontent.com/24800888/176581616-b03ebff1-1140-4da6-8bd5-f4bb7eb92b14.png)
<p>Intuitively, rodenticides and mosquito repellent have a greater market opportunities.

![image](https://user-images.githubusercontent.com/24800888/176582442-5a2f9ba1-afac-46b0-a995-4d330812ebdd.png)
<p>It can be seen that for rodenticides and anti-moth tablets, the growth rate is relatively stable, while others have decreased or even become negative.<p>
4.1.3 Conclusion for Pesticide Market<p>
- The overall pesticide market is in a stage of rapid growth and tends to grow to maturity.<p>
- The market share of rodenticide is relatively large (more than 60%), which is about twice that of the second mosquito repellent, and the market growth rate is close to 40%. It can be considered as a star product category, which requires continuous investment and focus.<p>
4.2.1 Niche Market Opportunities <p>





