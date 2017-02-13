# ASSIGNMENT-1.1
 QN 1.SOURCES OF BIG DATA
1. Social network profiles—Tapping user profiles from Facebook, LinkedIn, Yahoo, Google, and specific-interest social or travel sites, to cull individuals’ profiles and demographic information, and extend that to capture their hopefully-like-minded networks
2.    Social influencers—Editor, analyst and subject-matter expert blog comments, user forums, Twitter & Facebook “likes,” Yelp-style catalog and review sites, and other review-centric sites like Apple’s App Store, Amazon, ZDNet, etc.   
3.    Activity-generated data—Computer and mobile device log files, aka “The Internet of Things.” This category includes web site tracking information, application logs, and sensor data – such as check-ins and other location tracking – among other machine-generated 
4.    Software as a Service (SaaS) and cloud applications—Systems like Salesforce.com, Netsuite, SuccessFactors, etc. all represent data that’s already in the Cloud but is difficult to move and merge with internal data.  (Distributed data integration technology, in-memory caching technology and API integration work may be appropriate here.)
5.    Public—Microsoft Azure MarketPlace/DataMarket, The World Bank, SEC/Edgar, Wikipedia, IMDb, etc. – data that is publicly available on the Web which may enhance the types of analysis able to be performed.  (Use the same types of parsing, usage, search and categorization techniques as for the three previously mentioned sources.)
6.    Hadoop MapReduce application results—The next generation technology architectures for handling and parallel parsing of data from logs, Web posts, etc., promise to create a new generations of pre- and post-processed data.   We foresee a ton of new products that will address application use cases for any kinds of Big Data – just look at the partner lists of Cloudera and Hortonworks.   In fact, we won’t be surprised if layers of MapReduce applications blending everything mentioned above (consolidating, “reducing” and aggregating Big Data in a layered or hierarchical approach) are very likely to become their own “Big Data”. 
7.    Data warehouse appliances—Teradata, IBM Netezza, EMC Greenplum, etc. are collecting from operational systems the internal, transactional data that is already prepared for analysis.  These will likely become an integration target that will assist in enhancing the parsed and reduced results from your Big Data installation. 
8.    Columnar/NoSQL data sources—MongoDB, Cassandra, InfoBright, etc. – examples of a new type of map reduce repository and data aggregator.  These are specialty applications that fill gaps in Hadoop-based environments, for example Cassandra’s use in collecting large volumes of real-time, distributed data.
9.    Network and in-stream monitoring technologies—Packet evaluation and distributed query processing-like applications as well as email parsers are also likely areas that will explode with new startup technologies.     
10.  Legacy documents—Archives of statements, insurance forms, medical record and customer correspondence are still an untapped resource.  (Many archives are full of old PDF documents and print streams files that contain original and only systems of record between organizations and their customers. Parsing this semi-structured legacy content can be challenging without specialty tools like Xenos.



QN 2.3 V’S of big data
1.Volume
2.Velocity
3.Variety
Volume:
large amount of data usually in TERABYTES,large volume of records for example facebook deals with data which piles with each and every  photo uploaded
velocity
velocity deals with the time factor of these data being received take  the case of an online booking system like Indian Railways which deals with large real time data which changes within a fraction of data.
Variety
Usually large unstructured data which cannot be stored in a conventional RDBMS and needs a special format for handling the data



QN 3.vertical scaling
	Vertical scaling means that you scale by adding more power (CPU, RAM) to an existing machine.
Relatively cheap
complex and time consuming  
less reliable 
Horizontal scaling
scale by adding more machines into your pool of resources 	
Relatively costly
highly reliable
coordination between systems


QN 4.NEED AND WORKING OF HADOOP
To avoid the failure of distributed working system
1.to avoid HARDWARE FAILURES
2.TO COORDINATE THE TASK AND COMBINE RESULTS FROM MULTIPLE MACHINES
Hadoop works by using 
HDFS for storage 
Map reduce for processing
