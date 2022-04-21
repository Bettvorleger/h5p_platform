# h5p_platform

1. Run <code>docker-compose up -d</code>
2. Wait for the containers to build, then visit http://localhost for the moodle login page
3. Use "admin" and "qwer1234" to login as admin user
5. Install the official H5P plugin (Site administration > Plugins > Install Plugins) with the .zip from https://moodle.org/plugins/mod_hvp
6. Create a course and use the two example .h5p files in the "h5p_test" folder

To access the SQL LRS visit http://localhost:4040 and use the same login as above

<b>TODO</b>: Trigger an xAPI event inside moodle and receive the event in the SQL LRS.
Seems like it's not natively supported by moodle to save the xAPI statements to another LRS, so the H5P plugin has to be modified (using this <a href="https://digitallearningsolutions.com.au/connecting-h5p-interactive-activity-in-moodle-to-an-lrs/?utm_source=ReviveOldPost&utm_medium=social&utm_campaign=ReviveOldPost">guide</a>
