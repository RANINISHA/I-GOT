<h1 align="center"> Kubernetes / Compute Resources / Workload Dashboard in grafana <h1>
 
   <h2 align="center"> WHAT IS GRAFANA </h2>
 
 <p align="center">  Grafana is a widely used open source visualization tool with a strong community support. It is used in every other organization mostly for live Dashboard and monitoring purposes. It supports a huge number of databases including InfluxDB, MySQL, Graphite & Elasticsearch. It also gives a huge option for plugin which can help to fulfill your requirements and customize your dashboard.</p >
  
 <h2 align="center"> WHAT IS kUBERNATES </h2>
 
 <p align="center"> Kubernetes, as a platform, is a comprehensive set of tools for orchestrating containers at scale. It consists of a modular architecture of specific components with a defined purpose. For example, the scheduler finds the ideal match for a particular pod and the kube-proxy manages the networking between the nodes and the master. </p >
  
 <h2 align="center"> GRAFANA HOME PAGE </h2>
 
 <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/Screenshot%20from%202021-09-08%2012-26-07.png"> </p>
  
 <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/Screenshot%20from%202021-09-08%2012-26-48.png?raw=true"> </p>
 
   <h2 align="center"> ABOUT THE DASHBOARD </h2>

 
 <p align="center">  This dashboard shows you all the same panels for CPU, memory and network, narrowed down to a single workload view.
 Select a namespace then a workload, and the panels will show metrics for all pods that correspond to that workload.</p >
  
 <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/Screenshot%20from%202021-09-08%2012-27-55.png?raw=true"> </p>
 
 <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/Screenshot%20from%202021-09-08%2012-48-34.png?raw=true"></p>



 ------- 
   
  
  <h2 align="center"> Metrics List </h2>
   <details close="close"> 
    <summary><b> Click here</b> :point_left:</summary>

  <ul>
  <li> cpu usage: it shows cpu  utilization</li>
      <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/cpu_usage.png"> </p>

   <li>cpu quota : in this matrics we have cpu request and cpu limit </li>
      
   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/cpu_quota.png"> </p>
   
   <li> Memory usage : It shows memory utilization </li>

   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/memory_usage.png"> </p>

   
  <li> Memory quota : I this matrics we have memory request and memory limit</li>
      
  <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/memory_quota.png"> </p>

  <li> current network usage :Network utilization is the proportion of the current network traffic to the maximum amount of traffic that can be handled. It indicates the bandwidth consumption in the network. While high network traffic means that the network is overloaded, low network traffic means that the network is not busy.</li>
      
   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/Network_usage.png"> </p>

   <li> Recieved bandwidth: </li>
      
   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/rb.png"> </p>

   <li>transmitted bandwidth : in this matrics we have cpu request and cpu limit </li>
      
   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/Tb.png"> </p>

  <li> Average Container Bandwidth Received by pod : I this matrics we have memory request and memory limit</li>
      
   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/acbbp.png"> </p>

  <li> Average Container Bandwidth Transmitted by pod :</li>
      
   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/acbbpt.png"> </p>

   <li> Rate of Received Packets: </li>
      
   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/rorp.png"> </p>

   <li> Rate of Transmitted Packets : </li>
      
   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/rotp.png"> </p>
   
   <li> Rate of Received Packets Dropped: </li>
      
   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/rorpd.png"> </p>

   <li> Rate of Transmitted Packets Dropped : </li>
      
   <p align="center" > <img src="https://github.com/RANINISHA/RANINISHA/blob/main/rotpd.png"> </p>

   
   </ul>
  </details>
  
 
