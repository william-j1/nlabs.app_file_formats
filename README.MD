# File Formats

NLABS.app encompasses many object types and each has its own format for data exchange.

# Object Types

| Object     | Description                        | Serial Format                              | Sample                     |
|:----------:|------------------------------------|--------------------------------------------|----------------------------|
| Histogram  | a series of rectangular bins       | Min:Max:Bins:X_Label:Y_Label:X_Values ...  | 1:2:3:eA==:eQ==:1,2,1...   |
| Image      | a series of (r,g,b,a) tuples       | Constant:Width:Height:RGBA_Values ...      | Image:100:100:102,53,...   |
| Linegraph  | a series of 1-dimensional edges    | X_Label:Y_Label:Y_Values ...               | eA==:eQ==:0,2,1.76,6...    |
| Scatter	 | a series of 0-dimensional vertices | X_Label:Y_Label:X_Values,Y_Values ...      | eA==:eQ==:2,3,6,1,1.7,5... |

# Encoding

| Object  | Type    |
|:-------:|---------|
| X_Label | base 64 |
| Y_Label | base 64 |
