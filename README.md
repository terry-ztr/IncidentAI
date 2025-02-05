### Project Vision
Leverage Large Language Models (LLMs) to automate incident diagnosis data collection, root cause analysis (RCA), and mitigation, reducing manual efforts and accelerating resolution.

### Application Features
1. **Multi-source data integration**
    - Access blackbox data (e.g., CloudWatch logs).
    - Access whitebox data (e.g., AWS SQL metrics).
    - Access greybox data (e.g., Jira incident tickets).
    - Access historical incident reports (e.g., Google Docs or internal KBAs).
2. **Configurable and extensible**
    - Users can configure data sources and diagnostic workflows to match their environment.
    - Allows for easy integration with third-party monitoring tools and incident tracking systems.
3. **Automated incident diagnosis**
   - Uses predefined or dynamically generated workflows to collect, filter, and prioritize relevant diagnostic data upon incident detection.
   - Handles information overload by summarizing key details.
4. **Intelligent root cause analysis**
     - LLMs analyze aggregated data and predict root cause categories with reasoning.
5. **Mitigation step generation** (stretch goals)
    - Recommends actionable mitigation steps based on past incidents and learned patterns.
    - Offers explanations for recommended actions to assist engineers in decision-making.
6. **Human-AI collaboration** (stretch goals)
    - Provides suggested RCA and mitigation but allows engineers to override and refine recommendations.
    - Enables interactive querying of historical incidents and diagnostic steps.

### Technology Selections
- Frontend: HTML + CSS + JavaScript (Easy to understand and maintain)
- Backend: Django + Python (Multiple APIs support the MVC architecture and Ideal for creating scalable REST APIs)
- Database: AWS SQL (Easy integration to the AWS ecosystem)
- Cloud Server: AWS EC2 (Easy integration to the AWS ecosystem)
- LLM model: gpt-4o-mini (cost-efficient, fine-tuning capable with conversation example)
- Test: Postman*(Provides an intuitive ui and supports collaboration by allowing teams to share collections, environments, and tests)
- API documentation: apifox(free)
