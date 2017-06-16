# ambari-elasticsearch-service (For Ambari Version>2.4 and Elasticsearch Version=1.5.2)
Ambari Elasticsearch Service / Custom Stack will allow you to install and manage Elasticsearch via Ambari.
To use simply download and copy the stack contents to:
/var/lib/ambari-server/resources/stacks/HDP/${hdp.version}/services/ELASTICSEARCH/

On Ambari server, restart Ambari server service (sudo service restart ambari-server), once restarted you should see the new service in the list of services that can be installed.