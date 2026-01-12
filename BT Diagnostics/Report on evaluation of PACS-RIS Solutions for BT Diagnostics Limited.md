All PACS/RIS solutions assessed were evaluated with respect to the functionality of their:
- PACS
- Dicom viewer
- Modality work-list
- Radiology information System 
Using the following criteria:
- PACS
	1. Ease of configuration
	2. Speed
	3. Ease of migration to other solutions
- Dicom viewer
	1. Speed
	2. Windowing/Leveling presets
	3. Hanging protocol
	4. Availability of advanced functionality such as:
		1. Multiplanar reformation
		2. Curved multiplanar reformation
		3. 3-D volume rendering
		4. Cross-hair triangulation
		5. Minimum/Maximum intensity projection
- Modality work-list
	1. Filter studies by modality, day, week, month
	2. Real-time notification of status of a study ie (Unreported | Being reported | Reported)
	3. Show identity of radiologist working on a study
	4. RIS/PACS manager ability to assign/re-assign study to specific radiologist
- Radiology information system
	1. Availability of clinical history
	2. Ability to integrate with modality work-list to notify and easily look up previous studies done by same patient
	3. Audit trail of reports with time-stamps
	4. Save report templates in the application with option of exporting/downloading for use in other application

Key:

| Feature                                                                  | Symbol |
| ------------------------------------------------------------------------ | ------ |
| Present and evaluated to be functional                                   | +      |
| Stated and viewed to be present but functionality could not be confirmed | -      |
| Not present                                                              | x      |


## Manesia PACS (app.manesia.ai)
- PACS
	1. Ease of configuration: + (Based on Orthanc open source server, extendable and configurable in the lua language also has bindings to the python language.)
	2. Speed: + 
	3. Ease of migration to other solutions: +
- Dicom viewer
	1. Speed: x (Not very fast for most use-cases. Does not adequately implement pre-fetching of images)
	2. Windowing/Leveling presets: x (Not present)
	3. Hanging protocol: x (Not present)
	4. Availability of advanced functionality:
		1. Multiplanar reformation: - (Present but not performant or functional)
		2. Curved multiplanar reformation: x (Absent)
		3. 3-D volume rendering: - (Present but not performant or functional)
		4. Cross-hair triangulation: - (Present but not performant or functional)
		5. Minimum/maximum intensity projection: x (Absent)
- Modality work-list
	1. Filter by modality/day/week/month: + (Present)
	2. Real-time notification of status of study: + (Present)
	3. Show identity of radiologist working on a study: x (Absent) 
	4. RIS/PACS manager ability to assign/re-assign study to specific radiologist: (Not evaluated)
- Radiology Information System
	1. Availability of clinical history: x (Absent)
	2. Ability to integrate with modality work-list to notify and easily look up previous studies done by same patient: (Not evaluated)
	3. Audit trail of reports with time-stamps: + (Present)
	4. Save report templates in the application with option of exporting/downloading: (Present but not evaluated)
- Overall score: 6

## Neorad RIS Solution (only thin client was evaluated)
This has a number of functionalities that could not be evaluated with the demo account provided (probably due to restrictions from the vendor)
- PACS
	1. Ease of configuration: - (Not evaluated)
	2. Speed: + (Good, implements pre-fetching well)
	3. Ease of migration to other solutions: - (Not evaluated)
- Dicom viewer
	1. Speed: + (Fast enough for most use-cases.)
	2. Windowing/Leveling presets: - (Present but not evaluated, only available following MPR)
	3. Hanging protocol: x (Not present)
	4. Availability of advanced functionality:
		1. Multiplanar reformation: - (Present but not performant or functional)
		2. Curved multiplanar reformation: x (Absent)
		3. 3-D volume rendering: - (Present but not performant or functional)
		4. Cross-hair triangulation: - (Present but not performant or functional)
		5. Minimum/maximum intensity projection: - (Present but not performant or functional)
- Modality work-list
	1. Filter by modality/day/week/month: + (Present)
	2. Real-time notification of status of study: + (Present)
	3. Show identity of radiologist working on a study: x (Absent) 
	4. RIS/PACS manager ability to assign/re-assign study to specific radiologist: (Not evaluated)
- Radiology Information System
	1. Availability of clinical history: x (Absent)
	2. Ability to integrate with modality work-list to notify and easily look up previous studies done by same patient: x (Absent)
	3. Audit trail of reports with time-stamps: x (Absent)
	4. Save report templates in the application with option of exporting/downloading: (Present but not evaluated)
- Overall score: 4


## Radspa (radspain.teleradtech.com)
The standalone viewer is a 16-bit application which could not run on a 64-bit system. Whether this was an oversight by the vendor on the demo account or severe limitation in functionality of this application is unknown.
Only the web viewer was therefore evaluated
The reporting functionality could also not be evaluated with the demo account provided (probably due to restrictions from the vendor)
- PACS
	1. Ease of configuration: - (Not evaluated)
	2. Speed: + (Good, implements pre-fetching well)
	3. Ease of migration to other solutions: - (Not evaluated)
- Dicom viewer
	1. Speed: + (Fast enough for most use-cases.)
	2. Windowing/Leveling presets: + (Present)
	3. Hanging protocol: + (Present)
	4. Availability of advanced functionality:
		1. Multiplanar reformation: - (Not evaluated)
		2. Curved multiplanar reformation: - (Not evaluated)
		3. 3-D volume rendering: - (Not evaluated)
		4. Cross-hair triangulation: + (Present)
		5. Minimum/maximum intensity projection: + (Present)
- Modality work-list
	1. Filter by modality/day/week/month: + (Present)
	2. Real-time notification of status of study: - (Not evaluated)
	3. Show identity of radiologist working on a study: + (Present) 
	4. RIS/PACS manager ability to assign/re-assign study to specific radiologist: (Not evaluated)
- Radiology Information System
	1. Availability of clinical history: + (Present)
	2. Ability to integrate with modality work-list to notify and easily look up previous studies done by same patient: + (Present)
	3. Audit trail of reports with time-stamps: x (Absent)
	4. Save report templates in the application with option of exporting/downloading: - (Not evaluated)
- Overall score: 9