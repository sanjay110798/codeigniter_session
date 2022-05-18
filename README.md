# CodeIgniter

# Downloading CodeIgniter
https://codeload.github.com/bcit-ci/CodeIgniter/zip/3.1.13

# Upload .htaccess file in application folder

# Update Base url in Config file
/application/config/config.php

$config['base_url'] = 'http://localhost/your codeigniter folder name/';

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
