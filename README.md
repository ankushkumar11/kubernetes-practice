# kubernetes-practice

### Basic use-cases -

Create a deployment running nginx version 1.16.1 that will run in 2 pods that uses /var/www as its root dir and Nginx should run on port 8090.

```sh
$ kubectl apply -f nginx_var_www_deployment.yml
```



#### Kubernetes

See [KUBERNETES.md](https://kubernetes.io/docs/concepts/)


### Todos

 - Canary Upgrade

License
----

MIT
