# Usage
### Please add the following code 
```
module "app" {
  source    = "farrukh90/release/helm"
  namespace = "default"
  name      = "wordpress"
  wait      = false
  chart     = "./application"
  values = []
}
```
