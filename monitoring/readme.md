# kubeCDN: Monitoring Setup

## Instructions
1. Update the value of `adminPassword` in the file `grafana-values.yaml`
2. Run: `./setup_monitoring.sh`
3. After prometheus and grafana have been installed, navigate to the exposed endpoint for grafana 
4. Create a new dashboard using the "import" method. Use [this](https://grafana.com/dashboards/6781) dashboard by entering `6781` in the "Grafana.com Dashboard" text box and click "Load". 
5. For `prometheus`, select "Prometheus". Leave default values for all other fields. Click "Import". 
6. You should now see the dashboard. 
7. Repeat steps 3-6 for each region (this will be automated in the future). 
