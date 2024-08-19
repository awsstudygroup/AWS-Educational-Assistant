### AWS Educational Assistant: Product Overview

**AWS Educational Assistant** is a simple demonstration that integrates Amazon Bedrock with the Anthropic Claude 3 Sonnet model, leveraging the capabilities of Langchain and Streamlit. This demo showcases how these tools can be combined to create an interactive educational assistant, providing a foundational example for building similar applications.

**Key Features:**
- **Amazon Bedrock Integration:** Utilize Amazon Bedrock's powerful foundation models.
- **Anthropic Claude 3 Sonnet:** Leverage the capabilities of Claude 3 for advanced natural language understanding and generation.
- **Langchain Integration:** Use Langchain for building complex language model workflows.
- **Streamlit Interface:** A simple and interactive web interface for easy use and deployment.

For more details, please refer to:
- [Amazon Bedrock](https://aws.amazon.com/bedrock/)
- [Anthropic Claude 3](https://www.anthropic.com/news/claude-3-family)

### Demo and Sample Data

To view the demo and explore sample data:
- Access the `demo` folder for a demonstration video.
- Access the `samples` folder for sample videos.

### Step-by-Step Setup Guide

**1. Install Python:**
   - Follow the installation guide for [Python](https://docs.python-guide.org/starting/install3/linux/).

**2. Set Up Python Environment:**
   - Follow the instructions to set up a [Python Environment](https://docs.python-guide.org/starting/install3/linux/).

**3. Install AWS CLI:**
   - Set up AWS CLI by following the [AWS CLI Quickstart Guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html).

**4. Clone the Repository:**
   ```bash
   git clone https://github.com/awsstudygroup/AWS-Educational-Assistant
   ```
   
**5. Navigate to the Project Directory:**
   ```bash
   cd AWS-Educational-Assistant
   ```

**6. Install Required Python Packages:**
   ```bash
   pip3 install -r requirements.txt
   ```

**7. Run the Streamlit Application:**
   ```bash
   streamlit run Home.py --server.port 8080
   ```

### Additional Resources

To learn more about prompt design and the Claude 3 model:
- [Introduction to Prompt Design](https://docs.anthropic.com/claude/docs/introduction-to-prompt-design)
- [Claude 3 Model Card](https://www-cdn.anthropic.com/de8ba9b01c9ab7cbabf5c33b80b7bbc618857627/Model_Card_Claude_3.pdf)