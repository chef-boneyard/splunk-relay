# Splunk relay for Chef Automate

[![Deploy to Azure](https://azuredeploy.net/deploybutton.svg)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fchef-partners%2Fsplunk-relay%2Fmaster%2Fazuredeploy.json)

Use this Chef Automate Splunk integration to channel notification messages such as:

 - Chef Client run failures
 - Compliance failures

into Splunk.

You will need a Splunk account that has been configured with an [HTTP Event Collector input](http://docs.splunk.com/Documentation/SplunkCloud/6.6.1/Data/UsetheHTTPEventCollector). From Splunk you will need the customer id and the token in order to post data.

## How to deploy the template

Simply press the [Deploy to Azure](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fchef-partners%2Fsplunk-relay%2Fmaster%2Fazuredeploy.json) button to launch the template within your Azure Subscription. You are required to complete the form:

