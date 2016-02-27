# knowledge-discovery-healthcare
“Implementation of methods for (i) the investigation of hospital admission cases and (ii) the integration of appropriate decision making algorithms

##DESCRIPTION
    Web Application to achieve the following:
    -A methodology that is useful for the investigation of variations in a series of clinical and financial outcomes,in           relation to any patient admission diagnosis code.
    -Feature Selection to identify the most important features which are important towards the prediction of the discharge        status.
    - Logistic Regression analysis based on the features selected
    - Core Association Rule Mining functionality (Based on user defined support and confidence thresholds
    
  ##TECHNICAL SPECIFICATIONS
    Database: MySql 5.5
    IDE: Eclipse Luna
    Tools used: MySQL Workbench
    Database Name: healthcare
    Web Technologies: JSP(Java Server Pages)
    Server: Tomcat Server 7.0
    Languages: Java
    JSP Files: home.jsp, results.jsp
    Dataset: dataset.arff
    Languages: Java
    Algorithms Used : Logistic Regression, CFS-subset-evaluation, Greedy-Stepwise, Association Rule Mining, CuSum
    External Libraries: Libsvm-3.1.7-sources-jar, weka-dev-src.jar, weka-stable-3.6.10.jar
    
    
##STEPS
    1. Import the attached WAR file into eclipse Luna (or any later version)
    2. Run home.jsp on the server. Fill the form and validate the results.
    3. Click on the Top AdDiagnoses button to view the top ten admitting diagnosis codes for the average length of stay,            death on discharge ratio and the average total charges.
    4. Getthewekajarfilesandthe.arfffile.
    5. Runproject2java.java
    6. Observe the results on console
    7. Run features.jsp on the server
    8. Select the features(check boxes) manually on the web page. Enter the min support and confidence and click on the Show        rules button. The rules which satisfy the min support and confidence constraints are displayed along with the support        and the confidence.
    9. Run cusum.jsp on the server.
    10.Enter the values for the temporal dataset along with the mean, standard deviation and the sigma value. Click on the          showdatapoints button to display the cumulative sum values and the data points which fall above and below the                threshold boundaries.
    
    
    
