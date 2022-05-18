# CodeIgniter

# Downloading CodeIgniter
https://codeload.github.com/bcit-ci/CodeIgniter/zip/3.1.13

# Upload .htaccess file in Main Folder

your_codeigniter_folder_name/.htaccess


# Update Base url in Config file
/application/config/config.php

$config['base_url'] = 'http://localhost/your_codeigniter_folder_name/';

# Remove Index.php
$config['index_page'] = '';

# Set Database

For Localhost
==========================
'hostname' => 'localhost',

'username' => 'root',

'password' => '',

'database' => 'youre database name',

For Server
============================
'hostname' => 'localhost',

'username' => 'Mysql User name',

'password' => 'Mysql User password',

'database' => 'Database name',

# Set Default Route 

// $route['default_controller'] = 'welcome'; // Change this to your default controller

$route['default_controller'] = 'home';

When enter http://localhost/your codeigniter folder name/ 

then call index function in Home Controller
