---
title: "Services"
linkTitle: "Services"
date: 2021-12-08T09:22:27+01:00
weight: 1
description: >
Learn how to create an outpatient visit and find the outpatient visit created previously
---

# **Services**

You can create required services by the 'Services' session. To create a new service, you have to select a product as a service , because the Dynamics 365 corresponding product table is used inside MedAX . Thus, the product created in Dynamics 365 become a service. The service type is determined by selecting the proper 'Medical Meaning'.

## General

----

### *Clinic*

In service details, you can specify the clinic in which the service is provided. For example, laboratory examination is opened for the patient in 'Visit List' session. Service list is displayed and when you select a product such as 'Blood Group', you can see 'Lab' in 'Processing Clinic' field. Because 'Lab' has been specified as clinic while creating the 'Blood Group'.

### *Clinic mandatory*

If this is selected as 'Yes', 'Processing Clinic' can not be changed while a service is opened for a patient in 'Visit List' session.

### *Need left/right*

If this is selected as 'Yes', left or right organ can be determined while the service is opened.

### *Quantity defaults*

You can specify the quantity(number) of a service while created. Thus, the patient gets the number of service that you specify in 'Default Qty' field. You can also specify the max quantity within 'Max Qty' field.

### *Hide at Trans Add*

You can hide transaction while opening a service for patient by using the option. Because some of transactions is editted automatically and should not be editted manually.

### *Service prices*

The categories display the dimensions of the prices. For example, you can specify Chest-X-Ray price depending on clinic or facility or physician or insurrance class. You can differentiate the prices with the dimensions.

### *Item Prices*

You can specify the price by using the dimensions such as configuration, size, color, style, batch number and serial number.

## Laboratory

---

If the 'Medical Meaning' field is determined as laboratory. You can specify the laboratory group, sample container and laboratory type related with the service created.

## Radiology

---

If the 'Medical Meaning' is determined as radiology, you can specify the equipment type.


## Creating a new service

---

To create a new service, you can apply the following instructions.

1.	Click New.
2.	In the list, find and select the desired record.
3.	Click the Selected Product tab.
4.	In the Price Group field, enter or select a value.
5.	In the list, click the link in the selected row.
6.	In the Medical Meaning field, select an option.
7.	Click Apply all.
8.	Click OK.
9.	In the list, find and select the desired record.
10.	In the Clinic field, enter or select a value.
11.	In the list, select row 11.
12.	In the list, click the link in the selected row.
13.	Select Yes in the Clinic Mandatory field.
14.	In the Service Unit Type field, select an option.
15.	Select Yes in the Facility field.
16.	Click Save.





