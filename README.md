# Quilombo UK – Data Analysis Project

### Overview

This project investigates the factors associated with underemployment in the United Kingdom, using data from Understanding Society (the UK Household Longitudinal Study, UKHLS). The analysis focuses on the 2021 and 2022 calendar years.

Underemployment is understood here as a mismatch between individuals’ skills, qualifications, desired hours, or wage expectations and the work they actually perform. It is often invisible in standard labour statistics but has profound implications for social mobility, income, and well-being.

This project builds and analyses key indicators of underemployment across demographic groups, with particular attention to gender and migration status.

### Project Workflow
#### 1. Data Extraction

Relevant variables were extracted from the 2021 and 2022 waves of UKHLS.

Columns were selected to capture:

employment status

education

occupation

hours worked

wages

satisfaction and well-being

Additional variables related to immigration were obtained through the sub_data files.

#### 2. Data Cleaning & Merging

Two notebooks are used for data preparation:

main_data_edit.ipynb – cleans each year’s dataset and aligns variables.

sub_data_edit.ipynb – extracts and processes immigration-related variables.

Datasets for 2021 and 2022 are then merged to produce a unified analytical dataset.

#### 3. Analysis

#### All analysis is contained in:

analysis.ipynb – includes construction of underemployment indicators, descriptive statistics, subgroup comparisons, and outcome assessments.

#### Conceptual Background: What Is Underemployment?

Underemployment refers to individuals who are working but not in jobs that match their potential. This may take several forms:

#### Types of Underemployment

#### Skills underemployment (overqualification):
When education or skills exceed the requirements of the job (e.g., a graduate working in a low-skilled role).

#### Wage underemployment:
When hourly pay is lower than expected based on education, occupation, or labour market norms.

#### Multiple or combined underemployment:
When individuals experience two or more disadvantages simultaneously (e.g., low pay and working below skill level).

Underemployment tends to be involuntary, and is associated with long-term stagnation in career progression, financial insecurity, and poorer mental health.

Study Population
Inclusion Criteria

#### Include individuals who:

Are of working age (16–64).

Are employed or self-employed at the time of the survey.

Provide valid data on education, occupation, hours, or wages.

Report paid work during the reference period.

Provide information relevant to underemployment or job satisfaction.

Exclusion Criteria

#### Exclude individuals who are:

Full-time students whose main activity is study.

Retired individuals or anyone above statutory retirement age.

Working under external hour restrictions (e.g., visa limits).

Part-time by choice (i.e., satisfied and not wanting more hours).

Unpaid family workers or volunteers.

#### Key Indicators to Construct
Goals:

Build consistent measures of underemployment.

Test reliability across demographic groups (gender, migration status, education).

Indicators

Skills mismatch

Wage mismatch

Combined or multiple underemployment

Perceived underemployment (using satisfaction variables)

Validation Tasks

Ensure logical consistency of indicators.

Check frequencies across relevant subgroups.

Identify discrepancies across the 2021–2022 data waves.

#### Descriptive Analysis
Goals

Document patterns of underemployment in the UK.

Assess how underemployment relates to well-being and satisfaction.

Tasks

Profile underemployment by:

gender

migration status

education

disability status

Compare different forms of underemployment (skills, wage, hours, combined).

Explore associations with:

mental health indicators

job satisfaction (overall and specific dimensions)

Record any variable inconsistencies across years for future cleaning.
