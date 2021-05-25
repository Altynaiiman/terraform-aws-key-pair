# Please copy paste below code

```
module "app" {
  source       = "altynaiiman/key-pair/aws"
  region       = "us-east-1"
  key_name     = "review-class"
  key_location = "~/.ssh/id_rsa.pub"
}
```