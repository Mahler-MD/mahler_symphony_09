**mahler_symphony_09-01**

data sets for performance analyses of the first movement of Gustav Mahler's Ninth Symphony (1909–10) GMW 50

This repository introduces the data sets created during research on recorded performances of the first movement of Gustav Mahler's Ninth Symphony (1909–10) GMW 50. It complements the following article:

Christian Utz. 2023. “Performative Form im ersten Satz von Gustav Mahlers Neunter Symphonie: Eine Diskussion der Deutungen von Erwin Stein, Bruno Walter, Leonard Bernstein und Michael Gielen auf Basis einer Korpusstudie zu 121 Aufnahmen.” *Archiv für Musikwissenschaft* 80, no. 2: 127–150. https://doi.org/10.25162/afmw-2023-0007. open access (accepted manuscript) at KUG Scholar: https://phaidra.kug.ac.at/o:130780

Tables, Figures, Audio and Video Examples for this article can be accessed at https://phaidra.kug.ac.at/o:130764.

The current dataset includes data on segmentation points, durations, and tempi of 121 recordings of the movement. Segmentation points follow a structural analysis of the movement based on 88 *segments* introduced in the article (Tabelle 3, https://phaidra.kug.ac.at/o:130744). A simplified formal structure based on 17 *sections* is shown in Tabelle 1 of the article (https://phaidra.kug.ac.at/o:130742).

* **[Mahler_IX-1_seg_dataSV.tsv](https://github.com/Mahler-MD/mahler_symphony_09-01/blob/main/Mahler_IX-1_seg_dataSV.tsv)** shows all 89 segmentation points for each of the 121 recordings, based on detailed measurements in Sonic Visualiser
* **[Mahler_IX-1_seg_durations.tsv](https://github.com/Mahler-MD/mahler_symphony_09-01/blob/main/Mahler_IX-1_seg_durations.tsv)** shows the duration of each segment as well as the total duration (= sum of 88 segmentation durations) for each of the 121 recordings
* **[Mahler_IX-1_seg_tempi.tsv](https://github.com/Mahler-MD/mahler_symphony_09-01/blob/main/Mahler_IX-1_seg_tempi.tsv)** shows the mean tempo of each segment as well as the average tempo (mean of 88 segment tempi) for all 121 recordings.

The Excel file **Mahler_IX-1_seg+sec_tpi-dur-pts.xlsx** combines all three data tables and in addition calculates the mean tempi of *sections* for all 121 recordings. In addition to the recordings, this table also includes the tempi provided or dervied from Erwin Stein's 1924 article (Stein 1924; Erwin Stein, "Die Tempogestaltung in Mahlers IX. Symphonie." *Pult und Taktstock* 1, no. 5 (1924): 97--99 [part 1]) and Leonard Bernstein's conduction score ("Bernstein score").

* **columns JH–NX** show all 89 segmentation points for each of the 121 recordings, based on detailed measurements in Sonic Visualiser
* **columns EM–JE** show 88 segmentation durations as well as the total duration (= sum of 88 segmentation durations) for each of the 121 recordings for each of the 121 recordings, based on the segmentation points; in addition the mean duration for each segment is calculated (columns JD and JE); the lower part of the sheet (lines 95–184) calculates the percentage of every segment from the total duration of its superordinate section, excluding segments in which continuous tempo changes (ritardandi or accelereandi) are indicated in the score (lines marked blue); these percentages are used to calculate section tempi based on weighted means; further below (lines 197-285) logarithmically scaled deviations of each segment duration from the overall mean duration of the respective segment is indicated.
* **columns N--EJ** show the mean tempo of each segment as well as the average tempo (mean of 88 segment tempi) for all 121 recordings 
