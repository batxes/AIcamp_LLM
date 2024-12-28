# Day 2: Cloud AI with Amazon Bedrock & Claude

## Preface
Today we dive into cloud-based AI services, focusing on Amazon Bedrock and Claude. You'll learn how to set up and interact with professional-grade AI services, understanding their capabilities and best practices. This session bridges the gap between basic LLM interaction and production-ready AI implementation.

## Goals
By the end of today, you should:
- Have working access to Amazon Bedrock
- Understand Claude's capabilities
- Be able to make basic API calls
- Know how to handle responses
- Understand cloud AI best practices

## Main Resources
### Required Accounts
- AWS Account
- AWS Access Keys
- Claude API access
- Python environment(IDX)

### Core Services
- Amazon Bedrock Console
- Bedrock Runtime
- Claude API
- boto3 (AWS SDK for Python)

### Development Tools
- Python 3.8+
- Development environment from Day 1
- AWS CLI (optional)

## Tasks
1. AWS Setup
   - Configure AWS account
   - Request model access
   - Set up authentication
   - Test console access

2. Basic Integration
   - Install required packages
   - Configure credentials
   - Test basic calls
   - Handle responses

3. Claude Exploration
   - Understand capabilities
   - Test different prompts
   - Explore parameters
   - Document results

## Instructions
### AWS Configuration
1. Account Setup
   - Create AWS account if needed
   - Create AWS user
   - Add Read Bdrock permissions to user, and invoke LLM and stream
   - Create Access credentials(external service)
   - Note credentials safely

2. Model Management
   - Request access for Anthropic Sonnet
   - Fill out the request form


### Environment configuration
1. Environment Setup
   - Set up an IDX environment with jupyter notebook configured

2. Github code download
   - Make sure to 
   >git clone https://github.com/aicampg/aisg-5-day-aiimmersion.git
   - Open folder day-2 and select the workshop workbook
   - Run the workbook step by step, enter your credentials when asked for.



## Further Resources
### Documentation
- AWS Bedrock: [https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html)
- Claude API: [Anthropic Bedrock documentation](https://docs.anthropic.com/en/api/claude-on-amazon-bedrock)

### Learning Materials
- AWS Bedrock Getting Started
- Claude Prompt Design Guide
- AWS SDK Tutorials

### Additional Reading
- Cloud AI Best Practices
- Security Guidelines
- Cost Management
- Performance Optimization

### Troubleshooting
- Authentication Issues
- API Response Errors
- Rate Limits
- Common Setup Problems

### Preparation for Day 3
- Review multi-modal concepts - [Google Documentation](https://cloud.google.com/use-cases/multimodal-ai)
- Check Google Cloud access - [GCP](https://cloud.google.com/)
- Understand vision APIs - [Documentation](https://ai.google.dev/gemini-api/docs/vision?lang=python)

### Tips
- Keep credentials secure
- Monitor API usage
- Test with small requests first
- Document error messages
- Use version control for code