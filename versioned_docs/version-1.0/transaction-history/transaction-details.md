---
sidebar_position: 3
toc_max_heading_level: 2
---

# Transaction Details

Dive deep into individual transactions to understand the complete context, product movements, and operational details of your inventory operations.

## 🎯 **Accessing Transaction Details**

### From Transaction History

- **Click Any Row**: Click on any transaction in the main history table
- **Navigation**: Opens detailed transaction view
- **URL Pattern**: `/transaction-history/details?requestId={id}&type={type}`
- **Context Preservation**: Maintains warehouse and filter context

## 📋 **Transaction Header Information**

### Header Layout

The transaction detail page displays comprehensive header information:

- **Sender Information**: Who initiated the transaction
- **Transaction Flow**: Visual arrow showing movement direction
- **Receiver Information**: Who received the transaction
- **Transaction Metadata**: Dates, status, and reference information

### Transaction Types & Colors

- **Check In** 🟢: Customer → Warehouse (green header)
- **Check Out** 🔴: Warehouse → Customer (red header)
- **Internal** 🔵: Store → Store (blue header)
- **Replacement** 🟠: Product exchange (orange header)

## 📦 **Product Information**

### Product Details Table

The main table shows all products involved in the transaction:

| Column                | Description                    |
| --------------------- | ------------------------------ |
| **Product**           | Product name and model         |
| **Serial Number**     | Individual item serial numbers |
| **Quantity**          | Transaction quantity           |
| **Additional Fields** | Custom serial number fields    |

### Product Display

- **Individual Items**: Shows each serial number separately
- **Bulk Items**: Shows total quantity for non-serialized products
- **Additional Information**: Custom fields and specifications

## 🔁 **Transaction Flow Visualization**

### Visual Representation

- **Sender → Receiver**: Clear directional flow
- **Color Coding**: Matches transaction type colors
- **Context Labels**: Shows warehouse/store names when applicable

### Transaction Context

- **Warehouse Transfers**: Shows source and destination warehouses
- **Store Movements**: Displays store names within warehouses
- **Customer Transactions**: Customer names and organization details

## 📊 **Additional Transaction Information**

### Transaction Metadata

- **Transaction ID**: Unique identifier
- **Request ID**: Associated request number
- **Created Date**: When transaction was recorded
- **Completed Date**: When transaction was fulfilled
- **Approval Status**: Approved/rejected/pending status

### Service Integration

For service-related transactions:

- **Service Reports**: Links to field service documentation
- **Technician Information**: Field technician details
- **Service Notes**: Additional service context

## 🔙 **Navigation**

### Back to History

- **Breadcrumb Navigation**: Return to transaction history
- **Filter Preservation**: Maintains applied filters
- **Context Retention**: Keeps search and filter state

### Related Transactions

- **Customer History**: View other transactions for same customer
- **Product History**: See other movements of same product
- **Serial Tracking**: Follow specific serial number history

## 💡 **Best Practices**

### Detail Review

- **Complete Context**: Review all product and serial information
- **Status Verification**: Check approval and completion status
- **Customer Communication**: Use details for customer inquiries
- **Audit Trail**: Maintain complete transaction records

### Navigation Tips

- **Efficient Movement**: Use breadcrumbs for quick navigation
- **Context Awareness**: Review related transactions using the links provided

:::info Need Help?
Contact our support team for assistance with transaction details, understanding transaction flow, or navigating between related transactions. Available 24/7 in Hindi and English.
:::
