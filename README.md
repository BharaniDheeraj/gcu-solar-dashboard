# GCU Solar Dashboard

## Deploy to Vercel
1. Create a new GitHub repository and upload `index.html` and `vercel.json`.
2. In Vercel, choose **Add New → Project**, import the repository, and deploy.
3. Framework preset: **Other**. No build command is required.
4. After deployment, Vercel provides a public `*.vercel.app` URL.
5. Add a custom domain in Project Settings → Domains if required.

The current dataset is embedded in `index.html`. For true live data, replace the embedded data source with an inverter/BMS API or Modbus-backed API endpoint.
