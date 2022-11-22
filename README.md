## How to make cluter IP?

This type of service is used to make a network on which the pods can connect in kubernetes.

For this template to work, you have to give the `name` to the service in place of `<desired-service-name>`. After that you have to mention the `namespace` in place of `<expected-namespace>` in which you are deploying your application and the cluster IP. Then we have `appliaction port` on which the application will run and the `application name`. 

You can deploy this service by `kubectl apply -f cluster-ip.yml - <namespace>`