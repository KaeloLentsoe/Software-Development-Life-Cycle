# The Software Development Life Cycle (SDLC) Models

Popular SDLC Models

The software development life cycle (SDLC) encompasses various methodologies for the development and maintenance of software systems. One widely recognized model is the V-Model, characterized by its documentation-intensive approach and sequential execution of processes in a V-shaped manner. Below are some of the key phases of the SDLC life cycle:

# 1. V-Model

The V-Model is an extension of the traditional waterfall model, often referred to as the Verification and Validation model. It emphasizes the association of testing phases with corresponding development stages, ensuring a systematic approach to software development. In this model, each phase of development is directly followed by a testing phase, promoting a disciplined and methodical progression through the project lifecycle.

V-Model - Design

In the V-Model, testing phases are planned concurrently with development phases, forming a distinct pattern resembling a 'V'. On one side of the V, verification phases ensure that each stage of development meets specified requirements, while on the other side, validation phases validate the software against user expectations and needs. The Coding Phase serves as the bridge between these two sides of the V-Model, facilitating the integration of development and testing efforts.

**The following illustration depicts the different phases in a V-Model of the SDLC.**
![Models](/V_Model.jpg)

### There are several verification phases in the V-Model, each of which is explained in detail below:

1. Business Requirement Analysis

This initial phase of the development cycle involves understanding the product requirements from the customer's perspective. Detailed communication with the customer is crucial to grasp their expectations and exact needs, considering that many customers may not have a clear understanding of their requirements. This phase lays the foundation for acceptance test design planning, as business requirements serve as inputs for acceptance testing.

2. System Design

Once the product requirements are clear and detailed, the focus shifts to designing the complete system. System design entails understanding and detailing the entire hardware and communication setup for the product under development. Developing the system test plan based on the system design is critical, as doing so early in the process allows more time for actual test execution later on.

3. Architectural Design

In this phase, architectural specifications are understood and designed, often involving the proposal of multiple technical approaches. The final decision is made based on technical and financial feasibility. The system design is further broken down into modules, each handling different functionalities. This phase, also known as High-Level Design (HLD), clearly defines data transfer and communication between internal modules and with external systems. Integration tests can be designed and documented during this stage based on this information.

4. Module Design

This phase focuses on specifying the detailed internal design for all system modules, referred to as Low-Level Design (LLD). It's crucial for the design to be compatible with other modules in the system architecture and with external systems. Unit tests play a vital role in identifying faults and errors at an early stage, and designing them based on internal module designs can help eliminate maximum issues.

### The V-Model, like any software development methodology, has its own set of advantages and disadvantages:

**Pros:**

1. **Clarity and Structure:** The V-Model provides a clear and structured approach to software development, with each stage having corresponding testing phases. This clarity helps in better understanding and management of the development process.

2. **Early Defect Detection:** Since testing is integrated into each phase of development, defects are identified early in the process, reducing the cost and effort required for fixing them later. This leads to overall higher software quality.

3. **Traceability:** The V-Model promotes traceability by establishing direct links between requirements, design, and testing phases. This ensures that the final product meets the specified requirements and objectives.

4. **Customer Involvement:** The model emphasizes customer involvement throughout the development lifecycle, particularly during the requirements and acceptance testing phases. This helps in aligning the final product with customer expectations.

5. **Documentation:** The V-Model is documentation-intensive, which can be advantageous in maintaining project records, facilitating communication among team members, and ensuring compliance with regulatory standards.

**Cons:**

1. **Rigidity:** The V-Model can be perceived as rigid and inflexible, as it follows a sequential approach where each phase must be completed before proceeding to the next. This may not be suitable for projects with changing or evolving requirements.

2. **Cost and Time:** Due to its thorough and systematic approach, the V-Model may require more time and resources compared to other agile methodologies. This can result in longer development cycles and higher costs.

3. **Late Adaptation:** Since testing is deferred until later stages of development, any changes or modifications identified during testing may require significant rework, leading to delays in project timelines.

4. **Limited Customer Interaction:** While the V-Model emphasizes customer involvement, the level of interaction may still be limited, especially during the development phases. This could result in misunderstandings or misalignment between the final product and customer expectations.

5. **Not Suitable for Small Projects:** The V-Model may be overly complex and bureaucratic for small-scale projects where a more lightweight and flexible approach would be more appropriate.

In summary, while the V-Model offers benefits such as clarity, early defect detection, and traceability, it also has limitations related to rigidity, cost, and limited adaptability. Its suitability depends on factors such as project size, complexity, and the level of customer involvement desired.

# 2. Spiral Model

The spiral model is a risk-driven process model in software development. Unlike traditional linear models, such as the waterfall model, the spiral model allows teams to adopt elements from various methodologies, such as waterfall, incremental, or evolutionary prototyping. It combines the strengths of both the prototyping model and the waterfall model, incorporating rapid prototyping and concurrent design and development activities.

