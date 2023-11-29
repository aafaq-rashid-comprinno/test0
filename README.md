# argoCD

# Post Installation of ArgoCD


Steps: 
1. Make a clone of the Argocd repositoy
    ```bash
    git clone https://github.com/vy-labs/argoCD.git 
    ```

2. Go to the base folder of the repository and then checkout to the required branch.
    ```bash
    cd argocCD && git checkout <branch>
    ```

3. apply the application manifests which are in the Argocd-applications directory
    ```bash
    kubectl apply -f Argocd-applications/<your-application-manifest-file>
    ```


Now check the application state in the Argocd console # test0
