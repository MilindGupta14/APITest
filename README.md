# APITest
To run the Jmeter test first step is to add the Prometheus listner into the Jmeter bin.
Kindly add the jar in the below Jmeter path "apache-jmeter\lib\ext"

#How to run test
Currently Postive scenario is enabled. You can run the test with multiple iteration by mentioning the iteration count in thread group.
To run test for a longer duration specify the thread life time.
Also make sure your .csv file are pointing to right path.

#To run test through Snappet.bat
Keep the batch job file in the Jmeter bin direction.
Edit the Snappet.bat by entering the .jmx file path. Also need to change the .jtl path for output file 


#To view Prometheus Listner output
Prerequiste:
Install Prometheus
Add Endpoint into Target and restart prometheus

Install Grafana
Add Prometheus as a data source.
Use the Jmeter.json to build the dashboard in Grafana.
