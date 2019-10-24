# OpenShift DokuWiki 

OpenShift DokuWiki template with sensible settings changed in Dockerfile

* Create & install template:

  ``
  oc process -f dokuwiki.yml | oc apply -f - 
  ``
