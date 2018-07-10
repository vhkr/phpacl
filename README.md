# ACL Manager

## Installation
To install add the following dependency to your composer.json

```js
"vhkr/phpacl": "dev-master"
```

and run `composer update`

## Usage

This library use 3 class :

 - Phpacl : The main class to instance
 - Permission : The object to which permission is granted (ex: add, edit)
 - Resource : The object to which access is controlled (ex: action)
 - Role : The object that may request access to a Resource (ex: user)
