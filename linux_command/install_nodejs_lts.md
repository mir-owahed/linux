Sure, here's the content rewritten in Markdown format:

```markdown
# Documentation: Installing Node.js LTS using Downloaded Tarball

This document details the steps to install Node.js Long-Term Support (LTS) version 20.11.1 on a Linux system using a downloaded tarball.

## Prerequisites:

- Downloaded tarball file: `node-v20.11.1-linux-x64.tar.xz` (replace with the actual filename)
- Terminal access
- Root privileges (recommended)

## Steps:

1. **Navigate to the Downloads directory:**

   ```bash
   cd Downloads
   ```
   *Use code with caution.*

2. **List the contents of the directory:**

   ```bash
   ls
   ```
   *Use code with caution.*

3. **Extract the tarball:**

   ```bash
   tar xf node-v20.11.1-linux-x64.tar.xz
   ```
   *Use code with caution.*

4. **List the extracted directory contents:**

   ```bash
   ls
   ```
   *Use code with caution.*

5. **Move the extracted directory to a desired location:**

   ```bash
   mv node-v20.11.1-linux-x64 ~/nodejs
   ```
   *Use code with caution.*

6. **Navigate to the bin directory within the installed Node.js directory:**

   ```bash
   cd ~/nodejs/bin/
   ```
   *Use code with caution.*

7. **Verify Node.js and npm versions:**

   ```bash
   # Check node version
   ./node -v

   # Check npm version
   ./npm -v
   ```
   *Use code with caution.*

8. **Optional:** Add Node.js to PATH (for system-wide access):

   a. Open the `.bashrc` file in a text editor:

   ```bash
   nano ~/.bashrc
   ```
   *Use code with caution.*

   b. Add the following line, replacing `/path/to/nodejs/bin` with the actual path to your bin directory:

   ```bash
   export PATH=$PATH:/path/to/nodejs/bin
   ```
   *Use code with caution.*

   c. Save the file and source it to apply changes:

   ```bash
   source ~/.bashrc
   ```
   *Use code with caution.*

9. **Verify Node.js accessibility from any directory:**

   ```bash
   cd
   ls -la
   node -v
   npm -v
   ```
   *Use code with caution.*

## Additional notes:

- Running commands with `./` is often unnecessary, as `node` and `npm` might already be available in your PATH.
- Setting the PATH is optional but recommended for system-wide access to Node.js tools like `node` and `npm`.
- Remember to replace `/path/to/nodejs/bin` with the actual path you used in step 8.
- This documentation serves as a guide and might require adjustments depending on your specific system and preferences.

I hope this documentation helps you successfully install and use Node.js LTS on your system!
```

Save this content in a file with the `.md` extension, such as `install_node_lts.md`.
