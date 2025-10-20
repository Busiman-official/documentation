---
sidebar_position: 5
toc_max_heading_level: 2
---

# Transaction Types

Understand the different types of inventory transactions in Busiman and how they work within your business operations.

## 🎯 **Transaction Categories**

Busiman supports four main transaction types that cover all inventory movement scenarios:

### Check In 🟢

- **Direction**: Customer → Warehouse
- **Purpose**: Products returned to inventory
- **Use Cases**: Customer returns, service returns, warranty repairs
- **Color**: Green rows in transaction history

### Check Out 🔴

- **Direction**: Warehouse → Customer
- **Purpose**: Products issued to customers
- **Use Cases**: Sales, rentals, service deployments
- **Color**: Red rows in transaction history

### Internal 🔵

- **Direction**: Store → Store (within warehouse)
- **Purpose**: Inventory redistribution
- **Use Cases**: Stock balancing, location optimization
- **Color**: Blue rows in transaction history

### Replacement 🟠

- **Direction**: Product exchange
- **Purpose**: Defective product replacement
- **Use Cases**: Warranty replacements, defective returns
- **Color**: Orange rows in transaction history

## 🔄 Transaction Flow & Approval

A typical transaction goes through request → (optional approval) → inventory update → recorded in history. Some transactions (for example high-value replacements) may require manager approval.

## 📊 **Transaction Details**

### Common Fields

All transactions include:

- **Date & Time**: When transaction occurred
- **Products**: Items involved (with quantities/serial numbers)
- **Parties**: Who sent/received the items
- **Location**: Warehouse and store information
- **Reference**: Related order or service numbers

### Type-Specific Information

#### Check In Transactions

- **Return Reason**: Why items are being returned
- **Condition**: Item condition upon return
- **Service History**: Any service work performed

#### Check Out Transactions

- **Usage Purpose**: Why items are being issued
- **Expected Return**: When items are expected back
- **Customer Information**: Customer contact details

#### Internal Transfers

- **Reason**: Why items are being moved
- **Source/Destination**: Store locations involved
- **Urgency**: Priority level of the transfer

#### Replacement Transactions

- **Defective Item**: Details of item being replaced
- **Replacement Item**: Details of replacement item
- **Warranty Status**: Whether covered under warranty

## 💡 **Best Practices**

### Transaction Management

- **Accurate Recording**: Always record complete transaction details
- **Serial Tracking**: Use serial numbers for valuable items
- **Approval Workflows**: Follow proper approval processes
- **Documentation**: Include relevant reference numbers

### Type Selection

- **Check In**: Use for all returns to inventory
- **Check Out**: Use for all issues to customers
- **Internal**: Use for warehouse reorganization
- **Replacement**: Use for defective item exchanges

:::info Need Help?
Contact our support team for assistance with transaction types, approval processes, or transaction recording best practices. Available 24/7 in Hindi and English.
:::
