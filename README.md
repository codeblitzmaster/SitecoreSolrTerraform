# Sitecore Solr Terraform
Terraform templates for Sitecore Solr installation on Microsoft Azure Windows VM. 

This Terraform takes care of complete automation by:
  - Creating a Public IP assigned Azure Windows VM
  - Installing Solr
  - Create Sitecore Cores
  - Create xConnect(xDB) Cores
  - Firewall updates for Solr to be accessed externally
