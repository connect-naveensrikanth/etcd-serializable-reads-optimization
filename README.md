# Optimizing Read Performance in Distributed Key-Value Stores Using Serializable Consistency
* Author: Naveen Srikanth Pasupuleti
* Published In : International Journal of Innovative Research and Creative Technology (IJIRCT)
* Publication Date: June 2024
* E-ISSN: 2454-5988
* Impact Factor: 9.142
* Link: [Read the paper](https://www.ijirct.org/viewPaper.php?paperId=2505045)

**Abstract**:\
ETCD is a distributed key-value store that ensures high availability and strong consistency using the Raft consensus protocol. It supports two types of read operations: linearizable reads, which guarantee the most up-to-date data but with higher latency, and serializable reads, which offer lower latency with slightly stale data. This paper focuses on addressing performance bottlenecks caused by linearizable reads by leveraging serializable read operations. By balancing consistency and efficiency, the proposed approach enhances ETCD’s scalability and responsiveness—making it more adaptable to the evolving needs of distributed systems.

**Queries per second:**\
  A metric used to measure the number of requests a system receives and processes per second.

**Key Contributions:** 
* **Algorithm Development:** \
  Designed and optimized a Serializable Read methodology targeting higher query-per-second (QPS) processing rates.
* **Performance Comparison:** \
  Conducted benchmarking between linearizable and serializable read operations to measure QPS improvements.
* **Research Leadership:**
  Led the research and technical implementation, with a focus on advancing distributed databases through algorithmic innovation.

**Relevance & Real-World Impact**

* **Read performance optimization:**\
In large-scale deployments, serializable reads improve response time and throughput by bypassing the coordination overhead required by linearizable reads.

* **Scalability benefits:**\
Serializable reads maintain consistent efficiency as cluster size increases, making them well-suited for distributed systems with demanding read-heavy workloads.

* **Academic relevance:**\
Recognized in academic and technical literature for addressing efficiency trade-offs in consistent data retrieval within distributed key-value systems.

* **Educational contribution:**\
Used in instructional content and research contexts to illustrate trade-offs in distributed read models, supporting deeper exploration of system architecture and consistency strategies.

**Experimental Results (Summary)**

| Cluster Size (Nodes) | Linearizable Read QPS | Serializable Read QPS | Improvement (%) |
| ---------------------| --------------------- | --------------------- | ----------------|
| 3                    | 1200                  | 1350                  | 12.5            |
| 5                    | 1050                  | 1250                  | 19.0            |
| 7                    | 900                   | 1100                  | 22.2            |
| 9                    | 800                   | 1050                  | 31.3            |
| 11                   | 700                   |  950                  | 35.7            |

**Citation**
* **Optimizing Read Performance in Distributed Key-Value Stores Using Serializable Consistency**
*   Naveen Srikanth Pasupuleti
*   International Journal of Innovative Research and Creative Technology
*   E-ISSN-2454-5988

**License**
* This research is shared for academic and research purposes. For commercial use, please contact the author.

**Resources**
*  [https://www.ijirct.org](https://www.ijirct.org)

**Author Contact** 
  * LinkedIn: https://www.linkedin.com/in/naveensrikanth | Email: connect.naveensrikanth@gmail.com
