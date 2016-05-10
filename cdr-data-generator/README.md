# Telecom Call Data/Detail Record Generator ( CDR Generator )
Utility to generate Telecom Call Detail/Data Records Generator.

## How it works
It simply generates a random value for each of the call detail record features. There are no latitudes and longitudes values. Features are listed in the 'data format' section. The program generates the values and prints it in the console.

## To Build

Clone the repo. and execute following command

```mvn clean install```

## To generate records

Run as Java Application

## Data Format
id, calling_number, called_number, start_time, end_time, call_type, charge, call_result

See [wikipedia article](https://en.wikipedia.org/wiki/Call_detail_record) for more details.

## Sample Data

```
7693f957-179f-4d01-84e7-85faf6d7de13|9917618284|5084342972|2016-02-19T18:57:31.082+05:30|2016-02-19T18:57:31.082+05:30|SMS|0.71523774|ANSWERED
```
