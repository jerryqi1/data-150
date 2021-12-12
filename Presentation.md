An introduction to your selected human development topic. Identify salient harms, quantify their significance, and describe the inherent and complex nature of the human development process you have been investigating. Provide motivation, if the signifance is not obvious: why should we care? Elucidate your research in terms of scope, processes, hierarchy, or dynamics. Permutate through the details of your human development topic.
State the data science methods you selected in your methodological investigation. Identify and describe the data sources used as well as incorporated variables and methods of sensing or collection. Describe what each method does and how it advances an improved understanding of your selected human development process. Identify the most salient findings resulting from the application of your data science methods. Be sure to use formulas, tables, charts, graphs, and maps, as needed.
Identify an area of the literature that requires further investigation, such as the one identified in your methodological investigation. Discuss how data or models fail to describe, analyze, or predict some essential element of your selected human development process. Reformulate your central research question such that it addresses your defined research gap. Position this newly formed central research question in relation to both the broader and more specific questions you had previously articulated.
Propose a research plan that you will implement in order to answer your central research question. Focus on the design of the plan rather than the cost. Keep in mind a 1-3 year time frame from the point of approval and funding to achieving planned goals and objectives.











Hi everyone! Today I want to talk about the disaster managements and predictions on the coastal area of south and southeast Asia. 
As we all know, coastal areas are usually the economic and cultural center of countries with dense populations. Under the threats of frequent hazards like floods and extremely rainfalls in the rainy season because of the monsoon climate, coastal areas become highly vulnerable, for it can seriously affect people’s lives, causing deaths, injuries, and huge amount of economic losses, thus slowing down the pace of human development. Therefore, it is very important to manage these disasters properly. 
I did some investigation to countries of south and southeast Asia like India and Bangladesh because they both have densely populated areas and high hazard vulnerabilities areas. I mainly did the research of risk analysis and vulnerability assessments. In order to assess the risk of hazards on the coast, scientists have to gather lots of geospatial data and analyze them in a proper way. The use of Data science methods is very important in these researches. Now lets focus on two methods in my methodological investigation. 
First, in the research of floods and extreme rainfall on the Tamil Nadu coast, The researchers first divide the the coast area under threat of hazards into two separate parts: the flooding area, in which the level of hazards may be higher, and the built-up area, in which the damage to human lives and economic losses may be more severe. Then the authors analyzed data in these two part using different methods and combine them at last, obtaining a comprehensive result with distinct characteristics in both aspects. As shown in the graph, scientists used the Sentinel-1 SAR method to study the flooding area and the Landsat-8, OLI method to study the built-up area inundation. 
When it comes to the Sentinel-1SAR method, it includes 4 steps to process data.In the first step, scientists used VV polarization mode (vertical launch and vertical receive of electromagnetic wave ) and IW (Interferometric Wide swath) to extract ground range detected (GRD) data in flooding area of the study region. In short, high resolution special geospatial image was formed. After that, the image experience a series of corrections like radiometric calibrations (corrections to the radar back-scatter), Lee filer (quality improvements in the texture of the image), and Range Doppler Terrain Correction (corrections on the distortions of the distance in the image due to topographical variations of a scene and tilt of satellite sensor). Finally, the histogram analysis and binary image of the flooding area was carried out. 

The second method is called the Landsat-8, OLI method. Landsat is a series of satellites launched by NASA and Landsat 8 is the eighth of them. OLI stands for Operational Land Imager. The Landsat-8 OLI processed the Built-up area extraction by firstly using EarthExplorer to acquire imagery contains no cloud cover and atmospheric correction. Then, 4 equations are used to process the ToA (Top-of-Atomsphere) information. 
Let’s just call it TOA. ToA planetary reflectance values was developed using Eqs. 2 and 3. ToA radiance conversion was done using Eq.4 which subsequently converted into at sensor brightness temperature in degree Celsius using Eq. 5. 


After accuracy assessment using BAEM (built-up area extraction method), a GIS analysis was carried out and the level of risk of disasters came out. After combining the two main Methods and their results, a comprehensive flood map was developed to assess flood risk in two ways: population and and building density and seriousness of the floods.
Second, in the assessment of coastal vulnerability along the eastern coast of Bangladesh, scientists mainly used CVI (coastal vulnerability index) approach. In order to develop an integrated CVI map, the author first selected 8 parameters: Elevation, Sea level rise, Slope, Mean tide range, Geomorphology, Bathymetry, Shoreline change and Storm surge height. After gathering these information, scientists analyzed the vulnerability classes of each parameter and rank them based on their vulnerability. To directly show the vulnerability of each parameter, scientists divided the 470-kilometer-coast in 470 1km * 1km grids. After that, 8 parameters are studied to find out how many grids with high vulnerabilities on the coast do each parameter have. Finally, the CVI can be calculated as the square root of the ranked parameters divided by the total number of parameters using this equation. Besides doing calculations, scientists also visited 22 locations and verify the CVI results and the results of observation is similar to the calculation, which proved the validation of the CVI results. 

Besides these researches, I think it is also important to study the history of the disasters of these coastal areas and find out how did the patterns of the disasters change overtime. Because I think some of the environmental changes are closely related to the increase of human activities like global warming, air pollution, changes in biodiversity. So if we can combine the data about historical disasters and modern data about coastal vulnerabilities, we may find the trend of how disasters appear and evolve, which is very helpful to our further research on the management of disasters.

I have made a research plan and the central research question is the connection between the coastal vulnerability changes and human activities. For the first year, I plan to study some documents about historical disasters in the region of south and southeast Asia and learn the former natural environment. Also some important geographic information can be found in the rocks and sands on the coastline which include information in different times about the environment on the coast. For the second year, I plan to use the data science methods I mentioned before to study these data of the old times. Based on these information, I can assess the disaster vulnerability many years before. For the third year, I plan to compare the geospatial data nowadays and the historical information. Through comparison of the coastal vulnerabilities and geographic information of different times, we can find some patterns about changes of these geospatial data. After that, we can combine these data to the change of human’s activities, population, technology developments and introductions of policies about environment. 
With this new research, people can learn more about the reasons of disaster vulnerabilities in coastal areas, making it easier for disaster managements, including disaster responses, predictions and preparations.