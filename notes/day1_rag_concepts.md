RAG brings real-time external knowledge into LLM reasoning → reduces hallucination + keeps answers updated + domain grounded.

Benefits
1. Uses enterprise private data without retraining
   No GPU retraining cost for every new doc update

2. Keeps LLM answers updated
   Vector store update = knowledge refresh → continuous learning   

3. Reduces hallucination significantly
   Model grounds answers on retrieved text not internal memory

4. Cheaper + faster to scale
   You scale storage + retrieval, not huge model weights


RAG = automated + structured retrieval pipeline.

RAG is best when the problem is “knowledge grounding on large external/company data”, not when the problem is “changing model behavior”
