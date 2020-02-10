gen_mta Application

Build Command:
```
cd mta_gen_mta ; mkdir -p target ; mbt build -p=cf -t=target --mtar=mta_gen_mta.mtar
```

Deploy Command:
```
cf deploy target/mta_gen_mta.mtar -f
```

UnDeploy Command:
```
cf undeploy gen_mta -f --delete-services
```
