How to add SSH KEY to GIthub

To add an SSH key to your GitHub account, you can follow these steps:

1. Generate an SSH key pair:
   - Open the terminal on your local machine.
   - Enter the following command: `ssh-keygen -t ed25519 -C "your_email@example.com"`.
   - You can replace the email address with your own.
   - Press enter to accept the default file location and enter a passphrase (optional) when prompted.

2. Copy the SSH public key:
   - Use the following command to copy the public key: `pbcopy < ~/.ssh/id_ed25519.pub`.
   - If you're using Windows, you can open the file `id_ed25519.pub` located in `C:\Users\YourUsername\.ssh` and copy its contents.

3. Add the SSH key to GitHub:
   - Go to the GitHub website and log into your account.
   - In the top-right corner of any page, click on your profile picture and then select "Settings".
   - In the left sidebar, click on "SSH and GPG keys".
   - Click on "New SSH key" or "Add SSH key".
   - Provide a suitable title for your key in the "Title" field.
   - Paste your copied public key into the "Key" field.
   - Click on "Add SSH Key".

4. Verify that everything is working:
   - Open a terminal and run: `ssh -T git@github.com`.
     You might see a warning about authenticity of host, type 'yes' to continue.
     If everything is set up correctly, you should see a message like: "Hi username! You've successfully authenticated...".

Now you have successfully added an SSH key to your GitHub account. This will allow you to clone repositories and interact with GitHub using SSH instead of HTTPS.