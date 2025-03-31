# Categorization of tasks by prompting

# 1. Scope of application

## 1.1. Purpose of classification

This document establishes a unified system for classifying tasks in the field of industrial engineering, intended for:

1. Standardization of approaches to identification and categorization of tasks solved using industrial engineering methods
2. Ensuring a uniform understanding of task types by all participants in the development process
3. Optimization of the process of selecting technical solutions through clear identification of the task category
4. Simplifying the processes of documenting, scaling and supporting solutions based on Prompt Engineering

The classification is applied at all stages of the solution development life cycle, including:
- Initial requirements analysis
- Design of solution architecture
- Development and testing of prompts
- Documentation of implemented solutions
- Support and development of existing systems

## 1.2. Principles of categorization

The task categorization system is based on the following fundamental principles:

### 1.2.1. Unambiguity of classification
Each task must be clearly related to a certain main category, excluding the possibility of dual interpretation. In the presence of complex tasks, they are decomposed into individual components with subsequent categorization of each component.

### 1.2.2. Completeness of coverage
The classification system provides the ability to categorize any task in the field of industrial engineering. The category structure is designed to cover all possible types of tasks that arise in the process of developing and operating systems based on language models.

### 1.2.3. Scalability
The classification structure provides for the possibility of expanding and detailing categories without violating the basic principles of organization. This ensures the adaptability of the system to the emergence of new types of tasks and the development of industrial engineering technologies.

### 1.2.4. Universality of application
The classification is applicable to industrial engineering tasks regardless of:
- Subject area of ​​application
- Language models used
- The scale of the tasks to be solved
- Implementation specifics

### 1.2.5. Practical applicability
The categorization system is oriented towards practical application and provides:
- Simplicity of defining the task category
- Clear classification criteria
- Clear categorization procedures
- Possibility of process automation

## 1.3. Scope

This classification applies to:
1. All projects using industrial engineering methods
2. All stages of the solution development life cycle
3. All types of problems solved using language models
4. All processes of documentation and standardization in the field of industrial engineering

## 1.4. Limitations of use

When using the classification, the following limitations should be taken into account:
1. The classification does not define specific technical solutions for problems
2. The category system does not prescribe mandatory implementation methods.
3. Classification does not replace the need for detailed analysis of requirements
4. Categorization is an auxiliary tool in the development process

# 2. Classification structure

## 2.1. Main categories of tasks

The classification system includes seven main categories of industrial engineering tasks:

### 2.1.1. Transformation
Tasks involving the transformation of existing information from one form to another without significantly changing the semantic content. Includes:
- Data format conversion
- Translation between languages
- Change of style or tone
- Restructuring of information
- Data normalization

### 2.1.2. Generation
Tasks aimed at creating new content based on input data or parameters. Includes:
- Creation of new content
- Expansion of existing content
- Data synthesis
- Creative generation
- Formation of answers

### 2.1.3. Analysis
Tasks related to extracting information, identifying patterns, and evaluating content characteristics. Includes:
- Classification
- Extracting information
- Pattern detection
- Quality assessment
- Semantic analysis

### 2.1.4. Validation
Tasks to check and confirm that content meets specified criteria and requirements. Includes:
- Checking the correctness
- Identification of inconsistencies
- Data verification
- Checking for compliance with standards
- Quality control

### 2.1.5. Interaction
Tasks related to organizing and maintaining a dialogue between the system and the user. Includes:
- Implementation of dialogue systems
- Processing requests
- Formation of contextual responses
- Role emulation
- Dialogue management

### 2.1.6. Augmentation
Tasks to enrich and supplement existing content with additional information. Includes:
- Data enrichment
- Adding metadata
- Context expansion
- Supplementing information
- Data linking

### 2.1.7. Optimization
Tasks aimed at improving existing content or processes. Includes:
- Improving the quality of content
- Increased efficiency
- Adaptation to requirements
- Customization for target metrics
- Refactoring

## 2.2. Hierarchy and relationships

### 2.2.1. Hierarchy structure
1. Top level: main categories of tasks
2. Middle level: subcategories within the main categories
3. Bottom level: specific types of tasks within subcategories

