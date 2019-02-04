# kubundancy
Multi-region Kubernetes deployment 

## Instructions 
*(rough draft of instructions)

1. Build infrastructure: this will build EKS masters, worker nodes etc. 
	* `cd` to `terraform` and run `terraform apply`
	* Install dashboard: `./setup.sh` (**needs to be updated**)
2. Install helm into cluster (**may not be needed**) 
3. Install ExternalDNS - from `externalDNS` dir 
4. Deploy service 
