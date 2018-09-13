# idbook-BA-VRF
Byzantine Agreement Consensus

IDBook applies consensus mechanism based on Verifiable Random Function (VRF) Byzantine Agreement (BA) algorithm, which can randomly select a few institutions as notarization nodes and confirm the priority of them.

Consensus will be implemented every minute, and a number of institutional nodes will be randomly selected as notarization nodes for each consensus. The notarization nodes have the right to send the notarization unit, and the notarization unit must meet the parent-child reference rules in the DAG consensus. After the notarization unit sent by notarization node becomes the stable unit of the main chain, the notarization node can get the notarial reward. When the transaction is active, new units are generated continuously, then notarized nodes can get notarial rewards in time. When transaction is not active, the nodes which have sent notarization units which become stable units of the main chain get notarization rewards; and the nodes that send no notarial units will not. 

