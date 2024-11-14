terraform {
    backend "s3" {
        bucket = "terraform-state-github-actions"
        key    = "terraform.tfstate"
        region = "eu-central-1"
    }
}