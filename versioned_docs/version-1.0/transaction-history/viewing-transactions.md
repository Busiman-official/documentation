---
sidebar_position: 2
toc_max_heading_level: 2
---

# Viewing & Filtering Transactions

Learn how to view transaction history and use advanced filtering and search capabilities to find specific transactions quickly and efficiently.

## 🏠 **Accessing Transaction History**

### Navigation Path

Access transaction history through the main dashboard:

1. **Navigate to Dashboard**: Go to your main dashboard
2. **Find Transaction History**: Look for "Transaction History" in the navigation menu
3. **Click to Access**: Opens the main transaction history page

### URL Structure

The transaction history page uses the following URL pattern:

```bash
/manager/dashboard/{branchId}/transaction-history
```

## 📊 **Main Interface Overview**

### Page Layout

The transaction history page consists of several key sections:

- **Top Action Bar**: Navigation breadcrumbs and action buttons
- **Metrics Dashboard**: Transaction volume summary
- **Filters Section**: Advanced filtering controls
- **Transaction Table**: Main data display area
- **Pagination Controls**: Navigation through large datasets

### Metrics Dashboard

Located at the top of the page, the metrics dashboard shows:

- **Check In** 🟢: Products returned to inventory (green badge)
- **Check Out** 🔴: Products issued to customers (red badge)
- **Internal** 🔵: Store-to-store transfers (blue badge)
- **Replacement** 🟠: Product exchanges (orange badge)

## 📋 **Transaction Table**

### Table Structure

The main table displays transactions with these columns:

| Column          | Description                                              | Sortable |
| --------------- | -------------------------------------------------------- | -------- |
| **DATE**        | Transaction date (DD MMM YYYY)                           | ✅       |
| **PRODUCT**     | Product name/alias                                       | ✅       |
| **STOCK**       | Opening balance before transaction                       | ✅       |
| **QTY**         | Quantity with sign (+ for additions, - for subtractions) | ✅       |
| **TYPE**        | Transaction type                                         | ✅       |
| **ISSUED BY**   | Source person/entity                                     | ✅       |
| **RECEIVED BY** | Destination person/entity                                | ✅       |

### Row Color Coding

- **Check In Rows**: Light green background
- **Check Out Rows**: Light red background
- **Internal Rows**: Light blue background
- **Replacement Rows**: Light orange background

## 🔍 **Filtering & Search**

### Advanced Filters Modal

Access comprehensive filtering through the "Filters" button:

#### Filter Categories

- **Transaction Type**: All, Check In, Check Out, Internal, Replacement
- **Warehouse**: Select multiple warehouses
- **Store**: Filter by stores within selected warehouses
- **Customer**: Filter by specific customers
- **Product**: Filter by specific products

#### Date Range Filter

- **Desktop**: Date range picker in top action bar
- **Mobile**: Date range option in filter modal
- **Format**: From date → To date

### Text Search

Located at the bottom of the page:

- **Real-time Search**: Results update as you type
- **Multi-field Search**: Searches products, serial numbers, customers, references
- **Case-insensitive**: Search works regardless of case

### Filter Application

- **Apply Filters**: Click "Apply Filters" to apply all selections
- **Remove Filters**: Click "Remove Filters" to clear all filters
- **URL Preservation**: Filter state saved in URL for bookmarking

## 👥 **Customer Inventory**

### Accessing Customer Inventory

- **Trigger**: Appears when customer filter is active
- **Button Location**: Top action bar next to Filters button
- **Modal Features**: Search and view products held by selected customers

### Modal Interface

- **Customer Selection**: View inventory for all selected customers
- **Product Display**: Shows products with serial numbers or quantities
- **Search Within**: Find specific products or serial numbers
- **Transaction Links**: Access related transaction history

## 🎯 **Row Interaction**

### Click Behavior

- **Primary Action**: Click any row to view transaction details
- **Navigation**: Opens detailed transaction view
- **URL Pattern**: `/transaction-history/details?requestId={id}&type={type}`

## 📊 **Performance Considerations**

### Large Datasets

- **Pagination**: Loads data in chunks
- **Filter Optimization**: Server-side filtering
- **Date Range Limits**: Use specific ranges for better performance

## 💡 **Best Practices**

### Efficient Navigation

- **Use Filters First**: Apply filters before browsing
- **Date Range Limits**: Use specific date ranges
- **Search Specificity**: Use specific search terms

### Data Interpretation

- **Color Awareness**: Use row colors for transaction types
- **Quantity Signs**: Green (+) for additions, red (-) for subtractions
- **Balance Tracking**: Use STOCK column for inventory impact

:::info Need Help?
Contact our support team for assistance with transaction history navigation, filtering, and search functionality. Available 24/7 in Hindi and English.
:::
