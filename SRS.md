## Description

Foodar is a food delivery service application. Foodies will order take-out from
a local restaurant, then use Foodar to find a Driver to pick up and deliver it
to them. Delivery fees will be calculated based on distance driven, plus a
base fee. Users must register a card to autopay drivers the approved amount.

 

### User Roles:

**Foodie**: will create a delivery mission to pick up their food from a restaurant.

**Driver**: can accept delivery missions, and manage income.
 

Primary stakeholders have decided that Foodar users should have the ability to
register for a Foodar account and view a simple website that advertises its
services. Now that you know a little about the system, we'll get you setup with
some coding. We'll add more information to the SRS in a later activity.

[Example Foodar link](http://showcase.revature.com/foodar100/)


### Purpose

The purpose of this document is to provide a guide for developers and testers who are responsible for the development of the platform. It provides the information necessary to design, develop, and test the software.

 

### Scope

This document serves as a description of the required improvements to the project. It contains a workflow description, functional and nonfunctional requirements, and appropriate diagrams to fully describe the system.

 

### System Overview

This enterprise project consists of one layer; the front-end. This layer is the primary portal through which users will interact with the application. JavaScript is used to enhance a user's experience and provide additional functionality.

 
![Model View Controller - MVC](./images/img_MVC.jpg)


The above graphic describes the different components that you'll use to implement using the technologies that we'll introduce to you. It follows a design pattern called MVC or Model, View, Controller. For now you just need to know that it consists of three parts"

one that is the visual part that users interact with - the view,
one that represents the object being modeled - the model,
and something that manages data between the different parts - the controller.