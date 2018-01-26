# Test Report - 2018-01-27 00:49

- tests  : **358 passed**. **42 failed**
- branch name : **[master](https://github.com/apache/incubator-skywalking/tree/master)**
- commit id : **[8c859d1ce880cbf65bd46e8eaaf1adb1d1a1cd7f](https://github.com/apache/incubator-skywalking/commit/8c859d1ce880cbf65bd46e8eaaf1adb1d1a1cd7f)**
- cases branch: **[master](https://github.com/SkywalkingTest/skywalking-autotest-scenarios/tree/master)**
- cases commit id: **[4128aa83f282494e566898cdd4d71d79e54b26df](https://github.com/SkywalkingTest/skywalking-autotest-scenarios/commit/4128aa83f282494e566898cdd4d71d79e54b26df)**

## Cases List

| Case description | Status | Cases|
|:-----|:-----:|:-----:|
|Jedis| **21 passed. 3 failed**| [click me](#jedis) |
|Strut2_H2| **46 passed. 3 failed**| [click me](#strut2_h2) |
|Spring-RestTemplate_Annotation_RestAnnotation| **70 passed. 9 failed**| [click me](#spring-resttemplate_annotation_restannotation) |
|Mysql| **47 passed. 1 failed**| [click me](#mysql) |
|Feign| **8 passed. 0 failed**| [click me](#feign) |
|RocketMQ| **0 passed. 3 failed**| [click me](#rocketmq) |
|PostgreSQL| **49 passed. 6 failed**| [click me](#postgresql) |
|JettyClient_JettyServer| **60 passed. 10 failed**| [click me](#jettyclient_jettyserver) |
|Httpasyncclient| **7 passed. 0 failed**| [click me](#httpasyncclient) |
|Httpclient| **14 passed. 0 failed**| [click me](#httpclient) |
|OKHttp3| **16 passed. 1 failed**| [click me](#okhttp3) |
|Motan| **8 passed. 0 failed**| [click me](#motan) |
|MongoDB| **5 passed. 2 failed**| [click me](#mongodb) |
|Kafka| **0 passed. 4 failed**| [click me](#kafka) |
|Dubbo| **6 passed. 0 failed**| [click me](#dubbo) |
|Dubbox| **1 passed. 0 failed**| [click me](#dubbox) |

## Jedis

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 2.8.1  | :heavy_check_mark:||
| 2.8.0  | :heavy_check_mark:||
| 2.5.0  | :heavy_check_mark:||
| 2.6.2  | :heavy_check_mark:||
| 2.7.2  | :heavy_check_mark:||
| 2.5.2  | :heavy_check_mark:||
| 2.6.3  | :heavy_check_mark:||
| 2.7.3  | :heavy_check_mark:||
| 2.6.0  | :heavy_check_mark:||
| 2.4.2  | :heavy_check_mark:||
| 2.6.1  | |:heavy_check_mark:|
| 2.9.0  | :heavy_check_mark:||
| 2.4.1  | :heavy_check_mark:||
| 2.5.1  | :heavy_check_mark:||
| 2.4.0  | :heavy_check_mark:||
| 2.8.2  | :heavy_check_mark:||
| 2.7.1  | :heavy_check_mark:||
| 2.7.0  | :heavy_check_mark:||

|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 2.1.0  | |:heavy_check_mark:|
| 2.2.1  | :heavy_check_mark:||
| 2.2.0  | :heavy_check_mark:||
| 2.3.0  | :heavy_check_mark:||
| 2.0.0  | |:heavy_check_mark:|
| 2.3.1  | :heavy_check_mark:||

## Strut2_H2

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| H2-1.3.149_Struts2-2.3.1.2  | |:heavy_check_mark:|
| H2-1.3.154_Struts2-2.5.12  | :heavy_check_mark:||
| H2-1.3.153_Struts2-2.5.13  | :heavy_check_mark:||
| H2-1.3.161_Struts2-2.5  | :heavy_check_mark:||
| H2-1.3.160_Struts2-2.5.1  | :heavy_check_mark:||
| H2-1.3.148_Struts2-2.3.1.2  | |:heavy_check_mark:|
| H2-1.3.159_Struts2-2.5.2  | :heavy_check_mark:||
| H2-1.3.151_Struts2-2.5.14.1  | :heavy_check_mark:||
| H2-1.3.155_Struts2-2.5.10.1  | :heavy_check_mark:||
| H2-1.3.157_Struts2-2.5.8  | :heavy_check_mark:||
| H2-1.3.152_Struts2-2.5.14  | :heavy_check_mark:||
| H2-1.3.150_Struts2-2.3.1.2  | |:heavy_check_mark:|
| H2-1.3.156_Struts2-2.5.10  | :heavy_check_mark:||
| H2-1.3.158_Struts2-2.5.5  | :heavy_check_mark:||

|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| H2-1.3.163_Struts2-2.3.33  | :heavy_check_mark:||
| H2-1.4.179_Struts2-2.3.16.1  | :heavy_check_mark:||
| H2-1.4.185_Struts2-2.3.14.3  | :heavy_check_mark:||
| H2-1.4.180_Struts2-2.3.16  | :heavy_check_mark:||
| H2-1.3.175_Struts2-2.3.20.1  | :heavy_check_mark:||
| H2-1.3.171_Struts2-2.3.24.3  | :heavy_check_mark:||
| H2-1.4.187_Struts2-2.3.14.1  | :heavy_check_mark:||
| H2-1.4.192_Struts2-2.3.4.1  | :heavy_check_mark:||
| H2-1.3.167_Struts2-2.3.29  | :heavy_check_mark:||
| H2-1.4.181_Struts2-2.3.15.3  | :heavy_check_mark:||
| H2-1.3.173_Struts2-2.3.24  | :heavy_check_mark:||
| H2-1.3.176_Struts2-2.3.20  | :heavy_check_mark:||
| H2-1.4.190_Struts2-2.3.8  | :heavy_check_mark:||
| H2-1.4.186_Struts2-2.3.14.2  | :heavy_check_mark:||
| H2-1.3.168_Struts2-2.3.1.2  | :heavy_check_mark:||
| H2-1.3.165_Struts2-2.3.31  | :heavy_check_mark:||
| H2-1.3.162_Struts2-2.3.34  | :heavy_check_mark:||
| H2-1.3.166_Struts2-2.3.30  | :heavy_check_mark:||
| H2-1.4.178_Struts2-2.3.16.2  | :heavy_check_mark:||
| H2-1.3.170_Struts2-2.3.28  | :heavy_check_mark:||
| H2-1.4.188_Struts2-2.3.14  | :heavy_check_mark:||
| H2-1.4.183_Struts2-2.3.15.1  | :heavy_check_mark:||
| H2-1.4.196_Struts2-2.3.1  | :heavy_check_mark:||
| H2-1.4.195_Struts2-2.3.1.1  | :heavy_check_mark:||
| H2-1.3.174_Struts2-2.3.20.3  | :heavy_check_mark:||
| H2-1.4.177_Struts2-2.3.16.3  | :heavy_check_mark:||
| H2-1.4.191_Struts2-2.3.7  | :heavy_check_mark:||
| H2-1.4.194_Struts2-2.3.3  | :heavy_check_mark:||
| H2-1.3.169_Struts2-2.3.28.1  | :heavy_check_mark:||
| H2-1.4.189_Struts2-2.3.12  | :heavy_check_mark:||
| H2-1.3.164_Struts2-2.3.32  | :heavy_check_mark:||
| H2-1.3.172_Struts2-2.3.24.1  | :heavy_check_mark:||
| H2-1.4.184_Struts2-2.3.15  | :heavy_check_mark:||
| H2-1.4.182_Struts2-2.3.15.2  | :heavy_check_mark:||
| H2-1.4.193_Struts2-2.3.4  | :heavy_check_mark:||

## Spring-RestTemplate_Annotation_RestAnnotation

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| Spring-RestTemplate-3.2.3_Annotation-3.2.3_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.1.7_Annotation-4.1.7_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.1.1_Annotation-4.1.1_RestAnnotation-4.3.5  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.6_Annotation-3.0.6_RestAnnotation-4.3.0  | |:heavy_check_mark:|
| Spring-RestTemplate-3.2.16_Annotation-3.2.16_RestAnnotation-4.3.9  | :heavy_check_mark:||
| Spring-RestTemplate-4.1.4_Annotation-4.1.4_RestAnnotation-4.3.3  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.3_Annotation-3.0.3_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.5_Annotation-4.3.5_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.8_Annotation-4.0.8_RestAnnotation-4.3.8  | :heavy_check_mark:||
| Spring-RestTemplate-5.0.1_Annotation-5.0.1_RestAnnotation-4.3.13  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.3_Annotation-3.1.3_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.4_Annotation-3.2.4_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.13_Annotation-4.3.13_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.1.0_Annotation-4.1.0_RestAnnotation-4.3.6  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.1_Annotation-3.1.1_RestAnnotation-4.3.0  | |:heavy_check_mark:|
| Spring-RestTemplate-3.2.7_Annotation-3.2.7_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.3_Annotation-4.0.3_RestAnnotation-4.3.13  | |:heavy_check_mark:|
| Spring-RestTemplate-4.2.4_Annotation-4.2.4_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-5.0.2_Annotation-5.0.2_RestAnnotation-5.0.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.6_Annotation-3.2.6_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.3_Annotation-4.3.3_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.2.8_Annotation-4.2.8_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.1.2_Annotation-4.1.2_RestAnnotation-4.3.4  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.0_Annotation-3.2.0_RestAnnotation-4.3.0  | |:heavy_check_mark:|
| Spring-RestTemplate-4.2.2_Annotation-4.2.2_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.10_Annotation-3.2.10_RestAnnotation-4.3.3  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.9_Annotation-4.3.9_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.12_Annotation-3.2.12_RestAnnotation-4.3.5  | :heavy_check_mark:||
| Spring-RestTemplate-4.1.9_Annotation-4.1.9_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.13_Annotation-3.2.13_RestAnnotation-4.3.6  | :heavy_check_mark:||
| Spring-RestTemplate-4.1.6_Annotation-4.1.6_RestAnnotation-4.3.1  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.4_Annotation-4.3.4_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.2.6_Annotation-4.2.6_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.1_Annotation-4.0.1_RestAnnotation-5.0.1  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.11_Annotation-3.2.11_RestAnnotation-4.3.4  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.6_Annotation-4.0.6_RestAnnotation-4.3.10  | :heavy_check_mark:||
| Spring-RestTemplate-4.2.3_Annotation-4.2.3_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.9_Annotation-4.0.9_RestAnnotation-4.3.7  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.2_Annotation-3.0.1_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.5_Annotation-3.2.5_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.2.5_Annotation-4.2.5_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.0_Annotation-4.0.0_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.0_Annotation-4.0.0_RestAnnotation-5.0.2  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.2_Annotation-3.1.2_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.2_Annotation-4.0.2_RestAnnotation-5.0.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.2.7_Annotation-4.2.7_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.0_Annotation-3.1.0_RestAnnotation-4.3.0  | |:heavy_check_mark:|
| Spring-RestTemplate-4.3.12_Annotation-4.3.12_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.14_Annotation-3.2.14_RestAnnotation-4.3.7  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.8_Annotation-3.2.8_RestAnnotation-4.3.1  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.7_Annotation-3.0.7_RestAnnotation-4.3.0  | |:heavy_check_mark:|
| Spring-RestTemplate-3.1.4_Annotation-3.0.4_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.15_Annotation-3.2.15_RestAnnotation-4.3.8  | :heavy_check_mark:||
| Spring-RestTemplate-4.2.0_Annotation-4.2.0_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.9_Annotation-3.2.9_RestAnnotation-4.3.2  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.8_Annotation-4.3.8_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.1_Annotation-4.3.1_RestAnnotation-5.0.2  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.0_Annotation-4.3.0_RestAnnotation-5.0.1  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.7_Annotation-4.3.7_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.2_Annotation-3.2.2_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.1_Annotation-3.2.1_RestAnnotation-4.3.0  | |:heavy_check_mark:|
| Spring-RestTemplate-5.0.0_Annotation-5.0.0_RestAnnotation-4.3.12  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.4_Annotation-3.1.4_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.2_Annotation-3.0.2_RestAnnotation-4.3.0  | |:heavy_check_mark:|
| Spring-RestTemplate-4.1.8_Annotation-4.1.8_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.2.9_Annotation-4.2.9_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.18_Annotation-3.2.18_RestAnnotation-4.3.11  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.5_Annotation-4.0.5_RestAnnotation-4.3.11  | :heavy_check_mark:||
| Spring-RestTemplate-3.2.17_Annotation-3.2.17_RestAnnotation-4.3.10  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.2_Annotation-4.3.2_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.5_Annotation-3.0.5_RestAnnotation-4.3.0  | |:heavy_check_mark:|
| Spring-RestTemplate-4.3.10_Annotation-4.3.10_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.11_Annotation-4.3.11_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.4_Annotation-4.0.4_RestAnnotation-4.3.12  | :heavy_check_mark:||
| Spring-RestTemplate-4.2.1_Annotation-4.2.1_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.1.5_Annotation-4.1.5_RestAnnotation-4.3.2  | :heavy_check_mark:||
| Spring-RestTemplate-3.1.2_Annotation-3.0.0_RestAnnotation-4.3.0  | :heavy_check_mark:||
| Spring-RestTemplate-4.0.7_Annotation-4.0.7_RestAnnotation-4.3.9  | :heavy_check_mark:||
| Spring-RestTemplate-4.3.6_Annotation-4.3.6_RestAnnotation-4.3.0  | :heavy_check_mark:||

## Mysql

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 5.1.10  | :heavy_check_mark:||
| 5.1.35  | :heavy_check_mark:||
| 5.1.32  | :heavy_check_mark:||
| 5.1.21  | :heavy_check_mark:||
| 5.1.44  | :heavy_check_mark:||
| 5.1.43  | :heavy_check_mark:||
| 5.1.34  | :heavy_check_mark:||
| 5.1.23  | :heavy_check_mark:||
| 6.0.3  | :heavy_check_mark:||
| 5.1.42  | :heavy_check_mark:||
| 5.1.29  | :heavy_check_mark:||
| 5.1.25  | :heavy_check_mark:||
| 5.1.16  | :heavy_check_mark:||
| 5.1.8  | :heavy_check_mark:||
| 5.1.9  | :heavy_check_mark:||
| 5.1.27  | :heavy_check_mark:||
| 6.0.6  | :heavy_check_mark:||
| 5.1.39  | :heavy_check_mark:||
| 5.1.11  | :heavy_check_mark:||
| 5.1.36  | :heavy_check_mark:||
| 5.1.40  | :heavy_check_mark:||
| 5.1.5  | :heavy_check_mark:||
| 6.0.4  | :heavy_check_mark:||
| 5.1.19  | :heavy_check_mark:||
| 5.1.18  | :heavy_check_mark:||
| 5.1.3  | :heavy_check_mark:||
| 5.1.2  | :heavy_check_mark:||
| 5.1.45  | :heavy_check_mark:||
| 5.1.17  | :heavy_check_mark:||
| 5.1.22  | :heavy_check_mark:||
| 5.1.24  | :heavy_check_mark:||
| 5.1.14  | :heavy_check_mark:||
| 5.1.37  | :heavy_check_mark:||
| 5.1.20  | :heavy_check_mark:||
| 6.0.5  | :heavy_check_mark:||
| 5.1.38  | :heavy_check_mark:||
| 5.1.28  | :heavy_check_mark:||
| 5.1.13  | :heavy_check_mark:||
| 5.1.12  | :heavy_check_mark:||
| 5.1.6  | :heavy_check_mark:||
| 5.1.26  | :heavy_check_mark:||
| 5.1.30  | :heavy_check_mark:||
| 5.1.4  | :heavy_check_mark:||
| 5.1.31  | :heavy_check_mark:||
| 5.1.41  | :heavy_check_mark:||
| 6.0.2  | |:heavy_check_mark:|
| 5.1.33  | :heavy_check_mark:||
| 5.1.15  | :heavy_check_mark:||

## Feign

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 9.3.1  | :heavy_check_mark:||
| 9.4.0  | :heavy_check_mark:||
| 9.5.0  | :heavy_check_mark:||
| 9.2.0  | :heavy_check_mark:||
| 9.1.0  | :heavy_check_mark:||
| 9.5.1  | :heavy_check_mark:||
| 9.3.0  | :heavy_check_mark:||
| 9.0.0  | :heavy_check_mark:||

## RocketMQ

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 4.0.0-incubating  | |:heavy_check_mark:|
| 4.1.0-incubating  | |:heavy_check_mark:|
| 4.2.0  | |:heavy_check_mark:|

## PostgreSQL

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 9.4.1210.jre6  | |:heavy_check_mark:|
| 9.4.1210  | :heavy_check_mark:||
| 9.4.1211.jre7  | |:heavy_check_mark:|
| 9.4.1212.jre7  | |:heavy_check_mark:|
| 9.4.1208  | :heavy_check_mark:||
| 9.4.1209.jre7  | :heavy_check_mark:||
| 9.4.1209.jre6  | :heavy_check_mark:||
| 9.4.1209  | :heavy_check_mark:||
| 9.4.1212  | :heavy_check_mark:||
| 9.4.1208.jre7  | :heavy_check_mark:||
| 9.4.1207  | :heavy_check_mark:||
| 9.4.1211  | :heavy_check_mark:||
| 9.4.1212.jre6  | |:heavy_check_mark:|
| 9.4.1208.jre6  | :heavy_check_mark:||
| 9.4.1210.jre7  | |:heavy_check_mark:|
| 9.4.1211.jre6  | |:heavy_check_mark:|

|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 9.4-1201-jdbc4  | :heavy_check_mark:||
| 9.3-1101-jdbc41  | :heavy_check_mark:||
| 9.4-1206-jdbc42  | :heavy_check_mark:||
| 9.4-1202-jdbc42  | :heavy_check_mark:||
| 9.3-1100-jdbc3  | :heavy_check_mark:||
| 9.2-1002-jdbc4  | :heavy_check_mark:||
| 9.3-1103-jdbc41  | :heavy_check_mark:||
| 9.3-1102-jdbc4  | :heavy_check_mark:||
| 9.2-1003-jdbc3  | :heavy_check_mark:||
| 9.4-1202-jdbc41  | :heavy_check_mark:||
| 9.4-1202-jdbc4  | :heavy_check_mark:||
| 9.4-1205-jdbc42  | :heavy_check_mark:||
| 9.3-1100-jdbc4  | :heavy_check_mark:||
| 9.4-1203-jdbc42  | :heavy_check_mark:||
| 9.2-1004-jdbc3  | :heavy_check_mark:||
| 9.4-1203-jdbc41  | :heavy_check_mark:||
| 9.3-1104-jdbc41  | :heavy_check_mark:||
| 9.4-1204-jdbc4  | :heavy_check_mark:||
| 9.4-1206-jdbc41  | :heavy_check_mark:||
| 9.4-1200-jdbc4  | :heavy_check_mark:||
| 9.3-1101-jdbc3  | :heavy_check_mark:||
| 9.3-1100-jdbc41  | :heavy_check_mark:||
| 9.2-1004-jdbc41  | :heavy_check_mark:||
| 9.4-1201-jdbc41  | :heavy_check_mark:||
| 9.3-1103-jdbc3  | :heavy_check_mark:||
| 9.4-1206-jdbc4  | :heavy_check_mark:||
| 9.2-1004-jdbc4  | :heavy_check_mark:||
| 9.3-1101-jdbc4  | :heavy_check_mark:||
| 9.4-1200-jdbc41  | :heavy_check_mark:||
| 9.4-1203-jdbc4  | :heavy_check_mark:||
| 9.3-1104-jdbc4  | :heavy_check_mark:||
| 9.4-1204-jdbc41  | :heavy_check_mark:||
| 9.3-1102-jdbc3  | :heavy_check_mark:||
| 9.3-1102-jdbc41  | :heavy_check_mark:||
| 9.4-1205-jdbc41  | :heavy_check_mark:||
| 9.4-1205-jdbc4  | :heavy_check_mark:||
| 9.2-1003-jdbc4  | :heavy_check_mark:||
| 9.4-1204-jdbc42  | :heavy_check_mark:||
| 9.3-1103-jdbc4  | :heavy_check_mark:||

## JettyClient_JettyServer

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 9.1.6.v20160112  | :heavy_check_mark:||
| 9.2.0.v20140526  | :heavy_check_mark:||
| 9.0.5.v20130815  | |:heavy_check_mark:|
| 9.3.7.v20160115  | :heavy_check_mark:||
| 9.3.19.v20170502  | :heavy_check_mark:||
| 9.4.8.v20171121  | :heavy_check_mark:||
| 9.4.7.v20170914  | :heavy_check_mark:||
| 9.2.9.v20150224  | :heavy_check_mark:||
| 9.3.18.v20170406  | :heavy_check_mark:||
| 9.1.5.v20140505  | :heavy_check_mark:||
| 9.2.8.v20150217  | :heavy_check_mark:||
| 9.4.4.v20170414  | :heavy_check_mark:||
| 9.2.10.v2015031  | |:heavy_check_mark:|
| 9.0.3.v20130506  | |:heavy_check_mark:|
| 9.4.2.v20170220  | :heavy_check_mark:||
| 9.0.2.v20130417  | |:heavy_check_mark:|
| 9.3.15.v20161220  | :heavy_check_mark:||
| 9.1.0.v20131115  | :heavy_check_mark:||
| 9.3.3.v20150827  | :heavy_check_mark:||
| 9.3.17.v20170317  | :heavy_check_mark:||
| 9.3.22.v20171030  | :heavy_check_mark:||
| 9.2.4.v20141103  | :heavy_check_mark:||
| 9.0.0.v20130308  | |:heavy_check_mark:|
| 9.3.10.v20160621  | :heavy_check_mark:||
| 9.0.6.v20130930  | |:heavy_check_mark:|
| 9.4.6.v20170531  | :heavy_check_mark:||
| 9.4.0.v20161208  | :heavy_check_mark:||
| 9.1.2.v20140210  | :heavy_check_mark:||
| 9.3.11.v20160721  | :heavy_check_mark:||
| 9.3.0.v20150612  | :heavy_check_mark:||
| 9.2.11.v2015052  | |:heavy_check_mark:|
| 9.2.18.v20160721  | :heavy_check_mark:||
| 9.2.12.v20150709  | :heavy_check_mark:||
| 9.4.5.v20170502  | :heavy_check_mark:||
| 9.2.15.v20160210  | :heavy_check_mark:||
| 9.2.2.v20140723  | :heavy_check_mark:||
| 9.3.1.v20150714  | :heavy_check_mark:||
| 9.4.1.v20170120  | :heavy_check_mark:||
| 9.2.7.v20150116  | :heavy_check_mark:||
| 9.3.14.v20161028  | :heavy_check_mark:||
| 9.2.23.v20171218  | :heavy_check_mark:||
| 9.3.8.v2016031  | |:heavy_check_mark:|
| 9.3.4.v20151007  | :heavy_check_mark:||
| 9.0.1.v20130408  | |:heavy_check_mark:|
| 9.2.21.v20170120  | :heavy_check_mark:||
| 9.2.5.v20141112  | :heavy_check_mark:||
| 9.3.9.v20160517  | :heavy_check_mark:||
| 9.2.3.v20140905  | :heavy_check_mark:||
| 9.3.12.v20160915  | :heavy_check_mark:||
| 9.3.2.v20150730  | :heavy_check_mark:||
| 9.0.4.v20130625  | |:heavy_check_mark:|
| 9.1.1.v20140108  | :heavy_check_mark:||
| 9.2.13.v20150730  | :heavy_check_mark:||
| 9.2.22.v20170606  | :heavy_check_mark:||
| 9.2.16.v20160414  | :heavy_check_mark:||
| 9.3.6.v20151106  | :heavy_check_mark:||
| 9.1.4.v20140401  | :heavy_check_mark:||
| 9.3.20.v20170531  | :heavy_check_mark:||
| 9.3.5.v20151012  | :heavy_check_mark:||
| 9.2.14.v20151106  | :heavy_check_mark:||
| 9.1.3.v20140225  | :heavy_check_mark:||
| 9.3.13.v20161014  | :heavy_check_mark:||
| 9.3.21.v20170918  | :heavy_check_mark:||
| 9.2.17.v20160517  | :heavy_check_mark:||
| 9.2.20.v20161216  | :heavy_check_mark:||
| 9.3.16.v20170120  | :heavy_check_mark:||
| 9.2.1.v20140609  | :heavy_check_mark:||
| 9.2.19.v20160908  | :heavy_check_mark:||
| 9.2.6.v20141205  | :heavy_check_mark:||
| 9.4.3.v20170317  | :heavy_check_mark:||

## Httpasyncclient

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 4.0  | :heavy_check_mark:||
| 4.0.1  | :heavy_check_mark:||
| 4.1.3  | :heavy_check_mark:||
| 4.0.2  | :heavy_check_mark:||
| 4.1  | :heavy_check_mark:||
| 4.1.2  | :heavy_check_mark:||
| 4.1.1  | :heavy_check_mark:||

## Httpclient

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 4.3.4  | :heavy_check_mark:||
| 4.3.6  | :heavy_check_mark:||
| 4.5.1  | :heavy_check_mark:||
| 4.3  | :heavy_check_mark:||
| 4.4.1  | :heavy_check_mark:||
| 4.5  | :heavy_check_mark:||
| 4.3.3  | :heavy_check_mark:||
| 4.3.5  | :heavy_check_mark:||
| 4.5.3  | :heavy_check_mark:||
| 4.3.2  | :heavy_check_mark:||
| 4.5.4  | :heavy_check_mark:||
| 4.5.2  | :heavy_check_mark:||
| 4.4  | :heavy_check_mark:||
| 4.3.1  | :heavy_check_mark:||

## OKHttp3

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 3.4.1  | :heavy_check_mark:||
| 3.0.1  | :heavy_check_mark:||
| 3.3.1  | :heavy_check_mark:||
| 3.6.0  | :heavy_check_mark:||
| 3.1.0  | :heavy_check_mark:||
| 3.9.0  | :heavy_check_mark:||
| 3.1.2  | :heavy_check_mark:||
| 3.4.2  | :heavy_check_mark:||
| 3.5.0  | :heavy_check_mark:||
| 3.8.0  | :heavy_check_mark:||
| 3.7.0  | :heavy_check_mark:||
| 3.2.0  | :heavy_check_mark:||
| 3.8.1  | :heavy_check_mark:||
| 3.1.1  | |:heavy_check_mark:|
| 3.3.0  | :heavy_check_mark:||
| 3.4.0  | :heavy_check_mark:||
| 3.0.0  | :heavy_check_mark:||

## Motan

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 0.2.0  | :heavy_check_mark:||
| 0.2.1  | :heavy_check_mark:||
| 1.0.0  | :heavy_check_mark:||
| 0.2.2  | :heavy_check_mark:||
| 1.1.0  | :heavy_check_mark:||
| 0.3.0  | :heavy_check_mark:||
| 0.2.3  | :heavy_check_mark:||
| 0.3.1  | :heavy_check_mark:||

## MongoDB

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 3.4.1  | :heavy_check_mark:||
| 3.6.0  | |:heavy_check_mark:|
| 3.4.0  | :heavy_check_mark:||
| 3.4.2  | :heavy_check_mark:||
| 3.5.0  | :heavy_check_mark:||
| 3.6.1  | |:heavy_check_mark:|
| 3.4.3  | :heavy_check_mark:||

## Kafka

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 0.11.0.0  | |:heavy_check_mark:|
| 1.0.0  | |:heavy_check_mark:|
| 0.11.0.1  | |:heavy_check_mark:|
| 0.11.0.2  | |:heavy_check_mark:|

## Dubbo

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 2.6.0  | :heavy_check_mark:||
| 2.5.8  | :heavy_check_mark:||
| 2.5.6  | :heavy_check_mark:||
| 2.5.5  | :heavy_check_mark:||
| 2.5.4  | :heavy_check_mark:||
| 2.5.7  | :heavy_check_mark:||

## Dubbox

### 
|  Version     | Passed | Failed|
|:------------- |:-------:|:-----:|
| 2.8.4  | :heavy_check_mark:||

