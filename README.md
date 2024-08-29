# Installing-gke-gcloud-auth-plugin-for-accessing-gke-cluster-from-local-desktop
GKE plugin for accessing gke cluster from local desktop

    curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo gpg --dearmor -o /usr/share/keyrings/cloud.google.gpg
    
    echo "deb [signed-by=/usr/share/keyrings/cloud.google.gpg] https://packages.cloud.google.com/apt cloud-sdk main" | sudo tee -a /etc/apt/sources.list.d/google-cloud-sdk.list
    
Now first install CLI

    sudo apt-get update && sudo apt-get install google-cloud-cli

then install google cloud sdk

    sudo apt-get update && sudo apt-get install google-cloud-sdk
    
then install gke-gcloud-auth-plugin

    sudo apt-get update && sudo apt-get install google-cloud-cli-gke-gcloud-auth-plugin

site link:

        https://cloud.google.com/sdk/docs/install-sdk#deb
