## To run the Docker Image:

`docker run -p 5000:5000 prachetshah/ethanalytics`

## Introduction:

- In recent years, the use of digital currencies has grown exponentially, leading to an explosion in transaction volumes on blockchain networks

- Big data engineering techniques can play a crucial role in managing and analyzing blockchain data and gaining insights on them.

- These techniques can help in processing and analyzing large volumes of data

## Aim:

- To perform real-time analysis of ethereum transactions while also reducing the cost to store the massive data in a database by storing only the analytics instead of all the data.

- Taking in Big Data and creating analysis out of the real-time data stream.

- Making cumulative analytics data and thus reducing the storage space taken up by the data.

## Data Pipeline Architecture:

![DataPipeline.png](https://github.com/fibre-ether/bde-miniproject/blob/master/DataPipeline.png)

- Service 1 (Data Streaming and Analysis)
  ![Service1](https://github.com/fibre-ether/bde-miniproject/blob/master/Service1.png)

- Service 2 (Real Time Data Retreival and Analysis)
  ![Service2](https://github.com/fibre-ether/bde-miniproject/blob/master/Service2.png)

## Result TestBeds

- **Volume**: Amount of data is high since it is real-time occurring ethereum transactions.

- **Velocity**: Speed of Data Generation is high as transactions are happening continuously over the ethereum blockchain.

- **Variety**: Data coming is in unstructured format which is then processed using Spark.

- **Availability**: The analysis of data was stored in an SQL database and was available for real-time retrieval and display on the Flask frontend.

## Conclusion

- This project presented an analysis of Ethereum transaction data using PySpark and various data visualization tools which is deployed as a docker container for running the image locally on any device.

- The data analysis revealed several interesting findings, including:

  1. the most commonly used transaction methods
  2. the busiest times of the day for transactions,
  3. the top senders in terms of transaction volume,
  4. the total value of Ethereum transferred over the entire time period.

- Overall, this project provides a valuable contribution to the growing field of blockchain analytics.
