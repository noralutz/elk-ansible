# ELK

This project contains roles , example inventory and supporting templates to deploy a basic Elasticsearch, Logstash, and Kibana cluster, with Filebeat log aggregation.

You will need to create an ansible vault file in roles/nginx/vars/kib_admin.yml and set "kibadminpw" to populate the htpasswd file for kibana
