# Functional Requirements

## Sales
- S01: Quotations for existing products with configurable variants and corresponding prices.
- S02: Quotations for custom products.
- S03: 5% loyal-customer discount on saleable products, excluding shipping.
- S04: Delivery charges of $110 Perth metro, $150 outside Perth metro, $0 pickup, or quoted interstate delivery.
- S05: 30% deposit on sales-order confirmation, with balance due on delivery.

## Procurement
- P01: RFQs to at least three suppliers for non-stock items with supplier comparison.
- P02: Purchase orders for stock items to preferred suppliers.
- P03: Purchase approval for purchases of $1,000 or more.

## Manufacturing
- M01: Automatically generate manufacturing orders after sales-order confirmation.
- M02: One BOM for existing-range products supporting variants.
- M03: Editable BOM template for customised orders.
- M04: Track production costs and time.

## Inventory
- I01: Automated reordering below defined inventory levels.

## Accounting
- A01: Process payments and invoices.
