# MonoVM VPS Hosting WHMCS Reseller Module #
The MonoVM VPS Hosting WHMCS Reseller Module provides a seamless solution for resellers to offer MonoVM's VPS Hosting services through the WHMCS platform. This module is designed to automate VPS provisioning, management, and billing, ensuring a smooth experience for both resellers and end-users.

# https://monovm.com/vps-server/ #

## Features ##
Automated VPS Provisioning: Instantly provision MonoVM VPS instances through WHMCS.
Customizable Plans: Configure and manage VPS hosting plans tailored to your customers.
Comprehensive Billing Integration: Full integration with WHMCS billing to automate invoicing and payment collection.
User-friendly Management: Allow customers to manage VPS settings directly from their WHMCS client area.
Detailed Server Control: Reboot, suspend, and terminate VPS instances from the WHMCS admin panel.
## Requirements ##
WHMCS Version: Compatible with WHMCS 8.0 and above.
MonoVM API Access: Requires access to the MonoVM API (contact MonoVM support for API credentials).
PHP Version: Requires PHP 7.4 or above.
## Installation ##
### 1. Download the Module ###
Download the latest release from the MonoVM GitHub repository.

### 2. Upload to WHMCS ###
Unzip the downloaded file.
Upload the module files to the /modules/servers/monovm/ directory in your WHMCS installation.
### 3. Activate the Module ###
Log in to your WHMCS Admin Panel.
Go to Setup > Products/Services > Servers.
Click Add New Server and configure the MonoVM VPS server with your API credentials.
### 4. Configure Product ###
Go to Setup > Products/Services > Products/Services.
Click Create a New Product and select MonoVM VPS as the module.
Customize the VPS product settings as needed.
## Configuration ##
### API Settings ###
Navigate to Setup > Products/Services > Servers in WHMCS.
Select the MonoVM VPS server.
Enter your MonoVM API key, secret, and other required credentials.
Test the connection to ensure successful integration.
### Product Options ###
Customize the VPS product options, such as:

Plan Selection: Choose from predefined MonoVM VPS plans.
Disk Space, Bandwidth, and RAM: Customize specifications per client needs.
Additional Add-ons: Configure add-ons like additional IPs, SSL certificates, etc.
## Usage ##
Once installed and configured, resellers can start selling MonoVM VPS Hosting packages. Customers can manage their VPS directly from the WHMCS client area with options to restart, reinstall, or access console features (if enabled).

## Support ##
For any issues or additional support, please contact MonoVM Support or reach out through the GitHub Issues page.

## License ##
This module is licensed under the MIT License.

## Contribution ##
Contributions to improve this module are welcome. Please fork the repository and create a pull request for any changes.

## https://monovm.com/vps-server/ ##
