# Deploy a static website on S3 using Terraform

## Overview

This beginner-friendly project demonstrates how to host a static website on Amazon S3 using Terraform. It provides step-by-step instructions for setting up Terraform, configuring an S3 bucket, and managing resources efficiently. Please be mindful of AWS costs associated with the resources created.

## Prerequisites

1. **Terraform Installation**

   Install Terraform on your local machine by following the official guide by HashiCorp:
   - [Install Terraform using CLI](https://learn.hashicorp.com/tutorials/terraform/install-cli)
   - [Download Terraform](https://www.terraform.io/downloads.html)

2. **Visual Studio Code Installation**

   Download and install Visual Studio Code by following this guide:
   - [Download Visual Studio Code](https://code.visualstudio.com/download)

## Task Details

1. **Sign in to AWS Management Console**

   - Access the AWS Management Console at [AWS Console](https://aws.amazon.com/console/).

2. **Setup Visual Studio Code**

   - Open Visual Studio Code and configure it for your Terraform project.

3. **Create a `variables.tf` File**

   - Define your variables in a `variables.tf` file.

4. **Create an S3 Bucket and Its Components**

   - Define the S3 bucket and its components in the `main.tf` file.

5. **Confirm Terraform Installation**

   - Verify the installation by checking the version:
     ```bash
     terraform version
     ```

6. **Apply Terraform Configurations**

   - Execute the Terraform commands to apply the configurations:
     ```bash
     terraform init
     terraform apply
     ```

7. **Check AWS Resources**

   - Verify the created S3 bucket and its settings in the AWS Management Console.

8. **Host Your Static Website**

   - Upload your static website files to the S3 bucket and configure the bucket for static website hosting.

9. **Retrieve the Website URL**

   - Obtain the website URL from the S3 bucket properties and test your static website.

10. **Delete Resources**

    - Remove the resources by executing:
      ```bash
      terraform destroy
      ```

## Cost Considerations

Be aware that creating and managing AWS resources may incur costs. Review and understand the pricing for S3 storage and other related services you are using. Always delete resources when they are no longer needed to avoid unnecessary charges.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Notes

- Ensure you follow best practices for managing AWS resources and Terraform configurations.
- For additional help, refer to the official [Terraform Documentation](https://www.terraform.io/docs) and [AWS Documentation](https://docs.aws.amazon.com/), or seek support from the community.
