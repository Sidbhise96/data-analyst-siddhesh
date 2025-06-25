# data-analyst-siddhesh
Project Title:  Understanding Road Condition Patterns in Vancouver

Project Description: The project will entail a descriptive analysis of the data on the state of the roads in the City of Vancouver. The aim will be to summarize the local state of pavement infrastructure in terms of the Pavement Condition Index (PCI), determine the trends over time, and reveal information that may be used to make decisions about municipal maintenance planning and budgeting.
AWS Deployment and Service Models 

Objective: The major purpose is to discuss road segment data to realize the trends in the pavement quality, retrieve the number of sections with poor conditions by segment location or type, and suggest what should be maintained first.

Dataset: The dataset used for this analysis is a CSV file titled pavement-condition-rating-major-road-network.csv, containing 524 entries. It includes the following key fields:
•	Year
•	Road Name
•	From Street
•	To Street
•	Length (m)
•	PCI Rating (Very Poor, Poor, Fair, Good, Very Good)
•	Geom (location-based geometry data)

Methodology:
1-	Preparation and Collection of Data:
a.	Read the CSV in using the Pandas library of Python.
b.	Separated the concatenated fields by semicolon delimiters.
c.	The cleaned data types were fitted, blank characters/whitespaces were ignored, and numeric data consistency such as year, and length was made.
2-	Descriptive Statistics:
a.	The distribution of PCI ratings was calculated.
b.	Held a comparison into the average length of the road segments by rating category.
c.	Determined the number of entries per year to know the coverage of the data.
3-	Data Visualization:
a.	Bar charts of PCI ratings distributions calculated.
b.	Drew histograms to see the distributions of length of segments based on PCI rating.
c.	Visualized road segmentation over a spatial view (through Geom field) with the help of draw.io.
4-	Segmentation of Customers (Road):
a.	Categorized road lengths into PCI groups (e.g. Very Poor and Very Good).
b.	Compared the distributions of the segment length in various PCI groups.
c.	Identified the areas where the PCI scores were low on several occasions.
5-	Insights and Findings:
a.	The majority of the road segments measured as FAIR or GOOD, but there were still quite significant numbers of road segments rated as VERY POOR, and these areas were concentrated around particular neighborhoods.
b.	Areas that were more used or in business areas received low PCI ratings.
c.	But those roads that displayed a low PCI were shorter, meaning that they were regularly repaired with patchwork or had some disintegration remaining in a corner.

6-	Recommendations:
a.	Give priority to resurfacing or maintenance of short road segments with the constant Very Poor PCI rating.
b.	Implement predictive maintenance on those segments that have fair ratings frequently.
c.	Combine PCI and the length in a smarter way of allocating budget, or project-scheduling.
Tools and technologies:
•    Python (Pandas, Matplotlib, Seaborn) - data cleaning and statistical analysis
Cloud-based ETL processing With AWS S3 and AWS Glue DataBrew
•	draw.io spatial visualisation and architecture

	     
	The three pictures as a student allowed me to clearly have a comprehension of the main contrast in traditional computing versus cloud computing models, different options of cloud deployment as well as the levels of cloud service models (IaaS, PaaS and SaaS). Based on the first picture, I quenched my thirst of how the traditional computing keeps the data localized and under the complete control of the business whereas the cloud computing operates in a more flexible and liable mode with the globally distributed centers of AWS handling the data closer than in the case of a traditional computing. The second illustration covered the various types of cloud deployments, such as the Private, Public, Hybrid, and Multi-Cloud, showing how other entities can combine and overlap their cloud strategies depending on the control, scalability, and redundancy requirements. Lastly, the third image helped me learn about the differences between the cloud service models in relation to the responsibility and the level of abstraction of the user- infrastructure control in IaaS, platform control in PaaS, and completely managed software solutions in SaaS. The diagrams and comparison tables were useful in showing the various reports on location, access, and privacy responsibility of data of all the models that enhanced my practical and theoretical understanding of the frameworks in cloud computing. 