### 2.2.2. Types of relationships between categories
1. Vertical connections:
   - Relationships "public-private"
   - Inheritance of characteristics
   - Clarification of requirements

2. Horizontal connections:
   - Complementary relationships
   - Sequential dependencies
   - Alternative approaches

### 2.2.3. Principles of hierarchy organization
1. Logical consistency of categories at all levels
2. Unambiguous assignment of tasks to categories
3. Possibility of expansion without breaking the structure
4. Support for complex relationships between tasks

## 2.3. Criteria for classification into categories

### 2.3.1. Main criteria
1. The intended purpose of the task
2. The nature of information transformation
3. Type of expected result
4. Input data requirements
5. Implementation Features

### 2.3.2. Additional criteria
1. Complexity of implementation
2. Resource requirements
3. Specificity of the subject area
4. Limitations of use
5. Requirements for the quality of the result

### 2.3.3. Rules for applying criteria
1. Sequential verification of criteria
2. Priority of the main criteria
3. Taking into account specific requirements
4. Documenting the rationale for the choice

## 2.4. Procedures for maintaining relevance

### 2.4.1. Regular review of the structure
1. Periodic assessment of the relevance of categories
2. Analysis of new types of tasks
3. Identifying the need for change
4. Updating documentation

### 2.4.2. Update mechanisms
1. Procedures for making changes
2. Validation of modifications
3. Control of the integrity of the structure
4. Informing users

### 2.4.3. Versioning Management
1. Tracking changes
2. Documenting modifications
3. Support backward compatibility
4. Archiving previous versions

# 3. Description of categories

## 3.1. Category "Transformation"

### 3.1.1. Definition
Transformation is a category of tasks aimed at converting existing information from one form to another while preserving the main semantic content. The main goal is to change the presentation of data without significantly changing its semantic load.

### 3.1.2. Characteristics
1. Entry requirements:
   - Availability of source content for conversion
   - Clear definition of the target format
   - Specification of transformation rules
   - Semantics Preservation Criteria

2. Output characteristics:
   - Converted content to target format
   - Preservation of semantic load
   - Compliance with the given rules
   - Validity of the result

3. Key Features:
   - Reversibility of transformations
   - Preservation of structural connections
   - Formatting support
   - Processing of special elements

### 3.1.3. Examples of tasks
1. Convert formats:
   - Convert JSON to XML
   - Convert HTML to Markdown
   - Transformation of tabular data into text
   - Structuring unformatted text

2. Language transformations:
   - Translation between natural languages
   - Content localization
   - Adaptation to regional standards
   - Text transliteration

3. Stylistic changes:
   - Changing the tone of the narrative
   - Adaptation of the text formality
   - Adjustment of the target audience
   - Modification of emotional coloring

### 3.1.4. Implementation Features
1. Recommended Prompting Techniques:
   - Zero-shot for simple transformations
   - Few-shot for complex transformations
   - Chain-of-Thought for multi-stage transformations
   - Self-Consistency for results validation

2. Quality control mechanisms:
   - Validation of structural integrity
   - Checking semantic conformity
   - Formatting verification
   - Testing edge cases

3. Process optimization:
   - Caching of typical transformations
   - Data pre-processing
   - Batch processing
   - Parallel execution

### 3.1.5. Requirements for setting tasks
1. Mandatory description elements:
   - Specification of the original format
   - Definition of the target format
   - Conversion rules
   - Criteria for the quality of the result

2. Additional information:
   - Features of handling special cases
   - Performance requirements
   - Resource restrictions
   - Error handling mechanisms

3. Evaluation metrics:
   - Conversion accuracy
   - Preservation of semantics
   - Performance
   - Resource efficiency

## 3.2. Category "Generation"

### 3.2.1. Definition
Generation covers the tasks of creating new content based on input parameters, requirements or existing data. The main goal is to form original content that meets specified criteria and constraints.

### 3.2.2. Characteristics
1. Entry requirements:
   - Content Requirements Specification
   - Definition of target characteristics
   - Contextual restrictions
   - Quality parameters

