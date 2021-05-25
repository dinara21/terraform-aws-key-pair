# Please copy paste below code

```
module "dinara" {
  source       = "dinara21/key-pair/aws"
  region       = "us-east-1"
  key_name     = "review"
  key_location = "~/.ssh/id_rsa.pub"
}
```