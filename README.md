# docker-mon_logs
Docker Compose Stack con Grafana Loki, Promtail.  
Esta configuración está diseñada para facilitar el monitoreo de sistemas mediante la recopilación, almacenamiento y visualización de registros.

## Despliegue
Ejecutar previamente el fichero [script_mon_logs.sh](script_mon_logs.sh) para crear los diferentes directorios necesarios para ejecutar el contenedor Docker 
```
./script_mon_logs.sh
```
Desplegar los servicios Loki, Promtail y Grafana
```
docker-compose up -d
```

## Resultado
### Dashboard
![image](https://github.com/user-attachments/assets/8f5e3903-d3d6-4629-ae27-ffe5ea4f8743)

### Contact Points
![image](https://github.com/user-attachments/assets/dd531ccb-6937-4f33-8380-2e3787999bfa)
![image](https://github.com/user-attachments/assets/c0fec13f-a5c8-485c-9a02-d8012466e89f)

### Alert rules
![image](https://github.com/user-attachments/assets/77b14b32-565a-43ac-9c51-3feb7befdc37)

### Alertas en Discord
![image](https://github.com/user-attachments/assets/e489683d-a1db-4fe4-a943-a7b7286919f9)