2. Output characteristics:
   - Original content
   - Compliance with requirements
   - Internal consistency
   - Stylistic unity

3. Key Features:
   - Creativity of generation
   - Uniqueness of results
   - Quality control
   - Scalability of solutions

### 3.2.3. Examples of tasks
1. Creating text content:
   - Writing articles
   - Generation of descriptions
   - Creation of technical documentation
   - Generation of reports

2. Creative generation:
   - Creation of artistic texts
   - Dialogue generation
   - Development of scenarios
   - Writing poetry

3. Data synthesis:
   - Generation of test sets
   - Creation of training examples
   - Formation of synthetic data
   - Template generation

### 3.2.4. Implementation Features
1. Recommended Prompting Techniques:
   - Few-shot for structured generation
   - Chain-of-Thought for complex content
   - Self-Consistency for quality control
   - Tree-of-Thought for creative tasks

2. Control mechanisms:
   - Validation of compliance with requirements
   - Uniqueness check
   - Content quality assessment
   - Verification of consistency

3. Process optimization:
   - Preliminary preparation of templates
   - Use of reference examples
   - Iterative improvement
   - Automatic validation

### 3.2.5. Requirements for setting tasks
1. Mandatory description elements:
   - Targeted content characteristics
   - Restrictions and requirements
   - Quality criteria
   - Result format

2. Additional information:
   - Reference examples
   - Stylistic requirements
   - Specific restrictions
   - Requirements for uniqueness

3. Evaluation metrics:
   - Content quality
   - Compliance with requirements
   - Uniqueness
   - Relevance

## 3.3. Category "Analysis"

### 3.3.1. Definition
Analysis is a category of tasks aimed at extracting information, identifying patterns, and evaluating content characteristics in order to obtain structured conclusions and insights. The main goal is to transform unstructured or semi-structured information into formalized knowledge.

### 3.3.2. Characteristics
1. Entry requirements:
   - Availability of data for analysis
   - Defining the objectives of the analysis
   - Criteria for evaluating results
   - Requirements for the depth of analysis

2. Output characteristics:
   - Structured analysis results
   - Reasonable conclusions
   - Quantitative and qualitative assessments
   - Identified patterns

3. Key Features:
   - Objectivity of analysis
   - Reproducibility of results
   - Depth of research
   - Validity of conclusions

### 3.3.3. Examples of tasks
1. Classification and categorization:
   - Definition of the text theme
   - Classification of requests
   - Categorization of documents
   - Sentiment analysis

2. Extracting information:
   - Highlighting key facts
   - Extracting named entities
   - Definition of relationships
   - Collection of statistical data

3. Analytical tasks:
   - Trend analysis
   - Detection of anomalies
   - Content quality assessment
   - Semantic analysis

### 3.3.4. Implementation Features
1. Recommended Prompting Techniques:
   - Chain-of-Thought for complex analysis
   - Tree-of-Thought for multi-level analysis
   - Zero-shot for easy classification
   - Self-Consistency for results validation

2. Quality control mechanisms:
   - Verification of conclusions
   - Checking the consistency of results
   - Validation of methodology
   - Reliability assessment

3. Process optimization:
   - Data pre-processing
   - Structuring intermediate results
   - Automation of routine operations
   - Parallel processing

### 3.3.5. Requirements for setting tasks
1. Mandatory description elements:
   - Goals and objectives of the analysis
   - Research methodology
   - Requirements for results
   - Quality criteria

2. Additional information:
   - Limitations and Assumptions
   - Accuracy requirements
   - Results presentation format
   - Specific conditions

3. Evaluation metrics:
   - Accuracy of analysis
   - Completeness of conclusions
   - Validity of the results
   - Reproducibility

## 3.4. Category "Validation"

### 3.4.1. Definition
Validation covers the tasks of checking and confirming the compliance of content or processes with specified criteria, standards and requirements. The main goal is to ensure quality and compliance with established standards.

### 3.4.2. Characteristics
1. Entry requirements:
   - Material for verification
   - Validation criteria
   - Conformity standards
   - Quality requirements

