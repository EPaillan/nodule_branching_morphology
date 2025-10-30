### Analysis Examining nodule branching effects on alfalfa host fitness and rhizobial fitness.

Elizabeth Paillan, Alejandra Gil-Polo, Sohini Guha, Andy Swartley, Liana Burghardt

##### Main experiment:

We isolated 39 strains from Oneida, 39 strains from Vernal, and 39 Strains from SW410. The 117 strains were inoculated in Oneida, Vernal, and SW410. We also inoculated commercial strains EXC and NIG.

7-isolate experiment:

We selected 7 strains from the main experiment and measured the amount of CFU released from different-sized nodules

##### Folders:

data/

AVT_CFU_count.csv - It has the information on the colony-forming units that were obtained after crushing nodules and performing dilution plating.

  *What's inside:* Plant -\> Plant ID

  Nodule -\> Nodule ID number

  Nodule.area -\> Recorded nodule surface area from ImageJ

  Nodule.lobe -\> Count of nodule branches present

  Dilution.counted -\> number of dilution that were counted

  Spot.1 - 5 -\> Count of colonies in spots

  Spot.avg -\> Average colony count across the spots

  Counted by -\> Who counted. Coauthors MAG = Alejandra Gil-Polo, SG = Sohini Guha, LTB = Liana Burghardt

  Comments = Text on the condition of the sample

  Lianas rhizobia released per nodule calculation

  Morphology - whether the colonies were found alone in a previous experiment (R) or partner (P) colonies were found in a previous experiment with another rhizobia (NOT USED for THIS MANUSCRIPT)

MasterSpreadsheet_AVT.csv - It has the information on traits (shoot biomass, chlorophyll content, nodule number, etc) from each single and mixed inoculation experiment.

  *What's inside:* Strain -\> Isolate number

  Variety -\> Host Variety ON = Oneida SN = SW410 VL= Vernal

  Rep -\> Replications

  Label -\> Official label used for plant tags

  Tray -\> Tray ID number used for randomization

  Slot -\> Location where each plant was placed in the slot, allowing for space in between pots and finer randomization

  Location -\> Final location for the pot

  Plantarea -\> Measure of plant leaf area at 3 weeks

  Chloro_1-5 -\> Chlorophyll measurements on every plant 1 - 5 times

  Chloro_check -\> Verify the reliability of the above chlorophyll measurements

  Chloro_avg -\> Average chlorophyll across checks

  Rootweight_g -\> Dry root weight

  Shootweight_g -\> Dry shoot weight

  Nodule_lobe -\> number of branched nodules

  Nodule_unlobed -\> number of unbranched nodules

  Nodule_Picker-\> Initials of person who processed nodule counts

  Morphology - whether the colonies were found alone in a previous experiment (R) or partner (P) colonies were found in a previous experiment with another rhizobia (NOT USED for THIS MANUSCRIPT)

  Notes -\> comments written during processing

Analysis/

Main Rmarkdown:

  Nodule_branching_analysis

figures/

  Figure 1_ver9 -\> made in inkscape

  Figure_2_ver4

  Figure_3

tables/ - Contains ANOVA outputs for models used in the manuscript

  Biomass-response_anova

  Nodulearea-by-surfacearea_anova

  Nodule-Area-response_anova

  Nodulenumber-response_anova

  RhizobiaReleased-responsed_anova

  Supplement_table1 = Raw version of the supplement table 1 exported from R

 
