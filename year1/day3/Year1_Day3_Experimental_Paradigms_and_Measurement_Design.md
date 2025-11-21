Year 1 – Day 3

Signal Modeling & Construct-Level Feature Engineering
Research Log — Cognitive Modeling & Personalized AI Systems
Author: Julián Rojas


1. Objective of Day 3

Define the measurable signals that correspond to each cognitive construct and build the first formal “feature engineering layer” that translates raw behavior into structured cognitive indicators.

This is the bridge between theory (Day 1) and architecture (Day 2).


2. Construct-to-Signal Mapping Framework (CSMF)

The goal of this framework is to specify exactly how abstract cognitive constructs become empirical features.

2.1 Mapping Principles

Each cognitive construct must have:
	•	A theoretical definition (from the Cognitive Atlas).
	•	An operationalization schema (Day 2 outcome).
	•	A signal extraction plan describing what data is required.
	•	A feature transformation rule defining how raw data becomes a cognitive indicator.


3. Signal Categories (Clean Academic Specification)

3.1 Behavioral Signals

Signals derived from user actions and choices:
	•	Decision latency (reaction times, hesitation)
	•	Exploration vs exploitation patterning
	•	Error recovery behavior
	•	Sequential decision trajectories

These allow inference of constructs such as cognitive control, uncertainty, and strategy selection.


3.2 Interaction Dynamics Signals

Pattern-level metrics across interactions:
	•	Response variability
	•	Micro-patterns in adjustment after feedback
	•	Multi-step intention stability
	•	Task-switching fluidity

These map to constructs like cognitive flexibility and working memory load.


3.3 Linguistic-Cognitive Signals

Extracted through LLM-based semantic analysis:
	•	Ambiguity markers
	•	Confidence expressions
	•	Goal-statement clarity
	•	Cognitive load linguistic indicators
	•	Strategy descriptions embedded in natural language

These signals feed directly into Bayesian inference of mental states.


3.4 Temporal Signals

Time-based dynamics reflecting cognitive state transitions:
	•	Short-term adaptation slope
	•	Long-term drift in strategy
	•	Phase-shift patterns in uncertainty

These support probabilistic modeling of cognitive stability and transitions.


4. Feature Engineering Specification (Professional Technical Format)

For each construct, we define:

Construct Name
	•	Raw Signals: (list)
	•	Processing: normalization, smoothing, semantic embedding, or filtering method
	•	Final Feature: scalar value, vector embedding, or probabilistic indicator

Example (Fully Polished): Working Memory Load
	•	Raw signals:
	•	average latency per decision
	•	semantic complexity of user question
	•	error patterns in multi-step tasks
	•	Processing:
	•	z-scored latency normalization
	•	language complexity embedding
	•	temporal smoothing across trials
	•	Final Feature:
	•	WM_Load_Index (continuous variable, 0–1)


Example: Decision Uncertainty
	•	Raw signals:
	•	hesitation markers in text
	•	oscillation between choices
	•	sequential divergence from optimal path
	•	Processing:
	•	hesitation classifier
	•	choice divergence model
	•	Final Feature:
	•	P(uncertainty | signals) as a Bayesian posterior


5. Integration with Day 2 Architecture

Once features are extracted:
	1.	The SOE receives raw signals and applies these feature engineering rules.
	2.	Clean cognitive indicators are passed into the Bayesian Mental State Module.
	3.	Neural language embeddings from the NRCIM influence the weighting of each feature.
	4.	The CCI fuses probabilistic estimates and neural interpretations.

This completes the bottom-up pipeline of the system.


6. Academic Contribution (Strong, Subtle, and Professional)

This feature engineering layer introduces construct-level interpretability into the hybrid architecture by:
	•	Creating a direct computational realization of cognitive ontology concepts.
	•	Allowing reproducible inference of mental states based on standardized indicators.
	•	Providing a scalable approach to modeling cognition through measurable signals rather than opaque heuristics.

This aligns with modern computational cognitive science and emerging work on integrating ontological structure into machine learning pipelines.


End of Day 3 Entry

Year 1 — Cognitive Signal Modeling & Feature Engineering
