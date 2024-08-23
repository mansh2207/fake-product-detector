# Product Authentication on Blockchain

## Vision
![Screenshot (22)](https://github.com/user-attachments/assets/7491708a-a54f-4852-803a-7e84dceef40b)


The **ProductAuthentication** smart contract aims to create a decentralized and transparent system for authenticating products. By storing product details such as serial numbers, manufacturers, and timestamps on the blockchain, it helps combat counterfeiting and provides customers with a reliable method for verifying product authenticity. This solution fosters trust between manufacturers and consumers by ensuring that product information is immutable and accessible.

## Flowchart

```plaintext
+-------------------+
|                   |
|  Register Product |
|                   |
+---------+---------+
          |
          v
+---------+---------+
|                   |
|   Product Stored  |  -----> Mapped by Serial Number
|                   |
+---------+---------+
          |
          v
+---------+---------+
|                   |
| Verify Product    |
|                   |
+---------+---------+
```

### Flow:

1. **Register Product**:  
   The manufacturer registers a product by inputting its name, manufacturer, and serial number. This data is securely stored on the blockchain.
   
2. **Product Stored**:  
   The product's information is mapped by its serial number and saved on the blockchain, ensuring immutability.
   
3. **Verify Product**:  
   Users can verify a product by providing its serial number. The contract will return the product’s details if it is found.

## Contract Details

- **Contract Address**: 0x274c8f6ece77259fee9C76C9695926f698b9c1d2
- ![image](https://github.com/user-attachments/assets/2b66a628-bef5-4710-a903-6c316f8155bb)

- **Network**: Educhain

## Installation and Usage

To interact with the **ProductAuthentication** contract, follow these steps:

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/yourusername/product-authentication.git
   ```

2. **Compile and Deploy**:  
   Use Hardhat or Truffle to compile and deploy the contract to your preferred network.

3. **Interact with the Contract**:  
   After deploying, interact with the contract using the address where it was deployed. Use tools like Remix, MetaMask, or your preferred Ethereum wallet.

## Future Scope

- **Ownership Transfer**:  
  Add functionality to transfer product ownership between parties, recording every transfer on the blockchain.
  
- **Supply Chain Tracking**:  
  Extend the contract to track the entire supply chain of a product, ensuring transparency and traceability from manufacturer to consumer.
  
- **Integration with QR Codes**:  
  Generate QR codes for each registered product that link to its blockchain record for quick verification by customers.

- **Enhanced Metadata**:  
  Allow for additional product information, such as warranties, expiry dates, and custom attributes, to be stored on-chain.

## Contact

- **Developer**:Manash Kamal Das 
- **Email**: dasmanashkamal@gmail.com
- **GitHub**: [https://github.com/
- **LinkedIn**: [Your LinkedIn Profile URL]  
- **Twitter**: [@yourtwitterhandle](https://twitter.com/yourtwitterhandle)

---

Feel free to reach out for any collaboration or inquiries regarding the project!
