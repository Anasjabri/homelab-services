Secrets(route53) should be in the same namespace in which cert-manager is running.

I now use helm chart to install cert-manager
* Set the following args if planning to use DNS acme challenges to fetch certs 
`--set 'extraArgs={--dns01-recursive-nameservers=8.8.8.8:53,1.1.1.1:53}'`