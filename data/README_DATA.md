# Instacart Databricks Project Dataset

This folder contains a compact, relationally consistent dataset prepared for
Databricks Free Edition.

## Files

- `orders_project.csv` — sampled prior orders plus matching train orders
- `order_products_prior_project.csv` — 750,000 sampled prior line items
- `order_products_train_project.csv` — train line items for sampled users
- `products.csv` — product dimension
- `aisles.csv` — aisle lookup
- `departments.csv` — department lookup
- `sampling_manifest.json` — generation logic, counts, and limitations

## Important analytical note

The prior-order data is a sample rather than complete customer history. Product,
basket, reorder, pipeline, data-quality, and sampled customer-behaviour analysis
are appropriate. Any customer lifetime or order-frequency result must be labelled
as sample-based.
