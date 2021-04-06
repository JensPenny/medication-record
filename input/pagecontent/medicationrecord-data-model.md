  
The Medication Record needs to contain several data objects that are in the Modular Reccord (and therefore may be standardized separately).

A brief walkthrough of the data objects that are part of the Medication Record:

![Patient Modular](./patrecord-medrecord.png "Patient Record and Medication Record")
<br clear="all" />

* The Patient record contains a lot more information about the patient, we only focus on those related to the medication
* The Medication Record can contain any of the relevant information related to medication usage:
  * Known Medication Allergies
  * Conditions for which the medication treatments have been given
  * An indication of the protocols that were followed in the medication treatments
  * The details about the medication, as they are available and relevant, for several medication lines:
    * Planned medication (i.e. considered, but not yet fully prescribed, such as a long-term treatment planned for 1 year but only prescribed for 2 weeks.
    * Prescriptions (and also treatment changes, e.g. verbal changes to the dosage that do not have a prescription)
    * Dispenses
    * Administration reports
    * Any adverse events reported
  * A series of summaries of those events, organized / compiled according to several criteria




### Structure of the medication record
For meeting the structure above, 
The medication record shall therefore indicate some metadata (data about the record itself), and, depending on the type of record, may contain structured medication data that is relevant about the medication, such as:

- Metadata
  - time window
  - authorship
  - Time of preparation


* Medication Data
  * Prescriptions
  * Changes in treatment not documented in a prescription
  * History of medication adverse events
  * Known medication allergies
  * Dispenses
  * Administrations
  * Summarized data






