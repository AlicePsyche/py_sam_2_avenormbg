takes a folder of sam files and generates bedgraph files and big wigs with optional size selection.

The bedgraphs are normalized as follows:
using the bedtools genomecov command with a scaling factor of (genome size/number of mapped fragments genome).
