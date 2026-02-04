# Data Formats

NLABS.app encompasses many object types and each has its own format for data exchange.

# Object Types

| Object     | Serial Format                         | Sample                          |
|:----------:|---------------------------------------|---------------------------------|
| Histogram  | Min:Max:Bins:X_Label:Y_Label:X_Values | Histogram:1:2:3:eA==:eQ==:1,2,1 |
| Image      | Constant:Width:Height:RGBA_Values     | Image:100:100:102,53            |
| Linegraph  | X_Label:Y_Label:Y_Values              | Linegraph:eA==:eQ==:0,2,1.76,6  |
| Scatter	 | X_Label:Y_Label:X_Values,Y_Values     | Scatter:eA==:eQ==:2,3,6,1,1.7,5 |

# Encoding

| Object  | Type    |
|:-------:|---------|
| X_Label | base 64 |
| Y_Label | base 64 |