**The following illustration is a representation of the Spiral Model, listing the activities in each phase.**
![Spiral](/Sprial_Model.jpg)

The spiral model consists of four phases, with a software project passing through these phases iteratively, referred to as Spirals.

1. Identification

The Identification phase initiates with gathering business requirements in the baseline spiral. Subsequent spirals focus on identifying system, subsystem, and unit requirements as the product evolves. Continuous communication between the customer and system analyst aids in understanding system requirements. By the spiral's conclusion, the product is deployed in the targeted market.

2. Design

The Design phase commences with conceptual design in the baseline spiral and progresses to include architectural design, logical module design, physical product design, and final design in subsequent spirals.

3. Construct or Build

During the Construct phase, actual software production occurs in each spiral. In the baseline spiral, a Proof of Concept (POC) is developed to gather customer feedback while the design is being refined. Subsequent spirals produce working software models called builds with version numbers, reflecting increased clarity on requirements and design details. These builds are then shared with customers for feedback.

4. Evaluation and Risk Analysis

Risk Analysis involves identifying, estimating, and monitoring technical feasibility and management risks, such as schedule slippage and cost overruns. Upon testing the build, the customer evaluates the software and provides feedback at the end of each iteration.

# 3. Big bang model

The Big Bang model focuses on software development and coding with minimal or no planning. Requirements are implemented as they arise, making it suitable for small projects with small development teams working collaboratively. It is also beneficial for academic software projects and situations where requirements are unknown or there's no fixed release date.

**Pros:**

1. **Simplicity:** The Big Bang model is straightforward and requires minimal planning, making it easy to manage.

2. **Flexibility:** Developers have the flexibility to adapt and implement requirements as they come, allowing for quick adjustments.

3. **Low Resource Requirement:** This model requires very few resources, making it suitable for small projects with limited resources.

4. **Learning Aid:** It serves as a good learning aid for newcomers or students to understand software development processes.

**Cons:**

1. **High Risk:** The lack of planning and upfront analysis results in high risk and uncertainty. Changes or misunderstandings in requirements can lead to project failure or complete scrapping.

2. **Not Suitable for Complex Projects:** The Big Bang model is not suitable for complex or object-oriented projects where a structured approach is required.

3. **Poor for Long-Term Projects:** It is not ideal for long-term or ongoing projects as it lacks a systematic approach to handle evolving requirements over time.

4. **Potential for High Cost:** Misunderstood or changing requirements can lead to costly rework, making the project expensive in the long run.

In summary, while the Big Bang model offers simplicity, flexibility, and low resource requirements, its high risk and lack of suitability for complex projects make it less favorable for long-term, large-scale software development endeavors.

# 4. Waterfall model

The waterfall model is a well-established SDLC model that divides the software development process into distinct phases. Each phase's outcome serves as input for the next phase.

The waterfall methodology typically starts with extensive planning and design phases. Once the software is developed, it undergoes testing before being deployed for use. However, many consider the waterfall model to be too rigid for accommodating changing requirements. It lacks support for feedback throughout the process, which can result in implementing outdated or incorrect requirements.

Recognizing these limitations, more flexible methodologies like Agile have gained popularity. Agile methodologies emphasize iterative development, continuous feedback, and adaptability to changing requirements, making them better suited for dynamic software development environments.

**The following illustration is a representation of the Waterfall Model, listing the activities in each phase.**
![Waterfall](/Requirement_Docs_Image.jpg)

The Waterfall method of software development follows a rigid, predetermined path through a set of phases, originally adapted from traditional engineering practices. Ironically, the paper credited as the origin of the Waterfall method actually describes it as fundamentally flawed. The method we now know as "Waterfall" was mistakenly derived from a misinterpretation of this original work. Nonetheless, Waterfall became a widely adopted, even standard methodology for large projects worldwide.

**Advantages of the Waterfall Model:**

1. Departmentalization and Control: Waterfall development allows for clear departmentalization and control. A schedule with deadlines for each stage of development can be established, enabling the product to progress through the development process model phases one by one.

2. Sequential Progression: Development moves through concept, design, implementation, testing, installation, troubleshooting, and concludes with operation and maintenance. Each phase of development proceeds in strict order.

3. Simple and Easy to Understand: The Waterfall model is simple and easy to understand and use, making it accessible even to those unfamiliar with software development methodologies.

4. Rigidity Facilitates Management: The model's rigidity makes it easy to manage, as each phase has specific deliverables and a defined review process.

5. Effective for Smaller Projects: Waterfall works well for smaller projects where requirements are well understood, as it offers clearly defined stages and milestones.

6. Well-Documented Process: Tasks are easily arranged, and both the process and results are well-documented, facilitating clarity and accountability throughout the development lifecycle.

In summary, while the Waterfall model has its flaws and limitations, its advantages include simplicity, clear progression, ease of management, and effectiveness for smaller projects with well-understood requirements.

