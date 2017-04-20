rest_api_demo
=============

This repository contains boilerplate code for a RESTful API based on Flask and Flask-RESTPlus.

The code of this demo app is described in an article on my blog:
http://michal.karzynski.pl/blog/2016/06/19/building-beautiful-restful-apis-using-flask-swagger-ui-flask-restplus/

## *Note:
when try to run in PyCharm, make sure change following, set
`Run --> Edit Configurations... --> Working directory` to
`<to your local path>/rest_api_demo`, not `<to your local path>/rest_api_demo/rest_api_demo`, otherwise `logger` can't found its config file `logging.conf`.