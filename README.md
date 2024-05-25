# autoISF version 3.0.1 (branch under construction!)
The autoISF add-on to AAPS V3.2.0.4 using oref1 can adapt ISF if glucose or its trends show certain behaviour. See the Quick Guide for details of those scenarios. The effects can be tuned individually to further improve your results if you already have a TIR of about 90%.

Currently the repo with the complete code can be found here (**TO BE UPDATED ONCE PROJECT IS PUBLISHED**): https://github.com/T-o-b-i-a-s/AndroidAPS/tree/3.2.0.2-ai3.0
Beware that in Android Studio you first start with its related master branch, wait for all the downloading and other updates and only finally switch to the above branch. More detailed build instructions are given in that repo.

The main new features provided by the upgrade from 3.0 to 3.0.1 are.
* Merging the research Libre branch into mainmstream
* 5 settings were withdrawn because over time it proved they were not really necessary
* In the SMB tab the script debug section is now shown first
* Now 100 logfiles instead of just 30 will be kept before getting recycled
* The SMB tab shows the current value of *iob_threshold_percentage* and how it was adapted to become the effective iob threshold

For details of these see the Preface in the Quick Guide.

In 3.0 there was a bug related to the *iob_threshold_percentage* being inactive when setting it to 100%. Once modulated by exercise or similar it became active unintentionally.
