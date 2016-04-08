# Bootstrap v4.0.0-alpha.2 with SASS


For changing use command - compass watch

By default all of Bootstrap is imported.

You can also import components explicitly. To start with a full list of modules copy _bootstrap.scss file into your 
assets as _bootstrap-custom.scss. Then comment out components you do not want from _bootstrap-custom. 
In the application Sass file, replace @import 'bootstrap-custom' with:

@import 'bootstrap';
