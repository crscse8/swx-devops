all: .terraform plan

clean:
	[ ! -d .terraform ] || rm -fr .terraform
	[ ! -f terraform.tfstate.backup ] || rm -f terraform.tfstate.backup

plan:
	terraform plan

apply:
	terraform apply

.terraform:
	bash ./tf.sh
