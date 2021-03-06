# System-scalability π₯οΈ
_The ability of a platform to respond to different requirements will determine the success or failure of a project through its growth stages. **Scalability** is the ability of a software system to adapt to more demanding operating conditions while maintaining its functionality. In general, a scalable system is one that can "grow" (increase the volume of its database, incorporate modules, serve a greater number of users) without ceasing to function or worsening the quality of its service._

## Big key to success ποΈ
_For the success of small and medium-sized companies is to consider in their plans a growth strategy that foresees athe future needs of the business and its possible expansion. The problem for some companies lies in their limited scalability, their limited ability to adapt to more demanding operating conditions and to respond in a timely manner. The scalability of a site is determined by the **characteristics of the hardware, software, code and design**. When designing a scalable website the main objective should be to ensure efficient resource management. To achieve this, measures in both the user interface and data storage should be planned and implemented well in advance of implementation, taking into account the available resources._

## Step-by-step growth π£
_Normally the growth of our web application goes step by step and if we have had a good study and development of our application it will not cost us to add new features. In most web developments we never know when we may receive sudden and drastic increases in the volume of users._

## Why does one need scalability? π
_Looking at the websites of the frontline companies, we donβt always realise what kind of workload they are to withstand. Neither do we think about the importance of high productivity and usability for the success of the company. To one extent or another, most of them experience such issues. However, the degree of their complexity depends on how well the web applications were designed from the very beginning. Scaled development is not a special kind of development. Itβs a set of principles and techniques that help you design an application to a high standard.By sticking to specific rules of the application setup, you will be able to:_

- Reduce the page load time, number of errors, time to implement changes, and the cost to update the site.
- Improve the user experience.
- Extend the life cycle of the services or products offered.
- As a result, increase sales and brand loyalty.

_In addition to scalability, there is a number of related concepts that help better understand the problem. One of them is recoverability. Recoverability is the ability of the system to restore its operability after a failure. It is closely related to the concept of a saturation point. A saturation point is a certain degree of the workload intensity at which the system begins to malfunction. Unjustified jumps in the operation of the system usually lead to failure. Under normal conditions, the programβs performance changes proportionally to the load, which increases gradually. If at some point the predictable growth is replaced by abnormal jumps β the saturation point has been reached. Testing aimed at identifying this point is called a ramp-up test. It helps to determine the reliability and scalability of a web application, as well as identify the system bottlenecks that undermine the effective operation of the entire system._

# What characteristics affect the web application scalability?

- **Architecture**. This is one of the most important parts of app scalability.
- **Framework load**. Sometimes scalability is limited to the framework, so its choice affects the performance of an app with the increase of features.
- **Sustainable design**. The quality of code also significantly affects scalability.
- **Sustainable load testing**. With proper load and performance testing, youβll be able to find and eliminate the bottlenecks of your app and ensure its smooth growth.
- **Hardware limitations**. As you see, not only software can affect scalability.
- **Third-party component integration**. It is the most widespread cause of bottlenecks and failures in operation.

## Frontend vs Backend 

