1. Get details of deployment: `kubectl describe deployment clip-deployment`
<br>
![Screenshot](Images\deployment_describe.JPG)


2. Get details of the pods: `kubectl describe <your_pod>`
![Screenshot](Images\pod_describe.JPG)

3. Get details of the ingress: `kubectl describe ingress clip-ingress`
![Screenshot](Images\ingress_describe.JPG)

4. Check for CPU and Memory usage by each pod: `kubectl top pod`
![Screenshot](Images\top_pod.JPG)

5. Check details of node(s): `kubectl top node`
![Screenshot](Images\top_node.JPG)

6. Get details of all yaml configuration: `kubectl get all -A -o yaml`
