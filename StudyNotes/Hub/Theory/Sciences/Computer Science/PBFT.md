---
Aliases: PBFT, Practical Byzantine Fault Tolerance
---

Practical Byzantine Fault Tolerance (PBFT) is a consensus algorithm used in distributed systems to achieve fault tolerance against Byzantine failures. It was introduced by Miguel Castro and Barbara Liskov in 1999.

In a distributed system, where multiple nodes need to agree on a common decision, Byzantine failures refer to arbitrary and malicious behaviors of nodes, such as sending conflicting information or intentionally delaying messages. These failures can disrupt the consensus process and potentially lead to incorrect decisions.

PBFT addresses this problem by providing a solution that allows correct nodes to tolerate up to one-third of the total number of faulty (Byzantine) nodes. It ensures that all correct nodes reach agreement on the order of requests they receive and the output they produce.

The algorithm works by using a leader-based approach, where one node is designated as the primary or leader for a specific round. The primary proposes an order for incoming requests, and all other nodes replicate and validate this proposal. Once enough replicas agree on the proposed order, it becomes the decided order for that round.

PBFT ensures safety (agreement on decisions) by requiring two conditions: validity and agreement. Validity means that if the primary is correct and receives a valid request from a client, then all correct replicas will agree on its execution. Agreement means that if any correct replica decides on an order for a request, then all other correct replicas must also decide on the same order.

To achieve liveness (progress in making decisions), PBFT uses timeouts and view changes. Timeouts are used to ensure progress even if some messages are delayed or lost. If a replica suspects that the primary is faulty due to timeout or other reasons, it initiates a view change process where another replica takes over as the new primary for subsequent rounds.

While PBFT provides practical Byzantine fault tolerance, it has some limitations including high message complexity (O(n^2)) and dependence on synchronous networks. However, it has been widely used and studied in various distributed systems, particularly in the blockchain field where consensus is crucial for maintaining the integrity of a decentralized ledger.