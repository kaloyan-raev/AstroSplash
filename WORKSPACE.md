Welcome to the Developer Workspace of the Astro Splash application!

This workspace has Zend Server 9.0 installed with Z-Ray and PHP 7.

The project's code is already cloned from GitHub and available in the Project Explorer view on the left side.

At the bottom left corner you will see that the "auto setup" command is finishing the setup of your workspace.

It executes the following steps:

1. Change the permissions of the project's `data/` folder. Required by Doctrine to write its cache.
2. Change the web server's document root to the project's `public/` folder. Required by Zend Expressive to run correctly.
3. Set the Zend Server UI URL in the Z-Ray configuration. Required by Z-Ray to run correctly.
4. Install the Composer dependencies.
5. Enable the Process Control (pcntl) extension in Zend Server. Required by the script for fetching the thumbnails from NASA.
6. Run `bin/update.php` to fetch the thumbnails from NASA.
7. Start Zend Server.

You can see the command's output at the bottom pane.

The command is finished when you see `Zend Server started...` in the output.

Then you can click on the Preview link, which will open a new browser tab with the running application.