2. Output characteristics:
   - Test results
   - Identified inconsistencies
   - Recommendations for correction
   - Confirmation of compliance

3. Key Features:
   - Objectivity of the assessment
   - Completeness of verification
   - Clarity of criteria
   - Reproducibility of results

### 3.4.3. Examples of tasks
1. Verification of compliance with standards:
   - Documentation validation
   - Check formatting
   - Data structure control
   - Verification of metadata

2. Quality control:
   - Grammar and style check
   - Validation of logical coherence
   - Assessment of the completeness of information
   - Verification of data accuracy

3. Specialized validation:
   - Code check
   - Prompt validation
   - Verification of algorithms
   - Testing scenarios

### 3.4.4. Implementation Features
1. Recommended Prompting Techniques:
   - Few-shot for typical checks
   - Chain-of-Thought for complex validation
   - Self-Consistency for increased reliability
   - Tree-of-Thought for multi-criteria testing

2. Control mechanisms:
   - Multi-level verification
   - Cross-validation
   - Automated testing
   - Expert assessment

3. Process optimization:
   - Standardization of procedures
   - Automation of routine checks
   - Creation of validation templates
   - Optimization of criteria

### 3.4.5. Requirements for setting tasks
1. Mandatory description elements:
   - Validation object
   - Verification criteria
   - Requirements for results
   - Verification procedures

2. Additional information:
   - Specific testing conditions
   - Limitations and exclusions
   - Reporting requirements
   - Escalation procedures

3. Evaluation metrics:
   - Completeness of verification
   - Validation accuracy
   - Process efficiency
   - Reliability of results

## 3.5. Category "Interaction"

### 3.5.1. Definition
Interaction is a category of tasks aimed at organizing and maintaining an effective dialogue between the system and the user. The main goal is to ensure natural, context-sensitive and goal-oriented communication to achieve the set goals.

### 3.5.2. Characteristics
1. Entry requirements:
   - Context of interaction
   - Communication goals
   - User parameters
   - Dialogue limitations

2. Output characteristics:
   - Relevant answers
   - Maintaining context
   - Adaptive behavior
   - Dialogue management

3. Key Features:
   - Context dependency
   - Personalization of communication
   - Dialogue sequence
   - Adaptability of interaction

### 3.5.3. Examples of tasks
1. Dialogue systems:
   - Conducting a conversation
   - Answers to questions
   - Consulting
   - User support

2. Role interaction:
   - Emulation of a specialist
   - Role-playing scenarios
   - Educational dialogues
   - Simulation of the interlocutor

3. Context management:
   - Maintaining dialogue history
   - Status tracking
   - Transition management
   - Link processing

### 3.5.4. Implementation Features
1. Recommended Prompting Techniques:
   - Chain-of-Thought for complex dialogues
   - Few-shot for typical scenarios
   - Context Window Management for long conversations
   - Self-Consistency for checking answers

2. Control mechanisms:
   - Relevance validation
   - Consistency check
   - Context control
   - Quality monitoring

3. Process optimization:
   - Context caching
   - Preparing answers in advance
   - State management
   - Memory optimization

### 3.5.5. Requirements for setting tasks
1. Mandatory description elements:
   - Goals of interaction
   - Dialogue scenarios
   - Communication restrictions
   - Quality criteria

2. Additional information:
   - User profiles
   - Specific requirements
   - Exception handling
   - Performance metrics

3. Evaluation metrics:
   - Relevance of answers
   - User satisfaction
   - Effectiveness of dialogue
   - Quality of interaction

## 3.6. Category "Augmentation"

### 3.6.1. Definition
Augmentation covers the tasks of enriching and supplementing existing content with additional information, context or metadata. The main goal is to increase the informativeness and usefulness of content by adding relevant data.

### 3.6.2. Characteristics
1. Entry requirements:
   - Original content
   - Requirements for enrichment
   - Sources of additional data
   - Relevance criteria

2. Output characteristics:
   - Enriched content
   - Added metadata
   - Extended context
   - New connections

3. Key Features:
   - Preservation of original information
   - Relevance of add-ons
   - Data consistency
   - Traceability of changes

