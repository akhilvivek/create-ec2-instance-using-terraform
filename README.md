# create-ec2-instance-using-terraform
provider "aws"
{
region = "us-east-1"
}
resource "aws_instance" "this"
{
  ami                     = "ami-0dcc1e21636832c5d"
  instance_type           = "m5.large"
}
