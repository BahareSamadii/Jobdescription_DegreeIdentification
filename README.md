# Jobdescription_DegreeIdentification
#Check The notes on the excel sheet of summary of results (important notes) saved in OwnCload
#These codes aim to analyse the job description in Breezy dataset to identify if the competencies mentionned in the job description #correspond to a PhD degree. Our bench mark for the competencies that PhDs possess is the core competency of PhD published in 'The core competencies of PhDs' https://www.researchgate.net/publication/277952119_The_core_competencies_of_PhDs.
To do so:
#1-  We removed all the positions without a job description
#2- We kept the positions, written in English and with the education.
#We tested three different models in 3 different codes as bellow:

# JobDescriptionClassification_BreezyDB_1
#We did not consider a weight for the repetition of the competency
# JobDescriptionClassification_BreezyDB_2
#We considered the TF-IDF method
# JobDescriptionClassification_BreezyDB_3
#We considered a weight for the repetition of the competency
