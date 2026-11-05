# EX.NO.4 – GENERATE AND EVALUATE DIFFERENT PROMPT PATTERNS

DATE: 05.11.2026 

REGISTER NUMBER: 212225230071 

## AIM

To generate prompts using Zero-shot, Few-shot, Chain of Thought, Persona, Reverse, Graph, and Active Prompting techniques and evaluate their effectiveness using a rubric.

## EXPLANATION

Prompt Engineering is the process of designing effective instructions to obtain meaningful responses from AI tools such as ChatGPT, Gemini, and Copilot.

## SCENARIO

**IoT-Based Smart Manufacturing Automation**

The manufacturing industry aims to improve production efficiency by 30%, reduce machine downtime, enable real-time monitoring, and reduce energy consumption using IoT devices and embedded controllers.

## PROCEDURE

### 1. Zero-shot Prompting

**Definition:** Giving instructions without examples.

**Prompt:**
"Explain how IoT automation improves manufacturing efficiency and reduces machine downtime."

**Output:**
IoT automation uses sensors and controllers to monitor machines, detect failures, improve production, and reduce energy consumption.

### 2. Few-shot Prompting

**Definition:** Providing examples before asking the AI to perform a task.

**Prompt:**
"Problem: Machine overheating. Solution: Install temperature sensors.

Problem: High energy consumption. Solution: Use energy monitoring.

Now solve: Frequent machine breakdowns. Provide a solution."

**Output:**
Install vibration sensors and predictive maintenance software to detect machine problems before failure.

### 3. Chain of Thought Prompting

**Definition:** Asking AI to provide a structured, step-by-step explanation.

**Prompt:**
"Explain step by step how IoT automation can improve manufacturing efficiency by 30%, reduce downtime, and save energy."

**Output:**
1. Identify manufacturing problems.
2. Install IoT sensors.
3. Connect sensors to controllers.
4. Monitor machine performance.
5. Implement predictive maintenance.
6. Optimize energy consumption.
7. Evaluate production efficiency.

### 4. Persona Pattern

**Definition:** Assigning a specific role to the AI.

**Prompt:**
"Act as an Industrial Automation Engineer. Design an IoT-based manufacturing system using sensors, embedded controllers, and predictive maintenance."

**Output:**
The system uses IoT sensors, PLCs, embedded controllers, and monitoring software to collect machine data, detect faults, and improve production efficiency.

### 5. Reverse Prompting

**Definition:** Working backward from a desired result to identify requirements and develop a suitable prompt.

**Prompt:**
"I want to reduce machine downtime and improve production efficiency. Identify the requirements and create an effective prompt for designing an IoT automation system."

**Output:**
Required components include sensors, embedded controllers, IoT gateways, monitoring software, and predictive maintenance algorithms.

### 6. Graph Prompting

**Definition:** Representing information using nodes and relationships.

**Prompt:**
"Create a graph showing how IoT sensors, controllers, monitoring systems, and predictive maintenance work together in manufacturing."

**Output:**

<CodeBlock language="mermaid" editable>
flowchart TD
A[Manufacturing Machines] --> B[IoT Sensors]
B --> C[Embedded Controllers]
C --> D[Monitoring System]
D --> E[Predictive Maintenance]
E --> F[Maintenance Alerts]
</CodeBlock>

### 7. Active Prompting

**Definition:** Asking questions to collect missing information before generating a solution.

**Prompt:**
"Before designing an IoT manufacturing system, ask five questions about machine types, production capacity, downtime, budget, and energy consumption."

**Output:**
AI asks questions about machine types, production capacity, maintenance requirements, budget, and electricity consumption to prepare a customized solution.

## EVALUATION USING RUBRIC

Each prompt is evaluated out of 5 marks based on clarity, relevance, completeness, accuracy, and usefulness.

| Prompt Pattern | Score / 25 |
|---|---:|
| Zero-shot | 18 |
| Few-shot | 20 |
| Chain of Thought | 24 |
| Persona | 23 |
| Reverse | 23 |
| Graph | 23 |
| Active | 23 |

*Note: These are illustrative scores, not actual cross-platform test results.*

## CONCLUSION

The seven Prompt Engineering techniques were successfully applied to the smart manufacturing scenario. Each technique generated different types of responses based on the given instructions.

## RESULT

Thus, the prompts were successfully generated and evaluated using a rubric-based evaluation method.
