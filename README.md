# EKG

## EKG reader

Convert GE MUSE version 8.0 xml file to csv

![image](https://github.com/cgmhaicenter/EKG/blob/master/figs/ekg.png)

### Dependencies
Requires the following libraries:

- xml
- base64
- struct
- pandas

### Usage

### Structure
* RestingECG
  * PatientDemographics
    * PatientID
    * PatientAge
    * AgeUnits
    * DateOfBirth
    * Gender
    * PatientLastName
    * PatientFirstName
  * TestDemographics
    * DataType
    * Site
    * SiteName
    * AcquisitionDevice
    * Status
    * EditListStatus
    * Priority
    * Location
    * AcquisitionTime
    * AcquisitionDate
    * CartNumber
    * AcquisitionSoftwareVersion
    * AnalysisSoftwareVersion
    * HISStatus
  * RestingECGMeasurements
    * VentricularRate
    * AtrialRate
    * PRInterval
    * QRSDuration
    * QTInterval
    * QTCorrected
    * PAxis
    * RAxis
    * TAxis
    * QRSCount
    * QOnset
    * QOffset
    * POnset
    * POffset
    * TOffset
    * ECGSampleBase
    * ECGSampleExponent
    * QTcFrederica
  * Diagnosis
    * DiagnosisStatement
  * Waveform
    * WaveformType
    * WaveformStartTime
    * NumberOfLeads
    * SampleType
    * SampleBase
    * SampleExponent
    * LeadData
      * LeadByteCountTotal
      * LeadTimeOffset
      * LeadSampleCountTotal
      * LeadAmplitudeUnitsPerBit
      * LeadAmplitudeUnits
      * LeadHighLimit
      * LeadLowLimit
      * LeadID
      * LeadOffsetFirstSample
      * FirstSampleBaseline
      * LeadSampleSize
      * LeadOff
      * BaselineSway
      * LeadDataCRC32
      * WaveFormData
  * PharmaData
    * PharamaUniqueECGID
    

