# cesm-timeseries-pp-fix-scripts
Repo with simple scripts to fix additional time-slices in post-processed data from yearly (or more?) chunks


This repo contains simple bash scripts that use NCO and GNU parallel to 'reprocess' time-series output from the CESM Postprocessing tool, given that that tool is no longer supported yet renders NetCDF timeseries files with incorrect elements (extra time slices in some components).  

This is a short-term fix; the proper solution is a new (and supported) time-series generation tool that properly handles less-than-complete runs and/or smaller 'chunks' of output.
