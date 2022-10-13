### Pipeline by Luis Morgado

Luis Morgado wrote a pipeline that runs the major steps in a Metabarcoding pipeline. It is available on Saga: 
```/cluster/projects/nn9338k/Luis_metabarding_pipeline```
It contains a set of scripts and dependency codes. 
He has written a 

**Content - interactive scripts:**
```
script_1_demultiplex_cutadapt_2_7.sh
script_2_remove_demult_files_with_very_low_read_number.sh
script_3_dependency_R_code.R
script_3_run_DADA2_v1.12.sh
script_4_parallel_itsx_fungi.sh
script_5_VSEARCH_cluster.sh
script_6_LULU.sh
script_6_R_code_LULU.R
script_7.2_Blast_and_match_tax_ready_for_F_guild.sh
script_7.2_matching_blast_with_OTU_table_for_funguild.R
script_7_Blast_and_match.sh
script_7_matching_blast_with_OTU_table.R
script_8_FunGUILD.sh
script_9_FUNGUILD_to_FINAL_OTU_table.R
script_9_match_OTU_table_with_tax_guild.sh
```

**Content - slurm scripts:**
```
batch_file.txt
script_7_Blast_and_match.sh
slurm_script_1_dem.sh
slurm_script_2_runDADA2_v1.12.sh
slurm_script_7_Blast_ASVs_with_COI_NCBI_BOLD.sh
```
