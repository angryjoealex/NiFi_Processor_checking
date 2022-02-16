# NiFi_Processor_checking
Apache NiFi processor checking flow
Get info about all processors within contolled group (including subgroups)
Group UID should be set to "Generate Flow File" ->"Custom Text" one by one
Flow get inwormation about group connections and processors and all sub groups connections and processors. If connection\queue has > 0 Flow Files and Processor process = 0, then processor is not working
