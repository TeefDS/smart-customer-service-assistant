# smart-customer-service-assistant

The Smart Customer Service Assistant is an LLM-based customer service system designed to handle common customer requests such as order tracking, return requests, refund status, and payment issues.

The system uses structured data extraction and validation to process customer information safely and accurately. It also includes guardrails to prevent prompt injection, restrict unsupported requests, mask sensitive information, and control access to customer-service tools.

To improve efficiency, the assistant uses model routing to send simple requests to a lower-cost model and more complex cases to a stronger model. It can also escalate unresolved or unsupported cases to a human agent.

The project includes an evaluation framework to test different customer scenarios, a regression gate to ensure new changes do not reduce system quality, and optimization techniques such as routing and caching to reduce cost and response time.
