# Tax Sale Tooling

1. Search for all unpaid property tax records via [orchestrator-sc-york](https://github.com/LocalTaxSale/orchestrator-sc-york)
2. Fetch geographical and economical data via [retriever-sc-york](https://github.com/LocalTaxSale/retriever-sc-york) for every yielded parcel
3. Updates (new and/or removed parcels) are propagated via [app-webhooks](https://github.com/LocalTaxSale/app-webhooks)
4. Notifications, ETL
5. Normalized data made accessible by [app-api] to [app-web]

Options:
- ETL
- Webhook
