# WHO-PHSM
Repository for releases of the WHO PHSM dataset

![](./images/phsm-header1.png)

A repository for access to the PHSM dataset. 

The dataset is also available [here](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/phsm).

## master dataset reference
**processed**  
  - values: `["not_cleansed", "cleansed", "sequenced"]`    
  - description: Whether a column has been cleaned by volunteers. Not cleansed (no volunteer validation), cleansed (validated by volunteers), sequenced (intergated with other preceding and following interventions).  
<br/>
**who_id**  
  - values:  
  - description: A unique id column for the who_intervention dataset  
<br/>
**dataset**  
  - values: `["ACAPS", "OxCGRT", "JH_HIT", "CDC_ITF", "WHO_IHR", "GPHIN", "CSHVienna"]`  
  - description: The provider of each record (will change as more records are cleaned).  
<br/>
**prop_id**  
  - values:  
  - description: A proprietary ID number used by each provider (some are unique, others are unreliable)  
<br/>
**keep**  
  - values:  
  - description: Used internally by volunteer teams.  
<br/>
**duplicate_record_id**  
  - values:  
  - description: The who_id of a record that refers to an identical intervention  
<br/>
**who_region**  
  - values:  
  - description: WHO region of the record  
<br/>
**country_territory_area**  
  - values:  
  - description: Country name  
<br/>
**iso**  
  - values:  
  - description: iso3c code - NOTE: WHO has particular regulations about contested territories and areas that do not align with ISO conventions. Kosovo, Taiwan, Macau, Hong Kong, Occupied Palestine.  
<br/>
**iso_3166_1_numeric**  
  - values:  
  - description: iso3166 numeric code. See note above.  
<br/>
**admin_level**  
  - values: `["national", "other", "state"]`  
  - description: Whether a record has a "national" or "state" (Admin 1) or "other" extent. Changes to these values coming.   
<br/>
**area_covered**	  
  - values:  
  - description: Name of a national subregion. May cause problems for contested subregions - see note in `iso`.  
<br/>
**prov_category**  
  - values:  
  - description: Record provider intervention classifiction.  
<br/>
**prov_subcategory**  
  - values:  
  - description: Record provider intervention classifiction.  
<br/>
**prov_measure**  
  - values:  
  - description: Record provider intervention classifiction.  
<br/>
**who_code**  
  - values:  
  - description: Numeric code of who intervention classification. See codebook   https://www.who.int/emergencies/diseases/novel-coronavirus-2019/phsm.  
<br/>
**who_category**  
  - values:  
  - description: WHO intervention classifiction.  
<br/>
**who_subcategory**  
  - values:  
  - description: WHO intervention classifiction.  
<br/>
**who_measure**  
  - values:  
  - description: WHO intervention classifiction.  
<br/>
**comments**  
  - values:  
  - description: Free text comments about a record (format and quality varies by provider).  
<br/>
**date_start**  
  - values:  
  - description: Start date of an intervention.    
<br/>
**measure_stage**  
  - values:  ["new", "extension", "modification", "phase-out", "finish"]  
  - description: Type of intervention implementation.  
<br/>
**prev_measure_number**  
  - values:    
  - description: who_id of any preceding interventions.  
<br/>
**following_measure_number**    
  - values:    
  - description: who_id of any following interventions.  
<br/>
**date_end**  
  - values:  
  - description: End date of an intervention.  
<br/>
**reason_ended**  
  - values: ["finish", "extension", "modification", "phase-out", "time limited", "new"]  
  - description: Reason for the end of an intervention.   
<br/>
**targeted**  
  - values:  
  - description: Whether the intervention is targeted at a specific subgroup. Values vary by provider.  
<br/>
**enforcement**  
  - values:  
  - description: Whether the intervention is enforced. Values vary by provider.  
<br/>
**non_compliance_penalty**  
  - values:  
  - description: Penalty for non-compliance. Values vary by provider.  
<br/>
**value_usd**  
  - values:  
  - description: USD value of an economic intervention (only available for records from OxCGRT).  
<br/>
**percent_interest**  
  - values:  
  - description: % interest rate change (only available for records from OxCGRT).  
<br/>
**date_entry**  
  - values:  
  - description: Date of record entry by provider. Only available from some providers.  
<br/>
**link**  
  - values:  
  - description: Link to record source.  
<br/>
**link_live**  
  - values:  
  - description: Used internally by volunteer teams.  
<br/>
**link_eng**    
  - values:  
  - description: Used internally by volunteer teams.    
<br/>
**source**  
  - values:  
  - description: Free text description of source.  
<br/>
**source_type**    
  - values:    
  - description: Type of data source. Only available from some providers.  
<br/>
**alt_link**  
  - values:  
  - description: Alternate link to record source.  
<br/>
**alt_link_live**  
  - values:  
  - description: Used internally by volunteer teams.  
<br/>
**alt_link_eng**  
  - values:  
  - description: Used internally by volunteer teams.  
<br/>
**source_alt**  
  - values:  
  - description: Free text description of alternate source.  
<br/>
**queries_comments**  
  - values:  
  - description: Used internally by volunteer teams.  