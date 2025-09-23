---
title: Forms
parent: Core Concepts
nav_order: 2
---

# Adapt Forms

Forms are a fundamental and powerful component used throughout Adapt Applications. They are the primary interface for collecting data from users, enabling seamless interaction and data management.

## Core Purpose

Adapt forms are designed to collect data that can be saved and sent to various destinations, including:

* **Email:** Submitting form data as an email.
* **API:** Sending data to an external API for processing or storage.
* **Timeline:** Logging form submissions as events on a timeline.
* **Database:** Storing collected data directly in a database for later use.

## Structure of a Form

Forms are built using the following components:

### Fields

Fields are the individual components used to collect specific pieces of information. Each field can be customised with various properties, such as:

* **Type:** Defines the kind of data to be collected (e.g., text, number, date, checkbox).
* **Label:** A descriptive name for the field that is visible to the user.
* **Validation Rules:** Ensures the user provides data in the correct format (e.g., a valid email address, a required field).

### Pages

Forms can be broken down into multiple pages using the Page Break field. This helps improve the user experience, especially for long or complex forms. This approach:

* **Organises Information:** Groups related fields together, making the form more logical.
* **Enables Progressive Disclosure:** Guides the user through a multi-step process.

## Advanced Features

### Linked Forms

Forms can be linked together throught Single-Link and Multi-Link fields to help share data across the system. This allows for greater flexibilty and power when building, making accessing and utilising collected data easy.

### Rules

Rules are the cornerstone of dynamic form behavior. They allow you to define conditional logic to control the form's appearance and functionality. Using rules, you can:

* **Display or Hide Fields:** Show or hide specific fields based on user input in other fields. For example, a "Do you have a pet?" checkbox could reveal a "Pet's name" field when checked.
* **Validate Data:** Enforce complex validation logic to ensure data integrity.

### Timeline Integration

Forms can be integrated directly into a timeline, allowing for event-based data collection. This means a form can be automatically triggered or made available at a specific point in a process or workflow. This is particularly useful for tasks such as:

* **Check-ins:** A form appears on the timeline at a specific date for a project check-in.
* **Feedback Collection:** A survey form is added to the timeline after a user completes a task.