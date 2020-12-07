![IRD logo](Images/IRlogo.gif)
![Software Dev](Images/SoftwareDev.png)

# Transaction Data Services (TDS) 

The TDS is a suite of business services that provides access to IR customers transaction data for consumption by software packages.  In turn these packages present that data to their users. 
Financial transaction data includes amounts assessed and associated credits or debits.  There is no data sent associated with the details of how an assessment has been calculated

## What's Changed

### XSD Schema Changes

* Account.v1.xsd
	* Update field forecastedBalance to forecastedTotalBalance

* Transactions.v1.xsd
	* Update field transaction to transactions
	* Update field forecastedBalance to forecastedTotalBalance
	* update simpleType TransactionLinkIDType field maxLength to 20 character

### Added R4 Scenarios for Student loans
* Updated examples of Transactions Types with Period Impacts which covers Student Loans account type	

## TDS Build Packs

| PDF Build Pack | Document Overview|
| --- | --- |
| [TDS Overview and Transition ](TDS%20Overview%20and%20Transition%20-%20Build%20Pack%2008122020.pdf) | This document is provided to Software Providers to support their use of Transaction Data Services (TDS). It<br/>•  provides an high level business overview of TDS to enable an understanding of the service being offered<br/>•  describes the data being made available through the services<br/>•  describes the permission model |
| [TDS Bulk File Feed](TDS%20Real%20Time%20-%20Build%20Pack.pdf) |This document is provided to software providers to support the build and use of the Transaction Data Service (TDS) Real Time web services. <br/>  It also describes the relationship with other build packs, the architecture of the technical solution, schemas (file formats), end points, and sample payloads.  | 
| [TDS Real Time ](Gateway%20Services%20Build%20Pack%20-%20TDS%20Real%20Time.pdf)| This document is provided to Software Providers to support the build and use of the Transaction Data Service (TDS) Real Time web services. It also describes the relationship with other build packs, architecture of the technical solution, schemas (file formats), and endpoints; it also provides sample payloads.|

## TDS Data Scenarios and Sample Messages
* [Data Scenarios](Data%20Scenarios/)
	#### The Data Scenarios includes:
	
		* TDS Overview and Transition Data Conversion Scenarios
		* TDS Overview and Transition Data Scenarios
		* TDS Overview and Transition Release 3 Data Scenarios 
		* TDS Overview and Transition Release 4 Data Scenarios
		
* [TDS Bulk File Feed samples](TDS%20Bulk%20File%20Feed%20samples/)
* [TDS Real-Time sample messages](TDS%20Real-Time%20sample%20messages/)

## WSDL and XSD schemas
* [TDS WSDL and XSD schemas](WSDL%20and%20XSD/)
* View and Download [Common Schema v1](../WSDL%20and%20XSD/Common.v1.xsd)

## Supporting services
* [Service - Intermediation](https://github.com/InlandRevenue/Gateway_Services-Access/tree/master/Service%20-%20Intermediation)
* [Service - Software Intermediation](https://github.com/InlandRevenue/Gateway_Services-Access/tree/master/Service%20-%20Software%20Intermediation)
* [Service - Identity and Access](https://github.com/InlandRevenue/Gateway_Services-Access)



