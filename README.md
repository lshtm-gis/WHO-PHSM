# WHO-PHSM
Repository for releases of the WHO PHSM dataset

![](./images/phsm-header1.png)

A repository for access to the PHSM dataset. 

The dataset is also available [here](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/phsm).

## master dataset reference
**processed**  
  - values: `["not_cleansed", "cleansed", "sequenced"]`    
  - description: Whether a column has been cleaned by volunteers. Not cleansed (no volunteer validation), cleansed (validated by volunteers), sequenced (intergated with other preceding and following interventions).  
**who_id**  
  - values:  
  - description: A unique id column for the who_intervention dataset  
**dataset**  
  - values: `["ACAPS", "OxCGRT", "JH_HIT", "CDC_ITF", "WHO_IHR", "GPHIN", "CSHVienna"]`  
  - description: The provider of each record (will change as more records are cleaned).  
**prop_id**  
  - values:  
  - description: A proprietary ID number used by each provider (some are unique, others are unreliable)  
**keep**  
  - values:  
  - description: Used internally by volunteer teams.  
**duplicate_record_id**  
  - values:  
  - description: The who_id of a record that refers to an identical intervention  
**who_region**  
  - values:  
  - description: WHO region of the record  
**country_territory_area**  
  - values:  
  - description: Country name  
**iso**  
  - values:  
  - description: iso3c code - NOTE: WHO has particular regulations about contested territories and areas that do not align with ISO conventions. Kosovo, Taiwan, Macau, Hong Kong, Occupied Palestine.  
**iso_3166_1_numeric**  
  - values:  
  - description: iso3166 numeric code. See note above.  
**admin_level**  
  - values: `["national", "other", "state"]`  
  - description: Whether a record has a "national" or "state" (Admin 1) or "other" extent. Changes to these values coming.   
**area_covered**	  
  - values:  
  - description: Name of a national subregion. May cause problems for contested subregions - see note in `iso`.  
**prov_category**  
  - values:  
  - description: Record provider intervention classifiction.  
**prov_subcategory**  
  - values:  
  - description: Record provider intervention classifiction.  
**prov_measure**  
  - values:  
  - description: Record provider intervention classifiction.  
**who_code**  
  - values:  
  - description: Numeric code of who intervention classification. See codebook   https://www.who.int/emergencies/diseases/novel-coronavirus-2019/phsm.  
**who_category**  
  - values:  
  - description: WHO intervention classifiction.  
**who_subcategory**  
  - values:  
  - description: WHO intervention classifiction.  
**who_measure**  
  - values:  
  - description: WHO intervention classifiction.  
**comments**  
  - values:  
  - description: Free text comments about a record (format and quality varies by provider).  
**date_start**  
  - values:  
  - description: Start date of an intervention.    
**measure_stage**  
  - values:  ["new", "extension", "modification", "phase-out", "finish"]  
  - description: Type of intervention implementation.  
**prev_measure_number**  
  - values:    
  - description: who_id of any preceding interventions.  
**following_measure_number**    
  - values:    
  - description: who_id of any following interventions.  
**date_end**  
  - values:  
  - description: End date of an intervention.  
**reason_ended**  
  - values: ["finish", "extension", "modification", "phase-out", "time limited", "new"]  
  - description: Reason for the end of an intervention.   
**targeted**  
  - values:  
  - description: Whether the intervention is targeted at a specific subgroup. Values vary by provider.  
**enforcement**  
  - values:  
  - description: Whether the intervention is enforced. Values vary by provider.  
**non_compliance_penalty**  
  - values:  
  - description: Penalty for non-compliance. Values vary by provider.  
**value_usd**  
  - values:  
  - description: USD value of an economic intervention (only available for records from OxCGRT).  
**percent_interest**  
  - values:  
  - description: % interest rate change (only available for records from OxCGRT).  
**date_entry**  
  - values:  
  - description: Date of record entry by provider. Only available from some providers.  
**link**  
  - values:  
  - description: Link to record source.  
**link_live**  
  - values:  
  - description: Used internally by volunteer teams.  
**link_eng**    
  - values:  
  - description: Used internally by volunteer teams.    
**source**  
  - values:  
  - description: Free text description of source.  
**source_type**    
  - values:    
  - description: Type of data source. Only available from some providers.  
**alt_link**  
  - values:  
  - description: Alternate link to record source.  
**alt_link_live**  
  - values:  
  - description: Used internally by volunteer teams.  
**alt_link_eng**  
  - values:  
  - description: Used internally by volunteer teams.  
**source_alt**  
  - values:  
  - description: Free text description of alternate source.  
**queries_comments**  
  - values:  
  - description: Used internally by volunteer teams.  

