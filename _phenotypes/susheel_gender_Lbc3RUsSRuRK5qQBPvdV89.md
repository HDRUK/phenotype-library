---
layout: phenotype
title: Gender
phenotype_id: Lbc3RUsSRuRK5qQBPvdV89
name: Gender
type: Lifestyle Risk Factor
group: Demographics
data_sources:
    - National Neonatal Research Database
    - Maternity Services Data Set
validation: 
codelists:
    - susheel_gender_Lbc3RUsSRuRK5qQBPvdV89_DMD.csv
    - susheel_gender_Lbc3RUsSRuRK5qQBPvdV89_GPRD.csv
clinical_terminologies: 
    - NHS Data Model and Dictionary
    - GPRD Local Classification
author: Susheel Varma
status: DRAFT
date: 2021-02-07
modified_date: 2021-02-07
version: Revision 1
---

### Primary Care

{% include csv.html csvdata=site.data.codelists.susheel_gender_gprd_Lbc3RUsSRuRK5qQBPvdV89_Local %}

### Secondary Care

{% include csv.html csvdata=site.data.codelists.susheel_gender_Lbc3RUsSRuRK5qQBPvdV89_DMD %}