AWS Cost Analysis 

 
	The Case Study #5: AWS Pricing Calculator graphical representation inclined me to figure out the ways I can efficiently estimate the cost of cloud services through the pricing calculator of AWS. To use the calculator, one can enter certain configuration-related information (e.g., the type of service (e.g., EC2, compute, and S3, storage), region, used hours and storage requirements). The output has a detailed estimate of the costs included monthly cost estimates and 12 months projection, which is imperative in budgeting of academic exercises, research planning or project simulations. With the help of this tool, I was able to learn how to plan the cloud resources efficiently and justify their costs even before their real deployment. This helps make sound decision making, particularly with a departmental or short-term academic constraint. The screenshots also supported the ease with which it is possible to visualize and compare costs in real-time, and it is easier to make AWS transparent and manageable to education use cases. AWS Global infrastructure 
 

	AWS global infrastructure was an eye-opener in regard to the layered architecting of the global service delivery network of AWS. The picture represents the manner through which data is handled and dispensed in three primary infrastructure elements, including Regional Edge Caches, Edge Locations, and Regions. I came to know that contents in Edge Locations are replicated to enable low-latency access and accelerate content distribution using Content Delivery Network (CDN) of AWS, whereas Regional Edge Caches are staged to store frequently requested content to eliminate redundant access to the origin. AWS Regions, in their turn, are full-fledged data centers, where original datasets are stored with high protection through the use of enhanced encryption and access rules. The comparative table was also clear enough to show the differences in video display between each layer in the context of location, access to privacy, which helped me understand how AWS guarantees the performance, scalability, and security on the world scale. Such knowledge will be critical with respect to the development of cloud-based applications, which must have wide reception, as well as data safety.
AWS IAM 
 

 

	AWS especially on academic cloud operation. The screenshot of a submission to Lab 1: Introduction to AWS IAM indicates that I managed to work on the task of dealing with identities and user permissions in AWS-based resources and develop the initial skills in securing AWS resources. Second Case Study #8 image augment this since it segregates responsibilities between the UCW (University Canada West) and AWS along the four levels; EC2, Platform, Software and Dataset. I came to know that AWS has a design to maintain physical infrastructure, virtualization, and storage longevity whereas the operating system, platform configuration and learning tools, and securing academic information is carried out by UCW. This outlined distinction strengthens the idea that the facilities of cloud providers provide the backbone, and configuration, access and data protection has to be dealt with by the customers themselves. It is an important observation in future professional and academic career in the context of cloud computing.
AWS VPC
 
	The Lab #10: Build your VPC (Case Study #10), gave me some practical, practical experience of setting up AWS Virtual Private Cloud (VPC) and launching a web server inside the VPC. As demonstrated in the lab screenshot, I have completed all of the tasks, namely, assigning a VPC, created subnets, routing tables and launched an ec2 instance with a web server. This activity made me realize the basics behind cloud networking, including how to segregate resources and accomplish traffic management with the help of security groups, and the secure and scalable deployment requirements. Not only did I revise theoretical information during this lab but I also improved practical technical experience that is essential in the field of cloud administration and solution architecture.
 AWS Lambda 
 
	Being a student, Case Study #11: Create an AWS Lambda Function helped me understand the main principles of server less computing as well as implementing event driven applications using AWS Lambda. Through the screenshots, I was able to carry out some tasks such as defining a Lambda, simulating events, and confirming the operation of the Lambda as desired. I now know that AWS Lambda enables the execution of code in reaction to triggers without the provisioning and management of servers, and this is best suited to lightweight and should be automated. This lab has taught me the ways to incorporate serverless functions into the cloud that can minimize the operation overhead, enhance scalability, and facilitate data processing in real-time. Such lessons are particularly useful in the current scenario in application development where agility and automation are being pursued.

AWS EBS
 

	Case Study #12: Amazon EBS (Elastic Block Store) Working with storage volumes in the cloud gave me firsthand experience with how to manage migration of clouds. Based on the lab screen shot, I have successfully done some of the lab tasks like creating EBS volume and attaching the volume to EC2 instance, formatting and mounting volume, and even created snapshot and restored the same. This activity made me realize how I can use EBS to create persistent block-level storage in AWS, which is of importance when I need to store data about applications, database as well as backup. I understood the operation of EBS volumes as virtual hard disk and I realized how snapshots support durability and recovery of data. This laboratory reinforced my understanding of the AWS storage services and stressed the necessity of the effective volume administration in the real life aspects of the cloud infrastructure.
