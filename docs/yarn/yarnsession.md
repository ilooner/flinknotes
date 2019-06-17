# Yarn Session

## Starting the yarn session

 1. Set the hadoop classpath
    ```
    export HADOOP_CLASSPATH=`hadoop classpath`
    ```
 1. Start the yarn session
    ```
    ./bin/yarn-session.sh
    ```

## Killing the yarn session

 1. Find the yarn session
    ```
    yarn appication -list
    ```
    This command will should the Flink session if it is running
    ```
    Total number of applications (application-types: [] and states: [SUBMITTED, ACCEPTED, RUNNING]):1
                    Application-Id	    Application-Name	    Application-Type	      User	     Queue	             State	       Final-State	       Progress	                       Tracking-URL
    application_1560731218845_0002	Flink session cluster	        Apache Flink	    hadoop	   default	           RUNNING	         UNDEFINED	           100%	http://ip-172-31-26-227.ec2.internal:35845
    ```
 1. Kill the yarn session
 
