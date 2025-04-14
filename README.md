# Install Burpsuite's or any CA certificate to system store in Android 15
For Android 15 users, managing certificates can sometimes be a bit challenging, especially when you need to move a certificate from the user store to the system store. But worry not! With the help of a handy tool called Allow-All-Cert-Fixer, you can easily accomplish this task. In this blog, we'll walk you through the steps to install a new certificate to the system store or move an existing certificate from the user store to the system store using Allow-All-CertFixer.
What is Cert-Fixer?
GitHub - pwnlogs/cert-fixer: Cert-Fixer is a Magisk module that copies all the user certificates to system certificate store.
Allow-All-Cert-Fixer is a Magisk module that simplifies the process of moving certificates from the user store to the system store on rooted Android devices. By leveraging the power of Magisk, Allow-All-Cert-Fixer ensures that your certificates are properly installed and trusted by the system, making it easier for apps to recognize and trust them.
Prerequisites
Before you get started, make sure you have the following prerequisites:
Rooted Device: Ensure your Android device is rooted using Magisk.
Magisk Installed: Download and install the latest version of Magisk.

Step-by-Step Guide
Follow these steps to install a new certificate to the system store or move an existing certificate from the user store to the system store:
Download Allow-All-CertFixer:

Go to the Allow-All-Cert-Fixer GitHub repository and download the latest version of the Allow-All-Cert-Fixer module.

2. Install Allow-All-CertFixer:
Open the Magisk Manager app on your device.
Go to the "Modules" section.
Tap on the "Install from Storage" button.
Select the downloaded Allow-All-CertFixer zip file.
Once the installation is complete, reboot your device.

3. Install Your Certificate:
If you need to install a new certificate, go to your device's settings and install the certificate as you normally would. Allow-All-Cert-Fixer will automatically move it from the user store to the system store during boot.

4. Verify the Certificate:
After rebooting, you can verify that the certificate has been moved to the system store. Open your browser or any app that requires the certificate and check if it recognizes and trusts the certificate.

Benefits of Using Allow-All-Cert-Fixer
Using Allow-All-Cert-Fixer offers several benefits:
Enhanced Security: Ensures that your certificates are trusted by the system, enhancing the security of your device.
App Compatibility: This makes it easier for apps to recognize and trust the certificates.
Simplified Process: Automates the process of moving certificates, saving you time and effort.
