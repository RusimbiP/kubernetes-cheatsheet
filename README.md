# Kubernetes cheat sheet 😉 

 ## 🤫 Secrets
  **Creating secrets:**
  `kubectl create secret generic {name of the secret} --from-literal={key}={value}`
  
  **Getting secrets:**
  `kubectl get secrets`
  
  ## Namespaces
   **Getting Namespaces:**
  `kubectl get namespace`
  
   **Cross Namespace Service Communication**
   `http://NAMEOFSERVICE.NAMESPACE`
   
  ## Services
   **Getting Services:**
  `kubectl get Services`
  
   **Getting Services inside Namespaces:**
  `kubectl get Services -n {name of the namespace}`
  
## Deleting commands
  **Deleting all podes:**

  `kubectl delete --all pods`

  **Deleting all deployments:**

  `kubectl delete --all deployments`
  
__Emojis from : https://emojipedia.org/__
