#deploy all avaliable image

kubectl apply -f https://raw.githubusercontent.com/aws-containers/retail-store-sample-app/main/dist/kubernetes/deploy.yaml



kubectl wait --for=condition=available deployments --all


