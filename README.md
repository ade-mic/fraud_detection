# Online Payment Fraud Detection using Machine Learning in Python

## Background
<p>
Online payment fraud has become a significant concern with the rise of e-commerce and digital transactions. Fraudsters are constantly developing new tactics to exploit vulnerabilities in payment systems, leading to substantial financial losses for businesses and customers. Traditional rule-based fraud detection systems, although effective to some extent, struggle to keep up with the evolving nature of fraudulent activities.
</p>

## Machine learning (ML)
<p>
Machine learning (ML) offers a more dynamic and robust approach to fraud detection. By analyzing vast amounts of transaction data, ML models can identify patterns and anomalies that may indicate fraudulent behavior. These models learn from historical data, enabling them to adapt to new and emerging threats more effectively than traditional systems.
</p>

## Why?
<ul>
<li>

Preventing Financial Losses: Fraudulent transactions can lead to significant financial losses for both businesses and customers. Machine learning models can help detect and prevent these transactions in real-time.
</li>
<li>
Enhancing Security: By analyzing patterns and anomalies in transaction data, machine learning models can identify potentially fraudulent activities, thereby enhancing the overall security of online payment systems.
</li>
<li>
Improving Customer Trust: When customers feel secure while making online payments, they are more likely to trust and continue using the service. Effective fraud detection systems contribute to building and maintaining this trust.
</li>
<li>
Reducing Operational Costs: Manual fraud detection processes can be time-consuming and expensive. Automating this process with machine learning can reduce operational costs and free up resources for other important tasks.
</li>
<li>
Adapting to New Threats: Fraudsters are constantly evolving their tactics. Machine learning models can continuously learn from new data, allowing them to adapt to emerging threats and stay ahead of fraudsters.
</li>
</ul>

## Datasets
<table>
<tr>
<th>Feature </th>
<th>Description </th>
</tr>
<tr>
<td>step </td>
<td>tells about the unit of time </td>
</tr>
<tr>
<td>type </td>
<td>type of transaction done </td>
</tr>
<tr>
<td>amount </td>
<td>the total amount of transaction </td>
</tr>
<tr>
<td>nameOrg </td>
<td>account that starts the transaction  </td>
</tr>
<tr>
<td>oldbalanceOrg </td>
<td>Balance of the account of sender before transaction  </td>
</tr>
<tr>
<td>newbalanceOrg </td>
<td>Balance of the account of sender after transaction  </td>
</tr>
<tr>
<td>nameDest </td>
<td>account that receives the transaction  </td>
</tr>
<tr>
<td>oldbalanceDest </td>
<td>Balance of the account of receiver before transaction </td>
</tr>
<tr>
<td>newbalanceDest </td>
<td>Balance of the account of receiver after transaction </td>
</tr>
<tr>
<td>isFraud </td>
<td>The value to be predicted i.e. 0 or 1 </td>
</tr>
</table>

## Libraries
- Pandas
- Seaborn/Matplotlib
- Numpy
