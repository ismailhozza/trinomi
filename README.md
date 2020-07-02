# Trinomi

## What is it?

![Trinomi](images/icon-96x96.png "Trinomi")

Trinomi is a simple CRM (contact management system) application containing the most fundamental features only. It's meant for **organizations** primarily, but can be used by small to medium sized companies also.

Trinomi offers three core features: **Contacts**, **Messaging** and **Fees/Invoicing**.

It's built to be simple and mobile friendly by design.

The fees and invoices module can be used separately by any one who gets regular payments from customers/contacts and wants to track those payments. This module allows you to easily create and manage invoices and track related payments.

Desktop and web version. This is how the app looks when used by desktop or web client.

![TrinoWeb](images/desktop.png "Trinomi for Web")

Mobile version. And this is how it looks on handheld devices.

![TrinoMobile](images/mobile.jpeg "Trinomi for Mobile")


## Contacts

**Contacts** are the core feature of the app. Contacts can be **students**, **members**, **guardians**, **teachers**, etc. Trinomi stores only basic information from each contact most notably name, gender, year of birth, phone number, family size, address, tags and notes. Only **name**, **gender** and **phone number** are required all other fields are optional. Besides these core fields any number of **custom fields** can be added to the contact. Custom fields are managed by administrator under the profile page.

Creating a new contact

![Contact](images/contact.gif "Create contact")

Contacts can be filtered by gender, tag, id or a free text like name. Filtered contacts is shown below.

![Filter](images/contacts-filter.gif "Filtering contacts")


## Tags

Tags offer a powerful and a simple way to categories and manage contacts. They can be anything that you might imagine. Some example tags might be: parent, teacher, kids, boys, girls, etc.

Tags are managed under the user profile and only user with administrator role can change/modify them.

Managing tags

![Tags](images/tags.gif "Manage tags")

Tags can be assigned to contacts, groups, courses and fees.

Adding tag to contact, group course or fee is shown below.

![Tags](images/add-tag.gif "Add tag")

## Groups

Groups are based on tags and they offer two features: **calendar** and **messaging** for group of related contacts. Calendar widget of the group is shown on the bottom of the group. Above calendar there is messages sent to this group. Calendar events can be one time or recurring events.

Group membership is based on tags, any contact that has any of the tags of the group will be part of that group.

Creating calendar event

![Events](images/new-event.gif "New event")

## Courses

Courses are very similar to groups. This feature is included in [GenA](https://ismailhozza.github.io/trinomi/), but not in Trinomi.

## Fees

Manage easily fees here. Create a new fee by specifying year, month and amount. Specify target contacts by adding **tags** to the fee. See details of the fee including current payments and statistics.

By default on fees of this year are shown and old ones are hidden.

On the top of the fee details page there are shortcuts to other fees.

Then comes details of this fee. Pie chart shows current payment statistics.

Below the chart there is the target contacts of the fee.

![Fees](images/fees.gif "New fee")

### Payments and Invoicing

Fee payments can be created easily on the bottom of the fee details page. This is useful when you need to record payments, but not create actual invoices. If you need to create and send invoices use the invoices feature.

![NewPayment](images/new-payment.gif "New payment")

Payments to multiple fees can be imported easily at one. The UI allows making corrections before actually importing the fees.

![ImportPayment](images/import-payment.gif "Import payments")

#### Invoices

Create a new invoice, add invoice lines, export as PDF and send to your contact/customer.

![CreateInvoice](images/new-invoice.gif "New Invoice")

## Messages

Messaging based on SMS is one of the core features of Trinomi. Message can target individual contact, a group, a course or fee. Two-way communication is possible allowing Trinomi to receive messages from registered contacts.

Automatic messages for events and fees are supported.

## Users and Devices

New users can be created easily. There three roles available: admin, instructor and cashier currently.

![Users](images/users.gif "New user")

## Devices

This page shows the status of the devices

![Devices](images/devices.gif "Devices")