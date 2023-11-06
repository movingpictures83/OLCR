# OLCR
# Language: Python
# Input: TXT
# Output: TXT
# Tested with: PluMA 2.0, Python 3.6

PluMA plugin that runs Least-Frequently Used (LFU) cache replacement.

Input is a TXT file of tab-delimited keyword-value pairs:
n: Cache size
infile: Cache accesses (one per line)
kind: OLCR, OLCR_RAND

Output is sent to TXT
