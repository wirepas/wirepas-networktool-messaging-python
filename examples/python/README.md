# WNT API Examples

This folder contains the Wirepas Network Tool API Examples. These examples show how to interact with
the server using authentication, metadata and real time situation connections.

Please note that these examples should not be taken as production quality, but more
as the examples about the message flow and content.

## Requirements

Before running the examples please ensure that the requirements are installed.

```shell
pip3 install -r requirements.txt
```

## WNT backend settings

For running the examples, WNT backend connection parameters must be given by creating settings.yml
file to the examples folder.

### Example settings file

```yaml
username: "username"
password: "password"
hostname: "wntbackend.mydomain.com"
```

## Examples

-   [applicationconfiguration.py][applicationconfiguration.py_link]
    -   Wirepas mesh application configuration and diagnostics interval setting \*

-   [authentication.py][authentication.py_link]
    -   Authentication and user querying, creation, updating and deletion.

-   [building.py][building.py_link]
    -   Building querying, creation, updating and deletion

-   [componentsinformation.py][componentsinformation.py_link]
    -   Component information querying

-   [floorplan.py][floorplan.py_link]
    -   Floor plan querying, creation, updating, deletion. Getting and setting of floor plan image and thumbnail.

-   [floorplanarea.py][floorplanarea.py_link]
    -   Floor plan area querying, creation, updating and deletion

-   [network.py][network.py_link]
    -   Network name querying, creation, updating and deletion

-   [node.py][node.py_link]
    -   Setting node metadata and adding node to floor plan

-   [nodedatamessage.py][nodedatamessage.py_link]
    -   Sending Wirepas mesh data message to node \*

-   [realtimedata.py][realtimedata.py_link]
    -   Connecting to the real time situation service and decoding protocol buffers messages \*

-   [scratchpadstatus.py][scratchpadstatus.py_link]
    -   Querying scratchpad status from the nodes \*

\*) Requires working Wirepas mesh network connected to the WNT backend

## Running an example

```shell
    # Run from examples folder
    python3 authentication.py
```

[applicationconfiguration.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/applicationconfiguration.py

[authentication.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/authentication.py

[building.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/building.py

[componentsinformation.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/componentsinformation.py

[floorplan.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/floorplan.py

[floorplanarea.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/floorplanarea.py

[network.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/network.py

[node.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/node.py

[nodedatamessage.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/nodedatamessage.py

[realtimedata.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/realtimedata.py

[scratchpadstatus.py_link]: https://github.com/wirepas/wirepas-networktool-messaging-python/tree/main/examples/python/scratchpadstatus.py
