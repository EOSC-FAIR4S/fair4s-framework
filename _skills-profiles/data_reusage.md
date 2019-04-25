---
name: data_reusage
needs: 
  knowledge: 
    - 
      description: |-
        Understand key characteristics of a trustworthy repository service, show familiarity with directories of these services and other reputable sources of data, code and other research outputs for the domain concerned. Understand basic metadata terms, descriptive information, constraints on reuse due to licensing or privacy conditions, and and the conversion, cleaning or normalisation techniques typically used with secondary data in the domain.
      level: basic
    - 
      description: |-
        Identify useful sources of data or code, understand how to search them. Identify good examples of data reuse in the domain, and the metadata or descriptive information used to enable this. Understand how to apply conversion, cleaning or normalisation techniques. Understand how others, e.g. Data Stewards and Research Software Engineers, may support reuse.
      level: intermediate
    - 
      description: |-
        Demonstrate expert knowledge and creativity to find, access, integrate and reuse data for novel purposes.
      level: expert
  skills: 
    - 
      description: |-
        Search for appropriate sources of data or code, find relevant material, describe techniques to reuse it.
      level: basic
    - 
      description: |-
        Demonstrate how to find, access and reuse data/ code in your domain, employing appropriate techniques to make these actionable for the current purpose, e.g. by transferring into a local workspace, cleaning and normalising to a standard, re-compiling or re-configuring code to prepare for reuse, possibly through integration with other objects.
      level: intermediate
    - 
      description: |-
        Demonstrate the ability to make reused data or code actionable for excellent research. Produce expert advice on reuse constraints due to licensing or privacy conditions.
      level: expert
  attitude: 
    - 
      description: |-
        Show willingness to look for existing data or software sources relevant to the problem, rather than creating new data by default, and seek help in doing so from colleagues and professional support services.
      level: basic
    - 
      description: |-
        Give helpful advice to students and colleagues on suitable sources and techniques for reuse, and seek advice from professional research support services where appropriate to broaden reuse opportunities.
      level: intermediate
    - 
      description: |-
        Show creativity in translating secondary data or code from its original context, to address new questions and problems, or to produce new tools to do so.
      level: expert
success_criteria: |-
  Research data, code, and related outputs are found, accessed, and made to interoperate with those locally available. They are made actionable for reuse within licensing or privacy conditions, and enable excellent research, teaching or other applications.
roles: 
  - 
    researcher: 
      - 
        name: r1
        directly_involved: true
      - 
        name: r2
        directly_involved: true
        keyskill: true
      - 
        name: r3
        directly_involved: true
      - 
        name: r4
        directly_involved: true
  - 
    data_scientist:
      - 
        name: r1
        directly_involved: true
        keyskill: true
      - 
        name: r2
        directly_involved: true
        keyskill: true
      - 
        name: r3
        directly_involved: true
      - 
        name: r4
        directly_involved: true
  - 
    data_advisor: 
      - 
        name: data_steward
        directly_involved: true
      - 
        name: research_manager
      - 
        name: user_support_training_outreach
      - 
        name: ethics_data_protection_advisor
        directly_involved: yes
      - 
        name: commercialisation_advisor
        directly_involved: true
  - 
    data_service_provider: 
      - 
        name: data_librarian
        directly_involved: true
      - 
        name: service_manager_project_manager
      - 
        name: research_software_engineer
        directly_involved: true
      - 
        name: data_service_architect
      - 
        name: archivist
        directly_involved: true
related_competences: 
  - name: repository_appraisal_and_selection
  - name: database_management
  - name: software_prototyping
  - name: workflow_setup_and_documentation
  - name: file_naming_and_organisation
  - name: data_cleaning_processing_and_software_versioning
  - name: creative_problem_solving_flexibility
  - name: data_transformation_and_integration
amplifying_capabilities: 
  - 
    name: legal_and_ethics_application
    description: |- 
      Develops local policies and guidelines for publishing research data and related objects, and for selecting repositories that comply with relevant regulatory and policy frameworks.
    services: 
      - Training and support
  - 
    name: fair_output_preparation_and_documentation
    description: |-
      Supports research groups to determine and fulfil appropriate criteria to reuse, manage, and share FAIR research outputs, and fulfil these expectations according to domain norms and standards.
    services: 
      - Sharing and discovery
      - Data management
  - 
    name: data_cleaning_processing_and_software_versioning
    description: |-
      Provides access to relevant tools, services and infrastructure.
    services: 
      - Service catalogue
      - Data management
      - Processing and analysis
---
