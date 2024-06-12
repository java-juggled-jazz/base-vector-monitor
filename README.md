# base-vector-monitor

This Docker container group is used for monitoring Nginx logs using Vector and visualising using Grafana.

- Nginx: ./nginx/nginx.conf.save is backup for nginx.conf. Keep it to roll back later if something is going wrong.
- Vector: ./vector/vector.conf.save is backup for vector.conf. Keep it to roll back later if something is going wrong.
