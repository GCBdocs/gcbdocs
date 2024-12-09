# Equations for Key Processes

Here are key equations that explain the underlying processes of KYC, authentication, encryption, risk management, and transaction throughput.\


### &#x20;KYC (Know Your Customer) Risk Scoring:

The risk score $$R_{\text{KYC}}$$ is a weighted sum of risk factors:

$$
R_{\text{KYC}} = w_1 \cdot R_{\text{location}} + w_2 \cdot R_{\text{transaction\_history}} + w_3 \cdot R_{\text{account\_activity}} + \dots
$$

Where:

* $$w_1, w_2, w_3$$  are the weights for each factor.
* $$R_{\text{location}}, R_{\text{transaction\_history}}, R_{\text{account\_activity}}$$ re the risk scores for each category.

### Authentication: Multi-Factor Authentication (MFA):

The probability $$P_{\text{auth}}$$ of successful authentication:

$$
P_{\text{auth}} = P_{\text{password}} \times P_{\text{MFA\_token}} \times P_{\text{biometric}}
$$

Where:

* $$P_{\text{password}}$$ is the probability of correct password entry.
* $$P_{\text{MFA\_token}}$$ is the probability of valid MFA token entry.
* $$P_{\text{biometric}}$$ is the probability of successful biometric verification.

### Encryption: Symmetric Encryption:

Encryption and decryption processes:



$$
C = E(K, P)
$$

$$
P = D(K, C)
$$

Where:

* E  is the encryption algorithm,  D  is the decryption algorithm.
* K  is the symmetric key,  P  is the plaintext, and  C  is the ciphertext.

### Transaction Processing Time (TP):

The time $$T_{\text{processing}}$$ to process a transaction:

$$
T_{\text{processing}} = T_{\text{validation}} + T_{\text{confirmation}}
$$

Where:

* $$T_{\text{validation}}$$ is the time to validate the transaction.
* $$T_{\text{confirmation}}$$ is the time for block confirmation.

&#x20;Risk Management in Trading:

The expected value E  of a trade:

$$
E = P_{\text{gain}} \cdot V_{\text{gain}} - P_{\text{loss}} \cdot V_{\text{loss}}
$$

Where:

* $$P_{\text{gain}}$$ is the probability of gain, $$V_{\text{gain}}$$ is the value of the gain.
* $$P_{\text{loss}}$$ is the probability of loss, $$V_{\text{loss}}$$ is the value of the loss.

### Hash Function for Block Generation:

The hash of a block $$H_{\text{block}}$$ :&#x20;

$$
H_{\text{block}} = H(D_{\text{block}} + N)
$$

Where:

* H  is the hash function (e.g., SHA-256),
* $$D_{\text{block}}$$ is the block data,
* N  is the nonce value.

### Throughput of the System (Transactions Per Second - TPS):

System throughput TPS :&#x20;

$$
TPS = \frac{N_{\text{transactions}}}{T_{\text{time}}}
$$

Where:

* $$N_{\text{transactions}} \$$ is the number of transactions,
* $$T_{\text{time}} \$$ is the time taken to process them.

This document represents a comprehensive guide on how GCB implements its technical architecture, security protocols, and regulatory strategies, including critical equations to explain the system’s key processes.

\
