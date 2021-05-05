# Quality-of-Patients-Care

The data has the records on 131 patients suffering from diabaties. It is the history of patients visited the hospital and description of their treatment. Each patient has been handled differently and cured accordingly. Based on the hospitality, it has been reviewed whether the patient recieved good care or not. Predictive models have built based on Logistic reg, SVC and KNN classifier algorithms. Such models can be used to review the quality of service providing by the Health care unit.

# Data description
MemberID numbers the patients from 1 to 131, and is just an identifying number.
InpatientDays is the number of inpatient visits, or number of days the person spent in the hospital.
ERVisits is the number of times the patient visited the emergency room.
OfficeVisits is the number of times the patient visited any doctor’s office.
Narcotics is the number of prescriptions the patient had for narcotics.
DaysSinceLastERVisit is the number of days between the patient’s last emergency room visit 
Pain is the number of visits for which the patient complained about pain.
TotalVisits is the total number of times the patient visited any healthcare provider.
ProviderCount is the number of providers that served the patient.
MedicalClaims is the number of days on which the patient had a medical claim.
ClaimLines is the total number of medical claims.
StartedOnCombination is whether or not the patient was started on a combination of drugs to treat their diabetes (TRUE or FALSE).
AcuteDrugGapSmall is the fraction of acute drugs that were refilled quickly after the prescription ran out.
PoorCare is the outcome or dependent variable, and is equal to 1 if the patient had poor care, and equal to 0 if the patient had good care.
