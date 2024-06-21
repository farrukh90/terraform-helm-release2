# Usage
### Please add the following code 
```
module "app" {
  source    = "farrukh90/release2/helm"
  namespace = "default"
  name      = "wordpress"
  wait      = false
  chart     = "./application"
  values = []
}
```
