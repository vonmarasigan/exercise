provider "aws" {
  region = "us-east-1"
}

resource "aws_instance" "test-ec2123" {
  ami           = "ami-0c614dee691cbbf37"
  instance_type = "t2.micro"
  key_name      = "von-keypair"
  tags = {
    Name = "von"

  }
}
