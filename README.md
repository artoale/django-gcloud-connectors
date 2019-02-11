# Django GCloud Connectors

**WARNING: This is very much a work in progress, is unstable, and not ready for use**

The aim of this project is to create Django database connector / backend for Google Cloud.

Currently it contains a connector for the Google Cloud Datastore (Datastore in Firestore mode) 
but in the future it may also include a Firestore connector, or even a MemoryStore one.

This is the continuation of the Datastore connector from the [Djangae project](https://github.com/potatolondon/djangae)
but converted to use the [Cloud Datastore API](https://googleapis.github.io/google-cloud-python/latest/datastore/) on Python 3.

If you are interested in submitting a patch, please refer to `CONTRIBUTING.md`


## Running the tests

```
$ pip3 install --user tox
$ tox
```
