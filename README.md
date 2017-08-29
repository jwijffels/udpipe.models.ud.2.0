# udpipe.models.ud.2.0 - R package containing Universal Dependencies 2.0 Models for UDPipe

NLP models working with udpipe. These models are made available at <http://hdl.handle.net/11234/1-2364> and are just redistributed here to be able to work with the udpipe R package (https://github.com/bnosac/udpipe) more easily.

The models made available at <http://hdl.handle.net/11234/1-2364> are merely copy-pasted in the [inst/udpipe-ud-2.0-170801](inst/udpipe-ud-2.0-170801) folder and are distributed under the CC BY-NC-SA (http://creativecommons.org/licenses/by-nc-sa/4.0/) licence.

More information on these models at the [README](inst/udpipe-ud-2.0-170801/README)

## Installation

Mark that the size of the package is >900Mb so this might take a while.

```
devtools::install_github("jwijffels/udpipe.models.ud.2.0")
```

Or install it from www.datatailor.be, which is faster as it is already packaged for you.

```
install.packages("udpipe.models.ud.2.0", repos = "http://www.datatailor.be/rcube", type = "source")
```
