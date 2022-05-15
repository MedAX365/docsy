---
title: "Agreement Clauses"
linkTitle: "Agreement Clauses"
weight: 3
date: 2018-07-30
description: >
Learn how to create an appointment and find the appointment arranged
---

# Agreement Clauses

A clause in an agreement is a provision related to the overall agreement. Typically, clauses clarify the responsibilities of each party in the agreement. A clause can require an action or can prevent an action.

The set of rules need to be created in this session.

## General

### *Admission Rules*

---

You can adjust the admission rules by determining whether there are insurrance class, ceiling, customer number, policy number, need for prepay (outpatient and inpatient). The prepay functions are important because if the patient is not charged for prepayment while selected as 'Yes', the relevant department can not notice the patient name on the waiting patient list.

### *Customer*

---

You can specify the currency type that the customer prefer. So you can calculate the amounts with different currencies. This is useful for foreign insurance company agreements. They might demand the claim with different exchange rates. This option provides you to calculate prices with required currency and create invoice currency.

### *Person*

---

For the patient, you can specify which currency you are going to use. This option provides you to calculate prices with required currency and create invoice currency. You can collect money with any currency you demand.

### *Provision*

A provision is a condition in an insurance contract or agreement. You can consult with the insurance company for each service. Before providing a service, you ask the insurance company what the payment will be or how much the insurance company will cover. Provision is used for such a purpose. If you specify the 'Provision Type', the visit file start to ask for a provision before the receptionist create an invoice or collect money for each service. There is a 'Provision Count' option. By the help of this, you can create multiple provision records or single one. If it is '0' (zero) it will be multiple, or we can specify any number you demand. It is usually specified as '1' (one). Because it contains any service expense. At the end of the patient discharge, you can create one final provision for every service taken by the patient.

### *Max Price*

Insurance company might limit the prices by determining maximum price declared in a tariff(Doctor's Union or Government). To meet the requirement, you can select a price list demanded by the insurance company in 'Price Lists' session created. So during the calculation, the price can not exceed the price determined in the price list.

### *Insurance Class*

You can specify the insurance class according to the agreement you have.

## Line Rule



In line rule, you can determine that the services use specific price list for the insurance company's share and same or another specific price list for the patient's share. To determine as that, you have to specify some amount of discount for each of them, respectively and find out the final price.

### *Insurance Class-Medical Meaning-Medical Type-Price Groups-Product-Line Type*

At the beginning of a line rule, you can see 'Insurance Class', 'Medical Meaning', 'Medical Type', 'Price Groups', 'Product' and 'Line Type'. MedAX create a query when a final price is needed to be calculated. The query firstly search 'Insurance Class' if there is an insurance class. If not, skip this part and search the next one 'Medical Meaning'. The query follows the order created in the Agreement Clauses Line Rule design. The aim here is to determine the correct line rule so that the correct price calculation can be made.

### *Clinic-Facility-Physician*

After the first part, you can see 'Clinic', 'Facility', 'Physician'. These are price groups depending on them. The query also search the groups. There is normal examinations in pediatry and dental clinic. The name of the medical service is same but the prices of them are different. For that reason, clinic type is essential to determine a right price. As for the 'Facility', prices can be differiantiated because of the facility price groups. To specify the right faicility group, you have to define the group in the 'Periods' in 'Agreements'. Thus, the facility group that is specified in the line rule have to be matched with the facility group specified in 'Periods' in 'Agreements'. Physician price group is usually used for if there is a medical doctor that has a special or remarkable functionality (For example, the doctor might be a proffessor). Various doctors might have a reputation on a medical field. That's why, the price of a service provided by such a doctor could be different from other services' prices.

### *Evaluation of the Prices-Rules*

#### *PS-Patient Share*

The patient share is only calculated. Any charge does not reflect to insurance company or government.

#### *SS-Sponsor Share*

Sponsor is an umbrella term. It represents an insurance company or a union or government. The sponsor share is calculated and any charge does not reflect to the patient share.

#### *PS SS - Patient Share and Sponsor Share*

The patient and sponsor share are calculated independently and the charges reflect them accordingly.

![](https://github.com/MedAX365/docsy/blob/main/images/LineRule_1.png)

#### *PS-SS - Patient Share minus Sponsor Share*

The patient and sponsor share are calculated, then sponsor share is substracted from the patient share. The remaining amount is reflected to the patient.

#### *SS% - The Ratio for Sponsor Share*

Sponsor might declare that the price of the service will be reflected to patients in a certain percentage of prices based on a certain price list.

![](https://github.com/MedAX365/docsy/blob/main/images/LineRule_2.png)

### *Alternative Price List*

In various cases, the price can not be found in the insurance company or government price lists, the sponsor allow to use another price list. The list is a alternative price list. It could be a health organization or union tariff.

#### *PS SS (PSa)*

The patient and sponsor share are calculated independently. When the price can not be found in the patient and sponsor share price lists, it is found in the alternative price list and that price is reflected to the patient.

#### *PS SS (SSa)*

The patient and sponsor share are calculated independently. When the price can not be found in the patient and sponsor share price lists, it is found in the alternative price list and that price is reflected to the sponsor.

### *Require Provision*

Various services requires provision, so you can adjust the requirement by the help of this option. Te selection of provision type in 'General' section is prerequisite for 'Req Provision'.

### *Max Price*

The maximum price would be calculated for the insurance company share price or whole price.

### *Description*

A brief explanation for the line rule used.

### *Supplemental

When you create an agreement clause in supplemental insurance type then you have to select an agreement in Agreements --> General --> Public Insurance Agreement. Afterwards, you can also create the line rule by specifying PS or SS or PS SS rule.

### *Error*

With the line rule, the price is calculated if the price is found in the price list. If not found, the error occurs, in that case you should update your price list or create a new alternative price list. With the error option, you can select 'Show error' that is used for warning or 'Continue'.













