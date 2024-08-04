# Sample Node.js App for Render Deployment Using Terraform

This project is a simple Node.js application used to demonstrate deploying a service on Render using Terraform.

## Project Structure

```
backend-service/
├── app.js
├── package.json
├── package-lock.json
└── terraform/
    └── main.tf
```

## Description

This is a basic Node.js application built with the Express framework. The application serves a simple "Hello, World!" message when accessed. The purpose of this project is to show how to deploy a Node.js application on Render and manage the infrastructure using Terraform.

## Prerequisites

- Node.js installed on your local machine.
- A Render account.
- A GitHub account.
- Terraform installed on your local machine.

## Steps to Deploy

1. **Clone the Repository**: Clone this repository to your local machine.
   
   ```sh
   git clone https://github.com/yourusername/backend-service.git
   cd backend-service
   ```

2. **Install Dependencies**: Install the required dependencies.

   ```sh
   npm install
   ```

3. **Set Up Terraform**: Navigate to the `terraform` directory and initialize Terraform.

   ```sh
   cd terraform
   terraform init
   ```

4. **Deploy with Terraform**: Apply the Terraform configuration to deploy the service on Render.

   ```sh
   terraform apply
   ```

   Confirm the apply action when prompted by typing `yes`.

## Environment Variables

The following environment variables are used in the Terraform configuration:

- `NODE_ENV`: The environment in which the application is running (default is `production`).

## Build and Run Commands

- **Build Command**: `npm install`
- **Start Command**: `npm start`

## Additional Information

- For more information on Terraform, visit the [Terraform documentation](https://www.terraform.io/docs).
- For more information on Render, visit the [Render documentation](https://render.com/docs).

## License
