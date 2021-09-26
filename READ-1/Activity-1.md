
# Activity 1: Investigating APIs

![](https://content.altexsoft.com/media/2019/06/https-lh6-googleusercontent-com-_nyclktg8po_wx5-.png)

##  **• Explain API types and the benefits of APIs, and analyse the differences between API and SDK.**

A set of processes, protocols, and tools for creating software applications is known as an application program interface (API).
In a nutshell, an API defines how software components should communicate with one another.
APIs are also utilized for creating graphical user interfaces (GUI)
components.
By giving all of the necessary information, a good API makes it easy to create a software.
constructing elements, The blocks are then put together by a coder.


### API Types :

Theres More than one way to look at API types 
**First one API By realise Police :**

|    Private APIs   | Partner APIs |  Public APIs   |
| :---        |    :----:   |                  ---: |
| These (API's)are intended to improve an organization's software and products. These APIs can be used by in-house engineers or freelancers to merge a corporation's IT systems or applications, as well as to create new systems or customer-facing apps that use current systems. Although if apps are made public, only those who directly work with the API distributor have access to the interface. A company can use the private approach to have total control over API usage.  |    A partner API is a tool for facilitating business-to-business transactions that is only accessible to a restricted group of outside programmers or API users. For example, if a company wishes to share customer information discreetly with outside CRM businesses, it can utilize a partnership API to link the internal customer data system with those external partners no other API use is allowed.Access to such APIs is limited to partners with certain permissions and licenses. As a result, partner APIs typically provide more robust authentication, authorisation, and security features. In addition, most businesses do not directly monetize APIs; rather, partners are compensated for their services rather than through API usage. |      Any outside programmer or company can utilize a public API since it is open and available. A company that develops and offers a public API will have a business plan that includes sharing its apps and data with other companies Authentication and authorisation are usually moderate in public APIs. An corporation might potentially try to commercialize the API by charging a charge for each request made to the public API.  |
|    |         |       |

**Second By API Usage :**

1. **APIs for databases**, Database APIs allow an application to communicate with a database management system. Developers work with databases by writing queries to extract data, change tables, and so on.

2. **APIs for operating systems**, Those APIs define how applications deal with OS services and resources. Any OS, has its own set of APIs, such as the Windows API or the Linux API (kernel–user space API and kernel internal API).

3. **APIs for the web**, This is the most popular API class. Web APIs allow for the transfer of machine-readable data and functionality across web-based systems that follow a client-server design. To convey requests from web applications and responses from servers, these APIs usually employ Hypertext Transfer Protocol (HTTP)..

### **The benefits of APIs :**

#### **For Business :**

* Improves connectivity and collaboration.
* Encourages innovation.
* Enhances customer experience.
* Improves marketing.
* Collects data for intelligence analytics.
* Creates new revenue opportunitie

#### **For Programmers :**

* **Automation** : This is the first and greatest obvious advantage of using API. Computers will perform the task instead of people, reducing overall time. APIs allow developers to handle work more efficiently and change processes in such a manner so they become more effective in less time.
* **Efficiency**: When you have access to the API, it is simple to post fresh material quickly. The technology instantly publishes the material and makes it available across all channels. As a result, the content is readily shared with a large audience. In comparison to traditional marketing, this function takes less time and costs less money.
* **Adaptation**:Any system must be updated frequently, and Custom API facilitates this process. It consumes a lot of effort and money for several firms to implement a new system update. If you include this technology into the system, By Using APIs ,data migration will be improved, and information may be evaluated more thoroughly. If a different interface had been used, the results would never have been as good as API.
* **More Scope**:An application layer can assist to transfer information to other systems and provide services to new consumers by introducing API into the system. This interface is fascinating because it allows developers to build a tailored service for new consumers.

### **API vs SDK**

API | SDK
------------ | -------------
Application programming interface (API) is a term that refers to a set of tools that An API allows interactions between different systems, either it is used as a standalone service or as part of an SDK. This is accomplished by enabling third-party programmers to use its proprietary code. The API method's programmers then can allow their own customers to use the API solution's service or services indirectly. | A software development kit is referred to as an SDK. The SDK, sometimes known as a devkit, is a collection of software development tools for a certain platform, comprising building blocks, debuggers, and, in some cases, a framework or group of code libraries, including a collection of operating system-specific functions (OS).

```
At least one API is frequently included in an SDK. These two contribute in separate ways, yet they can and do collaborate.

APIs, once again, govern how various platforms interact. They use specifications (protocols) to enable contact, and as facilitators, they are one of the instruments in a full kit.

SDKs are the entire package. They give everything needed to create new software for a certain platform or programming language, in addition to facilitation.
```

## **• The using of APIs may introduce some security concerns, assess these concerns.**

When using anything digital or connect to the Internet security risks may and will occur for sure, when talking about API’s there's many security risks associated with them, and there is ways to mitigate those risks, depending on the API type and use, famous security risks associated with API’s:

* **Broken object level**: Broken Object Level Authorization occurs when an application fails to verify that the user making the request has the necessary permissions to access another user's resource.
*	**user- and function-level authorization:** The API relies on the client to use user level or admin level APIs as appropriate. Attackers figure out the “hidden” admin API methods and invoke them directly.

* **excessive data exposure:** When an API client application does not analyze the data it receives before providing the data to the software's user, excessive data exposure occurs. When APIs deliver sensitive data, the client application should filter the information before passing it on to the client.
* **security misconfiguration**: Misconfiguration occurs when a system or database administrator or developer fails to correctly setup an application's, website's, desktop's, or server's security architecture, resulting in dangerous open routes for hackers.

* **insufficient logging and monitoring:** Missing security vital information logs or a lack of adequate log format, context, storage, security, and quick reaction to detect an event or breach are examples of insufficient logging and monitoring. An organization may be caught off guard by a breach that goes unnoticed, resulting in irreversible regulatory, financial, and legal consequences.

## **• Determine a range of APIs for a particular platform that covers a group of users.**





## **sources For Activity one :**

1. https://searchapparchitecture.techtarget.com/tip/What-are-the-types-of-APIs-and-their-differences 
2. https://en.wikipedia.org/wiki/API
3. https://www.altexsoft.com/blog/engineering/what-is-api-definition-types-specifications-documentation/
4. https://www.insightssuccess.com/5-benefits-of-api-for-developers-application-programming-interface/
5. https://www.ibm.com/cloud/blog/sdk-vs-api
6. https://www.redhat.com/en/topics/security/api-security
7. https://techbeacon.com/security/critical-api-security-risks-10-best-practices
8. https://blog.shiftleft.io/api-security-101-excessive-data-exposure-a730d351fbae
9. https://outpost24.com/blog/What-are-security-misconfigurations-and-how-to-prevent-them#:~:text=Misconfiguration%20normally%20happens%20when%20a,dangerous%20open%20pathways%20for%20hackers.