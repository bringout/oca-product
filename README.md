# OCA Product

This repository contains **10** OCA packages for product.

## Packages Included (10 packages)

- **odoo-bringout-oca-product-variant-product_variant_attribute_tax** - From product: variant_product_variant_attribute_tax
- **odoo-bringout-oca-product-variant-product_variant_configurator** - From product: variant_product_variant_configurator
- **odoo-bringout-oca-product-variant-product_variant_default_code** - From product: variant_product_variant_default_code
- **odoo-bringout-oca-product-variant-product_variant_name** - From product: variant_product_variant_name
- **odoo-bringout-oca-product-variant-product_variant_sale_price** - From product: variant_product_variant_sale_price
- **odoo-bringout-oca-product-variant-product_variant_specific_description** - From product: variant_product_variant_specific_description
- **odoo-bringout-oca-product-variant-purchase_variant_configurator** - From product: variant_purchase_variant_configurator
- **odoo-bringout-oca-product-variant-sale_order_line_variant_description** - From product: variant_sale_order_line_variant_description
- **odoo-bringout-oca-product-variant-sale_product_variant_attribute_tax** - From product: variant_sale_product_variant_attribute_tax
- **odoo-bringout-oca-product-variant-sale_variant_configurator** - From product: variant_sale_variant_configurator


## Installation

Install any package from this category:

```bash
# Install from local directory
pip install packages/oca-product/PACKAGE_NAME/

# Install in development mode  
pip install -e packages/oca-product/PACKAGE_NAME/

# Using uv (recommended for speed)
uv add packages/oca-product/PACKAGE_NAME/
```

## Repository Structure

Each package in this repository follows the standard Odoo addon structure:

```
oca-product/
├── odoo-bringout-oca-PROJECT-ADDON/
│   ├── ADDON_NAME/           # Complete addon code
│   │   ├── __init__.py
│   │   ├── __manifest__.py
│   │   └── ... (models, views, etc.)
│   ├── pyproject.toml        # Python package configuration
│   └── README.md            # Package documentation
└── ...
```

## Contributing

These packages are maintained as part of the [OCA (Odoo Community Association)](https://github.com/OCA) ecosystem.

## License

Each package maintains its original license as specified in the OCA repositories.
