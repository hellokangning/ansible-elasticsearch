# ansible-elasticsearch

This repo aims to deploy Elasticsearch with Ansible quickly.

There three tas in site.yml that we can setup Ambari step by step:

- install-es

- config-es

- start-es

- stop-se


Before excuting `ansible-playbook site.yml --tags install-es -i hosts`, you must modify these files below:

1. `hosts`, for all nodes

2. `group_vars`, for configs

