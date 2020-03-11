# Our open source tools

An index of the open source tools [FX Innovation](https://github.com/FXinnovation/) maintains for various ecosystems.

## Prometheus ecosystem

### Prometheus exporters
- [Azure Health exporter](https://github.com/FXinnovation/azure-health-exporter) : exposes Azure Health status as metrics (referenced on official [Prometheus doc](https://prometheus.io/docs/instrumenting/exporters/#apis)).
- [Azure Resources exporter](https://github.com/FXinnovation/azure-resources-exporter) : exposes Azure Resources status as metrics.
- [Alertmanager Silences Exporter](https://github.com/FXinnovation/alertmanager-silences-exporter) : exposes Alertmanager silences as metrics.

### Alertmanager webhook receivers
- [ServiceNow Alertmanager webhook](https://github.com/FXinnovation/alertmanager-webhook-servicenow) : manages ServiceNow incidents from Prometheus alerts (referenced on official [Prometheus doc](https://prometheus.io/docs/operating/integrations/#alertmanager-webhook-receiver)).
- [Rocket.Chat Alertmanager webhook](https://github.com/FXinnovation/alertmanager-webhook-rocketchat) : forward alerts from Prometheus Alertmanager to Rocket.Chat.

### Web UI
- [Alertmanager maintenance scheduler](https://github.com/FXinnovation/alertmanager-maintenance-scheduler) : a maintenance scheduler UI for Prometheus Alertmanager 

### Development templates
- [Alertmanager webhook template](https://github.com/FXinnovation/alertmanager-webhook-template) : starter template for quick development of Go lang Alertmanager webhook receivers.
- [Exporter template](https://github.com/FXinnovation/exporter-template) : starter template for quick development of Go lang Prometheus exporters.

# Our contribution to community

List of community projects on which [FX Innovation](https://github.com/FXinnovation/) is contributing.

- [CloudWatch exporter](https://github.com/prometheus/cloudwatch_exporter)
- [Azure Metrics exporter](https://github.com/RobustPerception/azure_metrics_exporter)
- [Rocket.Chat Go SDK](https://github.com/RocketChat/Rocket.Chat.Go.SDK)
