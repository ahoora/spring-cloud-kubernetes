Spring Cloud Kubernetes
-----------------------

Spring Cloud integreation with Kubernetes

### Features

-   Auto configuration for the Kubernetes client
-   DiscoveryClient implementation for Kubernetes
-   Health Indicator for Pods
-   Automatic activation of the "Kubernetes" profile when running inside Kubernetes.


### Building

You can just use maven to build it from sources:

    mvn clean install
    
    
### Usage

The project provides a "starter" module, so you just need to add the following dependency in your project.
    
    <dependency>
        <groupId>io.fabric8</groupId>
        <artifactId>spring-cloud-start-kubernetes</artifactId>
        <version>x.y.z</version>
    </dependency>
    