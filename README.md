# ps-sidecar

Remember to fork the repo and **make all changes to your fork**. You cannot make changes to this repo (I'm not accepting PRs).

Simple HTML config used for K8s sidecar demos

```bash
# to induce init container error
sed -i 's/govindarajanv/govindarajan/g' pod.yml 

# gitops, make changes after running this 
while true; do curl <svc cluster-ip>; sleep 2; done
```

## References

- Pluralsight vols and multi-container Pods video course
- The Kubernetes Book (2021 and 2022 editions)
