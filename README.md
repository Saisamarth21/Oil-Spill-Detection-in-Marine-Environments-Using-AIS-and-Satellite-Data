# Oil Spill Detection in Marine Environments Using AIS and Satellite Data

## **Overview**
Detecting oil spills in marine environments using Automatic Identification System (AIS) data and satellite datasets integrated with advanced machine learning techniques.

## **Solution**
A  system for detecting oil spills in marine environments by combining AIS data and satellite datasets, leveraging machine learning.

- **Machine Learning for Anomaly Detection**: DBSCAN clustering algorithm on AIS data to identify anomalies such as unexpected vessel behavior.
- **Customized CNN for Oil Spill Detection**: A Convolutional Neural Network trained on Synthetic Aperture Radar (SAR) images to detect oil spills.
- **Integrated System**: AIS and satellite data for precise detection.


## **Technical Approach**
### **Technologies Used**
- **Programming Languages**: Python  
- **Frameworks and Libraries**:  
  - Scikit-learn for DBSCAN  
  - TensorFlow/Keras for CNN  
  - Pandas and NumPy for data handling  
  - OpenCV for image manipulation  
  - SNAP tool for SAR image processing  
- **Database**: MongoDB

![Frame 65](https://github.com/user-attachments/assets/31d6dfab-c828-48a3-bbf2-507e391f8b08)



### **Process**
1. **Data Ingestion**: AIS data and satellite imagery.  
2. **Preprocessing**: Handling missing values and preparing datasets.  
3. **Model Development**:  
   - DBSCAN for anomaly detection in AIS data.  
   - CNN for analyzing SAR images.  
4. **Integration**: AIS anomaly detection results validated by satellite image analysis.
   
![Frame 66](https://github.com/user-attachments/assets/c1d6b56f-d969-49c3-bd9a-d0643f444135)



