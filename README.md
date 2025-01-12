# Домашнее задание к занятию "13.Системы мониторинга"

## Обязательные задания

1. Минимальный набор метрик:
   - Состояние дисковой подсистемы - свободное место, мониторинг значения очередей, iops и скорости read/write;
   - Проверка доступности сервиса по http-кодам;
   - Утилизация CPU;
   - Мониторинг RAM.
   
2. Необходимо **SLA** с клиентами об уровне обслуживания, в соответствии с **SLO**. Фактический уровень обслуживания будет отражен в **SLI**.

   
3. Предложу использовать систему перехватчик-ошибок **Sentry**.

   
4. В представленной формуле не учтены коды 3xx, исправленная формула выглядит так: ``(summ_2xx_requests + summ_3xx_requests)/(summ_all_requests)``

   
6. 5

    
7. Модели систем мониторинга:
   
| Система  | Модель |
| ------------- | ------------- |
| Prometheus  |  pull  |
| TICK        | push  |
| Zabbix        | push & pull  |
| VictoriaMetrics        | push & pull  |
| Nagios        | pull  |
  
  
  
  
  
  
7. 7
8. 8
9. 
