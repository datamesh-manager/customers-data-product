# Customers Data Product

This repository contains the **Customers** data product of the sales team.

It follows the recommended repository structure for
[Entropy Data](https://www.entropy-data.com/) Git integrations:
one repository per data product, with the data product YAML file in the root
folder and one sub-folder per output port containing its data contract.

```
customers-data-product/
├── dataproduct.yaml                          # the data product definition
├── databricks_customers_latest_npii_v1/      # output port
│   └── datacontract.yaml
└── databricks_customers_latest_pii_v2/       # output port
    └── datacontract.yaml
```

The `dataproduct.yaml` and the data contract files are connected to
Entropy Data via Git connections and kept in sync from there.
