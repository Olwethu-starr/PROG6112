# PROG6112

The Medicare Hospital Patient System is a basic Java console application developed in NetBeans to manage hospital patients and bed allocation. The system allows hospital staff to register and manage patient information, allocate and release beds, search for patients, and generate basic hospital reports. Patient information is stored in memory while the application is running.

Features:

-Patient Registration – Register new patients with their personal and medical information.
-Patient Categories – Supports Inpatient, Outpatient, and Emergency patients.
-Patient Search – Search for patients using their unique Patient ID.
-Update Patient Details – Modify existing patient information.
-Delete Patient – Remove patients from the system.
-Inpatient Management – Uses an Inpatient class that inherits from Patient.
-Bed Management – Manages 20 hospital beds, from B01 to B20.
-Bed Allocation – Assign available beds to inpatients.
-Bed Release – Release beds when patients leave.
-Ward Layout – Display the current availability of all beds.
-Reports – Shows total patients, occupied beds, available beds, and occupancy percentage.
-Patient Sorting – Sort patients by surname or Patient ID.
-JUnit Testing – Tests important functions such as registration, searching, updating, deleting, and bed allocation.
