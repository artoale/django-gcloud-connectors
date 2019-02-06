# Django GCloud Connectors

**WARNING: This is very much a work in progress, is unstable, and not ready for use**

The aim of this project is to create Django database connectors for Google Cloud. Currently
it contains a connector for the Google Cloud Datastore (Firestore in Datastore mode) but in future
it may also house a Firestore connector, or even a MemoryStore one.

This is the continuation of the Datastore connector from the [Djangae project](https://github.com/potatolondon/djangae)
but converted to use the [Cloud Datastore API](https://googleapis.github.io/google-cloud-python/latest/datastore/) on Python 3.


# Running the tests

```
$ pip3 install --user tox
$ tox
```
