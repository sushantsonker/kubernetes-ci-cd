node {

    stage "Build"
    
        sh "echo Build"
    
    stage "Push"

        sh "echo push" 

    stage "Deploy"

        sh "echo Deploy"
        kubernetesDeploy configs: "applications/busybox/k8s/pod.yaml", kubeconfigId: 'kenzan_kubeconfig'       

}
