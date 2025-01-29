# IncidentAI
### Project Vision
Leverage the power LLM to handle incidents accurately with no humman in the loop.

As a software provider:
1. I want to answer customer's question quickly.
2. I want to resolve incidents fast.
3. I want to gather multi-sourced diagnosis data easily and fast.
4. I want less manual labor when resolving incidents.

### Application Features
List the features you imagine will achieve the project vision.
1. Application can access blackbox data(CloudWatch).
2. Application can access whitebox data(AWS SQL).
3. Application can access greybox data(Jira).
4. Application can access past incident report(Google Doc).
5. Users can configure the application to collect data from a selection of sources.
6. Application integrates LLM models to generate a root cause with reasoning.
7. Application integrates LLM models to generate mitigation steps with reasoning.
8. Prediction has confidence intervals.

### Technology Selections
- Frontend: HTML + CSS + JavaScript (Easy to understand and maintain)
- Backend: Django + Python (Multiple APIs support the MVC architecture and Ideal for creating scalable REST APIs)
- Database: AWS SQL (Easy integration to the AWS ecosystem)
- Cloud Server: AWS EC2 (Easy integration to the AWS ecosystem)
- LLM model: DeepSeek v2 (powerful, openSource, inexpensive)
- Test: Postman*(Provides an intuitive ui and supports collaboration by allowing teams to share collections, environments, and tests)
