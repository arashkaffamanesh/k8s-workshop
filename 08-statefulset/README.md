# StatefulSet Demo

StatefulSet is the workload API object used to manage stateful applications.

Manages the deployment and scaling of a set of Pods , and provides guarantees about the ordering and uniqueness of these Pods.

Like a Deployment , a StatefulSet manages Pods that are based on an identical container spec. Unlike a Deployment, a StatefulSet maintains a sticky identity for each of their Pods. These pods are created from the same spec, but are not interchangeable: each has a persistent identifier that it maintains across any rescheduling.

A StatefulSet operates under the same pattern as any other Controller. You define your desired state in a StatefulSet object, and the StatefulSet controller makes any necessary updates to get there from the current state.

To create a statefulSet run the following command.

```
$ kubectl create -f 01-statefulSet.yaml
```


