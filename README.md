# Azure CLI v2 

Setup a new linux VM in azure using the new Azure CLI (AZ)


### Create a new Resource Group 

```{r, engine='bash', count_lines}
      $ az resource group create -l westus -n MyGroup

```


### Create a new VM in the new RG 

```{r, engine='bash', count_lines}
    $ az vm create -g MyGroup -n MyVM --image ubuntults

```


### Connect to the new VM 

```{r, engine='bash', count_lines}
    $ az ssh <Machine IP>

```
