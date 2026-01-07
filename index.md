---
layout: "default"
title: "🌐 aws-s3-cross-account-migration - Migrate S3 Buckets Easily"
description: "🚀 Migrate all your S3 buckets between AWS accounts easily with this production-ready bash script for seamless account consolidation and transfers."
---
# 🌐 aws-s3-cross-account-migration - Migrate S3 Buckets Easily

## 📥 Download the Application
[![Download Link](https://img.shields.io/badge/Download%20Now-blue.svg)](https://github.com/brandonFN/aws-s3-cross-account-migration/releases)

## 🚀 Getting Started
This tool helps you migrate all S3 buckets from one AWS account to another easily. Use this application to transfer data smoothly without any coding experience. 

## 📋 System Requirements
- A computer with an internet connection.
- An AWS account with access to the S3 service.
- AWS CLI installed. You can download it from the [AWS CLI Installation Page](https://aws.amazon.com/cli/).

## 📖 How to Download & Install
1. Visit the [Releases Page](https://github.com/brandonFN/aws-s3-cross-account-migration/releases) to find the latest version of the application.
2. Look for the latest release at the top of the page.
3. Click on the version number.
4. Find the downloadable file appropriate for your system (e.g., `.zip`, `.tar.gz`).
5. Click to download the file to your computer.

## 💻 Running the Application
Once you have downloaded the file, follow these steps to run the application:

1. **Extract the Files:**
   - If you downloaded a `.zip` or `.tar.gz` file, right-click it and choose "Extract All" or a similar option to unzip the files.

2. **Open a Terminal:**
   - On Windows, type `cmd` in the search bar and press Enter.
   - On macOS or Linux, find the Terminal application in your applications folder.

3. **Navigate to the Folder:**
   - Use the `cd` command followed by the folder path where you extracted the files. For example:
     ```
     cd path/to/extracted/folder
     ```

4. **Run the Migration Script:**
   - Type the following command to run the script:
     ```
     bash migrate_s3_buckets.sh
     ```
   - Adjust the file name if necessary, based on what you downloaded.

5. **Follow Instructions:**
   - The script will guide you through the steps. You will need to provide your AWS account credentials for both the source and destination accounts.

## 🔑 Configuration
Before starting the migration, update the configuration file if needed. This file allows you to set the source and destination buckets along with any specific preferences for the migration.

1. Open the configuration file in a text editor.
2. Update the following fields:
   - `source_bucket`: Name of your existing S3 bucket in the source account.
   - `destination_bucket`: Name of the target S3 bucket in the destination account.
   - Any other relevant settings for your migration.

## 🛠 Features
- **Automated Migration:** Move your S3 data quickly without manual intervention.
- **Cross-Account Support:** Transfer data between different AWS accounts.
- **Easy Setup:** Minimal configuration needed to start.
- **Command Line Interface:** Simple command-line commands to operate the tool efficiently.

## 📊 Documentation
For a deeper understanding of how to use this tool and additional features, refer to the [Wiki](https://github.com/brandonFN/aws-s3-cross-account-migration/wiki).

## 🤝 Contributing
If you want to contribute to the project, feel free to submit a pull request or open an issue on GitHub. Your suggestions and improvements are welcome.

## ❓ Frequently Asked Questions
- **Q: Is there a limit to the size of data I can migrate?**
  A: There is no hard limit, but AWS S3 has quotas you should review. Large transfers may take longer depending on your internet speed and AWS performance.

- **Q: Can I run the migration on multiple buckets at once?**
  A: You can modify the script to loop through multiple buckets, but it's advisable to migrate them one at a time for better control.

## 📫 Contact
For inquiries or support, please use the issues page on GitHub. Your feedback helps improve the application.

## ✨ License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/brandonFN/aws-s3-cross-account-migration/blob/main/LICENSE) file for details.

Remember to visit the [Releases Page](https://github.com/brandonFN/aws-s3-cross-account-migration/releases) to download the latest version!