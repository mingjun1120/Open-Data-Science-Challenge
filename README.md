
# Level 1 – Crop identification (EY)

This is an EY Open Science Data Challenge to learn how to use satellite imagery, data, algorithms and machine learning to help scientists, NGOs and governments draw actionable conclusions to solve world hunger issue. 


## Team Name & Members
**Team Name**
- The Data Dummies

**Team Members**
- [Lim Ming Jun](https://github.com/mingjun1120)
- Duar Xia Dan
- Mohammad Muaz Roshidi
- Michael Tam Jian Keong
## Background of Level 1 Challenge Summarization
- The challenge consists of two levels - Level 1 (Chosen) and Level 2.
- Level 1 requires participants to predict the presence or absence of rice crops at a given location.
- Using satellite data from the European Copernicus (Sentinel-1 and Sentinel-2) program and NASA's Landsat program.
- The Data Challenge encourages participants to make contributions towards solving world hunger and improving food security.
- The document provides guidance, suggestions, and dataset information to help Level 1 participants understand how to use satellite data to track rice crop location and growth and make corresponding predictions.
## Satellite Datasets Summarization

- Participants should consider using **optical data from Sentinel-2** and **Landsat**, as well as **radar data from Sentinel-1** for their solution.
- Landsat data has been available since the early 1980s with a spatial resolution of 30 meters per pixel and a revisit of 16 days for one mission. We currently have two operational missions (Landsat-8 and Landsat-9) which yield 8-day revisits at any given location.
- The **combination of Landsat and Sentinel-2** missions can **observe the ground 4 times every 10 days, providing coincident revisits about 9 times per year** but no worse than 5 days between views of the ground.
- **Optical data cannot penetrate clouds**, and in Vietnam, clouds are persistent over any one location about 2/3 of the time. So, only 1/3 of the data is available in a given year, and **filtering the data to remove clouds is necessary**.
- **Sentinel-1 radar missions**, launched in 2014 and 2016, **provide time-series radar data at an unprecedented temporal repeat**. The Sentinel-1 mission uses C-band radar at 10-meter resolution with a single mission revisit every 12 days. **Radar data** has the **unique capability to penetrate clouds, making it advantageous in regions with high cloud cover**.


### Which Type of Data should We Choose?
_`If we only want to choose 1 type of data`_


#### _For Advantageous (Harder)_
**Given the cloud cover in Vietnam**, it may be **advantageous to consider using the Sentinel-1 radar data**, which has the unique ability to penetrate clouds. 

#### _For Convenience (Easier)_
**Optical data** because **radar has lower spatial resolution** and the **need for special processing to correct for terrain variations** that can affect the quality of the data. **More difficult for non-experienced participants who are new to satellite data analysis**. Therefore, participants should carefully consider the advantages and disadvantages of each type of data and choose the one that best suits their needs and level of expertise. **If you choose to use optical data**, make sure to **consider filtering the data to remove clouds**. 

### What is Spatial Resolution?
Spatial resolution in remote sensing refers to the level of detail or ground coverage that can be seen in an image pixel. Higher spatial resolution means that the size of each pixel is smaller, allowing for more detail to be observed in the image. For example, if one satellite has a spatial resolution of 10 meters per pixel, it means that each pixel on the image represents an area of 10 by 10 meters on the ground. In contrast, a satellite with a spatial resolution of 30 meters per pixel would have less detail, with each pixel representing an area of 30 by 30 meters on the ground. Therefore, a higher spatial resolution allows for more detailed observation of the ground and can be beneficial for certain applications, such as agriculture monitoring, where smaller features or changes need to be detected.

### What is Optical Data? Is it Image Data?
Yes, optical data refers to data captured by optical sensors on satellites, which typically produce images of the Earth's surface. These sensors detect light in the visible, near-infrared, and shortwave infrared parts of the electromagnetic spectrum, and the resulting images can be used to identify and analyze features on the Earth's surface such as vegetation, water bodies, and urban areas.




## Analysis Region

- The data challenge will focus on the An Giang province in the Mekong Delta in Vietnam.
- Rice crop yield data was collected from late-2021 to mid-2022 over the Chau Phu, Chau Thanh, and Thoai Son districts.
- The region is a dense rice crop area with a mixture of double and triple cropping cycles (收割两到三次).
- The challenge assumes triple cropping (3 cycles per year 一年收割三次) and focuses on the Winter-Spring 2021-2022 season (November to April) and the Summer-Autumn 2022 season (April to August).
