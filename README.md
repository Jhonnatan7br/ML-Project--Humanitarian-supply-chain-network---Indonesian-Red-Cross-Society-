# ML Project  - Pumanitarian supply chain network ( Indonesian Red Cross Society)

This project aims to help the Indonesian Red Cross Society (Palang Merah Indonesia, PMI) to optimize its operations and improve its performance through data analytics and artificial intelligence.  One of the most important tasks of PMI is the distribution of emergency supplies to victims in affected areas during humanitarian crises. PMI operates a humanitarian supply chain network to receive supplies from suppliers  and donors, store them in its warehouses during normal times, and deliver them to victims during crises.

### Dataset Overview

| Feature                  | Description                                                                                           |
|--------------------------|-------------------------------------------------------------------------------------------------------|
| Sourcing                 | Likely represents the process of sourcing or acquiring goods from suppliers.                          |
| Transport                | Indicates the transportation activities, possibly related to moving goods between different locations.|
| Replenishment            | Represents the replenishment activities, involving restocking inventory to maintain desired levels.   |
| Distribution             | Likely represents the distribution process, involving delivering goods to customers or points of sale.|
| Total demand             | The total demand for the product or products being managed.                                           |
| Initial RW Inv           | Initial inventory level of a certain type (could be raw materials).                                   |
| Initial PW Inv           | Initial inventory level of another type (possibly work-in-progress inventory).                         |
| Initial DW Inv Total     | Initial inventory level of finished goods inventory.                                                  |
| Initial DW Inv 0-19      | Represents the initial inventory levels of finished goods across different time periods or categories.|
| Demand coverage after X hours | Likely represents the percentage of demand that can be covered after certain time intervals.         |
| Readiness (%)            | Represents the readiness of the supply chain or inventory system, indicating how prepared it is to meet demand. |

![Imagen de WhatsApp 2024-04-11 a las 15 50 13_c6d485bf](https://github.com/Jhonnatan7br/ML-Project--Humanitarian-supply-chain-network---Indonesian-Red-Cross-Society-/assets/104907786/c72b64c0-dceb-413d-867a-20a2ddcd3df7)

### Models

![Imagen de WhatsApp 2024-04-11 a las 16 19 22_613f0979](https://github.com/Jhonnatan7br/ML-Project--Humanitarian-supply-chain-network---Indonesian-Red-Cross-Society-/assets/104907786/a325e6d0-77dd-45b3-8db9-a581d446ee44)

>[!NOTE]
>This is a visualization of how could be structured the different models, but it is necessary to get into detail of different parameters to fit it well to obtain the desired target

### Model 1
For predicting the final readiness value in advance
Feedforward neural networks, convolutional neural networks (CNNs), or recurrent neural networks (RNNs) like Long Short-Term Memory (LSTM) networks or Gated Recurrent Units (GRUs). @Andre Kedge & @Mona Laraki 
URL: https://colab.research.google.com/drive/1hNhgtGZqFN0LysL-ZFstCUardq7FtKn5?usp=sharing 

### Model 2
For predicting subsequent demand coverage
deep learning architecture for time-series forecasting. Options may include recurrent neural networks (RNNs) like Long Short-Term Memory (LSTM) networks or Gated Recurrent Units (GRUs), or more @Cristian Medina - Data Analytics  & @Mélanie Kedge 
URL: https://colab.research.google.com/drive/1o9TKLApndriNatjOt9NEB_EKoJW67mvK?usp=sharing 
