# NestJS Serverless with Serverless PostgreSQL

## Overview

This repository contains a serverless backend application built with [NestJS](https://nestjs.com/), designed to run on AWS Lambda using the [Serverless Framework](https://www.serverless.com/). It also utilizes a PostgreSQL database through the [Serverless PostgreSQL Plugin](https://github.com/andyseal/serverless-postgresql) and the [Neon Database](https://neondb.io/) for efficient data storage.

## Features

- Serverless architecture using AWS Lambda and API Gateway.
- PostgreSQL database integration for data storage.
- Secure and scalable RESTful API endpoints.
- Built-in authentication and authorization mechanisms.
- Easily deployable with the Serverless Framework.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed.
- An AWS account with the necessary permissions.
- Serverless Framework CLI installed (`npm install -g serverless`).

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone git@github.com:idevnerds-Arslan/serverless-pg-nextjs.git
   cd nestjs-serverless-postgresql
   ```

2. Install the project dependencies

   ```bash
   npm install
   ```

3. Configure your AWS credentials

   ```bash
   serverless config credentials --provider aws --key YOUR_AWS_ACCESS_KEY --secret YOUR_AWS_SECRET_KEY
   ```

   Note:
   if you don't have serverless installed then first install it:

   ```bash
   npm install -g serverless
   ```

4. Deploy the application to AWS Lambda

   ```bash
   serverless deploy
   ```

   Note:
   if you don't have serverless installed then first install it

   ```bash
   npm install -g serverless
   ```

5. Access your deployed API endpoints.

   Use the provided API endpoints to interact with your serverless application.
   Customize the application logic by modifying the NestJS controllers and services.
   Configure and manage your PostgreSQL database using the Serverless PostgreSQL Plugin.
   Monitor and troubleshoot your Lambda functions using AWS CloudWatch.
   Documentation
   For detailed documentation and usage examples, please refer to the Wiki.

6. Acknowledgments
   [NestJS](https://nestjs.com/) - A progressive Node.js framework.
   [Serverless Framework](https://www.serverless.com/) - The Serverless Application Framework.
   [Serverless PostgreSQL Plugin](https://github.com/andyseal/serverless-postgresql) - For PostgreSQL integration with Serverless.
   [Neon Database](https://neondb.io/) - A serverless, auto-scaling database for AWS Lambda.
