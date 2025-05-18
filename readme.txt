
# Hosting an HTML Page on cPanel Hosting


## Introduction

This documentation will guide you through the steps to host an HTML page using cPanel. If your hosting provider does not support HTML files directly, this guide will also show you how to convert your HTML file to a PHP file.

## Prerequisites

- Access to a cPanel account.
- An HTML file ready to be uploaded.
- Basic understanding of file management in cPanel.

## Steps to Host an HTML Page

### 1. Log in to cPanel

1. Open your web browser.
2. Enter your cPanel URL (e.g., `https://yourdomain.com/cpanel`).
3. Enter your username and password.
4. Click the `Log in` button.

### 2. Access the File Manager

1. Once logged in, locate the `Files` section.
2. Click on the `File Manager` icon.

### 3. Navigate to the Public HTML Directory

1. In the File Manager, navigate to the `public_html` directory. This is the root directory for your website files.
2. If you want to place the HTML file in a subdirectory, navigate to or create the desired subdirectory.

### 4. Upload the HTML File

1. Once inside the `public_html` directory (or desired subdirectory), click the `Upload` button in the top toolbar.
2. Click the `Select File` button or drag your HTML file into the upload box.
3. Wait for the upload to complete. You will see a progress bar indicating the upload status.
4. Once uploaded, click the `Go Back to...` link to return to the File Manager.

### 5. Verify the HTML Page

1. In the File Manager, you should now see your uploaded HTML file.
2. To verify that your page is working, open your web browser and go to `http://yourdomain.com` or `http://yourdomain.com/{desire_folder}` (replace `yourdomain.com` with your actual domain and `index.html` with the name of your HTML file).



## Converting HTML to PHP (if HTML is not supported)

If your hosting provider requires PHP files instead of HTML files, follow these steps:

### 1. Rename Your HTML File

1. In the File Manager, locate your HTML file.
2. Right-click the file and select `Rename`.
3. Change the file extension from `.html` to `.php` (e.g., `index.html` to `index.php`).
4. Click the `Rename File` button.

### 2. Verify the PHP Page

1. In your web browser, go to `http://yourdomain.com` or `http://yourdomain.com/{desire_folder}` (replace `yourdomain.com` with your actual domain and `index.php` with the name of your PHP file).
2. Ensure that the page loads correctly.


## Conclusion
By following these steps, you can successfully host an HTML page on cPanel. If your hosting provider requires PHP files, you can easily convert your HTML file to a PHP file by renaming it and adding PHP code as needed. This guide ensures your web content is accessible regardless of the file format requirements of your hosting provider.
       