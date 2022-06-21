# k8s
Steps :
# 1 :
log into tn.cloud.creometry.com with your github then create a Public github repo
# 2 :
Create a yml file under the config folder
# 3 :
your desired yml file  will be  deployed automatically on Creometry dashboard 
# 4 :
you can then test deploying and monitoring apps in a real production cluster
# 5 :
Once deployed, grab your Kubeconfig from the platform dashboard 
and add it to Lens (choose your namespace in Lens since you can only acces one namespace)
Go back to the platform dashboard and deploy monitors 
and see what you get in network metrics, usage, memory, and disk if you have volumes.
