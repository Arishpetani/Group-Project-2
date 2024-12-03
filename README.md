# Group-Project-2
Group 4 Team Members:
Abhi Malik @Malik01010
Eric Kho @ek29262
Arish Petani @Arishpetani
Samuel Suen @samsuen999
Dan @danmmosu
Description of Dataset:
Our dataset was obtained from https://catalog.data.gov/dataset/border-crossing-entry-data-683ae. It contains border entry data into the United States through land ports. It includes the borders that the United States shares with Canada and Mexico. The data is taken by the United States Customs and Border Protection.

The dataset contains dimensions that capture the mode of transportation, the date of crossing (month, year), the volume on the date, the name of the port and the city the port belongs to. The data goes as far back as 1996 and as recent as January 2024.

Data Manipulations
In tableau we set the date of crossing as a date data type. We also renamed certain dimensions in tableau to make more sense, such as renaming "value" to "traffic" which represents the amount of border crossings for a given data point.

Considerations:
There is considerable more border activity between the United States and Mexico. Because of this our group decided to focus our analysis around the United States and Mexican border.

![image](https://github.com/user-attachments/assets/3d9d37a2-85f8-4254-9326-1e5c62987101)


![image](https://github.com/user-attachments/assets/f996fa6f-74f8-4e45-9501-2afa5203a0b7)


Covid-19 heavily decreased the amount of border crossings. The border was closed for non-essential travel, and it took some months for the amount of border crossings to recover as restrictions loosened up. A sharp decline can be seen in April 2020 which marks the peak of Covid-19 in the United States.

![image](https://github.com/user-attachments/assets/ca2f6eb8-3667-4016-9580-ee84f327973e)


Question 1:
Are there any trends in border crossing based on time dependent factors, such as seasons, holidays, or other special calendar events?

This question can help dictate if their are any fluctations in border crossing volume based on time dependent factors. From the fluctations we can try to create some explanations. By anticipating an increase in border crossing volume Customs and Border Protection can prepare their resources to accomodate the amount of traffic coming in. This information can also help drive policy decisions and can be used to help determine the economic impact of border crossing activity.

![image](https://github.com/user-attachments/assets/2df3363d-1184-4514-8eb6-9c3226dba7fc)

Migration over many years follows a consistent pattern.

![image](https://github.com/user-attachments/assets/c681defb-ef08-409c-a89e-3020d7e7ee42)

Migration peaks in the summer months and falls in the winter months. This suggest that the weather brought about by winter creates adverse conditions which discourages travel. There is a slight climb in the month of December. This suggest families are crossing the border to see relatives for Christmas and that there is increased movements of goods to meet increased demand for the holidays. After December border crossings continue to fall until reaching their lowest point in February.

Question 2:
What are the trends concerning transportation modes? Do different ports of entry see more of certain types of transportation?

This question helps to identify the main purpose each port serves. By understanding the main use of each port policy decisions and infastructure can be created to be service each port's needs. A port mainly servicing trucks would need more intensive searches and documenting of goods coming in by Customs and Border. Whilst a port mainly serving pedestrians and family vehicles would need different types of processing and customs, such as more biometrics or humanitarian services.

![image](https://github.com/user-attachments/assets/136946c3-6320-4a14-b7f1-063fef8c3773)

This first graph shows the ports with the highest passenger vehicles and pedestrian crossings. San Ysidro takes in the highest amount of this kind of traffic. Thus it should be serviced to accomodate this kind of traffic and volume. If policy makers felt the need to restrict migration most unrelated to trade they would most likely target these ports and slow migration through them.

![image](https://github.com/user-attachments/assets/79a3a66a-036c-438f-bf07-0a729f50b922)


This graph shows the ports with the highest amount of trucks coming in. The movement of goods is facilitated by trucks, and indicates trade and commerce. Laredo has the highest truck volume and makes up 57.6% of land port trade in the state of Texas, or about $234.7 billion in the year 2018 (Texas.GOV). Monitoring this port can help forcast finances, and drive economic decisions for policy makers.

TWB File
The Tableau workbook file is attached to the repository.
