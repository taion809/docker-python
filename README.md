# docker-python


A small collection of my docker files for building python projects

The image repository can be viewed on the docker.io [central repository.](https://index.docker.io/u/johnsn/)

* The base image is `ubuntu`
* `johnsn/python27` is built on top of `ubuntu`
* `johnsn/pip` is built on `johnsn/python27`
* `johnsn/scrapy` is built on `johnsn/pip`


If you wanted to build a python project without pip or setuptools you could use `johnsn/python27` as the base.

## License

These files are licensed under the MIT License.
