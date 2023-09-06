# Washing machine state

## START
topic:v1cdti/app/get/6310301023/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "START"
}

## READY
topic:v1cdti/app/get/6310301023/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/app/get/6310301023/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "FILLWATER"
}

## HEATWATER
topic:v1cdti/app/get/6310301023/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "HEATWATER"   
}

## WASH
topic:v1cdti/app/get/6310301023/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Wash_ON"    
}

## RINSE
topic:v1cdti/app/get/6310301023/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Rinse_ON"   
}

## SPIN
topic:v1cdti/app/get/6310301023/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Status",
    "value"     :   "Spin_ON"    
}

# Operation state

## DOORCLOSE
topic:v1cdti/app/set/6310301023/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "OP_Status_DoorClose",
    "name"      :   "DoorClose",
}

## WATERFULLLEVEL
topic:v1cdti/app/set/6310301023/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "OP_Status_WaterFullLevel",
    "value"     :   "WaterFullLevel"    
}

## TEMPERATUREREACHED
topic:v1cdti/app/set/6310301023/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "OP_Status_TemperatureRearched",
    "value"     :   "TemperatureRearched"    
}


# FAULT state

## TIMEOUT
topic:v1cdti/app/set/6310301023/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault_Status_Timeout",
    "value"     :   "TimeOut"    
}

## OUTOFBALANCE
topic:v1cdti/app/set/6310301023/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault_Status_OutofBalance",
    "value"     :   "OutofBalance"    
}

## MOTORFAILURE
topic:v1cdti/app/set/6310301023/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault_Status_Motorfailure",
    "value"     :   "MotorFailure"    
}

## FAULTCLEARED
topic:v1cdti/app/set/6310301023/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301023",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault_Status_Faultcleared",
    "value"     :   "Ready"    
}
