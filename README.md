# Usage
### Please add the  folloving code
```
module "appruslan" {
  source    = "ruslan8424/release/helm"
  namespace = "default"
  name      = "wordpress"
  wait      = false
  chart     = "./application"
  values = []

}

```