![image](https://user-images.githubusercontent.com/73659203/162005027-37159abc-2511-4143-81e4-cf9c70238dd3.png)

_The **frontend** is an abstraction that provides a user interface. A frontend is the visible part of a web application the user interacts directly with, in addition to being easy to use, a properly designed frontend also helps avoid problems with scalability in the future._

_**Backend** stands for everything that happens on the server. It interprets everything the user does on the frontend, communicates it to the database if necessary and sends a response back to the browser. This part takes up to 80% of the entire code and affects the performance of the whole application the most. Backend is responsible for the dynamic processes on the page and data storage management, which makes it more prone to bottlenecks. The backend can be built with any multifunctional programming language like Javascript, Python, Ruby, C#, etc._

![image](https://user-images.githubusercontent.com/73659203/161775667-bf095834-3745-45d8-b42f-a8d467bbd9fe.png)

_A multi-tier model is a software model that should contain three components: the client, the application server the client application connects to, and the database server to run the application. Each layer of such an application should perform only the most essential functions, thereby improving performance and scalability greatly. The multi-tier architecture is to implement two basic principles:_

- Minimise the functionality of client components, leaving the client only the functions of the user interface; maximum simplification and unification of the client software;
- Unload the database server from functions it shouldnβt run.

_Such architecture distributes the processing modules more intelligently, which in this case are performed on one or several separate servers._

## Popular scalable web app frameworks
_These are the tech stack options to explore while designing scalable web applications:_

- **Node.js**
_This technology is considered to be the best for scalable and asynchronous programming to date. It can handle multiple requests at a time without any disruptions and failures. This outstanding Javascript framework eliminates waiting while providing a single-threaded, non-blocking, asynchronous programming, which is very memory efficient. Also, it provides numerous packages with useful features optimising the work even more. You can learn more about this framework at its official web page._

- **Django**
_This high-level and extra fast Python web framework supports the clean and pragmatic design of the applications which contributes to the scalability as well β see a detailed list of its advantages. Continuous development from the concept to launch seems favourable for every startup, while reliable security helps to avoid many serious mistakes._

- **Ruby on Rails**
_RoR is familiar to everybody who uses Shopify, Airbnb, ZenDesk, GitHub, and many other popular platforms. It is known as the framework allowing to build a web application 30% faster than others while providing the same quality._

## Scalable web app principles

- **Smooth performance**
_In addition to availability, the application should have high performance. Otherwise, you risk getting an adverse reaction from customers and reducing the position of the website in search results β Google indexes such sites worse. Thus, a web application with low performance is unlikely to be able to deter a serious audience._

- **Continuous availability**
_For companies, it is vital that their web application is available all the time. Every minute it becomes inaccessible causes significant damage to the companyβs profits and reputation. For SaaS and cloud solutions, itβs crucial to ensure interrupted lifelong access to services. Therefore, it is necessary that a scalable website be accessible at any time of the day and from any place where your user can apply for the service._

- **Fast data retrieval**
_Working with data usually involves many performance problems. The fact is that third-party technologies are usually used for storing and accessing data, and their integration is an intractable task. At the junction of the main app part and database services, you can often find bottlenecks. Your responsibility is to avoid this problem in your project._

- **Malfunction traceability**
_The system has to be easy to operate, maintain, and update. Besides, all the problems that may arise already at the stage of product functioning should be easily traced and corrected. Good results are achieved by proper structuring and segmenting the application into relatively isolated parts._

- **Real-time response**
_Of course, the speed of your online application is important. It concerns not only the data retrieval on the storage or overall performance but also the speed of operations and response. No matter how useful your application is, you only have a few seconds to meet the customerβs needs._

# Database scalability
_Scalability is the ability to expand or contract the capacity of system resources in order to support the changing usage of your application. This can refer both to increasing and decreasing usage of the application. Increased usage of your application brings three main challenges to your database server:_

- The CPU and/or memory becomes overloaded, and the database server either cannot respond to all the request throughput or do so in a reasonable amount of time.

- Your database server runs out of storage, and thus cannot store all the data.

- Your network interface is overloaded, so it cannot support all the network traffic received.

_The first action you might take to address the need for increased capacity is application and database optimization. Examples include optimizing the application code, caching, and appropriately indexing your query patterns . These optimizations increase the efficiency of your application and should bring some relief. However, there comes a point when system resource limits are reached. At this point, you will want to consider scaling your database vertically, horizontally, or both._

# Whatβs the Difference Between Horizontal and Vertical Scaling?

## What is Vertical Scaling?

_Vertical scaling refers to increasing the processing power of a single server or cluster. Both relational and non-relational databases can scale up, but eventually, there will be a limit in terms of maximum processing power and throughput. Additionally, there are increased costs with high-performance hardware, as costs do not scale linearly._ 

![image](https://user-images.githubusercontent.com/73659203/161997479-f016e436-0373-4b4a-b4c8-21470a0350fb.png)


PROS
- The main benefit of vertical scaling is that nothing changes about your database infrastructure other than the hardware specifications of the machine running the database.

- As such, itβs transparent to the application. The only difference is that you have more CPUs, memory, and/or storage space.

- Vertical scaling is a good option to try first if massive storage and processing are not required.

CONS
- The downside of scaling up is that servers with more storage and processing power can be a lot more expensive.

- There is also a physical limit on the amount of CPUs, memory, network interfaces, and hard-drives that can be used on a single machine. For those scaling up using a cloud platform provider, you will eventually reach the highest tier of machine available.

- If scaling vertically requires a migration between hardwares, it could result in downtime or service disruption.

_When cost and/or machine limitations become an issue, be sure to consider horizontal scaling._

## What is Horizontal Scaling?
_Horizontal scaling, also known as scale-out, refers to bringing on additional nodes to share the load. This is difficult with relational databases due to the difficulty in spreading out related data across nodes. With non-relational databases, this is made simpler since collections are self-contained and not coupled relationally. This allows them to be distributed across nodes more simply, as queries do not have to βjoinβ them together across nodes._

![image](https://user-images.githubusercontent.com/73659203/161997528-44003c0d-988d-42eb-9160-7a5829fb59eb.png)


- Horizontal scaling (sharding) tries to be as transparent as possible, but may require application architecture and code changes. How you store and query the data can significantly affect your application performance.

- Database systems that are scaled horizontally are also more complicated to manage and maintain, leading to more work for you and your team.

# How to Increase Database Performance and Make it More Scalable

_There is a variety of scaling techniques which depend on the database system and what components are used. However, they all use the concept of a node, which is an individual machine storing some or all of the data. A group of nodes that work together is called a cluster. There are two commonly used horizontal database scaling techniques: replication and horizontal partitioning (or sharding)._

## Replication

_Replication refers to creating copies of a database or database node. Replication adds fault-tolerance to a system. Each node in a cluster contains a copy of the data. If one of the nodes goes down, the cluster is still able to serve client requests because the other nodes in the cluster can respond to the requests._

![image](https://user-images.githubusercontent.com/73659203/161998653-3dfa590c-0003-4516-a44f-db303eb7cede.png)

_Replication is also a form of scaling because client requests can be spread across all the nodes in the cluster instead of overwhelming a single node. This increases the capacity of the system to handle more database read requests. A set of replicated nodes is called a replica set. One of the nodes in a replica set is the primary node, and the other nodes are secondary nodes. Read requests are distributed between each of the nodes. However, only the primary node can be written to, and updates made to the primary node are then replicated to the other nodes._

# Partitioning

_Partitioning distributes data across multiple nodes in a cluster. Each replica set (known in MongoDB as a shard) in a cluster only stores a portion of the data based on a collection sharding key (sharding strategy), which determines the distribution of the data. This makes it possible to scale the storage capacity of the cluster virtually without limit. Since each node is only responsible for processing the data it stores, overall processing capacity for both reads and writes is increased as well. However, partitioning is a more complex scaling strategy than replication. Because each node only stores part of the data, for each request, the database queries need to determine which node or nodes contain the relevant data._

_If the data is stored across multiple nodes, the reads and writes could be done in parallel. For large volume data reads, performance is improved because each node can read its section of data in parallel with the other nodes. There is an overhead to reading from multiple nodes. The data from all the nodes still needs to be transferred over the network and then combined into a query result set. For small data reads, the network latency could be a significant portion of the overall query time. For those scenarios, itβs more efficient to query using targeted operations._

![image](https://user-images.githubusercontent.com/73659203/161999558-f0b2d2b9-017b-4395-a82b-71f8845c4546.png)

# Partitioning with Replication

_In order to take advantage of both scalability and fault tolerance, you need to combine partitioning and replication. You can configure multiple groups of nodes (replica sets in MongoDB) with replication and then run a sharded cluster on top of them. Each node in a replica set will hold a copy of the shard data. So, if a server goes down, the replica set can still respond to queries for the shard it holds. It would look something like this:_ 

![image](https://user-images.githubusercontent.com/73659203/162001066-8645f9e6-3d92-4667-a2be-97d1c283b914.png)


