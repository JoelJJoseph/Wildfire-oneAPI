# Wildfire-oneAPI

<img src="https://th.bing.com/th/id/R.2e122fc5cbbcdc65f7b1109326bef626?rik=70lB0a6MPhbOhA&riu=http%3a%2f%2fcdn.roaring.earth%2fwp-content%2fuploads%2f2016%2f12%2fgiphy-33.gif&ehk=XznsRaYr8SLs5PtlBAPtvfdPXk5sKA4ZB7dypnYQPUA%3d&risl=&pid=ImgRaw&r=0" height="600" width="1000"><br>


# INSPIRATION <img src="https://github.com/JoelJJoseph/oneapi-sa-hack/assets/72274851/0237fb2a-7625-422b-9346-6aace1656d8f" height="80" width="80"><br>

In a world increasingly marred by the devastating impact of wildfires, our inspiration for the project stems from a profound sense of responsibility and urgency. Witnessing the escalating frequency and severity of these natural disasters, we were driven by a collective determination to confront the pressing questions that surround them. Why are wildfires on the rise, and what toll are they exacting on our environment? How can we, as innovators, contribute to stemming this tide of destruction that affects not just individuals but entire ecosystems?


# What It Does <img src="https://github.com/JoelJJoseph/Wildfire-oneAPI/assets/72274851/a5fb9280-2288-4fd8-9810-5595b4d87f67" height="80" width="80"><br>
Immersing the user in a realm of predictive resilience, my application transcends the conventional by harnessing the power of technology to anticipate and mitigate the destructive impact of wildfires. It's not merely a tool; it's a visionary companion that empowers users with actionable insights into the probability, magnitude, and estimated putout time of potential wildfires in their area.

Imagine a world where individuals, armed with key information about their surroundings, can proactively prepare for the onset of a wildfire. My application enables just that. Users input essential details, and the AI algorithm, finely tuned through Python and Flask, unveils a forecast that goes beyond forewarning. It's about strategic preparedness, a tool that equips communities to navigate the environmental challenges posed by wildfires with precision.

The integration of the oneAPI toolkit optimizes the predictive model, ensuring optimal performance on Intel CPUs and GPUs across diverse computing platforms. The Intel Developer Cloud provides a collaborative environment, ensuring the solution adapts seamlessly to diverse computing environments, elevating it from a tool to a global solution.

# How I built it <img src="https://github.com/JoelJJoseph/Wildfire-oneAPI/assets/72274851/11794bf8-04f2-47b2-8483-ffdc4e43a497" height="80" width="80"><br>

### ✅ Data Processing and Model Construction:
* Utilized Python libraries, including Pandas, NumPy, and scikit-learn, for efficient data manipulation and preprocessing.
* Selected key features such as fire size, remoteness, discovery month, and vegetation for model training.
* Constructed a neural network model using the Keras library, configuring input, hidden, and output layers for predicting putout time.

### ✅Integration of Intel oneAPI Toolkit:
![intel](https://user-images.githubusercontent.com/72274851/218504609-585bcebe-5101-4477-bdd2-3a1ba13a64a8.png)
* Leveraged the capabilities of the Intel oneAPI toolkit, including oneDNN and oneDAL, to optimize deep learning tasks and data preprocessing.
* Modified model construction, compilation, and training steps to ensure efficient performance, particularly on my Intel CPU.
* Achieved cross-architecture compatibility, allowing seamless adaptation to diverse computing platforms.

### ✅Intel Developer Cloud:
* Utilized the Intel Developer Cloud for running high-process algorithms, providing computational power, and enabling collaborative testing and deployment.
* Ensured scalability and adaptability across diverse hardware configurations.

### ✅Cross-Architecture Compatibility:
* Integrated the Intel oneAPI toolkit to achieve cross-architecture compatibility, allowing the solution to seamlessly run on various platforms, optimizing performance on Intel CPUs.

### ✅Save the model


# What I learned <img src="https://github.com/JoelJJoseph/Wildfire-oneAPI/assets/72274851/f80a562a-50a0-46f2-a5f3-103fe4b75512" height="80" width="80"><br>



![image](https://user-images.githubusercontent.com/72274851/220130227-3c48e87b-3e68-4f1c-b0e4-8e3ad9a4805a.png)

### ⭐Intel Developer Cloud Utilization:
Leveraged the Intel Developer Cloud for running high-process algorithms, understanding its role in providing computational power and facilitating collaborative testing and deployment.

### ⭐Intel oneAPI Toolkit Integration:
Explored and implemented the capabilities of the Intel oneAPI toolkit, specifically oneDNN and oneDAL, learning to optimize deep learning tasks, data preprocessing, and achieve cross-architecture compatibility.

### ⭐Advanced Data Processing: 
Mastered the art of data preprocessing using Python libraries like Pandas, NumPy, and scikit-learn, enhancing efficiency in handling and extracting insights from complex datasets.

### ⭐Neural Network Modeling: 
Gained expertise in constructing and training neural network models using the Keras library, understanding the nuances of configuring layers and optimizing for specific predictions like putout time.

### ⭐Geospatial Visualization:
Developed proficiency in geospatial visualization using Folium, translating geographical data into interactive leaflet maps to visually represent wildfire distribution.

![image](https://github.com/JoelJJoseph/Wildfire-oneAPI/assets/72274851/49348eb7-a6fb-46fd-8d7e-11deb94ea5fb)
