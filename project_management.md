# Project management


Contents:

* [Overviews](#overviews)
* [Diagrams](#diagrams)
* [Lifecycles](#lifecycles)
* [Unified Processses](#unified_processes)
* [Program Evaluation and Review Technique (PERT)](#program-evalation-and-review-technique-pert)
* [Responsbility Assigment Matrix (RAM)](#responsbility-assignment-matrix-ram)
* [Service Level Agreement Metrics (SLAM)](#service-level-agreement-metrics)
* [Structured systems analysis and design method](structured-systems-analysis-and-design-method-ssadm)
* [Capability maturity model integration (CMMI)](#cmmi-capability-maturity-model-integration)
* [Miscellaneous](#misc)
* [TODO](#todo)


<a name="overviews">Overviews</a>:

* [List of system quality attributes](https://wikipedia.org/wiki/List_of_system_quality_attributes)
* [Outline of project management](https://wikipedia.org/wiki/Outline_of_project_management)
* [Comparison of project management software](https://wikipedia.org/wiki/Comparison_of_project_management_software)


<a name="Diagrams">Diagrams</a>

* [class diagram](https://wikipedia.org/wiki/Class_diagram)
* [data flow diagram (DFD)](https://wikipedia.org/wiki/Data_flow_diagram): a graphical representation of the flow of data through a system, modelling its process aspects.
* [DFD: data flow diagram](https://wikipedia.org/wiki/Data_flow_diagram): a graphical representation of the flow of data through a system, modelling its process aspects.
* [fishbone diagram a.k.a. Ishikawa diagram](https://wikipedia.org/wiki/Ishikawa_diagram): causal diagrams that show the causes of a specific event.
* [Ishikawa diagram a.ka. fishbone diagram](https://wikipedia.org/wiki/Ishikawa_diagram): causal diagrams that show the causes of a specific event.
* [package diagram](https://wikipedia.org/wiki/Package_diagram)
* [use case diagram](https://wikipedia.org/wiki/Use_Case_Diagram)


<a name="Unified Process">Unified Processes</a>

* [Unified Process](https://wikipedia.org/wiki/Unified_Process)
* [OpenUP](https://wikipedia.org/wiki/OpenUP)
* [agile unified process](https://wikipedia.org/wiki/Agile_Unified_Process)
* [Rational Unified Process](https://wikipedia.org/wiki/Rational_Unified_Process)


<a name="lifecycles">Lifecycles</a>:

* [concept-to-cash](TODO): the lifecycle from a new product concept (e.g. feature idea) to cash earned (i.e. the feature is producing financial value).
* [current state](TODO): what is happening right now with a system's people, processes, tools, etc. (cf. future state)
* [end-of-life (EOL)](https://wikipedia.org/wiki/End-of-life_(product)): a product is in the end of its useful life, from the vendor's point of view.
* [end-of-sale (EOS)](https://wikipedia.org/wiki/End-of-life_(product)): a product is in the end of its sales cycle, from the vendor's point of view.
* [EOL: end-of-life)](https://wikipedia.org/wiki/End-of-life_(product)): a product is in the end of its useful life, from the vendor's point of view.
* [EOS: end-of-sale)](https://wikipedia.org/wiki/End-of-life_(product)): a product is in the end of its sales cycle, from the vendor's point of view.
* [future state](TODO): what will be happening with a system's people, processes, tools, etc. (cf. current state)
* [GA: general availability](https://wikipedia.org/wiki/Software_release_life_cycle#GA): a software release life cycle phase when software is publically available.
* [general availability (GA)](https://wikipedia.org/wiki/Software_release_life_cycle#GA): a software release life cycle phase when software is publically available.
* [release to manufacturing (RTM)](https://wikipedia.org/wiki/Software_release_life_cycle#RTM): a software release life cycle phase when software is ready to be delivered or provided to the customer. A.k.a. "going gold".
* [release to web (RTW)](https://wikipedia.org/wiki/Software_release_life_cycle#RTW): a software release life cycle phase when software is ready to be published on the web.
* [RTM: release to manufacturing](https://wikipedia.org/wiki/Software_release_life_cycle#RTM): a software release life cycle phase when software is ready to be delivered or provided to the customer. A.k.a. "going gold".
* [RTW: release to web](https://wikipedia.org/wiki/Software_release_life_cycle#RTW): a software release life cycle phase when software is ready to be published on the web.


<a name="program-evaluation-and-review-technique-pert">Program evaluation and review technique (PERT)</a>

* [PERT: program evaluation and review technique](https://wikipedia.org/wiki/Program_evaluation_and_review_technique)
* [PERT event](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): a point that marks the start or completion of one or more activities. It consumes no time and uses no resources. When it marks the completion of one or more activities, it is not "reached" (does not occur) until all of the activities leading to that event have been completed.
* [predecessor event](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): an event that immediately precedes some other event without any other events intervening. An event can have multiple predecessor events and can be the predecessor of multiple events.
* [successor event](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): an event that immediately follows some other event without any other intervening events. An event can have multiple successor events and can be the successor of multiple events.
* [PERT activity](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): the actual performance of a task which consumes time and requires resources (such as labor, materials, space, machinery). It can be understood as representing the time, effort, and resources required to move from one event to another. A PERT activity cannot be performed until the predecessor event has occurred.
* [PERT sub-activity](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): a PERT activity can be further decomposed into a set of sub-activities. For example, activity A1 can be decomposed into A1.1, A1.2 and A1.3. Sub-activities have all the properties of activities; in particular, a sub-activity has predecessor or successor events just like an activity. A sub-activity can be decomposed again into finer-grained sub-activities.
* [optimistic time](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): the minimum possible time required to accomplish an activity (o) or a path (O), assuming everything proceeds better than is normally expected
* [pessimistic time](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): the maximum possible time required to accomplish an activity (p) or a path (P), assuming everything goes wrong (but excluding major catastrophes).
* [most likely time](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): the best estimate of the time required to accomplish an activity (m) or a path (M), assuming everything proceeds as normal.
* [expected time](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): the best estimate of the time required to accomplish an activity (te) or a path (TE), accounting for the fact that things don't always proceed as normal (the implication being that the expected time is the average time the task would require if the task were repeated on a number of occasions over an extended period of time).
* [standard deviation of time](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): the variability of the time for accomplishing an activity (†óte) or a path (†óTE)
* [float a.k.a. slack](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): a measure of the excess time and resources available to complete a task. It is the amount of time that a project task can be delayed without causing a delay in any subsequent tasks (free float) or the whole project (total float). Positive slack would indicate ahead of schedule; negative slack would indicate behind schedule; and zero slack would indicate on schedule.
* [critical path](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): the longest possible continuous pathway taken from the initial event to the terminal event. It determines the total calendar time required for the project; and, therefore, any time delays along the critical path will delay the reaching of the terminal event by at least the same amount.
* [critical activity](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): An activity that has total float equal to zero. An activity with zero float is not necessarily on the critical path since its path may not be the longest.
* [lead time](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): the time by which a predecessor event must be completed in order to allow sufficient time for the activities that must elapse before a specific PERT event reaches completion.
* [lag time](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): the earliest time by which a successor event can follow a specific PERT event.
* [fast tracking](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): performing more critical activities in parallel
* [crashing critical path](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): Shortening duration of critical activities
* [earliest start time (ES)](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): The earliest time, an activity can start once the previous dependent activities are over.
* [latest start time (LS)](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): LF - activity duration.
* [earliest finish time (EF)](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): ES + activity duration.
* [latest finish time (LF)](https://wikipedia.org/wiki/Program_evaluation_and_review_technique): The latest time an activity can finish without delaying the project.


<a href="responsbility-assignment-matrix-ram">Responsbility Assigment Matrix (RAM)</a>

* [RACI: responsible, accountable, consulted, informed](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [PACSI: perform, accountable, control, suggest, informed](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [RASCI: responsible, accountable, support, control, informed](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [RASI: responsible, accountable, support, informed](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [RACIQ: responsible, accountable, consulted, informed, quality review](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [RACI-VS: responsible, accountable, consulted, informed, verifier, signatory](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [RACIO a.k.a. CAIRO: responsible, accountable, consulted, informed, omitted](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [DACI: driver, approver, contributors, informed](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [RAPID: recommend, agree, perform, input, decide](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [RATSI: responsibility, authority, task, support, informed](https://wikipedia.org/wiki/Responsibility_assignment_matrix)


<a href="service-level-agreement-metrics">Service Level Agreement Metrics</a>

* Abandonment Rate: Percentage of calls abandoned while waiting to be answered.
* ASA (Average Speed to Answer): Average time (usually in seconds) it takes for a call to be answered by the service desk.
* TSF (Time Service Factor): Percentage of calls answered within a definite timeframe, e.g., 80% in 20 seconds.
* FCR (First-Call Resolution): Percentage of incoming calls that can be resolved without the use of a callback or without having the caller call back the helpdesk to finish resolving the case.
* TAT (Turn-Around Time): Time taken to complete a certain task.
* MTTR (Mean Time To Recover): Time taken to recover after an outage of service.


<a name="capability-maturity-model-integration">Capability maturity model integration (CMMI)</a>

* CAR: Causal Analysis and Resolution
* CM: Configuration Management
* DAR:Decision Analysis and Resolution
* IPM: Integrated Project Management
* MA: Measurement and Analysis
* OPD: Organizational Process Definition
* OPF: Organizational Process Focus
* OPM: Organizational Performance Management
* OPP: Organizational Process Performance
* OT: Organizational Training
* PMC: Project Monitoring and Control
* PP: Project Planning
* PM: Project Management
* PPQA: Process and Product Quality Assurance
* QPM: Quantitative Project Management
* REQM: Requirements Management
* RSKM: Risk Management
* SAM: Supplier Agreement Management


<a name="misc">Miscellaneous</a>:
* [5 Whys: questions to get to a root cause](https://wikipedia.org/wiki/5_Whys) (cf. RCA: Root Cause Analysis)
* [ADKAR: awareness, desire, knowledge, ability, reinforcement](https://www.prosci.com/adkar/adkar-model)
 Overview & Exercises | Prosc
* [ADKAR Change Management Model](https://www.prosci.com/adkar/adkar-model) ADKAR: awareness, desire, knowledge, ability, reinforcement
* [ADR: architectural decision record](TODO)
* [agile software development](https://wikipedia.org/wiki/Agile_software_development)
* [ambidextrous organization](https://wikipedia.org/wiki/Ambidextrous_organization): an organization†¢s ability to be efficient in its management of today†¢s business and also adaptable for coping with tomorrow†¢s changing demand.
* [architecturally significant requirement (ASR)](https://wikipedia.org/wiki/Architecturally_Significant_Requirements): requirements that have a measurable effect on a software system†¢s architecture.
* [ASR: architecturally significant requirement](https://wikipedia.org/wiki/Architecturally_Significant_Requirements): requirements that have a measurable effect on a software system†¢s architecture.
* [backlog](https://wikipedia.org/wiki/Backlog)
* [BDUF: big-design-up-front](TODO)
* [Best Known Method (BKM)](https://en.wikipedia.org/wiki/Best_practice) a.k.a best practice
* [best practice](https://en.wikipedia.org/wiki/Best_practice)
* [BKM: Best Known Method](https://en.wikipedia.org/wiki/Best_practice) a.k.a best practice
* [BPR: business process re-engineering](https://wikipedia.org/wiki/Business_Process_Re-engineering) (cf. CBD, CBSE, DSDM)
* [BPMN: business process model and notation](https://wikipedia.org/wiki/Business_Process_Model_and_Notation)
* [business logic](https://wikipedia.org/wiki/Business_logic)
* [business object](https://wikipedia.org/wiki/Business_object)
* [Capability Maturity Model (CMM)](https://en.wikipedia.org/wiki/Capability_Maturity_Model)
* [Capability Maturity Model Integration (CMMI)](https://en.wikipedia.org/wiki/Capability_Maturity_Model_Integration)
* [CCPM: critical chain project management](https://wikipedia.org/wiki/Critical_chain_project_management) (cf. TOC: Theory Of Constraints)
* [charrette](https://wikipedia.org/wiki/Charrette)
* [CM: change management](https://wikipedia.org/wiki/Change_management): any approach to transitioning individuals or teams that significantly reshape an organization.
* [CMM: Capability Maturity Model](https://en.wikipedia.org/wiki/Capability_Maturity_Model)
* [CMMI: Capability Maturity Model Integration](https://en.wikipedia.org/wiki/Capability_Maturity_Model_Integration)
* [component-based development](https://wikipedia.org/wiki/Component-based_development) (a.k.a. CBSE, cf. BPR, DSDM)
* [component-based software engineering](https://wikipedia.org/wiki/Component-based_software_engineering) (a.k.a. CBD; cf. BPR, DSDM)
* [contract data requirements list (CDRL)](https://wikipedia.org/wiki/Contract_data_requirements_list)
* [crash duration](TODO): the shortest possible time for which an activity can be scheduled.
* [critical path drag](https://wikipedia.org/wiki/Critical_path_drag): the amount of time that an activity or constraint on the critical path is adding to the project duration.
* [critical path method (CPM)](https://wikipedia.org/wiki/Critical_path_method): a project modeling technique that priortizes activities, durations, dependencies, and deliverables.
* [cross-fucntional team](https://wikipedia.org/wiki/Cross-functional_team)
* [CRRL: contract data requirements list](https://wikipedia.org/wiki/Contract_data_requirements_list)
* [deliverable](https://wikipedia.org/wiki/Deliverable): a tangible or intangible product or service produced as a result of the project that is intended to be delivered to a customer (either internal or external).
* [dependency](https://wikipedia.org/wiki/Dependency_(project_management))
* [dependency lag](TODO): the amount of time whereby a successor activity will be delayed with respect to a predecessor activity.
* [dependency lead](TODO): the amount of time whereby a successor activity can be advanced with respect to a predecessor activity.
* [design structure matrix (DSM)](https://wikipedia.org/wiki/Design_structure_matrix)
* [DSDM: dynamic systems development Method](https://wikipedia.org/wiki/Dynamic_systems_development_method) (cf. BPR, CBSE)
* [DSM: design structure matrix](https://wikipedia.org/wiki/Design_structure_matrix)
* [EVM: earned value management](https://en.wikipedia.org/wiki/Earned_value_management) a project management technique for measuring project performance and progress in an objective manner.
* [EVPM: earned value project/performance management)](https://en.wikipedia.org/wiki/Earned_value_management) a project management technique for measuring project performance and progress in an objective manner.
* [early adopter a.k.a. lighthouse customer](https://wikipedia.org/wiki/Early_adopter): an early customer of a given company, product, or technology.
* [effort management](https://wikipedia.org/wiki/Effort_management):  the effective and efficient allocation of time and resources to perform activities.
* [estimation](https://wikipedia.org/wiki/Estimation_(project_management))
* [FBE: fuzzy back-end](TODO): the action steps where the production and market launch occur. (cf. FFE)
* [FFE: fuzzy front-end](TODO): activities employed before a well-defined requirements specification is completed.
* [float](https://wikipedia.org/wiki/Float_(project_management))
* [fuzzy back-end (FBE)](TODO): the action steps where the production and market launch occur. (cf. FFE)
* [functional requirements, a.k.a. functional specification](TODO)
* [fuzzy front-end (FFE)](TODO): activities employed before a well-defined requirements specification is completed. (cf. FBE)
* [Gannt chart](https://wikipedia.org/wiki/Gantt_chart)
* [IMP: integrated master plan](https://wikipedia.org/wiki/Integrated_master_plan) documents the significant accomplishments necessary to complete the work and ties each accomplishment to a key program event. (cf. integrated master schedule)
* [integrated master plan (IMP)](https://wikipedia.org/wiki/Integrated_master_plan) documents the significant accomplishments necessary to complete the work and ties each accomplishment to a key program event. (cf. integrated master schedule)
* [iteration](https://wikipedia.org/wiki/Iteration)
* [International Organization for Standardization](https://wikipedia.org/wiki/International_Organization_for_Standardization)
* [ISO 31000 "Risk management •¡¹ Principles and guidelines on implementation"](TODO)
* [Kaizen](https://en.wikipedia.org/wiki/Kaizen)
* [law of two feet](https://wikipedia.org/wiki/Open_Space_Technology): If you are not learning nor contributing, use your two feet to go someplace else.
* [lean dynamics](https://en.wikipedia.org/wiki/Lean_dynamics)
* [linear responsibility chart (LRC)](https://wikipedia.org/wiki/Responsibility_assignment_matrix) a.k.a. RACI matrix.
* [LRC: linear responsibility chart](https://wikipedia.org/wiki/Responsibility_assignment_matrix) a.k.a. RACI matrix.
* [MBO: management by objectives][https://en.wikipedia.org/wiki/Management_by_objectives)
* [Management by objectives (MBO)][https://en.wikipedia.org/wiki/Management_by_objectives)
* [MDI: metric-driven initiative](TODO)
* [minimal viable product (MVP)](https://wikipedia.org/wiki/Minimum_viable_product): a product with just enough features to gather validated learning.
* [MMF: Minimal marketable feature](TODO) akin to minimal viable product.
* [MML: Modeling Maturity Levels](https://en.wikipedia.org/wiki/Modeling_Maturity_Levels)
* [Modeling Maturity Levels (MML)](https://en.wikipedia.org/wiki/Modeling_Maturity_Levels)
* [MoSCoW: must have, should have, could have, won't have](https://wikipedia.org/wiki/MoSCoW_method)): prioritization method
* [must have, should have, could have, won't have (MoSCoW)](https://wikipedia.org/wiki/MoSCoW_method)): prioritization method
* [MVP: minimal viable product](https://wikipedia.org/wiki/Minimum_viable_product): a product with just enough features to gather validated learning.
* [new product development (NPD)](https://wikipedia.org/wiki/New_product_development)
* [NFR: non-functional requirement](https://wikipedia.org/wiki/Non-functional_requirement): specifies criteria of the operation of a system. (cf. quality attributes)
* [non-functional requirement (NFR)](https://wikipedia.org/wiki/Non-functional_requirement): specifies criteria of the operation of a system. (cf. quality attributes)
* [OST: open space technology](https://wikipedia.org/wiki/Open_Space_Technology): an approach to purpose-driven leadership.
* [PDCA: plan•¡¹do•¡¹check•¡¹act](https://wikipedia.org/wiki/PDCA): a management method for process/product control and continual improvement. (a.k.a. Deming cycle)
* [Persona](https://wikipedia.org/wiki/Persona)
* [PERT: program evaluation and review technique](https://wikipedia.org/wiki/Program_evaluation_and_review_technique)
* [planning poker a.k.a. Scrum poker](https://en.wikipedia.org/wiki/Planning_poker): a consensus-based, gamified technique for estimating tasks.
* [PMBOK: Project Management Body of Knowledge](https://wikipedia.org/wiki/Project_Management_Body_of_Knowledge)
* [problem domain](https://wikipedia.org/wiki/Problem_domain)
* [Project Management Body of Knowledge (PMBOK)](https://wikipedia.org/wiki/Project_Management_Body_of_Knowledge)
* [PMO: project management office](https://wikipedia.org/wiki/Project_management_office)
* [project management triangle](https://wikipedia.org/wiki/Project_management_triangle)
* [PRINCE2: Projects In Controlled Environments](https://wikipedia.org/wiki/PRINCE2)
* [Project Management Body of Knowledge](https://wikipedia.org/wiki/Project_Management_Body_of_Knowledge):  a set of standard terminology and guidelines (a body of knowledge) for project management.
* [Project Management Institute](https://wikipedia.org/wiki/Project_Management_Institute)
* [product backlog](https://wikipedia.org/wiki/Scrum_(software_development)#Product_backlog)
* [program evaluation and review technique (PERT)](https://wikipedia.org/wiki/Program_evaluation_and_review_technique)
* [program management]https://wikipedia.org/wiki/Program_management): the process of managing several related projects, often with the intention of improving an organization's performance.
* [project](https://wikipedia.org/wiki/Project)
* [project management office (PMO)](https://wikipedia.org/wiki/Project_management_office)
* [project portfolio management (PPM)](https://wikipedia.org/wiki/Project_portfolio_management)
* [project risk management](https://wikipedia.org/wiki/Project_risk_management)
* [project workforce management](https://wikipedia.org/wiki/Project_workforce_management): the practice of combining the coordination of all logistic elements of a project.
* [propagation strategy](TODO)
* [quality attributes a.k.a. non-functional requirements](https://wikipedia.org/wiki/Quality_attributes)
* [QoS: Quality of Service](https://wikipedia.org/wiki/Quality_of_service): overall performance of a system.
* [RACI: Responsible, Accountable, Consulted, Informed](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [RACI matrix a.k.a. responsibility assignment matrix](https://wikipedia.org/wiki/Responsibility_assignment_matrix): list stakeholders and their responsibilities towards the project.
* [radar chart](https://en.wikipedia.org/wiki/Radar_chart)
* [RAID: Risks, Assumptions, Issues, Dependencies](TODO):
* [RAID log](https://wikipedia.org/wiki/RAID_log): a RAID log keeps track of a project's risks, assumptions, issues, and dependencies
* [RAM: responsibility assignment matrix](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [resource](https://wikipedia.org/wiki/Resource_(project_management)): project management resources are the project's people, equipment, facilities, funding, etc.
* [responsibility assignment matrix (RAM)](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [responsible, accountable, consulted, informed (RACI)](https://wikipedia.org/wiki/Responsibility_assignment_matrix)
* [risks, assumptions, issues, dependencies (RAID)](TODO)
* [requirement analysis](https://wikipedia.org/wiki/Requirements_analysis): elicit, analyze, and record what a systems needs to do.
* [retrospective](https://wikipedia.org/wiki/Retrospective): a look back at events that already have taken place.
* [risk management](https://wikipedia.org/wiki/Risk_management): the identification, assessment, and prioritization of uncertainties, followed by application of resources to minimize, monitor, and control the probability and/or impact of unfortunate events, or to maximize the realization of opportunities.
* [root cause analysis](https://wikipedia.org/wiki/Root_cause_analysis)
* [schedule](https://wikipedia.org/wiki/Schedule_(project_management))
* [scrum](https://wikipedia.org/wiki/Scrum_(software_development)): an iterative and incremental agile software development framework for managing product development
* [SDLC: systems development life cycle](https://wikipedia.org/wiki/Systems_development_life_cycle): a process for planning, creating, testing, and deploying an information system. (a.k.a. application development life-cycle)
* [service-level agreement (SLA)](https://wikipedia.org/wiki/Service-level_agreement): a commitment between a service provider and customer, typically explaining scope, quality, availability, responsibilities, etc.
* [SIPOC](https://en.wikipedia.org/wiki/SIPOC): a tool that summarizes using supplier, input, process, output, customer.
* [SLA: service-level agreement](https://wikipedia.org/wiki/Service-level_agreement): a commitment between a service provider and customer, typically explaining scope, quality, availability, responsibilities, etc.
* [SMART criteria](https://wikipedia.org/wiki/SMART_criteria)
* [software release life cycle](https://wikipedia.org/wiki/Software_release_life_cycle)
* [software requirements specification (SRS)](https://wikipedia.org/wiki/Software_requirements_specification)
* [software system](https://wikipedia.org/wiki/Software_system): a system of intercommunicating components based on software .
* [SOS: Statement Of Scope](TODO) (cf. SOW: Statement Of Work)
* [SOW: Statement Of Work](https://wikipedia.org/wiki/Statement_of_work) (cf. SOS: Statement Of Scope)
* [SRS: software requirements specification](https://wikipedia.org/wiki/Software_requirements_specification)
* [stakeholder](https://wikipedia.org/wiki/Project_stakeholder): an individual or group who may interact with a project's planning or ongoing use.
* [stand-up meeting](https://wikipedia.org/wiki/Stand-up_meeting)
* [systems development life cycle (SDLC)](https://wikipedia.org/wiki/Systems_development_life_cycle): a process for planning, creating, testing, and deploying an information system.
* [Taguchi methods](https://en.wikipedia.org/wiki/Taguchi_methods)
* [task](https://wikipedia.org/wiki/Task_(project_management))
* [task management](https://wikipedia.org/wiki/Task_management)
* [technical support](https://wikipedia.org/wiki/Technical_support)
* [thin-slicing](https://wikipedia.org/wiki/Thin-slicing)
* [timeboxing](https://wikipedia.org/wiki/Timeboxing): a project planning technique that allocates fixed time for a task.
* [time limit a.k.a. deadline](https://wikipedia.org/wiki/Time_limit)
* [TOC: theory of constraints](https://wikipedia.org/wiki/Theory_of_Constraints) (cf. CCPM: Critical Chain Project Management)
* [total project control (TPC)](https://wikipedia.org/wiki/Total_project_control): a project management method that emphasizes continuous tracking and optimization of return on investment (ROI).
* [Toyota Kata](https://en.wikipedia.org/wiki/Toyota_Kata): a book that explains Improvement Kata and Coaching Kata
* [TPC: total project control](https://wikipedia.org/wiki/Total_project_control): a project management method that emphasizes continuous tracking and optimization of return on investment (ROI).
* [Tuckman's stages of group development](https://en.wikipedia.org/wiki/Tuckman%27s_stages_of_group_development)
* [unified process a.k.a. unified software development process](https://wikipedia.org/wiki/Unified_Process)
* [use case, a.k.a. user story](https://wikipedia.org/wiki/Use_case): a list of actions in a system to achieve a goal.
* [value stream mapping (VSM)](https://wikipedia.org/wiki/Value_stream_mapping)
* [VSM: value stream mapping](https://wikipedia.org/wiki/Value_stream_mapping)
* [waterfall model](https://wikipedia.org/wiki/Waterfall_model)
* [WBS: work breakdown structure](https://wikipedia.org/wiki/Work_breakdown_structure): deliverable-oriented decomposition of a project into smaller components.
* [work breakdown structure (WBS)](https://wikipedia.org/wiki/Work_breakdown_structure): deliverable-oriented decomposition of a project into smaller components.


<a name="structured-systems-analysis-and-design-method-ssadm">Structured systems analysis and design method</a>

* [SSADM: structured systems analysis and design method](https://wikipedia.org/wiki/Structured_systems_analysis_and_design_method)
* [structured systems analysis and design method (SSADM)](https://wikipedia.org/wiki/Structured_systems_analysis_and_design_method)
* Logical data modeling; The process of identifying, modeling and documenting the data requirements of the system. The result is a data model containing entities, attributes, and relationships.
* Data Flow Modeling: The process of identifying, modeling and documenting how data moves around an information system. Data Flow Modeling examines processes, data stores, external entities, and data flows.
* Entity Event Modeling: A two-stranded process: Entity Behavior Modeling, identifying, modeling and documenting the events that affect each entity and the sequence (or life history) in which these events occur, and Event Modeling, designing for each event the process to coordinate entity life histories.
* SSADM method stages: Feasibility study, Investigation of the current environment, Business system options, Requirements specification, Technical system options, Logical design, Physical design.


<a name="todo">TODO</a>

* [product lifecycle](https://wikipedia.org/wiki/Product_lifecycle)
* [playbook](TODO): A document defining one or more business process workflows aimed at ensuring a consistent response to situations commonly encountered during the operation of the business.
* [runbook automation (RBA)](TODO): the ability to define, build, orchestrate, manage, and report on workflows that support system and network operational processes.
* [runbook](https://wikipedia.org/wiki/Runbook): a routine compilation of procedures and operations.
* [systems analysis](https://wikipedia.org/wiki/Systems_analysis)
* [systems development life cycle](https://wikipedia.org/wiki/Systems_development_life_cycle)
* [executive sponsor](https://wikipedia.org/wiki/Executive_sponsor)
* [scope](https://wikipedia.org/wiki/Scope_(project_management))
* [schedule](https://wikipedia.org/wiki/Schedule_(project_management))
* [sev: severity](TODO): for example "sev1" is high priority, "sev2" is medium priority, "sev3" is low priority.
* [p: priority](TODO): for example "p1" is high priority, "p2" is medium priority, "p3" is low priority.
* [outline of project management](https://wikipedia.org/wiki/Outline_of_project_management)
* [Project network](https://wikipedia.org/wiki/Project_network)
* [Project management_software](https://wikipedia.org/wiki/Project management_software)
* [Workflow management system](https://wikipedia.org/wiki/Workflow_management_system)
* [Process management](https://wikipedia.org/wiki/Process_management)
* [Project planning](https://wikipedia.org/wiki/Project_planning)
* [Project management](https://wikipedia.org/wiki/Project_management)
* [Work breakdown_structure](https://wikipedia.org/wiki/Work_breakdown_structure)
* [Earned value management](https://wikipedia.org/wiki/Earned value_management)
* [Integrated master plan](https://wikipedia.org/wiki/Integrated_master_plan)
* [SOP: standard operating procedure](https://wikipedia.org/wiki/Standard_operating_procedure)
* [standard operating procedure (SOP)](https://wikipedia.org/wiki/Standard_operating_procedure)
* [WIP: work in progress](TODO)
* [work in progress (WIP)](TODO)
* [WIP limit](TODO): A constraint in a workflow that mitigates potential bottlenecks
* [visual management](TODO): a philosophy that work is better managed through visual systems, such as Kanban, than text lists.
* [task switching](TODO) a.k.a. context switching, multi-tasking; shifting attention between multiple pieces of work.
* [source of demand](TODO): what is driving a business goal such as a requirement for work; the source is sometimes an external customer, sometimes an internal business stakeholder.
* [pull system](TODO): a work process where each stage only pulls work into progress when it has capacity to do so; the opposite of a push system, where work is assigned and added to a queue, regardless of capacity.
* [blocker](TODO): any factor preventing progress, thereby limiting the ability for work to move from one phase in a process to the next phase.
* [bottleneck](TODO): a constraint in the system that limits the flow of work.
* [hidden work-in-progress](TODO): work that a team member is working on but
hasn†¢t made visible, such as by adding a story card to a kanban board.
* [DSU: daily stand up](TODO): a team briefing meeting, typically at the start of each workday.
* [daily stand up (DSU)](TODO): a team briefing meeting, typically at the start of each workday.
* [daily stand down (DSD)](TODO): a team briefing meeting, typically at the end of each workday.
* [DSD: daily stand down](TODO): a team briefing meeting, typically at the end of each workday.
