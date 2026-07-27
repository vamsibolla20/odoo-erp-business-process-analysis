# Requirements Traceability Matrix

| ID | Business Requirement | Business Problem Addressed | Odoo Functionality / Configuration | Expected Business Value |
|---|---|---|---|---|
| S01 | Configure quotations for existing products with variants | Manual quotation effort and risk of inconsistent pricing | Product variants, attributes and units of measure | More consistent quotation setup for configurable products |
| S02 | Create quotations for custom products | Custom-order complexity | Custom product structure and order-specific customisation | Supports make-to-order sales requirements |
| S03 | Apply 5% loyal-customer discount excluding shipping | Need to apply pricing rules consistently | VIP pricelist and customer pricing configuration | Standardises discount handling |
| S04 | Apply delivery charges by delivery method | Manual delivery charge handling | Configured delivery methods and fixed charges | More consistent quotation totals |
| S05 | Receive 30% deposit with balance on delivery | Need to control order confirmation and payment timing | Down-payment invoicing | Supports staged payment process |
| P01 | Obtain and compare at least 3 supplier quotes | Supplier comparison was time-consuming and often bypassed | RFQs, alternatives and product-line comparison | Improves purchasing transparency and supplier selection |
| P02 | Purchase stock items from preferred suppliers | Need structured replenishment purchasing | Preferred-vendor purchase workflow | More consistent stock purchasing |
| P03 | Approve purchases ≥ $1,000 | Purchase-control requirement | Purchase-order approval threshold | Strengthens governance and approval control |
| M01 | Generate manufacturing order from confirmed sale | Disconnected handoff from sales to production | Make-to-order / replenish-on-order route | Connects sales demand to production |
| M02 | Use one BOM for existing product variants | Duplicate and obsolete BOMs | Variant applicability within BOM | Reduces unnecessary BOM duplication |
| M03 | Use editable BOM template for custom orders | Custom products require unique materials | Custom BOM template with editable components | Provides structure while retaining flexibility |
| M04 | Track production cost and time | Limited visibility of order-level production effort | Manufacturing reporting | Improves cost/time visibility |
| I01 | Reorder below defined inventory level | Replenishment relied heavily on employee judgement | Reordering rules | Supports more systematic replenishment |
| A01 | Process invoices and payments | Delays caused by fragmented/paper-based information | Customer invoicing, payment registration and down payments | Improves integration of order and payment information |

## Note

The expected business value is based on the case requirements and documented configuration. It describes the intended benefit of the proposed solution and does not claim independently measured production outcomes.
