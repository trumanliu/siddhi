Siddhi Complex Event Processing Engine 
======================================

---

|  Branch | Build Status |
| :------------ |:-------------
| master | [![Build Status](https://wso2.org/jenkins/view/wso2-dependencies/job/siddhi/job/siddhi/badge/icon)](https://wso2.org/jenkins/view/wso2-dependencies/job/siddhi/job/siddhi )|

---
##### New version of Siddhi v4.0.0 is built in Java 8.
##### Latest Released Version v3.0.5.
For all releases see https://github.com/wso2/siddhi/releases

Siddhi CEP is a lightweight, easy-to-use Open Source Complex Event Processing Engine (CEP) released as a Java Library under Apache Software License v2.0. Siddhi CEP process events generated by various event sources, analyze them and notifies appropriate complex events according to the user specified queries.

This project was initiated as a research project at University of Moratuwa, Sri Lanka, and now being improved by [WSO2 Inc](http://wso2.com/). 

#### Documentation 
Siddhi query guide: https://docs.wso2.com/display/CEP420/SiddhiQL+Guide+3.1 

Using Siddhi as a library: https://docs.wso2.com/display/DAS310/Using+Siddhi+as+a+Library

#### Siddhi Extensions can be found at https://github.com/wso2-extensions?q=siddhi

#### Try it with [WSO2 Data Analytics Server 3.1](http://wso2.com/smart-analytics)
https://docs.wso2.com/display/DAS310/Siddhi+Try+It+Tool

Siddhi is also used with [WSO2 IoT Server](http://wso2.com/iot) for IoT analytics and as a edge analytics library.


Features Supported
------------------
 - Filter
    - Multiple filter conditions can be defined 
    - Filters can be applied before and/or after Window operations
 - Join
    - Supports joining two streams into one based on a condition   
    - Match operation triggering can be configured (making "left" or "right" or both streams to trigger)
    - Supports Left, Right & Full Outer Joins and Inner Join
 - Aggregation
    - By default shipped with Avg, Sum, Min, Max, etc
    - Supports Custom Aggregations via its pluggable architecture
 - Group by
    - Supports Group by based on more than one attribute
    - Supported for all type of queries
 - Having
    - Supported for all type of queries
 - Window
    - Default implementations to Windows are: Time Window, Time Batch Window, Length Window, Unique Window, etc
    - Supports Window operators via the pluggable architecture
 - Conditions and Expressions
    - Supporting condition and expression evaluation
    - Conditions supported are: and, or, not, ==,!=, >=, >, <=, <, and arithmetic operations
    - Attributes supported are: boolean, string, int, long, float, double, object
    - Expressions can be implemented as extensions via Siddhi's pluggable architecture
 - Pattern processing
    - Identifies pattern occurrences within streams
    - Supports "every" condition
    - Can temporally process any amount of events from streams with followed by (->) operation
    - Can process two streams at the same time via "and" and "or" conditions
    - Can collect multiple events, with min and max limit, using "count" condition
 - Sequence processing
    - Identifies continuous sequence of events from streams
    - Can process two streams at the same time using "or" conditions on streams 
    - Supports zero to many, one to many, and zero to one condition
 - Event Tables
    - Support for using historical data in real-time processing
    - Can process with the in-memory, RDBMS or Hazelcast(In-memory data grid) based data collection
 - Partitions
    - Supports query partitions based on keywords and value ranges 
    - Multiple queries can be grouped within a partition
 - Scripting 
    - Support JavaScript & Scala Scripts within Siddhi Queries
 - Query Language
    - SQL-like query language 
    - Implemented on Antlr4
    - Supports Query, Stream Definition, and Query Plan compilation

System Requirements
-------------------

1. Minimum memory - 500 MB (based on in-memory data stored for processing)
2. Processor      - Pentium 800MHz or equivalent at minimum
3. Java SE Development Kit 1.7 or higher
4. To build Siddhi CEP from the Source distribution, it is necessary that you have
   JDK 1.7 version or later and Maven 3.0.4 or later

## Questions 
* Questions are welcomed & we are happy to help you integrate Siddhi to your project :)
* Post your questions on http://stackoverflow.com/ tagging ["siddhi"](http://stackoverflow.com/search?q=siddhi)

## How to Contribute
* Please report issues at [Siddhi Github Issue Tacker](https://github.com/wso2/siddhi/issues)
* Send your bug fixes and pull requests to [Siddhi Master Branch](https://github.com/wso2/siddhi) 

## Contact us 
Siddhi developers can be contacted via the mailing lists:
  * Carbon Developers List: dev@wso2.org
  * Carbon Architecture List: architecture@wso2.org

## Support 
Siddhi is supported by [WSO2](http://wso2.com/) by the very same engineers who build the technology. We are committed to ensuring that your deployment is completely supported from evaluation to production.
For more details please contact us by visiting http://wso2.com/support.

#### We welcome your feedback and contribution.

Siddhi CEP Team
