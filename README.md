kubectl apply -f jenkins-deploy-role.yml
Fixed the issue by defining role with corresponding permissions and rolebinding with group "system:serviceaccounts":
