Parsley.js
==========

Meteor packaging for Parsley.js.

If I forgot to upgrade to the latest Parsley version, please start a new issue
or find a way to notify me and I'll happily upgrade it for you. Or if you want
to be nice and save me a few seconds; fork it, make a PR and I'll merge it.

Quick Setup 
===========
mrt add parsley.js

Edit your .js file

```
Template.name.rendered = function () {

  // Setup parsley form validation
  // replace form with the id of your form
  $('#form').parsley({trigger: 'change'}));
}
```

Edit your .css file
This is the default CSS from parsley

```
/* Parsley CSS */
input.parsley-success,
select.parsley-success,
textarea.parsley-success {
  color: #468847;
  background-color: #DFF0D8;
  border: 1px solid #D6E9C6;
}

input.parsley-error,
select.parsley-error,
textarea.parsley-error {
  color: #B94A48;
  background-color: #F2DEDE;
  border: 1px solid #EED3D7;
}

.parsley-errors-list {
  margin: 2px 0 3px 0;
  color: red;
  padding: 0;
  list-style-type: none;
  font-size: 0.9em;
  line-height: 0.9em;
  opacity: 0;
  -moz-opacity: 0;
  -webkit-opacity: 0;

  transition: all .3s ease-in;
  -o-transition: all .3s ease-in;
  -ms-transition: all .3s ease-in;
  -moz-transition: all .3s ease-in;
  -webkit-transition: all .3s ease-in;
}

.parsley-errors-list.filled {
  opacity: 1;
}

/* End Parsley CSS*/
```