### 3.6.3. Examples of tasks
1. Content enrichment:
   - Adding explanations
   - Inclusion of examples
   - Expanding descriptions
   - Adding links

2. Metadata:
   - Content tagging
   - Categorization
   - Adding attributes
   - Linking documents

3. Contextualization:
   - Adding historical context
   - Enable help information
   - Linking to sources
   - Adding explanations

### 3.6.4. Implementation Features
1. Recommended Prompting Techniques:
   - Context Enrichment to add context
   - Chain-of-Thought for complex additions
   - Few-shot for typical enrichments
   - Self-Consistency for relevance checking

2. Control mechanisms:
   - Relevance validation
   - Consistency check
   - Quality control
   - Verification of connections

3. Process optimization:
   - Automation of enrichment
   - Preliminary data preparation
   - Caching information
   - Search optimization

### 3.6.5. Requirements for setting tasks
1. Mandatory description elements:
   - Purposes of enrichment
   - Requirements for add-ons
   - Data sources
   - Quality criteria

2. Additional information:
   - Volume restrictions
   - Enrichment priorities
   - Specific requirements
   - Data formats

3. Evaluation metrics:
   - Relevance of add-ons
   - Quality of enrichment
   - Usefulness of changes
   - Process efficiency

## 3.7. Category "Optimization"

### 3.7.1. Definition
Optimization is a category of tasks aimed at improving existing content or processes in order to increase their efficiency, quality, or compliance with certain criteria.

### 3.7.2. Characteristics
1. Entry requirements:
   - Source material
   - Optimization criteria
   - Target indicators
   - Process limitations

2. Output characteristics:
   - Improved content
   - Optimized processes
   - Increased efficiency
   - Measurable improvements

3. Key Features:
   - Measurability of results
   - Maintaining functionality
   - Controlled changes
   - Reversibility of optimizations

### 3.7.3. Examples of tasks
1. Content optimization:
   - Improved readability
   - Increased efficiency
   - Optimization of structure
   - Text refactoring

2. Process optimization:
   - Improvement of work processes
   - Resource optimization
   - Increased productivity
   - Automation of operations

3. Targeted optimization:
   - Adaptation to metrics
   - Improved performance
   - Optimization of parameters
   - Setting up efficiency

### 3.7.4. Implementation Features
1. Recommended Prompting Techniques:
   - Chain-of-Thought for complex optimizations
   - Self-Consistency for checking results
   - Tree-of-Thought for multi-objective optimization
   - Few-shot for typical improvements

2. Control mechanisms:
   - Measuring indicators
   - Validation of improvements
   - Process monitoring
   - Quality control

3. Process optimization:
   - Iterative improvement
   - Step-by-step validation
   - Change control
   - Feedback

### 3.7.5. Requirements for setting tasks
1. Mandatory description elements:
   - Optimization goals
   - Improvement criteria
   - Process limitations
   - Requirements for results

2. Additional information:
   - Optimization priorities
   - Permissible changes
   - Resource limitations
   - Time frame

3. Evaluation metrics:
   - Efficiency of improvements
   - Degree of optimization
   - Stability of results
   - Sustainability of changes

# 4. Documentation requirements

## 4.1. Task Description Format

### 4.1.1. General format requirements
1. Documentation structure:
   - Hierarchical organization of information
   - Clear division of sections
   - Consistent presentation
   - Formatting consistency

2. Requirements for design:
   - Using installed templates
   - Compliance with style guidelines
   - Uniformity of terminology
   - Correct formatting of code and examples

3. Language requirements:
   - Clarity and unambiguity of wording
   - Professional terminology
   - No jargon
   - Compliance with technical style

### 4.1.2. Structural elements
1. Mandatory sections:
   - Task title and ID
   - Brief description
   - Category and subcategory
   - Requirements and restrictions
   - Expected results
   - Acceptance criteria

2. Additional sections:
   - History of changes
   - Related tasks
   - Notes and comments
   - Applications and links

3. Metadata:
   - Date created/updated
   - Authorship and responsibility
   - Document status
   - Versioning

## 4.2. Necessary information

