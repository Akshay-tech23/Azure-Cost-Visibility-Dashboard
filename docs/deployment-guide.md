# Azure Cost Visibility Dashboard - Deployment Guide

## Prerequisites

- Azure Subscription (Azure for Students)
- Microsoft Account
- Internet Connection

---

## Deployment Steps

### Step 1

Create a Resource Group.

Resource Group Name:

rg-cost-dashboard

---

### Step 2

Open Azure Cost Management.

Navigate to:

Cost Management → Cost Analysis

---

### Step 3

Create Monthly Budget.

Budget Name:

Student-Monthly-Budget

Budget:

$10

---

### Step 4

Configure Budget Alerts.

50%

80%

100%

---

### Step 5

Create Azure Logic App.

Logic App Name:

la-cost-alert

---

### Step 6

Configure Workflow.

Trigger

When HTTP Request is Received

↓

Send Email (Office 365 Outlook)

---

### Step 7

Create Action Group.

Action Group Name:

ag-budget-alert

---

### Step 8

Connect Logic App.

Configure Logic App as an Action in the Action Group.

---

### Step 9

Test.

Monitor Budget.

Receive Email Notifications.

---

## Cleanup

Delete:

- Logic App

- Action Group

- Resource Group

to avoid unnecessary costs.