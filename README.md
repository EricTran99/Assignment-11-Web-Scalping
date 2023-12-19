# Web Scalping Mar Data - Web Scalping
This module focused on extracting data from a pre-exisiting website, and utilised the extracted data for analysis in order to find trends and outliners. The chosen websites were the _Mar News_ which collects the temperature data from the second link and was the main dataset for visual analysis. The first link leads to the origin to the main website. <br/>
 <br/>
1. 'https://static.bc-edx.com/data/web/mars_news/index.html'
2. 'https://static.bc-edx.com/data/web/mars_facts/temperature.html'

**Note: the websites used for web scalping are for assignment/learning purpose.** <br/>

## Development process
The repository contained two seperate python codes and one folder (which contains the exported csv file). The coding scripts had different purpose, though the process remained the same. <br/>
The first coding script extracted all of the title and text preview from the _Mars News_, which were seperated and stored into a dictionary. The purpose was to understand the scraping method which was performed by scraping texts found in the **html text element**. Below showed a small example from the large dictionary. <br/>
![image](https://github.com/EricTran99/Assignment-11-Web-Scalping/assets/134130254/8164e8a2-b70b-4891-9f9d-4f41221c2561) <br/>
 <br/>
The second script (which was the main data source for analysis) scraped _Mars temperature_ from the Mars temperature facts section. Each of the values were stored in the (_th_) text element, thus a loop was created to extracted the scarped data and stored into the corresponding lists. When all of the data were stored, each datatype were altered to match the data values for the preperation for visual data analysis. The processed DataFrame was shown below: <br/>
![image](https://github.com/EricTran99/Assignment-11-Web-Scalping/assets/134130254/ac894c1b-ca13-4e22-aa77-02e015f9f268) <br/>
![image](https://github.com/EricTran99/Assignment-11-Web-Scalping/assets/134130254/f1006997-87fc-4b1b-acdd-f50c47e2a3b0) <br/>
![image](https://github.com/EricTran99/Assignment-11-Web-Scalping/assets/134130254/81cad8c3-7ade-4f04-b697-9a42b4b037d0) <br/>
 <br/>
 
## Data visualisation & Observation
The main analysis focused on the Mars temperature, with the first analysis being the overall temperature across the months. The graph showsed two specific peaks; the first showing the coldest months being March and April, wheras the hottest months was August. Note that the average temperature were all in the negative degree Celsius. <br/>
![image](https://github.com/EricTran99/Assignment-11-Web-Scalping/assets/134130254/134aaa46-b9d2-474a-9416-ec825b6c42b5) <br/>
![image](https://github.com/EricTran99/Assignment-11-Web-Scalping/assets/134130254/80354caa-121d-49f8-a8a9-1cc6b6c7a0f7) <br/>
 <br/>
The second observation was to analysed the difference in atomspheric pressure and see if the temperature correlates with atmospheric pressure changes. The graph shows that the month with the highest pressure was September and lowest pressure month was June. Though the connection may be close with the hottest temperature and highest atmospheric pressure, there isn't enough supports to suggest that change in temperature has any impact on the Mars' atmospheric pressure. <br/>
![image](https://github.com/EricTran99/Assignment-11-Web-Scalping/assets/134130254/731cedfa-e9bb-4bb9-9088-0f2a00d62e92) <br/>
![image](https://github.com/EricTran99/Assignment-11-Web-Scalping/assets/134130254/f5baaf83-d8e7-40d7-bd81-39b6fcc651cd) <br/>
 <br/>
The third visual graph showed the change in Mars' minimal temperature across the terrestrial days. The graph showed certain peaks in the temperature that looks like outliners. However, due to the values coming from an offical Mars data website. It's unlikely to be an error, and thus being likely an unknown impact contributed to the Mars temperature not being aligned within the trend. <br/> 
![image](https://github.com/Nisloen/Assignment-11-Web-Scalping/assets/134130254/80ef0c89-5e2b-42a0-9104-e8b92f27d61e)
 <br/>
#Summary
The overall process in web scraping was mainly to learn the extracted processing with the first coding script testing on understanding the process with the Mars news. The second script takes the method and incorporate the process by creating graphs for analysis. The Mars temperature data was used to showcase insight upon which month had the highest and lowest temperature and atmospheric pressure. Lastly, the scraped data was exported into the file as a _csv_ which can be seen without the need to run the script.

