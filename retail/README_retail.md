# Online Retail Analysis

## Introduction
This is a transactional dataset which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

The dataset was retrieved from [UCI's Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail).

## Dataset Features

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Description</th>
      <th>Type</th>
      <th>Example(s)</th>
      <th>Comment(s)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>InvoiceNo</strong></td>
      <td>6-digit unique identifier for each invoice.<br>Prefix 'C' indicates cancellation</td>
      <td>Categorical</td>
      <td>536365 <br> C536383 </td>
      <td></td>
    </tr>
    <tr>
      <td><strong>StockCode</strong></td>
      <td>5-digit identifier unique for each product.</td>
      <td>Categorical</td>
      <td>85123A</td>
      <td></td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td>Product Name.</td>
      <td>Categorical</td>
      <td>WHITE HANGING HEART T-LIGHT HOLDER</td>
      <td></td>
    </tr>
    <tr>
      <td><strong>Quantity</strong></td>
      <td>Number of products purchased.</td>
      <td>Integer</td>
      <td>5</td>
    </tr>
    <tr>
      <td><strong>InvoiceDate</strong></td>
      <td>Date and time of transaction generation (D/MM/YY)</td>
      <td></td>
      <td></td>
      <td> Converted to datetime format (YYYY-MM-DD)</td>
    </tr>
    <tr>
      <td><strong>UnitPrice</strong></td>
      <td>Price (in Sterling) per unit of the product.</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td><strong>CustomerID</strong></td>
      <td>Unique identifier for the customer.</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td><strong>Country</strong></td>
      <td>Country where the customer resides.</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

