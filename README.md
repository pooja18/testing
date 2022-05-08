# testing of deployment of mediawiki application on kubernetes cluster
# all process should be triggered via jenkins pipeline
# jenkins pipeline will checkout source code , build the images of application and push it to docker hub repoistory make it as public 
# After pushing image , kubernetes deploy the application with and service will be as NodePort service for accessing the application externally.
