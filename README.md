# netuitive.packages.aws.nlb

For detailed information on this package, please refer to the [online documentation](https://help.netuitive.com/Content/Integrations/aws.htm).

[Cloudwatch reference](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-cloudwatch-metrics.html)

## Release History

### Version next

* Add a computed metric to calculate the percentage of unhealthy hosts
* Add policy for Active Flows Count (connections)
* Add policy for Process Bytes
* Add two policies for Unhealthy hosts (warning at 50% and critical at 75%)

### Version 1.0.0

* Initial production release of the package for monitoring AWS Network Load Balancer (NLB) resources.