### 4.2.1. Descriptive information
1. Main characteristics:
   - Full name of the task
   - Goals and objectives
   - Scope of application
   - Expected results

2. Technical details:
   - Prompting techniques used
   - Resource requirements
   - Technical limitations
   - Dependencies and preconditions

3. Business requirements:
   - Justification of necessity
   - Business value
   - Priority
   - Implementation deadlines

### 4.2.2. Technical information
1. Prompt specification:
   - Prompt structure
   - Parameters and variables
   - Input/output data formats
   - Usage examples

2. Implementation requirements:
   - Technical requirements
   - Performance requirements
   - Safety requirements
   - Scalability requirements

3. Testing procedures:
   - Testing methods
   - Test scenarios
   - Success criteria
   - Validation procedures

### 4.2.3. Operational information
1. Execution procedures:
   - Sequence of actions
   - Error handling
   - Monitoring of execution
   - Recovery procedures

2. Support requirements:
   - Update procedures
   - Service regulations
   - Monitoring requirements
   - Reservation procedures

3. Metrics and indicators:
   - Key metrics
   - Measurement methods
   - Target indicators
   - Reporting procedures

## 4.3. Documentation templates

### 4.3.1. Basic Task Template
```markdown
# Task: [Name]
Category: [Category/Subcategory]

## Description
[Detailed description of the task]

## Requirements
### Functional requirements
- [List of requirements]

### Technical requirements
- [List of requirements]

### Restrictions
- [List of restrictions]

## Acceptance Criteria
- [List of criteria]

## Metrics
- [List of metrics]
```

### 4.3.2. Results report template
```markdown
# Result Report: [Name]

## Implementation
### Prompting Techniques
- [Techniques Used]

### Prompt structure
[Description of structure]

## Results overview
[Brief description]

## Metrics
### Key indicators
| Metric | Value | Target | Deviation |
|---------|----------|----------|-----------|

### Analysis of deviations
[Description of deviations]

## Conclusions and recommendations
- [List of conclusions]
```

## 4.4. Documentation procedures

### 4.4.1. Creating documentation
1. Sequence of actions:
   - Definition of document type
   - Selecting a suitable template
   - Filling in the required sections
   - Adding additional information
   - Verification and validation

2. Process requirements:
   - Using installed templates
   - Compliance with formatting
   - Completeness of information
   - Data relevance

3. Quality control:
   - Checking compliance with requirements
   - Content validation
   - Formatting verification
   - Approval of documentation

### 4.4.2. Updating documentation
1. Update procedures:
   - Regular review
   - Making changes
   - Versioning
   - Notification of interested parties

2. Change control:
   - Tracking modifications
   - Documenting changes
   - Validation of updates
   - Archiving versions

3. Version control:
   - Version numbering
   - History of changes
   - Tracking of authorship
   - Conflict control

# 5. Categorization procedures

## 5.1. Methodology for determining the category

### 5.1.1. Categorization algorithm
1. Primary analysis of the problem:
   - Studying the task description
   - Definition of main goals
   - Identification of key requirements
   - Analysis of expected results

2. Evaluation of characteristics:
   - Input data type
   - The nature of the transformations
   - Expected result
   - Process requirements

3. Sequence of category definition:
   - Checking compliance with the main categories
   - Subcategory analysis
   - Clarification of specific characteristics
   - Validation of choice

### 5.1.2. Decision-making criteria
1. Main criteria:
   | Category | Key feature | Task focus | Typical result |
   |-----------|-----------------|---------------|-------------------|
   | Transformation | Reshaping | Transformation | Modified Data |
   | Generation | Creation of new | Creativity | New content |
   | Analysis | Knowledge Extraction | Research | Conclusions and Insights |
   | Validation | Compliance Check | Control | Inspection Report |
   | Interaction | Dialogue and communication | Communication | Relevant answers |
   | Augmentation | Content enrichment | Supplement | Extended content |
   | Optimization | Improvement | Efficiency | Improved Result |

2. Additional criteria:
   - Difficulty of implementation
   - Resource requirements
   - Specificity of the subject area
   - Application features

