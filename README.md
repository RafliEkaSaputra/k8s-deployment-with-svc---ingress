# k8s-deployment-with-svc---ingress

1. create directory final

        mkdir final

2. create 3 file yaml 

        vi nama.yaml

3. run file yaml

        kubectl apply -f nama.yaml

4. edit nginx-controller


        kubectl edit svc nama-service -n namespace

5. run in web browser

        http://final.local
