# Installing and Synchronizing Argo CD

## Installing Argo CD

1. Download the latest version of Argo CD from the [official Argo CD documentation](https://argo-cd.readthedocs.io/en/stable/getting_started/) and follow instructions.

## Synchronizing Argo CD with Applications

1. Open the Argo CD web interface by accessing `http://localhost:8080` (or use the appropriate server address).
2. Log in using your username and password.
3. Add an application by clicking the "Add Application" button or similar.
4. Specify the repository URL where the application configuration is located.
5. Set synchronization parameters, such as the path to configuration files and synchronization interval.
6. Click the "Save" button or similar to start the application synchronization.

1. Modify the `values.yaml` file to customize the Argo CD installation.
2. Open the `values.yaml` file in a text editor.
3. Update the desired configuration options, such as ingress settings, storage options, and authentication methods.
4. Save the `values.yaml` file.

## Accessing Argo CD Dashboard

1. Retrieve the Argo CD server URL by running the command `kubectl get svc -n argocd`.
2. Open a web browser and navigate to the Argo CD server URL.
3. Log in using the default username `admin` and the password retrieved during installation.
4. Explore the Argo CD dashboard to manage applications and monitor synchronization status.

## Demonstration
Here is a quick demonstration of an MVP app on Argo CD tool
[Watch the demonstration](https://youtu.be/Elln7ZN0Y2g)

