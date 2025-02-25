# Kafka-Tools
Collection of producers, consumers, and basic tools for IHR kafka cluster

### The following tools are implemented inside the Kafka-Toolbox
1. [Traceroute Producer](#traceroute-producer)
2. [Historic BGP Data Producer](#bgp-data-producer)
3. [Anomaly Detector](#anomaly-detector)
4. [PeeringDB](#peeringdb)

## About Kafka
<p><i>Kafka is a distributed streaming platform.</i> It's kind of a device or machine which make it easier to input continuous data and feed to the users.</p>
<div align="center">
<img src="https://github.com/user-attachments/assets/5da408e2-757b-457d-9158-2760dd4b8c0a" height="370px">
</div>
<br>
<p>Kafka receive different types of live data and then that is actually distributed into different servers (called brokers). This part where data is stored in different servers is what kafka does. This data can then be forwarded by different to different users from those distributed servers.</p>

### Architecture
<b>Kafka's architecture is designed for high-throughput, fault-tolerant, real-time data streaming. Below are some basic terminologies of Kafka which you will find in our source codes :</b>
<ol>
  <li>Topics:
    <ul>
      <li>These are categories or feeds to which records are published.</li>
      <li>Think of them as named streams of records.</li>
    </ul>
  </li>
  <li>Partitions :
    <ul>
      <li>Topics are divided into partitions.</li>
      <li>Partitions are ordered, immutable sequences of records. They act as queue on works on priviple of FIFO.</li>
    </ul>
  </li>
  <li>
    Producer: Who produces and send the messages to one or more queues
  </li>
  <li>
    Consumer: Who is subscribed to one or more queues and receives their messages when published.
  </li>
</ol>

# Text below is being added
## Setting Up Kafka
## Traceroute Producer
<ol>
  <li>Fetch Traceroute data</li>
  <li></li>
</ol>

## BGP Data Producer

## Anomaly Detector

## PeeringDB
#### It is a database of interconnection of networks at IXPs (Internet Exchange Point) and data centers
