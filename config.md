curl http://172.20.10.2/api/system/statistics
{"currentTimestamp":146386,"labels":["hashRate","temp","vrTemp","power","voltage","current","coreVoltageActual","fanspeed","fanrpm","wifiRSSI","freeHeap","timestamp"],"statistics":[]}(base) claire@calas-server:~$ 

curl http://172.20.10.2/api/system/asic
{
	"ASICModel":	"BM1368",
	"deviceModel":	"SupraHex",
	"swarmColor":	"darkblue",
	"asicCount":	6,
	"defaultFrequency":	490,
	"frequencyOptions":	[400, 425, 450, 475, 485, 490, 500, 525, 550, 575],
	"defaultVoltage":	1166,
	"voltageOptions":	[1100, 1150, 1166, 1200, 1250, 1300]
}