# Apache_beam_MLOPS_LAB


Changes Implemented:
 - Added a Top-N stage (beam.combiners.Top.Of) to write the most frequent words to outputs/top-*.
 - Computed total unique words (Count.Globally) and wrote the vocab size to outputs/stats-*.
 - Enriched word counts with COMMON/RARE buckets (and % of corpus) and wrote to outputs/part_enriched-*

all code changes made in the Try_Apache_Beam_Python.ipynb file 
