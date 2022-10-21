# HTCSS Job Event Log to CSV Summarizer

A simple script that reads HTCondor job event logs and outputs a CSV summary of job statistics.

The CSV file can be imported into a spreadsheet application and used to review jobs.
This tool may help when scaling up workloads or running larger workloads.

## Requirements

This script needs the following things:

*   Python 3
*   HTCondor Python bindings
    ([installation instructions](https://htcondor.readthedocs.io/en/latest/apis/python-bindings/install.html))

## Usage

Run `logs2csv -h` for usage information.
