NEELANSHI JAIN
# ELASTICSEARCH: FULL-TEXT SEARCH:

- [What is Elasticsearch and  features?](#A1)
- [Where Elasticsearch used?](#A2)
- [Why Elasticsearch?](#A3)
- [What programming languages does Elasticsearch support?](#A4)
- [Download(For Windows)](#A5)

# SOLR:  FULL-TEXT SEARCH:

- [What is Solr and it's features? ](#B1)
- [Apache Solr-Search Engine Basics](#B2)
    * [Search Engine Components](#B3)
    * [How Do Search Engines Work?](#B4)
    * [Download(For Windows)](#B5)


# LUCENE: FULL-TEXT SEARCH:
- [What is Lucene?](#C1)
- [Features of Lucene](#C2)
- [Lucene versus Solr](#C3)
- [when should I use Lucene?](#C4)
- [Download Lucene](#C3)

## [reference](#D1)

<br />

___


## FULL-TEXT SEARCH:

In this, we use a more advanced way to search a database. It quickly finds all instances of a word in a table without scanning rows and columns.
It works by using text indexes.
For example, let us say we have a document in that we have content "I am an engineer" When we want to find this content, we must find by full keyword "engineer":
![](https://github.com/neelanshijain3111998/NeelanshiMarkdown/blob/master/images/search_perfect.png)
but, if we search like this (like in SQL: like '%engin%''), we can't find any result:
![](https://github.com/neelanshijain3111998/NeelanshiMarkdown/blob/master/images/Not_correct.png)

<br />

### What is Elasticsearch?<a name="A1"></a> ![image](https://user-images.githubusercontent.com/79247910/125027149-6e509d00-e0a3-11eb-933b-5ce01fff9e55.png)

It is an open-source Analytics and full-text search engine. It was first released by **Elasticsearch N.V** in 2010. Elasticsearch built upon [Apache Lucene](https://lucene.apache.org/core/). It is for all types of data, including textual, numerical, structured, and unstructured.
With the help of Elasticsearch, we can store, search data very quickly. Many large organizations across the world use it.

![](https://github.com/neelanshijain3111998/NeelanshiMarkdown/blob/master/images/RelationalElastic.png)


An Elasticsearch document looks like this -

```
{  
    "first_name": "Neelanshi,
    "email": neel@gmail.com 
}
```

_Features_:
1) Schema-free
2) Real-time
3) fast
4) Scalability

<br />


### Where Elasticsearch used? <a name="A2"></a>

1) Application search
2) Website search
3) Security analytics
    - ELK stack, In  real time it provides a complete picture of what's going on across your systems

<br />

### Why Elasticsearch? <a name="A3"></a>
Because, With large datasets, relational database comparatively works slow and leads to slow search from the database.
Elasticsearch is a NoSQL distributed database, which is a solution for quick retrieval and storing data.

<br />


### What programming languages does Elasticsearch support? <a name="A4"></a>
`.NET` `Java` `JavaScript` `PHP` `Perl` `Python` `Ruby`


<br />

### Elasticsearch - Installation <a name="A5"></a>
> **steps-1:** check the java installed in your computer, if not then install it first . 

java -version
             
> **step-2:** Based on your operating system, [download](https://www.elastic.co/downloads/elasticsearch) Elasticsearch ZIP file.

___

<br />

### What is Solr? <a name="B1"></a> ![](https://user-images.githubusercontent.com/79247910/125015970-2bd09580-e08e-11eb-89ba-4684b3013147.png)

It's an open-source search platform written in Java from the Apache Lucene project. Not only for search, but we can also use Solr for 
storage purpose.

_features_:
* Flexible and Highly Scalable.
*Restful APIs
 -To work on Solr, there is no need to know Java. We can use restful APIs to communicate with Solr.
 - We can also enter files in XML, JSON, and. CSV formats in Solr and get results in the same format.

<br />

### Apache Solr-Search Engine Basics <a name="B2"></a>
Users can search for information by passing queries into the Search Engine with the help of keywords or phrases. The Search Engine then searches in its database and returns relevant links to the user.
<br />


![](https://user-images.githubusercontent.com/79247910/125018818-79033600-e093-11eb-86ee-10558fad3a98.png)

<br />

### Search Engine Components <a name="B3"></a>
three basic components of a search engine.
> -Web Crawler − It is a software component that traverses the web to collect  information.

> -Database − It stored all the information which is on the web.

> -Search Interfaces − It is an interface between user and database.
<br />

### How Do Search Engines Work? <a name="B4"></a>
Any search Engines perform some or all of the following operations.

|No |Title |Description |
| --- | --- | --- |
|1 |Acquire Raw Content|Collect the relevant content according to the user search.|
|2 |Build the document |from the relevant content, build the documents.|
|3 |Analyze the document|Before indexing document is analyzed.|
|4 |Indexing the document|After analyzed, index them.|
|5 |User Interface for Search|Once a database is ready, an application can perform a search operation. an application must provide a user interface where the user can enter the text.|
|6 |Build Query|Once the user enters the text, the application prepares a query object using this text.|
|7 |Search Query|the index database is checked to get the relevant details with the help of the query object.|
|8 |Render Results|Display the results to the user.|


### [Download](https://solr.apache.org/downloads.html) Solr <a name="B5"></a>

<br />

___


### What is Lucene? <a name="C1"></a>
It is a full-featured text search engine library written in Java. It is a powerful Java-based Search library. 
Lucene plays a role from step 2 to step 7 mentioned in the above table. It is the heart of any search application.

<br />

### Features of Lucene <a name="C2"></a> 
- Fast, Flexible, and stable
- scalable, High performance
- Full-text search capability
- Easy to integrate Lucene search functionalities into the application
- powerful, Accurate, and efficient search algorithms.
- An Apache library

### Lucene vs Solr <a name="C3"></a>
A simple way to explain Solr and Lucene is that of a car and its engine. You can't drive an Engine, But you can drive a car. Similarly, Lucene is a programmatic library that you can't use as-is,
but Solr is a complete application that you can use out-of-box.

<br />

### When should I use Lucene? <a name="C4"></a>
If we need to embed search functionality into a desktop application, then Lucene is the more appropriate choice.

<br />

### [Download](https://lucene.apache.org/core/downloads.html) Lucene <a name="C3"></a> 
 
___ 

## Reference <a name="D1"></a>
https://www.elastic.co/what-is/elasticsearch

https://blog.avenuecode.com/elasticsearch

https://www.tutorialspoint.com/apache_solr/apache_solr_quick_guide.htm

https://www.tutorialspoint.com/lucene/index.htm
