# Fortinet Security Session

## Stuff I Like

### Internet Services Database (ISDB)

No longer are you resigned to always entering complex firewall rules with vast lists of IPS or ports.

The Internet Service Database is a comprehensive public IP address database that combines IP address range, IP owner, service port number, and IP security credibility. The data comes from the FortiGuard service system. Information is regularly added to this database, for example, geographic location, IP reputation, popularity & DNS, and so on. All this information helps users define Internet security more effectively. You can use the contents of the database as criteria for inclusion or exclusion in a policy.

![ISDB](images/isdb.png)

[Online help for ISDB](https://docs.fortinet.com/document/fortigate/6.4.5/administration-guide/849970/policy-with-internet-service)

### Automation Stitches

Automation stitches allow you to set up automatic actions in response to Security Fabric events, such as a compromised host, downed connection, HA failover, or practically any other event.

![Automation Stitch](images/auto1.png)

Some of the kinds of actions you can perform for an event:

* Run a script
* Send an email or Slack message
* Fire off a webhook (super useful and flexible!)
* Execute an Azure/Google Cloud function

You *can* configure multiple actions to run.

![Automation Stitch Actions](images/auto3.png)

[Online help for Automation Stitches](https://docs.fortinet.com/document/fortigate/6.4.5/administration-guide/139441/automation-stitches)

### External Connectors

## Fortinet Training

Fortinet offers a bunch of great online training, and it's currently free during the pandemic.

Each course has a great table of contents that lets you skip around material quickly.

Check it out: https://training.fortinet.com/

## FortiAnalyzer

### Keys to understanding FortiAnalyzer reporting

#### Components of a FortiAnalyzer report

* Dataset: A dataset is essentially a SQL query and the resulting table of data.
* Chart: A chart is a report component fed by data from a dataset. A chart can be in the form of a pie graph, a line graph, a table, et cetera.
* Report: A report is pretty much a series of charts.