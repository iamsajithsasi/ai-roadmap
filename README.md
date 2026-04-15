# ai-roadmap

# AI / ML / LLM / Agentic AI Preparation Roadmap

---

## 1. Probability & Statistics
- Mean, Median, Mode
- Variance, Standard Deviation
- Probability basics
- Discrete vs Continuous data
- Distributions (Normal, etc.)
- Hypothesis testing (basic idea)

---

## 2. Linear Algebra (Basics)
- Vectors
- Matrices
- Dot product
- Eigenvalues (intuition)

---

## 3. ML Fundamentals
- Supervised / Unsupervised / Reinforcement Learning
- Self-supervised learning (Pretext & Downstream tasks)
- Discriminative vs Generative models
- Bias vs Variance
- Overfitting / Underfitting
- Train / Validation / Test split
- Cross-validation
- Data leakage

---

## 4. Data & Feature Engineering
- Feature extraction / selection / transformation
- Scaling (min-max, standardization)
- Encoding (one-hot, label)
- Missing values, outliers
- Correlation matrix

---

## 5. Core ML Algorithms

### Supervised
- Linear Regression
- Logistic Regression
- Decision Trees
- Random Forest
- KNN
- Naive Bayes
- SVM

### Unsupervised
- K-Means Clustering
- Hierarchical Clustering
- PCA
- Apriori (Association Rules)
  - Support, Confidence, Lift
- Isolation Forest (Anomaly Detection)

---

## 6. Evaluation Metrics

### Classification
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

### Regression
- MAE
- MAPE
- RMSE
- R² Score

---

## 7. Model Training & Optimization
- Training vs Inference
- Real-time vs Batch inference
- Iterations / Epochs / Batch size
- Learning rate
- Gradient Descent (Batch, SGD, Mini-batch)
- Convergence
- Learning curves
- Regularization (L1, L2, Dropout)
- Bias-Variance tradeoff

---

## 8. Hyperparameter Tuning
- Hyperparameters vs Parameters
- Grid Search
- Random Search
- Cross-validation
- Auto tuning (SageMaker, etc.)

---

## 9. ML Lifecycle
- Training
- Tuning
- Evaluation
- Deployment
- Monitoring
- Retraining

---

## 10. Deep Learning Basics
- Neural Networks
- Perceptron & XOR problem
- Activation functions (ReLU, Sigmoid, Softmax)
- Loss functions (MSE, Cross-Entropy)
- Backpropagation (high level)

---

## 11. NLP Foundations
- Tokenization
- TF-IDF
- Word Embeddings

---

## 12. Transformers / LLM Internals
- Input Embeddings
- Positional Encoding
- Multi-Head Attention
- Masked Multi-Head Attention
- Add & Norm
- Feed Forward Network
- Encoder vs Decoder
- Attention mechanism (Q, K, V)
- Transformer vs RNN/LSTM

---

## 13. GenAI / LLM

### Basics
- Tokens, Temperature
- Hallucination
- RLHF

### Prompt Engineering

#### Techniques
- Zero-shot
- One-shot
- Few-shot
- Persona-based prompting
- Chain-of-thought
- Automated reasoning

#### Formats
- Alpaca
- ChatML
- INST

#### Structure
- Instruction / Task
- Steps / Plan
- Context
- Output format
- Constraints
- Tools / Function calling
- Observation / Feedback loop

#### Roles
- System
- User
- Assistant
- Developer

---

## 14. RAG (Retrieval-Augmented Generation)

### Indexing Phase
- Data ingestion
- Chunking
- Embedding generation
- Vector storage

### Retrieval Phase
- Query embedding
- Vector similarity search
- Top-K retrieval
- Re-ranking
- Context injection

### Advanced RAG
- Hybrid search
- Metadata filtering
- Query rewriting
- Caching

---

## 15. Vector Search
- Vector similarity search
- Cosine similarity
- Euclidean distance
- Dot product
- ANN (Approximate Nearest Neighbor)
- HNSW
- FAISS indexing

---

## 16. LLM Ecosystem

### Models
- OpenAI, Claude, Gemini
- DeepSeek, Qwen, LLaMA, Mistral

### Platforms
- Hugging Face
  - Transformers
  - Datasets
  - Tokenizers
  - Pipeline API

### Local Inference
- Ollama
- vLLM

### Tools
- Open WebUI
- LM Studio

---

## 17. AI Backend Engineering
- FastAPI / Flask
- Pydantic (validation, schemas)
- REST APIs
- Async processing
- Streaming responses

---

## 18. Data Engineering
- Kafka
- Spark
- Batch vs Streaming pipelines

---

## 19. Deployment & Cloud
- Docker
- Kubernetes
- AWS / Azure
- CI/CD pipelines

---

## 20. Production AI Systems
- Observability (logs, metrics, tracing)
- Monitoring (latency, errors)
- Guardrails (validation, safety)
- Cost optimization
- Multi-tenant systems

---

## 21. System Design
- RAG system design
- AI platform architecture
- Scaling inference
- API design

---

## 22. API & Distributed Systems
- Rate limiting
- Caching
- Load balancing
- Retries
- Circuit breakers
- Queueing systems

---

## 23. AI System Tradeoffs
- Latency vs Accuracy
- Cost vs Performance
- Throughput vs Quality

---

## 24. Agentic AI Systems (VERY IMPORTANT)

### Core Concepts
- Agent = LLM + Tools + Memory + Planning
- Planning vs Execution

### Architectures
- Single-agent
- Multi-agent systems
- Planner–Executor
- Supervisor–Worker
- Router-based agents

### Workflows
- ReAct pattern (Reason + Act)
- Iterative refinement loops
- Task decomposition

---

## 25. Memory & State Management
- Short-term memory
- Long-term memory
- State management
- Session handling

---

## 26. Tooling & Integration
- Tool schema design
- API integrations
- Knowledge base integration
- Function calling

---

## 27. Safety & Guardrails
- Prompt injection defense
- PII handling
- Permission gating
- Sandboxing
- Output constraints

---

## 28. Structured Outputs
- JSON schema enforcement
- Output parsing
- Validation
- Error handling

---

## 29. Evaluation (LLM / Agents)
- Task success rate
- Tool correctness
- Grounding (RAG accuracy)
- Hallucination detection
- Human-in-the-loop

---

## 30. Testing & Release
- Regression testing
- Canary releases
- A/B testing
- Automated test generation

---

## 31. Reliability Engineering
- Observability
- Failure modes
- Incident response
- Post-mortems
- Runbooks

---

## 32. Performance Optimization
- Caching
- Memoization
- Context optimization
- Model selection
- Latency optimization

---

## 33. Workflow Orchestration
- Task queues
- Async workflows
- DAG systems

Examples:
- Airflow
- Temporal
- Celery

---

## 34. Enterprise AI Concepts
- Multi-tenant architecture
- Access control
- Data governance
- Auditability

---

## 35. Practical / Workflow
- AI-assisted coding
- Agent workflows
- Tool usage
