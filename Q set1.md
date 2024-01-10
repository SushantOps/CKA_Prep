## Q1. Create a new pod called 'admin-pod' with image 'busybox' Allow pod to able to set system, the container should sleep for 3200sec.

sol:-
```
kubectl run admin-pod --image=busybox  --command sleep 3200 -dry-run=client -o yml > 1.yml
```


