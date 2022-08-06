# Semana de imersão iniciativaDevops  
&nbsp;  
AULA 1 - 01/08  
[SEUS PRIMEIROS PASSOS NO UNIVERSO DEVOPS + DOCKER](https://iniciativadevops.com.br/aula1/)  
AULA 2 - 02/08  
[AS GRANDES OPORTUNIDADES QUE ESTÃO À SUA ESPERA + KUBERNETES](https://iniciativadevops.com.br/aula2/)  
AULA 3 - 03/08  
[O QUE O MERCADO ESPERA DE VOCÊ COMO ESPECIALISTA EM DEVOPS + TERRAFORM](https://iniciativadevops.com.br/aula3/)  
AULA 4 - 04/08  
[MELHORANDO O SEU POSICIONAMENTO PROFISSIONAL + GITHUB ACTIONS](https://iniciativadevops.com.br/aula4/)  
AULA 5 - 04/08  
[MÉTRICAS](https://iniciativadevops.com.br/aula5/)  

# Instalação do Prometheus  
&nbsp;  
helm upgrade --install prometheus prometheus-community/prometheus --set alertmanager.enabled=false,server.persistentVolume.enable=false,server.service.type=LoadBalancer,server.global.scrape_interval=10s  
  
# Instalação do Grafana  
&nbsp;  
helm upgrade --install prometheus prometheus-community/prometheus --set alertmanager.enabled=false,server.persistentVolume.enable=false,server.service.type=LoadBalancer,server.global.scrape_interval=10s,pushgateway.enable=false

