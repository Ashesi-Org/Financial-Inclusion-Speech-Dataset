# Financial-Inclusion-Speech-Dataset
A speech dataset to support financial inclusion in Ghana created by Ashesi University and Nokwary Technologies with funding from Lacuna Fund. You can read about the development and release of the dataset at https://ashesi-org.github.io.

## Languages

- Akuapem Twi (Dialect of Akan)
- Asanti Twi (Dialect of Akan)
- Fanti (Dialect of Akan)
- Ga

## Statistics
- ~38 hours of Akuapem Twi from ~200 speakers
- ~30 hours of Asanti Twi from ~200 speakers
- ~39 hours of Fanti from ~200 speakers
- ~40 hours of Ga from ~200 speakers
- Total of ~148 hours of speech data
- Total size: 1.19GB

## Recorded Sentences
- ~130 sentences were recorded for each language (dialect) per speaker
- The speakers for each language (dialect) recorded the same sentences.
- The recorded sentences were based on prompts from a "Wizard-of-Oz" financial services application, sentences from Linguists to help ensure phonetic balance, and common phrases in the language.

## Data Quality

We performed a stratified random sampling (5%) of the data for each language and reviewed it to get the following quality assessments.

- 0.1% of the Ga audios were of low quality
- 1.3% of the Fanti audios were of low qaulity.
- 1.6% of the Asanti Twi audios were of low quality.
- 2.8% of the Akuapem Twi audios were of low quality.
- Low quality means that what the user recorded did not match the given prompt either because there was a truncation or the recording was totally different from the prompt.

## Accessing the Data

The data is freely available for use based on the provided open source license and courtesy the funding from Lacuna Fund.

We randomly selected 10% of the data for each language into its own archive and the remaining 90% into its own archive as well. Their files names end with 10p and 90p respectively. We aim to develop the 10p into an evaluation set to support our research efforts and possibly that of others. 

*NB:* The 10% do not constitute a strict test set. Even though recordings in the 10% and 90% are mutually exclusive, speakers and phrases in the 10% may also be found in the 90%.

| Data      | Link |
| ----------- | ----------- |
| 90% of Ga data      | [Download](https://fisd-dataset.s3.amazonaws.com/fisd-ga-90p.zip)       |
| 10% of Ga data   | [Download](https://fisd-dataset.s3.amazonaws.com/fisd-ga-10p.zip)         |
| 90% of Fanti data   | [Download](https://fisd-dataset.s3.amazonaws.com/fisd-fanti-90p.zip)         |
| 10% of Fanti data   | [Download](https://fisd-dataset.s3.amazonaws.com/fisd-fanti-10p.zip)         |
| 90% of Akuapem Twi data   | [Download](https://fisd-dataset.s3.amazonaws.com/fisd-akuapim-twi-90p.zip)         |
| 10% of Akuapem Twi data   | [Download](https://fisd-dataset.s3.amazonaws.com/fisd-akuapim-twi-10p.zip)         |
| 90% of Asanti data   | [Download](https://fisd-dataset.s3.amazonaws.com/fisd-asanti-twi-90p.zip)         |
| 10% of Asanti data   | [Download](https://fisd-dataset.s3.amazonaws.com/fisd-asanti-twi-10p.zip)         |

## Meta Data 

Each folder contains a data.csv file with the audio file path, transcription and translation of the transcription into English. (*NB:* Ignore the first two directories in the file path)

The file name contains inforrmation about the speaker. An example file name is GaFm21-ATuJLn5X-Tmp083-zykm34.ogg. The first part contains the language, gender and age of the speaker. In this case, the language is Ga, the speaker is female and the age is 21. The second part of the file name is the unique speaker id. Each recording by that speaker has that unique id.

## Citation

Asamoah Owusu, D., Korsah, A., Quartey, B., Nwolley Jnr., S., Sampah, D., Adjepon-Yamoah, D. and Omane Boateng, L., 2022. GitHub - Ashesi-Org/Financial-Inclusion-Speech-Dataset: A speech dataset to support financial inclusion created by Ashesi University and Nokwary Technologies with funding from Lacuna Fund.. [online] GitHub. Available at: <https://github.com/Ashesi-Org/Financial-Inclusion-Speech-Dataset>.

