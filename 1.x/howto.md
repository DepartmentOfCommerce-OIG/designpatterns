## How to use the USPTO UI Design Library

### Prerequisites

Before proceeding with the UI Design Library, we are assuming that you are already aware about the basics of HTML and CSS. 

### Usage

#### Download UI Design Library
Download the latest version of UI Design Library [here](http://DepartmentOfCommerce-OIG.github.io/designpatterns/1.x/docs/resources.html).

![download-USWDS](https://raw.githubusercontent.com/DepartmentOfCommerce-OIG/designpatterns/gh-pages/resources/tut-resources/ui-intro.png)


##### Resources:
- Download CSS: Download the precompiled versions of UI Design Library CSS. No documentation or original source code files are included. 
- View on Github: Get the latest UI Design Library and JavaScript source code directly from GitHub. 

---

#### File Structure
If you have downloaded the UI Design Library source code then the file structure would be as follows:

![file-structure](https://raw.githubusercontent.com/DepartmentOfCommerce-OIG/designpatterns/gh-pages/resources/tut-resources/ui-file-structure.png)

---

#### What's included?

**CSS:** Global CSS settings and enhanced with extensible classes with an advanced grid system.  

---

#### How to use?
A basic HTML template using UI Design Library would look like this:
```
<!doctype html>
<html>
<head>
<title>UI Design Library </title>
<!-- DOC OIG Pattern Library CSS -->
<link rel="stylesheet" type="text/css" href="#">
</head>
<body>
<h1>Welcome to DOC OIG</h1>
</body>
</html>
```
#### Plugins: jQuery.js
```
<!doctype html>
<html>
<head>
<title>UI Design Library </title>
<!-- DOC OIG Pattern Library CSS -->
<link rel="stylesheet" type="text/css" href="css/uswds.css">
</head>
<body>
<h1>Welcome to DOC OIG</h1>
<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
<!-- Latest compiled JavaScript -->
<script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
</body>
</html>
```

#### Custom style sheets
To apply additional styling to your web application, simply add the proper code to your custom-styles.css file and include that file after all style sheets. There is no need to edit any of the original UI Design Library files directly.
```
<!doctype html>
<html>
<head>
<title>UI Design Library </title>
<!-- DOC OIG Pattern Library CSS -->
<link rel="stylesheet" type="text/css" href="css/uswds.css">
<!-- Custom CSS -->
<link rel="stylesheet" type="text/css" href="css/styleguide.css">
</head>
<body>
<h1>Welcome to DOC OIG</h1>
</body>
</html>
```


