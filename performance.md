# Performance :

## 1- Usage of CDN(Content Delivery Network):
A content delivery network, or content distribution network, is a geographically distributed network 
of proxy servers and their data centers. The goal is to provide high availability and performance by 
distributing the service spatially relative to end users.

We will try to use CDN in our Flex Management System, because we are actually aiming to make it readily available
for not only Fast-Nuces but also any college or University in the world. So, we have to make data centres accordingly.

![CDN](https://user-images.githubusercontent.com/105812482/206721659-b0e62516-2f6a-4d9e-aa14-4c4ab01e0244.png)

We will somehow try to manage a system as above, to make the data readily available for the particular region.
We aim to have big 7 servers in each of the `Continent` to make data readily available for that particular
Continent. It is all about user convenience and we try to make it easy for users.

## Requirments:
### 1. System should have latency rate of 2 seconds only.
#### 1.1 System should not lag for more than 1 seconds.
#### 1.2 System shall fetch the data from nearest respective server available.
### 2. System shall be available for any of 7 continents.
#### 2.1 System shall have data of all 7 continents.
### 3. System should use PWA to cache required content so that next time,request  don't go again to the server for same content.




## 2- Usage of Cache:
Caching is the process of storing copies of files in a cache, or temporary storage location, so that they can be accessed more quickly. 
Technically, a cache is any temporary storage location for copies of files or data, but the term is often used in reference to 
Internet technologies.

As our Flex management system will be readily available on web also, so that it it is also necessary to use cache and to make 
`latency rate` very minimum.

![web-cache](https://user-images.githubusercontent.com/105812482/206723284-4034f03d-54d9-455c-bdeb-42b60eddaedc.png)

We will actually make a system will this, if our main server is very far away from the user and many requests that 
are similar is coming to us many times, then we will make a server in between them and will do the cache loading in
the server, so that it will only take a long latency rate first time only but not after first time.

Even `Google` also provide the cache loading by the keyword of `cache: website.com`.


## Requirments:

### 1. System should atleast 1 cahche copy for each page.
#### 1.1 System should have 1 latest cache copy for each page in each server of 7 continents.
#### 1.2 System shall maintain each latest copy in every 1 minute.
#### 1.3 System shall have each cache copy synchronized with other servers.



## 3-  Lazy Loading:
The initialization of an object is postponed until the point at which it is required by using the design pattern known as "lazy loading," 
which is frequently used in computer programming and mostly in web design and development. If implemented correctly and responsibly, 
it can increase the program's operational efficiency.

![Lazy-Loading-2](https://user-images.githubusercontent.com/105812482/206724970-ba51b18d-dffe-4c95-8547-edee4cd2ca9b.jpg)

We will be implementing lazy loading, and only showing the contents of a particular page. Suppose if user is on our `Attendence page`
then we will not be loading any other page except that one. Other pages will only be loaded once user enter that particular page.
It will actually enhance the loading of our website and minimze the latency rate, as it will take along time to load all the pages
from the server rather than loading only one page. So we thought of implementing all the Performance requirments, because user will
only be our first priority.


## Requirments:
### 1. System should load each page when user needs.
#### 1.1 System should load 1 page at a time.
#### 1.2 System shall maintain the latency rate of 1 second on loading each page.
#### 1.3 System shall load the next page when user is halfway down to the already loaded page.



