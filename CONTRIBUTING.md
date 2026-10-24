<!---
Copyright 2026 Sahíl Sharma. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# Contribute to Search Agent

Everyone is welcome to contribute, and we value every contribution. Code contributions are not the only way to support the project. Improving AI agent behavior, Google Search integration, geolocation validation, LLM auditing, agent orchestration, performance, architecture, security, testing, or documentation are all valuable ways to contribute to **Search Agent**.

This project was developed as part of the Google Skills learning experience using Google Agent Development Kit (ADK). Contributions that improve the learning experience, reliability, maintainability, and practical application of multi-agent systems are especially welcome.

If you find this project helpful, consider sharing it with others, referencing it in your blogs or projects, discussing it on social platforms, or simply giving the repository a ⭐️ to support the project and the community.

**However you choose to contribute, please be mindful and respect our [Code of Conduct](https://github.com/sahil-me/search-agent/blob/main/CODE_OF_CONDUCT.md).**

## Ways to contribute

There are several ways you can contribute to **Search Agent**.

* **AI Agent Improvements:** Improve the agent's ability to understand user requests, provide relevant information, follow instructions, and deliver useful responses.
* **Google Search Improvements:** Improve search queries, retrieval relevance, result handling, source-grounded responses, and the handling of missing or incomplete search results.
* **Google ADK Improvements:** Improve agent definitions, instructions, tool usage, orchestration, session state, callbacks, and error handling.
* **Geolocation Validation Improvements:** Improve the geolocation validation agent, input validation, handling of invalid or incomplete location information, and reliability of location-related workflows.
* **LLM Auditor Improvements:** Improve the LLM auditor's evaluation workflow, validation logic, sub-agent coordination, and ability to identify unsupported or inconsistent responses.
* **Sub-Agent Integration:** Improve communication and coordination between the root agent and specialized sub-agents, including the critic and reviser components.
* **Gemini Integration:** Improve model configuration, response quality, reliability, instruction following, and integration with Google AI services.
* **Callback Logging Improvements:** Improve callback handling, logging, debugging information, error reporting, and observability while avoiding the exposure of sensitive information.
* **Agent Runtime Improvements:** Improve startup reliability, configuration, authentication, permissions, dependency management, and troubleshooting documentation.
* **Performance Optimization:** Improve search performance, tool execution, response handling, initialization time, and overall application efficiency.
* **Security Improvements:** Help identify and address issues involving credentials, environment variables, permissions, data handling, and configuration.
* **Testing:** Add or improve tests for agent behavior, search results, geolocation validation, auditing logic, sub-agent coordination, and error handling.
* **Documentation:** Improve the README, setup instructions, architecture documentation, usage examples, troubleshooting guidance, and contribution instructions.

> All contributions are valuable to the project and its learning community. 🥰

## Submitting a bug-related issue or feature request

Feel free to open an issue when you encounter a bug or have an idea for improving **Search Agent**. Include relevant error logs, reproduction steps, Python and dependency versions, environment details, or Google Cloud service information when appropriate.

Please check the existing issues before creating a new one. This helps avoid duplicate reports and makes it easier to track existing problems.

### Did you find a bug?

**Search Agent** becomes more reliable through community feedback, issue reporting, testing, and meaningful contributions.

Before reporting an issue, please make sure the bug has not already been reported under the repository's **Issues** section.

When submitting a bug report, please include the following information:

* Your **operating system** and version.
* Python version and relevant dependency versions.
* Steps to reproduce the issue.
* A short description of the expected behavior and what actually happened.
* Relevant error messages or application logs.
* The affected component, such as the Google Search agent, geolocation validator, LLM auditor, or a sub-agent.
* Relevant agent instructions, tool configuration, or orchestration details, when appropriate.
* Google Cloud service or deployment information, if applicable.
* Screenshots or screen recordings, if applicable.
* Any other information that may help reproduce or understand the issue.

Please **do not include API keys, passwords, authentication tokens, service-account credentials, `.env` files, temporary Google Skills lab credentials, or other sensitive information** in an issue.

### Do you want a new feature?

If there is a new feature you'd like to see in **Search Agent**, please open an issue and describe:

1. **Motivation**

   Explain the problem, limitation, or use case that the feature would address.

2. **Feature Description**

   Describe the proposed feature and how you would expect it to work.

3. **AI Agent Behavior**

   If the feature affects an agent, explain how it should influence instructions, search behavior, tool selection, validation, auditing, or responses.

4. **Search and Information Retrieval**

   If the feature depends on Google Search, explain what information should be retrieved, how relevance should be evaluated, and how missing or incomplete results should be handled.

5. **Agent Coordination**

   If the feature affects multiple agents, describe how the root agent and specialized sub-agents should coordinate.

6. **Validation and Auditing**

   If the feature affects geolocation validation or LLM auditing, describe the expected behavior, validation rules, and relevant assumptions.

7. **Implementation Details**

   If you have an implementation idea, architecture suggestion, or code example, feel free to include it.

8. **Additional References**

   If the feature is inspired by an external project, article, design, or technical reference, please include the relevant link.

A clear and well-written feature request makes it easier to evaluate and discuss the proposal.

## Do you want to improve Google Search?

Google Search integration is an important part of the agent's information retrieval workflow.

You can contribute by:

* Improving the construction and relevance of search queries.
* Improving the agent's use of available Google Search tools.
* Improving the interpretation and summarization of retrieved information.
* Improving how the agent handles missing, incomplete, or ambiguous search results.
* Improving error handling when search services are unavailable.
* Improving the agent's ability to distinguish retrieved information from unsupported assumptions.
* Improving response quality when multiple sources provide different information.
* Improving the handling of follow-up questions and search context.
* Improving documentation for search configuration and troubleshooting.
* Adding tests for normal, boundary, and failure scenarios.

When modifying search behavior, ensure that responses remain grounded in the information actually available to the agent. Avoid inventing facts, search results, citations, or source details.

## Do you want to improve AI agent behavior?

Contributions that improve agent behavior are especially welcome.

Examples include:

* Improving agent instructions and descriptions.
* Improving the understanding of user requests.
* Improving root-agent and sub-agent coordination.
* Improving tool selection and tool usage.
* Improving task decomposition and delegation.
* Improving session-state handling.
* Improving callback handling and logging.
* Improving the reliability of multi-agent workflows.
* Reducing hallucinations and unsupported claims.
* Improving the clarity and usefulness of responses.
* Improving handling of missing information and invalid inputs.
* Improving error recovery and graceful failure behavior.
* Improving the coordination between the critic and reviser sub-agents.
* Improving the consistency of agent outputs.

Changes to AI behavior should be tested against representative scenarios to ensure that existing functionality is not unintentionally affected.

## Do you want to improve geolocation validation?

The geolocation validator is a specialized component of **Search Agent**.

You can contribute by:

* Improving validation of location-related inputs.
* Improving handling of missing, malformed, or ambiguous location information.
* Improving input validation and error messages.
* Improving the agent's ability to identify incomplete or invalid inputs.
* Improving integration between geolocation validation and the broader agent workflow.
* Improving error handling for invalid or unexpected responses.
* Adding tests for valid, invalid, boundary, and incomplete inputs.
* Improving documentation for validation rules and assumptions.

When modifying validation logic, clearly document the rules and assumptions being applied. Ensure that invalid input is handled predictably and that validation results are not presented as verified facts without appropriate support.

Any change to validation behavior should be tested against known examples.

## Do you want to improve the LLM auditor?

The LLM auditor and its specialized sub-agents provide opportunities to improve evaluation, criticism, revision, and response quality.

You can contribute by:

* Improving the auditor's instructions and evaluation criteria.
* Improving the critic sub-agent's ability to identify weaknesses or inconsistencies.
* Improving the reviser sub-agent's ability to address identified issues.
* Improving coordination between the auditor, critic, and reviser.
* Improving the detection of unsupported claims and incomplete responses.
* Improving the consistency of evaluation results.
* Improving handling of missing context and ambiguous inputs.
* Improving error handling and callback logging.
* Adding tests for expected, incomplete, inconsistent, and unsupported responses.
* Improving documentation of the auditing workflow and its limitations.

Changes should be evaluated against representative examples. An LLM-generated evaluation should not automatically be treated as proof that a response is correct.

## Do you want to improve Google ADK or Gemini integration?

The project uses Google Agent Development Kit (ADK) to define and coordinate agents.

You can contribute by:

* Improving agent definitions and configuration.
* Improving agent instructions and tool integration.
* Improving root-agent and sub-agent coordination.
* Improving session-state management.
* Improving callback handling and logging.
* Improving model configuration.
* Improving error handling and recovery.
* Improving configuration validation.
* Improving dependency management.
* Improving local development and troubleshooting instructions.
* Improving documentation for Google ADK concepts used in the project.
* Improving the reliability and maintainability of agent workflows.

Infrastructure, model configuration, and permission changes should be reviewed carefully and tested in an appropriate development environment before being submitted.

Do not include temporary Google Skills lab credentials, project-specific secrets, or private configuration files in your changes.

## Do you want to improve testing and reliability?

Testing is an important part of making **Search Agent** easier to maintain and extend.

You can contribute by:

* Adding tests for individual agent components.
* Testing Google Search result handling.
* Testing geolocation validation behavior.
* Testing LLM auditor, critic, and reviser workflows.
* Testing root-agent and sub-agent coordination.
* Testing missing or malformed inputs.
* Testing error handling and unavailable services.
* Testing callback logging and diagnostic behavior.
* Improving repeatability of tests.
* Documenting manual testing procedures.
* Improving the separation of test configuration from production configuration.

Tests should be appropriate to the behavior being changed. Where a workflow depends on external Google services or a configured model, document the required setup and distinguish automated tests from manual integration tests.

## Do you want to improve documentation?

We're always looking for improvements that make **Search Agent** clearer and easier to understand.

You can contribute by:

* Fixing typos or grammatical errors.
* Improving the README.
* Improving setup and installation instructions.
* Clarifying environment-variable configuration.
* Documenting the project architecture.
* Documenting the responsibilities of individual agents and sub-agents.
* Documenting Google Search integration.
* Documenting geolocation validation.
* Documenting the LLM auditor, critic, and reviser workflow.
* Improving callback logging and troubleshooting guidance.
* Documenting Google ADK concepts used in the project.
* Adding examples of supported agent interactions.
* Improving testing instructions.
* Improving dependency and configuration documentation.
* Adding or improving architecture diagrams and screenshots.
* Linking to relevant Google Skills course and lab resources.

Documentation contributions are especially appreciated when they help new contributors understand the project, set up their environment, and get started safely.

## Fixing outstanding issues

If you notice an existing issue and have a fix in mind, feel free to **[start contributing](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)** and open a Pull Request.

### Making code changes

<details>
<summary><strong>Step-by-step contribution workflow</strong></summary>

#### 1. Fork the repository

Go to the [Search Agent repository](https://github.com/sahil-me/search-agent) on GitHub and click the **Fork** button.

#### 2. Clone your forked repository

Replace `<username>` with your GitHub username.

```bash
git clone https://github.com/<username>/search-agent.git
```

Navigate into the project directory:

```bash
cd search-agent
```

#### 3. Create a new branch

Create a separate branch for your feature or bug fix.

```bash
git checkout -b feature/your-feature-name
```

For a bug fix, you can use a name such as:

```bash
git checkout -b fix/issue-description
```

#### 4. Set up the Python environment

Make sure Python is installed. Create a virtual environment from the repository root:

```bash
python -m venv .venv
```

Activate the environment.

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

**macOS / Linux:**

```bash
source .venv/bin/activate
```

#### 5. Install dependencies

The repository contains a `requirements.txt` file under `adk_agents/`.

Install the listed dependencies from the repository root:

```bash
python -m pip install -r adk_agents/requirements.txt
```

If you are working on a component with additional dependency requirements, follow the relevant project instructions.

> Dependency installation commands may need to be adjusted if the repository's dependency files change.

#### 6. Configure Google services

Configure the Google services, authentication, permissions, and other resources required by the component you are working on.

Follow the current project README, the relevant Google Skills lab instructions, and official Google documentation.

Some workflows may require authorized access to Google Search, Gemini, Google Cloud, or other configured services. Contributors are responsible for using an appropriately authorized development environment.

> Never commit API keys, service-account credentials, access tokens, temporary lab credentials, or other secrets to the repository.

#### 7. Configure environment variables

Configure any required environment variables according to the current project and Google ADK setup instructions.

Use your own authorized development resources and follow the applicable configuration guidance.

> Do not commit `.env` files or other files containing sensitive configuration. Keep secrets out of logs, screenshots, and Pull Request descriptions.

#### 8. Run the agent locally

Follow the current project README and the official Google ADK documentation to launch the appropriate agent or development interface.

The repository includes multiple agent components, so the correct startup command and configuration may depend on the component you are working on.

Verify the working directory, installed dependencies, required environment variables, and service configuration before running the agent.

Make sure the relevant component starts successfully before making or testing changes.

#### 9. Make your changes

* Develop the feature or fix the issue.
* Follow the existing project structure and coding conventions.
* Keep changes focused and maintainable.
* Avoid unrelated modifications.
* Document important assumptions.
* Preserve existing functionality unless a change is intentional.
* Test your changes before submitting a Pull Request.

#### 10. Run and test agent behavior

If your changes affect the agent or its tools, test representative scenarios such as:

* Submitting a typical user request and checking the agent's response.
* Running a search-related request and reviewing the retrieved information.
* Handling missing, ambiguous, or incomplete information.
* Validating location-related inputs where applicable.
* Testing the LLM auditor's evaluation workflow.
* Testing critic and reviser sub-agent coordination.
* Verifying root-agent and sub-agent interactions.
* Handling invalid inputs or unexpected tool responses.
* Handling unavailable services or configuration errors.
* Checking that callback logging provides useful diagnostic information without exposing secrets.

Verify that the agent behaves as intended and that its outputs are supported by the information available to it. Do not assume that a plausible-looking AI response is necessarily accurate.

#### 11. Commit your changes

From the repository root, review the files you have changed and stage only the intended changes.

```bash
git status
git add <file-or-directory>
git commit -m "Describe your change"
```

Avoid committing credentials, local configuration files, generated files, or unrelated modifications.

#### 12. Push to your fork

```bash
git push origin feature/your-feature-name
```

Replace the branch name if you used a different one.

#### 13. Create a Pull Request

Open your fork on GitHub and create a Pull Request targeting the original **Search Agent** repository.

In your Pull Request description:

* Explain what you changed.
* Explain why the change was needed.
* Reference any related issue.
* Describe changes to agent behavior or orchestration.
* Explain changes to Google Search, geolocation validation, or auditing logic, if applicable.
* Include relevant screenshots or logs when appropriate.
* Describe the tests you performed.
* Mention Google Cloud configuration or integration changes, if applicable.
* Explain any setup requirements or limitations.

#### 14. Address feedback

If the project maintainer leaves comments or requests changes, address the feedback and push the required updates to your branch.

Thank you for taking the time to review and improve the project!

</details>

## Contribution Guidelines

To keep the project maintainable and welcoming:

* Keep Pull Requests focused on a single feature, fix, or improvement whenever possible.
* Avoid unnecessary changes to unrelated files.
* Follow the existing code style and project structure.
* Test changes before submitting a Pull Request.
* Test AI-agent behavior when modifying agent logic.
* Verify search-related changes against representative examples.
* Test validation logic against valid and invalid inputs.
* Evaluate auditor changes against representative responses.
* Document assumptions that affect agent behavior or validation.
* Avoid introducing unsupported facts or claims into agent responses.
* Keep credentials and sensitive configuration out of the repository.
* Do not commit API keys, `.env` files, service-account credentials, or other secrets.
* Do not make unverified claims about external services or deployment status.
* Provide clear commit messages and Pull Request descriptions.
* Include relevant screenshots, logs, or test results when appropriate.
* Be respectful and constructive when reviewing or discussing contributions.

## I want to become a maintainer of the project. How do I get there?

**Search Agent** is a learning and demonstration project focused on AI agents and multi-agent workflows using Google Agent Development Kit (ADK).

Contributors interested in improving Google Search integration, Gemini, geolocation validation, LLM auditing, agent orchestration, callback logging, testing, security, documentation, and Google Cloud integration are welcome.

If you are interested in contributing at a deeper level, consistently submitting meaningful improvements, reviewing Pull Requests, improving documentation, or helping maintain the project, feel free to get involved and collaborate.

Thank you for contributing to **Search Agent**! 🔎 
