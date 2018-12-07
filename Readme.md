# Author : Antony

Docker containers performace monitoring tool, uses prometheus, Docker, CAdvisor & Grafana

`How to run the project`

1. Ensure the docker is installed in the machine
2. Ensure docker is running
3. `cd prometheus-grafana-alertmanager`
4. Type the following command `docker-compose up -d`
5. Open a new terminal window
6. `cd cadvisor`
7.  Type the following command `docker-compose up -d`
8. Confirm that everything is up and running, run `docker ps`
9. Open you terminal window and watch the magic happen `localhost:9911 (for CAdvisor) & localhost:9090 (Prometheus), localhost:3000 (Grafana)`
10. Get to building your own custom metrics 

### NB: 

You can edit the `prometheus.yml` to match you server deployment confguration 
The file is under `prometheus-grafana-alertmanager/prometheusdata/`

