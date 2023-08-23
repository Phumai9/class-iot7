![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1/hw/get/6310301009/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "washing-01",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301009/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301009",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "firmware",
    "value"     : "114"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301009/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301009",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "geo-location",
    "value"     : "209,150"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/set/6310301009/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301009",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "geo-location",
    "value"     : "209,150"
}

```

## Monitor machine sensor
```
Topic: v1cdti/hw/Monitor/6310301009/model-01/WSH-SN001
Payload: 
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/set/6310301009/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301009",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "main"
}
```
