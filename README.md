# ANALYSIS OF HEALTH FACILITIES IN NIGERIA: FUNCTIONALITY & COVERAGE

![SCREENSHOT](https://github.com/user-attachments/assets/6e547d06-c9d4-4de0-a191-4e3132dd2a64)

## INTRODUCTION
Nigeria’s healthcare system faces significant challenges in delivering equitable access to health services across its diverse and populous landscape. With over 216 million people spread across 36 states and the Federal Capital Territory, understanding how health facilities are distributed and whether they’re actually functioning becomes critical for healthcare planning and policy development.

This comprehensive Power BI analysis examines Nigeria’s health facility landscape, revealing functionality patterns, coverage gaps, and distribution inequities that affect millions of Nigerians seeking healthcare services. The analysis transforms complex facility and population data into actionable insights that highlight which communities have adequate healthcare access and which areas require urgent attention.

Despite the presence of thousands of health facilities across Nigeria, there are major disparities in their functionality and distribution. Many communities, especially in densely populated or rural areas, lack adequate access to operational health centers — particularly primary health care (PHC) facilities. This uneven distribution raises serious concerns about equitable healthcare access, effective service delivery, and resource allocation across states and local governments.

This interactive dashboard serves as a strategic resource for healthcare policymakers, public health officials, state governments, healthcare investors, development organizations, and community health advocates seeking data-driven insights into Nigeria’s healthcare infrastructure and coverage patterns.

## PROJECT OVERVIEW
The primary objective of this Power BI analysis was to examine Nigeria’s health facility functionality and coverage patterns, analyzing how existing facilities align with population needs across states and local government areas (LGAs) to identify healthcare access gaps and distribution inequities.

The analysis addresses the critical need to understand where functional health facilities exist, how they serve Nigeria’s population, and which areas face the greatest healthcare access challenges. By combining facility functionality data with population distribution, this project provides comprehensive insights into Nigeria’s healthcare infrastructure effectiveness.

### Problem Statement
This project tackles the urgent need for stakeholders to understand Nigeria’s healthcare facility landscape and identify areas where citizens face barriers to healthcare access. Key questions driving this analysis include:

* How many of Nigeria’s health facilities are actually functional and operational?
* Which states have the best and worst healthcare facility coverage relative to their populations?
* What types of health facilities dominate Nigeria’s healthcare landscape?
* How do facility ownership patterns affect healthcare access across different regions?
* Which communities face the greatest challenges in accessing functional health facilities?
* How many people does each functional facility serve in different states?
* Understanding these relationships is essential for making informed healthcare policy decisions, allocating resources effectively, planning facility improvements, and ensuring that all Nigerians have reasonable access to functional healthcare services.

## DATASET OVERVIEW
This analysis combines two comprehensive datasets to provide a complete picture of Nigeria’s healthcare facility landscape and population distribution patterns.

### Primary Data Sources
* **Nigeria Health Facilities Dataset:** Sourced from open.africa (https://open.africa/dataset/nigeria-health-care-facilities-primary-secondary-and-tertiary), this dataset contains detailed information about health facilities across Nigeria, including their locations, categories, functionality status, and ownership structures. The dataset was last updated in 2020, which means some facility statuses may have changed since then.

* **Population Data:** Population figures for Nigerian states and local government areas were scraped from citypopulation.de (https://www.citypopulation.de/en/nigeria/admin/), providing census results and latest population projections that enable accurate population-to-facility ratio calculations.

### Dataset Scale and Scope
The analysis encompasses 46,000 total health facilities across Nigeria, with 34,000 identified as functional, representing a 53.11% functionality rate. The dataset covers Nigeria’s total population of 216.80 million people, creating an average of 6,320 people per facility nationwide.

Primary Health Centers (PHCs) emerge as the most common facility type, reflecting Nigeria’s emphasis on primary healthcare delivery. The ownership analysis reveals facility distribution across state primary healthcare systems, national primary healthcare programs, private sector providers, and other institutional arrangements.

### Key Data Dimensions Analyzed
* **Functionality Metrics:** Functional facility counts, functionality rates by state, operational status classifications, and facility category performance analysis
* **Coverage Analysis:** Population per facility ratios, facilities per 10,000 people calculations, geographic coverage patterns, and accessibility measurements
* **Geographic Distribution:** State-level facility counts, LGA-level distribution patterns, regional coverage comparisons, and population density correlations
* **Facility Classifications:** Primary, secondary, and tertiary facility categories, specialty hospital distributions, dispensary and maternity home coverage, and medical center locations
* **Ownership Patterns:** State versus national healthcare facility management, private sector healthcare provision, local government area facility ownership, and institutional healthcare delivery

## TOOLS AND TECHNOLOGIES
Microsoft Power BI served as the primary platform for this comprehensive healthcare facility analysis, leveraging its data integration capabilities, advanced modeling features, and interactive visualization tools to transform complex healthcare and population data into actionable insights.

**Power BI Features and Capabilities Utilized**
Power Query for Data Transformation: Extensively used Power Query to clean, standardize, and merge the health facilities and population datasets. This included significant work to ensure LGA names matched between datasets, handling naming variations and inconsistencies that could break geographic visualizations and analysis accuracy.

**DAX Calculations and Measures:** Implemented comprehensive DAX functions to create essential healthcare metrics including:
* **Average Population per Functional Facility:** Calculating how many people each functional facility serves in different states
* **Functional Facility Rate:** Determining the percentage of facilities that are operational
* **Functional Facility Count:** Aggregating operational facilities by geographic and category dimensions
* **Facilities per 10,000 People:** Standardizing facility coverage for population comparison across states
  
**Interactive Visualizations:** Developed dynamic charts, geographic maps, and comparative visualizations that allow users to explore healthcare coverage patterns across states, facility types, and population distributions.
**Geographic Mapping:** Implemented state-level visualizations showing facility distribution patterns across Nigeria’s diverse geographic landscape

**Cross-Filter Interactions:** Created seamless filtering across dashboard pages enabling users to drill down from national overview to state-specific healthcare facility analysis

## METHODOLOGY
The analysis employed systematic data integration, extensive Power Query transformations, and DAX-driven healthcare calculations to identify meaningful patterns in facility functionality, population coverage, and geographic distribution while maintaining focus on healthcare access equity.

### Data Integration and Transformation Challenges
* **LGA Name Matching Process:** One of the project’s biggest challenges involved ensuring that Local Government Area names matched perfectly between the health facilities dataset and population dataset. This required extensive Power Query work to standardize naming conventions, handle spelling variations, and resolve geographic classification differences that could break the analysis.
* **Data Cleaning and Standardization:** Used Power Query to standardize facility category classifications, handle missing functionality records, validate geographic assignments, and ensure consistent state and LGA classifications across both datasets. Applied data quality checks to maintain analytical integrity across healthcare metrics and population calculations.
* **Population Alignment Methodology:** Developed systematic approaches to link population data at LGA and state levels with facility records, ensuring that coverage calculations accurately reflect the communities served by each health facility.

## PRE-ANALYSIS
Before developing the detailed dashboard pages, I conducted a comprehensive pre-analysis phase to establish the analytical framework for understanding Nigeria’s healthcare facility functionality and coverage patterns.

**Project Structure and Healthcare Variables**
Identified key healthcare access metrics including facility functionality rates, population coverage ratios, geographic distribution patterns, and ownership structure analysis to understand the complex relationships within Nigeria’s healthcare delivery system. This helped establish which factors drive healthcare accessibility and what insights could guide policy and investment decisions.

**Analytical Framework Development**
The problem statement guided initial hypotheses about regional healthcare disparities, facility type distributions, and population coverage variations. Early analysis suggested that healthcare access might vary significantly across states, with urban areas potentially having better facility concentrations while rural regions could face coverage gaps.

**Dashboard Design Strategy**
Structured the analysis into complementary pages focusing on Coverage (facility functionality and distribution overview) and Population (how facilities align with population needs and demographic patterns). This organization enables stakeholders to progress from understanding facility availability to examining how well these facilities serve Nigeria’s population distribution.

**Stakeholder Consideration**
Considered the diverse needs of healthcare policymakers requiring coverage gap analysis, state governments seeking resource allocation guidance, development organizations identifying intervention priorities, and community health advocates documenting access disparities.

## ANALYSIS OF DASHBOARD PAGES
The Power BI dashboard reveals comprehensive insights into Nigeria’s healthcare facility landscape through two analytical pages that tell the complete story of functionality and coverage across the country:

### PAGE 1: COVERAGE: FACILITY FUNCTIONALITY AND DISTRIBUTION OVERVIEW

![TASK 34BP_cropped_page-0001](https://github.com/user-attachments/assets/1ebb8371-ae17-4140-8dd5-7c67554cb8a8)

The coverage page establishes the fundamental structure of Nigeria’s healthcare ecosystem, revealing that out of 46,000 total health facilities, only 34,000 are functional, achieving a 53.11% functionality rate that highlights significant operational challenges across the healthcare system.

* **Facility Category Distribution:** The analysis shows a clear hierarchy in Nigeria’s healthcare facility structure, with Primary Health Centers dominating at 28,000 facilities, followed by Dispensaries at 9,000, and other categories including Maternity Homes, Private Non-Profit facilities, Medical Centers, and Specialist Hospitals each contributing 1,000–4,000 facilities to the total healthcare infrastructure.
* **Ownership Patterns:** State Primary Healthcare systems lead facility ownership with 15,200 facilities, followed by National Primary Healthcare programs at 11,400 facilities. Other ownership categories, including Private sector (6,000), State Ministry of Health (1,700), and Local Government Areas (1,000) demonstrate the mixed public-private nature of Nigeria’s healthcare delivery system.
* **Geographic Distribution Excellence and Challenges:** Lagos State leads Nigeria in functional facilities with 2,165 operational facilities, followed by Benue (1,904), Kano (1,556), Niger (1,533), Katsina (1,475), and Osun (1,438). This reveals significant state-level variation in healthcare infrastructure development.
* **States Facing Healthcare Access Challenges:** The analysis identifies states with the lowest functional facility counts, including Federal Capital Territory (467), Gombe (454), Zamfara (405), Rivers (384), Bayelsa (319), and Yobe (242). These figures highlight regions requiring urgent healthcare infrastructure investment and support.

This page establishes that Nigeria’s healthcare landscape faces significant functionality challenges, with less than 60% of facilities operational, while also showing substantial geographic disparities in facility availability across states.

### PAGE 2: POPULATION: HEALTHCARE COVERAGE AND DEMOGRAPHIC ALIGNMENT

![TASK 34BP_cropped_page-0002](https://github.com/user-attachments/assets/a6c18d6d-c4c3-4482-a184-8225f8b88042)

The population analysis page reveals how Nigeria’s 216.80 million people are served by existing health facilities, showing an average of 6,320 people per facility nationwide, while identifying significant variations in coverage effectiveness across different states.

* **Population and Facility Alignment:** The top states by facility count and population analysis shows Lagos leading with 2,300 facilities serving 12.2 million people, Katsina with 2,200 facilities for 10.4 million people, and Oyo with 1,700 facilities serving 8.3 million people. This demonstrates how facility distribution aligns with population density in some regions while creating gaps in others.
* **Coverage Excellence and Disparities:** Osun State achieves the best facility coverage with optimal population-to-facility ratios, while Rivers State shows the worst facility coverage, highlighting dramatic differences in healthcare accessibility across Nigeria’s states.
* **Population Coverage Analysis:** The analysis reveals significant variations in population per functional health facility, with Rivers showing 18,900 people per facility, Yobe at 14,600, Zamfara at 13,600, Jigawa at 12,100, and Kebbi at 10,500. These figures indicate substantial healthcare access challenges in these states.
* **Facility Coverage Efficiency:** The top 5 states for functional facilities per 10,000 people include Osun (3.3), Cross River (3.1), Abia (3.0), Benue (3.0), and Ebonyi (2.7), while the bottom 5 states show much lower ratios: Kebbi (0.95), Jigawa (0.83), Zamfara (0.74), Yobe (0.69), and Rivers (0.53).

This page demonstrates that Nigeria’s healthcare facility distribution creates significant access disparities, with some states achieving reasonable coverage while others face severe healthcare infrastructure shortages relative to their populations.

## KEY OBSERVATIONS
### Healthcare Infrastructure Scale and Functionality Challenges
Nigeria operates 46,000 health facilities nationwide, but only 34,000 are functional, creating a concerning 53.11% functionality rate that suggests nearly half of the country’s healthcare infrastructure faces operational challenges. Primary Health Centers dominate the facility landscape at 28,000 facilities, indicating the healthcare system’s emphasis on primary care delivery, though functionality issues affect all facility categories.

### Geographic Healthcare Disparities and State Performance
Lagos State leads functional facility availability with 2,165 operational facilities, followed by Benue (1,904) and Kano (1,556), while states like Yobe (242), Bayelsa (319), and Rivers (384) face significant facility shortages. This geographic disparity creates substantial healthcare access inequities across Nigeria’s diverse regions and population centers.

### Population Coverage Variations and Access Challenges
Nigeria’s 216.80 million people create an average burden of 6,320 people per facility nationally, but state-level variations are dramatic. Rivers State shows 18,900 people per functional facility compared to better-served states, indicating that millions of Nigerians face significant barriers to accessing nearby health facilities.

### Healthcare Facility Ownership and Management Patterns
State Primary Healthcare systems manage 15,200 facilities while National Primary Healthcare programs operate 11,400 facilities, demonstrating the predominantly public nature of Nigeria’s healthcare infrastructure. Private sector involvement at 6,000 facilities suggests opportunities for expanded private healthcare delivery, particularly in underserved regions.

### Regional Healthcare Excellence and Infrastructure Gaps
Osun State achieves the best healthcare coverage with 3.3 functional facilities per 10,000 people, while Rivers State struggles with only 0.53 facilities per 10,000 people. This six-fold difference in coverage ratios reveals that healthcare access depends heavily on geographic location rather than universal healthcare availability.

### Population Density and Healthcare Service Alignment
States like Lagos serve large populations (12.2 million) with substantial facility networks (2,300 facilities), while rural states often lack proportional healthcare infrastructure. The analysis reveals that population density doesn’t always correlate with adequate facility coverage, creating access challenges in both urban and rural contexts.

### Healthcare System Efficiency and Resource Allocation
The substantial difference between total facilities (46,000) and functional facilities (34,000) indicates significant resource allocation challenges and operational inefficiencies within Nigeria’s healthcare system. Improving facility functionality could dramatically increase healthcare access without requiring new infrastructure construction.

## STRATEGIC RECOMMENDATIONS
### Immediate Healthcare Infrastructure Priorities
* **Focus on Functionality Improvement Before New Construction:** With only 53.11% of existing facilities functional, Nigeria should prioritize making the 12,000 non-functional facilities operational before building new healthcare infrastructure. This approach could dramatically improve healthcare access while maximizing existing resource investments and avoiding duplicated infrastructure costs.
* **Target Critical Coverage Gap States:** Rivers (0.53 facilities per 10,000 people), Yobe (0.69), Zamfara (0.74), Jigawa (0.83), and Kebbi (0.95) require immediate healthcare infrastructure intervention. These states need both facility rehabilitation and new construction to achieve reasonable coverage ratios comparable to better-served regions.
* **Implement Emergency Healthcare Access Programs:** States where individual facilities serve over 10,000 people (Rivers at 18,600, Yobe at 14,600) need immediate mobile health services, telemedicine programs, and temporary facility deployment to address acute healthcare access crises while permanent infrastructure develops.

### Regional Healthcare Development Strategy
* **Replicate Osun State’s Healthcare Success Model:** Osun’s achievement of 3.3 functional facilities per 10,000 people provides a replicable model for other states. Analyze Osun’s facility management practices, resource allocation strategies, and operational approaches to develop best practice frameworks for national implementation.
* **Create Regional Healthcare Hubs:** Leverage states with strong facility networks like Lagos (2,165 facilities), Benue (1,904), and Kano (1,556) as regional healthcare centers that can support neighboring states through referral systems, specialist services, and technical assistance for facility management and operations
* **Develop Cross-State Healthcare Partnerships:** Establish formal partnerships between high-performing states and underserved regions to share management expertise, technical resources, and operational strategies that can improve functionality rates and coverage effectiveness across state boundaries.

### Healthcare System Efficiency and Management
* **Implement Comprehensive Facility Auditing:** Conduct systematic assessments of the 12,000 non-functional facilities to identify rehabilitation requirements, resource needs, and operational barriers. Prioritize facilities that can be restored to functionality with minimal investment while targeting maximum population impact.
* **Strengthen Primary Healthcare Center Operations:** With 28,000 PHCs forming the backbone of Nigeria’s healthcare system, develop specialized management programs, resource allocation mechanisms, and operational support systems that ensure these critical facilities remain functional and accessible to the communities they serve.
* **Optimize Healthcare Resource Allocation:** Use the population-to-facility ratio analysis to guide resource distribution, ensuring that states with the highest population burdens per facility receive proportional support for infrastructure development, staffing, and operational resources.

### Public-Private Healthcare Partnership Development
* **Expand Private Sector Healthcare Involvement:** With private facilities representing 6,000 of Nigeria’s healthcare infrastructure, create incentive frameworks for private healthcare expansion in underserved states like Rivers, Yobe, and Zamfara, where public facility coverage remains inadequate.
* **Develop Healthcare Investment Attraction Programs:** Use the facility coverage gap analysis to attract domestic and international healthcare investors to regions with the greatest need, offering regulatory support, land access, and operational incentives for healthcare facility development in underserved areas.
* **Create Mixed Ownership Healthcare Models:** Leverage the success of State Primary Healthcare (15,200 facilities) and National Primary Healthcare (11,400 facilities) programs while incorporating private sector efficiency and innovation to create hybrid models that maximize both coverage and operational effectiveness.

### Population-Centered Healthcare Planning
* **Implement Population-Based Healthcare Allocation:** Use the 6,320 people per facility national average as a minimum standard, ensuring that no state exceeds 10,000 people per functional facility while working toward optimal ratios demonstrated by states like Osun and Cross River.
* **Develop Community Healthcare Access Programs:** For communities in states with poor facility coverage, implement community health worker programs, mobile clinic services, and telemedicine initiatives that can provide healthcare access while permanent infrastructure develops.
* **Create Healthcare Equity Monitoring Systems:** Establish ongoing monitoring of facility functionality rates and population coverage ratios to ensure that healthcare access improvements are sustained and that emerging coverage gaps are identified and addressed before they become critical access barriers.

These recommendations provide a comprehensive approach to addressing Nigeria’s healthcare facility challenges while building on existing strengths and successful models demonstrated across different states and regions.

## CONCLUSION
This comprehensive Power BI analysis of Nigeria’s health facilities reveals a healthcare system with substantial infrastructure but significant operational and distribution challenges that affect millions of Nigerians’ access to essential health services.

The analysis shows that while Nigeria operates 46,000 health facilities serving 216.80 million people, only 53.11% of these facilities are functional, creating substantial gaps between healthcare infrastructure availability and actual service delivery. The geographic analysis reveals dramatic disparities, with states like Osun achieving 3.3 functional facilities per 10,000 people while Rivers struggles with only 0.53 facilities per 10,000 people.

The insights demonstrate that Nigeria’s healthcare challenges stem not primarily from insufficient infrastructure but from functionality and distribution inequities that create vastly different healthcare access experiences depending on geographic location. States like Lagos, Benue, and Kano show strong facility networks while Rivers, Yobe, and Zamfara face critical coverage shortages.

The combination of facility functionality analysis and population coverage assessment, supported by extensive Power Query data transformation and DAX-driven calculations, provides stakeholders with the intelligence needed for targeted healthcare policy development, resource allocation decisions, and strategic investments in Nigeria’s healthcare system improvement.

This analysis serves as a foundation for evidence-based healthcare planning that can guide Nigeria toward more equitable healthcare access while maximizing the potential of existing infrastructure through improved functionality and strategic expansion in underserved regions.



