# Magento 2 Size Chart Extension

## Introduction
Magento 2 Size Chart Extension by CodeDecorator helps eCommerce stores display size charts on product pages. This extension enhances the shopping experience by providing accurate size guides, reducing return rates, and improving customer satisfaction. Easily configure and customize the size chart to match your store's design and product categories.

## How It Works
Magento 2 Size Chart Extension allows store owners to add and manage size charts for different products, categories, and customer groups. The extension provides an intuitive interface where admins can upload images, add tables, or enter text-based size guides. Customers can view the size chart in a popup or a dedicated section on the product page, ensuring they choose the right fit before purchasing.

## Key Features
- Add size charts to specific products, categories, or customer groups.
- Display size charts as popups or inline sections on product pages.
- Fully customizable design and layout.
- User-friendly admin panel for easy management.

## Custom Size Chart Management
Create and manage different size charts for various product categories. The admin can define unique size guides with text, images, and tables.

## Responsive Display
The extension ensures that size charts are mobile-friendly and adapt to different screen sizes, enhancing the user experience across all devices.

## Easy Customization
Admins can customize the appearance of the size chart, including colors, fonts, and layout, to match the store theme seamlessly.

## Reduce Return Rates
By providing customers with accurate size information, the extension helps in reducing incorrect orders and returns, saving operational costs.

## Extension Installation

### Step 1: Install the extension using Composer
```bash
composer require codedecorator/magento2-size-chart
```
For a specific version:
```bash
composer require codedecorator/magento2-size-chart:<version>
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run the following commands in Magento root directory
```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How to Configure Magento 2 Size Chart Extension

### Step 1 - Navigate to the Admin Panel
Go to **Stores > Configuration > CodeDecorator > Size Chart**.

### Step 2 - Enable the Extension
Toggle the **Enable Size Chart** option to "Yes" and configure display settings.

### Step 3 - Create a Size Chart
Navigate to **Catalog > Size Charts** and click **Add New Chart**. Upload an image or enter size details.

### Step 4 - Assign to Products or Categories
Select specific products or categories where the size chart should appear.

## Download Our [Magento 2 Size Chart](https://codedecorator.com/magento-2-size-chart.html) Extension
