# agriaf-gravitee-apim


helm install elasticsearch-gravitee bitnami/elasticsearch --set master.replicas=3,ingest.enabled=true

helm install gravitee -f custom-values.yaml graviteeio/apim3

helm upgrade gravitee -f custom-values.yaml graviteeio/apim3

Ref.:
https://community.gravitee.io/t/kubernetes-helm-gravitee-installation-complete-tutorial/373
