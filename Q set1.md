## Q1. Create a new pod called 'admin-pod' with image 'busybox' Allow pod to able to set system, the container should sleep for 3200sec.

sol:-
```
kubectl run admin-pod --image=busybox  --command sleep 3200 -dry-run=client -o yml > 1.yml
```

## Q2. A kubeconfig file called test.kubeconfig has been created in /root/TEST . There is something wrong with configuration so troubleshoot and fix it


## Q3. Create a new deployment called web-proj-268 with image nginx:1.16 and 1 replica. Next upgrade the deployment to version 1.17 using rolling upddate. Make sure that the version upgrade to recorded in the resource annotation.

## Q4. 

