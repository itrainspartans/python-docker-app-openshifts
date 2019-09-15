# python-docker-app
python-docker-app

How to run a docker container with Newrelic key and enable monitoring

docker run -p 5000:5000 -e NEW_RELIC_LICENSE_KEY=xxxxx -e NEW_RELIC_APP_NAME=python-app manee2k6/py-newrelic

Openshift deployment:

https://blog.openshift.com/using-new-relic-to-monitor-applications-on-openshift/
