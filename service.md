kubernetes services 

1st, if we are using the deploy.yaml. if the pod goes down.
replica set will up the pod.
but the new pod will get the new IP.
Because of that, the application team will not be able to access it.

By using the service, we can solve this problem.


1 load balancing.
2: Service service discovery
3. We can expose to external world by using load balancers.