3. Prioritization of criteria:
   - Primary focus on the main goal
   - Taking into account specific requirements
   - Consideration of limitations
   - Analysis of the context of application

### 5.1.3. Categorization tools
1. Category definition checklists:
   ```markdown
   □ The main objective of the task is defined
   □ Input data analyzed
   □ The nature of the transformations is determined
   □ Key requirements identified
   □ Checked for compliance with category criteria
   □ Specific features taken into account
   □ Selection validation completed
   ```

2. Decision making matrix:
   ```markdown
   1. Main question: What is the main goal?
      □ Change of form → Transformation
      □ Create new → Generate
      □ Knowledge Extraction → Analysis
      □ Compliance Check → Validation
      □ Maintaining a Dialogue → Interaction
      □ Content Supplement → Augmentation
      □ Improvement of the existing → Optimization

   2. Clarifying questions:
      □ Is the original meaning preserved?
      □ Is it necessary to create new content?
      □ Is it necessary to extract information?
      □ Are there any eligibility criteria?
      □ Is dialogue envisaged?
      □ Is data enrichment necessary?
      □ Is improvement needed?
   ```

3. Categorization process diagram:
   ```mermaid
   graph TD
   A[Start] --> B{Shaping?}
   B -->|Yes| C[Transformation]
   B -->|No| D{Create new?}
   D -->|Yes| E[Generation]
   D -->|No| F{Knowledge extraction?}
   F -->|Yes| G[Analysis]
   F -->|No| H{Conformance check?}
   H -->|Yes| I[Validation]
   H -->|No| J{Dialogue?}
   J -->|Yes| K[Interaction]
   J -->|No| L{Enrichment?}
   L -->|Yes| M[Augmentation]
   L -->|No| N[Optimization]
   ```

## 5.2. The process of classifying new tasks

### 5.2.1. Classification stages
1. Preparatory stage:
   - Collection of initial information
   - Requirements analysis
   - Definition of context
   - Identification of limitations

2. Main stage:
   - Application of categorization criteria
   - Checking compliance with specifications
   - Validation of category selection
   - Documenting the solution

3. Final stage:
   - Checking the correctness of the categorization
   - Coordination with stakeholders
   - Recording of results
   - Documentation update

### 5.2.2. Validation procedures
1. Checking the correctness:
   - Compliance with the category criteria
   - Completeness of characteristics accounting
   - No contradictions
   - Compliance with requirements

2. Expert assessment:
   - Checked by experienced specialists
   - Analysis of borderline cases
   - Evaluation of ambiguous situations
   - Coordination of decisions

3. Documenting the results:
   - Recording the rationale for the choice
   - Description of the decision-making process
   - Saving discussion history
   - Preparation of conclusions

## 5.3. Dispute Resolution

### 5.3.1. Identification of disputed cases
1. Signs of controversial cases:
   - Match multiple categories
   - Lack of obvious category features
   - Conflict of characteristics
   - Ambiguity of requirements

2. Analysis procedure:
   - Detailed study of requirements
   - Identification of contradictions
   - Analysis of borderline features
   - Risk assessment of categorization

3. Documenting the difficulties:
   - Description of problematic aspects
   - Fixing contradictions
   - Registration of ambiguities
   - Preserving context

### 5.3.2. Dispute Resolution Procedure
1. Sequence of actions:
   - Convening an expert group
   - Analysis of arguments
   - Discussion of alternatives
   - Decision making

2. Decision-making rules:
   - Priority of the main goal
   - Taking into account practical applicability
   - Minimization of risks
   - Documenting the rationale

3. Recording the results:
   - Registration of the decision
   - Documentation update
   - Informing participants
   - Archiving of materials

### 5.3.3. Preventive measures
1. Dispute Prevention:
   - Clear description of requirements
   - Preliminary examination
   - Proactive discussion
   - Documentation of precedents

2. Process improvement:
   - Regular analysis of controversial cases
   - Criteria update
   - Clarification of procedures
   - Training of participants

3. Knowledge Management:
   - Creation of a precedent base
   - Documentation of decisions
   - Exchange of experience
   - Regular practice reviews
   
