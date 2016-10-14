# must-go-faster
Data and analysis for "Must Go Faster: measuring the deployability of protocols supporting low latency"

## DSCP results and analysis

Information on this dataset will be available shortly.

## TCP Fast Open results and analysis

There are two analysis notebooks for use with [Jupyter](https://jupyter.org) in the `tfo` directory. 

- [tfo/tfo_1m_analysis.ipynb](tfo/tfo_1m_analysis.ipynb) contains analysis of the full top million dataset from a single vantage point, for discovering TFO support and anomalies as in Table 3 and Section 3.2 of the Must Go Faster paper. It requires a single `.fjson` output file from `pathspider tfo` as input. It will create CSV files for input to pathspider to further measure connectivity failure and behavior of negotiated TFO cookies from multiple vantage points.
- [tfo/tfo_multipoint_analysis](tfo/tfo_multipoint_analysis.ipynb) contains analysis of subsets of sites, as selected by the full analysis notebook. It requires one `.fjson` output file per vantage point and run.

Raw data for the runs described in the paper is available upon request, as it
is stored in the MAMI Path Transparency Observatory, which is currently in
closed testing.

## ALPN/NPN results and analysis

Information on this dataset will be available shortly.
