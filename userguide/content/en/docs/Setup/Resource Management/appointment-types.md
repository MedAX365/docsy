---
title: "Appointment Types"
linkTitle: "Appointment Types"
date: 2021-12-08T09:22:27+01:00
weight: 1
description: >
Learn how to create an outpatient visit and find the outpatient visit created previously
---

## Appointment Types

You can create appointment types by using 'Appointment Class' field that includes examination, consultation, operation, radiology, procedure and hospitalization. You have to name your class in 'Appointment Type' and specify your time slot(min). By specifying the admission type, you determine in which situation you arrange your appointments.

When you arrange your an appointment, you need to use various resources. In MedAX, the resources are person, equipment, room or bed. For example, for an operation appointment, you should assign multiple resources such as physician, anesthesialogist, room, equipment and bed. In 'Resources' section, you can specify the funcionality of each resource such as multi-select, mandatory,pointer resource, allow overlap and avaialble for duty physicians. Multi select means that it is used at the same time for different appointments. Mandatory means that the resource have to be used in the appointment. Allow overlap means that a resource can be used in consecutive appointments.

There is the resource list of your company in **Periodic-Resource Management-Resource Definitions**. To specify a person as a resource, you have to open **Setup-Staff-Staff List**. Specify as yes for appointment in 'General'. To specify an equipment, room or bed as resource, you have to open **Setup-Facilities**. Click the check boxes of them in 'Equipment' and 'Rooms' in 'Service Units'. Once you make the instructions above, you can see that the resources are added to the list in 'Resource Definitions'.


