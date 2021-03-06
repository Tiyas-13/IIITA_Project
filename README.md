# IIITA_Project  
Summer Project on EEG Signal Analysis and Classification for Epileptic Seizures  
DataSet - http://epileptologie-bonn.de/cms/front_content.php?idcat=193&lang=3&changelang=3      
**Method Applied :**
* 65 out of 100 Channels are selected using Principal Component Analysis.
* Level 4 Wavelet decomposition using 'db4' wavelet is applied on signal from each selected channel.  
* The sub-bands delta, theta, alpha, beta and gamma are obtained for each signal.  
* Statistical features of the wavelet coefficients of each sub-band is caluculated.   
* The obtained features are used to form a dataset.  
* The classes for healthy signals , inter-ictal and ictal signals are designated as 1, 0 , -1 respectively.  
* Classification algorithms are applied on the obtained dataset.   
