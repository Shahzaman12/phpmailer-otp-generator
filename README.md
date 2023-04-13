# PHP OTP Generator

This is a simple PHP script for generating one-time passwords (OTPs) and sending them to users' email addresses using the PHPMailer library. With built-in support for SSL/TLS encryption and configurable email server settings, this generator provides a secure and reliable solution for two-factor authentication, password reset workflows, and other applications that require user verification.

## Installation

1. Clone or download the repository to your web server
2. Install the PHPMailer library using Composer or by downloading it from the official website
3. Modify the `$config` array in `index.php` to match your email server settings
4. Customize the email subject and body in `index.php` as needed
5. Access `index.php` in your web browser to generate and send an OTP

## Requirements
1. PHP 7.0 or later
2. PHPMailer library
