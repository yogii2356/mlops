# mlops 


Create a Flask app that returns “Hello, World!”, containerize it with Docker, and run it.

 Here is how you can create and deploy a Kubernetes "Hello World" web app using Docker Desktop, and expose it on localhost using a NodePort service:

✅ Step 1: Create a simple Flask app – app.py



✅ Step 2: Create a Dockerfile

✅ Step 3: Build and push the Docker image
If you use Docker Hub, replace yourusername with your Docker Hub ID.
if you don't have docker hub , so create account.


docker build -t yourusername/hello-world .
docker push yourusername/hello-world


✅ Step 4: Create deployment.yaml


✅ Step 5: Create service.yaml (NodePort)

✅ Step 6: Apply the Kubernetes manifests

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

✅ Step 7: Access your app
Now go to your browser and open:


http://localhost:31234/

Hello, World from Kubernetes!