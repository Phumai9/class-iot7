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
Topic: v1/
Payload: {

}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1/
Payload: {

}
```

## Set geo-location or location placement
```
Topic: v1/
Payload: {

}
```

## Monitor machine sensor
```
Topic: v1/
Payload: {

}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1/
Payload: {

}
```
