# Computer Vision in Remote Sensing

![](https://media.giphy.com/media/Ju7l5y9osyymQ/giphy.gif)

Glacier and Snow Cover Mapping and Monitoring
	Snow is an important water resource that sustains our ability to live on Earth. Due to glaciers and snow, large amounts of fresh water are stored at the top of mountain ranges and areas within the North. However, Anthropogenic climate change threatens glaciers existence. As temperatures rise, it’ll be increasingly difficult to contain the structure and rigidity of glaciers as they are subject to melting frequently. Fortunately, remote sensing techniques and object-oriented analysis can help quantify glacier and snowpack regression rates. For instance, researchers have created neural networks and deep learning techniques to analysis spatial and spectral imagery taken by MODIS and Landsat TM data. With the introduction of these new techniques of remote sensing, researchers have been able to determine what environmental factors determine the size of their study sites glaciers.
	 To start, in an article analyzing how machine learning can improve MODIS imagery, the authors outline methodology of utilizing unmanned aerial vehicles to improve that accuracy. Their study area, based of a Tibetan Plateau has a sizable snowpack and represents a major water source within the surrounding countries. Due to its rugged conditions it’s impossible to monitor snowpack with field-based methods, that is why remote sensing techniques have been deployed to analyze the site (Liu et al 2020). Despite the use of satellite imagery, using traditional based methods like normalized difference snow index doesn’t return strong values such as low spatial resolution and mixed pixels. What has been working is the breakthrough use of UAVs where it can store high data quality, low cost, and small size. Moreover, the extremely high spatial resolution of UAVs can provide observations close to the ground, thereby providing reliable input parameters for the fraction snow cover (FSC) mapping algorithm (Liu et al 2020). This leads to higher accuracy in fractional snow cover (FSC) mapping alongside the use of machine learning algorithms. Due to UAVs ease of use and new techiniques, these methods will be critical in the fight against climate change as it provides quick, real-time updates about the tibetan plateau.
	In another case, a team of researchers used similar remote sensing techniques to determine an adequate run off model of snowpack within the alpine basin of the Rhone River at Sion. The use of satellite imagery in aiding the ability to create runoff models has been used throughout time, but its importance is understated as glacier melting is becoming more prominent with the advent of climate change (Seidel et al 2000). Regarding the authors study area, a basin at Sion, is a provider of hydroelectric power to Switzerland, accounting for over 80% of hydroelectricity during the wintertime. With this importance, they selected landsat imagery due to its strong spatial resolution and classified the imagery using GIS analysis. Having completed the prelimanary steps of imagery classification, the team created a SRM formula located below.
 
Figure 1: Snow and Glacier runoff formula SRM+G
	The formula can predict the occurance of snowmelt and type throughout the year, measuring ice melt, rain, new snow, and snowmelt. Since the formula was designed for prediction, the authors ran a couple of climate change scenarios designated by the IPCC, one measuring glacier area in 2030 and another in 2100. What was determined, to no one’s surprise, is the glaciers shrunk in size and runoff increased in the future if temperatures continued to rise. Below is a hydrograph of a runoff scenario in the year 2100. In conclusion, without the utilization of hydrological run off models monitoring snowmelt, it will become increasingly difficult for municipalities to account for extra water for hydroplants and or regular water usage.
 
Figure 2: Rhone-Sion Scenario 2100
	Lastly, another group of researchers used deep learning techniques to capture snow and glacier melt in the Himalyans. As stated previously, climate change is going to speed up the process of melting glaciers, yet new technoligies can capture the phenomenom more accurately. In the article, Khan et al 2022, utilize spectral and spatial convolutional neural networks to help remedy this issue. The proposed method showed success in classifying debris covering glaciers. Remote sensing is an applying method to glacier measurement as the terrain is impossible to manuever for field-based methods, but its accuracy is very dependant on conditions as debris covered glaciers is hard to quantify against clean ice glaciers from remote sensed images. A multitude of factors create this effect such as reflectance values, avalanches, and sediment amount, making it difficult to distinguish the difference. Although there is a wide range of inconsistencies, some solutions have been discovered such as Object Based Image Analysis (OBIA) which shows promising results in object detection of debris but requires a wide range of information and parameters to deliver accurate results. Other methods have sprung out of this problem, but the authors decided Deep Learning methods offered the most accurate results to these issues as they offer precise image extraction. In the article, the authors lay out their plan of action consisting of, “(1) Preprocessing (2) feature extraction and fusion (3) classification (4) post processsing” the selected glacier located in Pakistan.
 
	Futhermore, their framework was able to create an object-based image that separated the image into mostly three parts: ice, water, and glacier. In conclusion, the authors formed a deep learning technique to extract spectral and spatial features from satellite imagery, making sure to not miss any important features during extraction. Overall, the neural networks extracting features proved relatively successful and advantageous for monitoring debris covered glaciers, ice and land changes using remote sensing data. 
	Remote sensing data is primarily used in determining the area and size of receding glaciers and snowpack in mountanous regions. Due to rugged terrain and inaccessible locations, UAVs and satellites like Landsat and MODIS have spurned breakthrough technology in providing accurate and high-level data of these sites. Futhermore, deep learning and computer vision techniques have made classifying glaciers easier and accesible, hopefully aiding the fight against climate change and rising temperatures.
 
References:
Khan, A. A., Jamil, A., Hussain, D., Ali, I., & Hameed, A. A. (2022, June 3). Deep learning-based framework for monitoring of debris-covered glacier from remotely sensed images. Advances in Space Research. Retrieved April 28, 2023, from https://www.sciencedirect.com/science/article/pii/S0273117722004410?via%3Dihub 
Liu, C., Huang, X., Li, X., & Liang, T. (2020). Modis fractional snow cover mapping using machine learning technology in a mountainous area. Remote Sensing, 12(6), 962. https://doi.org/10.3390/rs12060962 
Seidel, K., Schaper, J., & Martinec, J. (n.d.). Mapping of snow cover and glaciers with high resolution remote sensing data for improved runoff modelling. Computer Vision Group, Communication Technology Laboratory, ETHZ, CH-8092 Zürich. Retrieved from seidel@vision.ee.ethz.ch.


