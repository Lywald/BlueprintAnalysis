DOCUMENTATION

```markdown
#  Blueprint Analysis Plugin

An advanced, all-in-one dashboard for analyzing Unreal Engine Blueprints. This plugin provides deep insights into your Blueprints’ structure, performance, and complexity. It helps you identify unused variables, overly nested branches, cross-Blueprint references, and more—saving you time and improving code quality.

## Features

- **Dashboard Overview:**  
  Quickly view key metrics such as node count, average depth, compile time, and memory usage.

- **Complexity Analysis:**  
  Analyze node type frequency and cyclomatic complexity to identify potential hotspots in your Blueprints.

- **Performance & Runtime Stats:**  
  Measure compile times and track runtime event frequencies to optimize performance.

- **Reference Explorer:**  
  Discover cross-Blueprint references and asset dependencies to understand your project’s structure and detect circular dependencies.

- **Lint & Best Practices:**  
  Automatically check for unused variables, naming convention issues, and deprecated nodes.

- **GPT Integration (Optional):**  
  Leverage GPT for advanced analysis, refactoring suggestions, and generating documentation directly from your Blueprints. Note: the plugin will by default load the API key from the system environment variable "OPENAI_API_KEY", so you don't have to retype it each time.

## Installation

**Required Dependencies:**  
   This plugin requires the **Web Browser** and **Editor Scripting Utilities** plugin for its web widget integration. Ensure it is enabled in your project.

## Usage

- **Dashboard & Analysis:**  
  Open the plugin’s UI panel from the Unreal Editor. The dashboard displays high-level metrics about your currently selected Blueprint. (be sure to click the Analyze button)

- **Graph Flow & References:**  
  View detailed logs of Blueprint graph flows and cross-Blueprint references in dedicated tabs for quick troubleshooting and insight.

- **Lint & Best Practices:**  
  Run automated lint checks on your Blueprints to identify potential issues and maintain coding standards.

- **GPT Tools:**  
  Use the integrated GPT query interface to generate docstrings, refactoring suggestions, or get advanced analysis of your Blueprint code.

## Compatibility

- Designed for **Unreal Engine 5.5**.
- Fully compatible with projects that use Blueprints heavily.
- Works best in Editor mode for analysis features (some functionalities are Editor-only). Please don't use it in shipping, finalized builds, that won't work.

## Support & Updates

I will be updating the plugin. Suggestions are welcome!


---

Elevate your Blueprint workflow, reduce technical debt, and optimize your project with the  Blueprint Analysis Plugin.
```
