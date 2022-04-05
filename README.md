# System-scalability
_The ability of a platform to respond to different requirements will determine the success or failure of a project through its growth stages. **Scalability** is the ability of a software system to adapt to more demanding operating conditions while maintaining its functionality. In general, a scalable system is one that can "grow" (increase the volume of its database, incorporate modules, serve a greater number of users) without ceasing to function or worsening the quality of its service._

## Big key to success
_For the success of small and medium-sized companies is to consider in their plans a growth strategy that foresees athe future needs of the business and its possible expansion. The problem for some companies lies in their limited scalability, their limited ability to adapt to more demanding operating conditions and to respond in a timely manner. The scalability of a site is determined by the **characteristics of the hardware, software, code and design**. When designing a scalable website the main objective should be to ensure efficient resource management. To achieve this, measures in both the user interface and data storage should be planned and implemented well in advance of implementation, taking into account the available resources._

## Step-by-step growth
_Normally the growth of our web application goes step by step and if we have had a good study and development of our application it will not cost us to add new features. In most web developments we never know when we may receive sudden and drastic increases in the volume of users._

## Why does one need scalability?
_Looking at the websites of the frontline companies, we don’t always realise what kind of workload they are to withstand. Neither do we think about the importance of high productivity and usability for the success of the company. To one extent or another, most of them experience such issues. However, the degree of their complexity depends on how well the web applications were designed from the very beginning. Scaled development is not a special kind of development. It’s a set of principles and techniques that help you design an application to a high standard.By sticking to specific rules of the application setup, you will be able to:_

- Reduce the page load time, number of errors, time to implement changes, and the cost to update the site.
- Improve the user experience.
- Extend the life cycle of the services or products offered.
- As a result, increase sales and brand loyalty.

_In addition to scalability, there is a number of related concepts that help better understand the problem. One of them is recoverability. Recoverability is the ability of the system to restore its operability after a failure. It is closely related to the concept of a saturation point. A saturation point is a certain degree of the workload intensity at which the system begins to malfunction. Unjustified jumps in the operation of the system usually lead to failure. Under normal conditions, the program’s performance changes proportionally to the load, which increases gradually. If at some point the predictable growth is replaced by abnormal jumps – the saturation point has been reached. Testing aimed at identifying this point is called a ramp-up test. It helps to determine the reliability and scalability of a web application, as well as identify the system bottlenecks that undermine the effective operation of the entire system._

## What characteristics affect the web application scalability?

- **Architecture**. This is one of the most important parts of app scalability.
- **Framework load**. Sometimes scalability is limited to the framework, so its choice affects the performance of an app with the increase of features.
- **Sustainable design**. The quality of code also significantly affects scalability.
- **Sustainable load testing**. With proper load and performance testing, you’ll be able to find and eliminate the bottlenecks of your app and ensure its smooth growth.
- **Hardware limitations**. As you see, not only software can affect scalability.
- **Third-party component integration**. It is the most widespread cause of bottlenecks and failures in operation.

## Frontend vs Backend

_The **frontend** is an abstraction that provides a user interface. A frontend is the visible part of a web application the user interacts directly with, in addition to being easy to use, a properly designed frontend also helps avoid problems with scalability in the future._

_**Backend** stands for everything that happens on the server. It interprets everything the user does on the frontend, communicates it to the database if necessary and sends a response back to the browser. This part takes up to 80% of the entire code and affects the performance of the whole application the most. Backend is responsible for the dynamic processes on the page and data storage management, which makes it more prone to bottlenecks. The backend can be built with any multifunctional programming language like Javascript, Python, Ruby, C#, etc._

![image](https://user-images.githubusercontent.com/73659203/161775667-bf095834-3745-45d8-b42f-a8d467bbd9fe.png)

_A multi-tier model is a software model that should contain three components: the client, the application server the client application connects to, and the database server to run the application. Each layer of such an application should perform only the most essential functions, thereby improving performance and scalability greatly. The multi-tier architecture is to implement two basic principles:_

- Minimise the functionality of client components, leaving the client only the functions of the user interface; maximum simplification and unification of the client software;
- Unload the database server from functions it shouldn’t run.

_Such architecture distributes the processing modules more intelligently, which in this case are performed on one or several separate servers._

## Popular scalable web app frameworks
_These are the tech stack options to explore while designing scalable web applications:_

- Node.js
_This technology is considered to be the best for scalable and asynchronous programming to date. It can handle multiple requests at a time without any disruptions and failures. This outstanding Javascript framework eliminates waiting while providing a single-threaded, non-blocking, asynchronous programming, which is very memory efficient. Also, it provides numerous packages with useful features optimising the work even more. You can learn more about this framework at its official web page._

- Django
_This high-level and extra fast Python web framework supports the clean and pragmatic design of the applications which contributes to the scalability as well — see a detailed list of its advantages. Continuous development from the concept to launch seems favourable for every startup, while reliable security helps to avoid many serious mistakes._

- Ruby on Rails
_RoR is familiar to everybody who uses Shopify, Airbnb, ZenDesk, GitHub, and many other popular platforms. It is known as the framework allowing to build a web application 30% faster than others while providing the same quality._

## Scalable web app principles

- Smooth performance
_In addition to availability, the application should have high performance. Otherwise, you risk getting an adverse reaction from customers and reducing the position of the website in search results — Google indexes such sites worse. Thus, a web application with low performance is unlikely to be able to deter a serious audience._

- Continuous availability
_For companies, it is vital that their web application is available all the time. Every minute it becomes inaccessible causes significant damage to the company’s profits and reputation. For SaaS and cloud solutions, it’s crucial to ensure interrupted lifelong access to services. Therefore, it is necessary that a scalable website be accessible at any time of the day and from any place where your user can apply for the service._

- Fast data retrieval
_Working with data usually involves many performance problems. The fact is that third-party technologies are usually used for storing and accessing data, and their integration is an intractable task. At the junction of the main app part and database services, you can often find bottlenecks. Your responsibility is to avoid this problem in your project._

- Malfunction traceability
_The system has to be easy to operate, maintain, and update. Besides, all the problems that may arise already at the stage of product functioning should be easily traced and corrected. Good results are achieved by proper structuring and segmenting the application into relatively isolated parts._

- Real-time response
_Of course, the speed of your online application is important. It concerns not only the data retrieval on the storage or overall performance but also the speed of operations and response. No matter how useful your application is, you only have a few seconds to meet the customer’s needs._
