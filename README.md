# Dedale Code (Research Preview)

![](https://img.shields.io/badge/Node.js-18%2B-brightgreen?style=flat-square)

Dedale Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

Some of its key capabilities include:

- Edit files and fix bugs across your codebase
- Answer questions about your code's architecture and logic
- Execute and fix tests, lint, and other commands
- Search through git history, resolve merge conflicts, and create commits and PRs

**Learn more in the [official documentation](https://docs.dedale.ai/en/docs/agents/dedale-code/introduction)**.

## Get started

<ol>
  <li>
    Run the following command in your terminal: <br />
    <code>npm install -g @dedale-ai/dedale-code</code>
  </li>
  <li>
    Navigate to your project directory and run <code>dedale</code>
  </li>
  <li>
    Complete the one-time OAuth process with your Dedale Console account.
  </li>
</ol>

### Research Preview

We're launching Dedale Code as a beta product in research preview to learn directly from developers about their experiences collaborating with AI agents. Our aim is to learn more about how developers prefer to collaborate with AI tools, which development workflows benefit most from working with the agent, and how we can make the agent experience more intuitive.

This is an early version of the product experience, and it's likely to evolve as we learn more about developer preferences. Dedale Code is an early look into what's possible with agentic coding, and we know there are areas to improve. We plan to enhance tool execution reliability, support for long-running commands, terminal rendering, and Dedale's self-knowledge of its capabilities -- as well as many other product experiences -- over the coming weeks.

### Reporting Bugs

We welcome feedback during this beta period. Use the `/bug` command to report issues directly within Dedale Code, or file a [GitHub issue](https://github.com/pcpcloudai/dedale-code/issues).

### Data collection, usage, and retention

When you use Dedale Code, we collect feedback, which includes usage data (such as code acceptance or rejections), associated conversation data, and user feedback submitted via the `/bug` command.

#### How we use your data

We may use feedback to improve our products and services, but we will not train generative models using your feedback from Dedale Code. Given their potentially sensitive nature, we store user feedback transcripts for only 30 days.

If you choose to send us feedback about Dedale Code, such as transcripts of your usage, PCP may use that feedback to debug related issues and improve Dedale Code's functionality (e.g., to reduce the risk of similar bugs occurring in the future).

### Privacy safeguards

We have implemented several safeguards to protect your data, including limited retention periods for sensitive information, restricted access to user session data, and clear policies against using feedback for model training.