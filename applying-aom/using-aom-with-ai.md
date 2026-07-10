---
description: >-
  How to connect the AoM to your AI tools, from sharing a single page to a full
  ongoing connection.
icon: sparkles
cover: >-
  https://images.unsplash.com/photo-1517816428104-797678c7cf0c?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHwxMHx8bWFya2V0aW5nfGVufDB8fHx8MTc3NTYwNTc1NXww&ixlib=rb-4.1.0&q=85
coverY: 0
coverHeight: 511
layout:
  width: default
  cover:
    visible: false
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: false
  tags:
    visible: true
  actions:
    visible: true
---

# Using AoM with AI

This wiki is designed so AI can read it clearly. Every page is structured consistently, every image and framework has a text description, and the whole site can be connected to your AI tools so they have ongoing access to the full framework, including updates as it evolves.

{% include "../.gitbook/includes/aom-divider.md" %}

### Why connect the AoM to your AI

Once connected, your AI has ongoing access to the full AoM framework. It can search across every definition, every fundamental, and every connected tool, and stays current as the AoM updates each quarter.

Rather than asking your AI a generic question and getting a generic answer, you can give it the AoM as a shared structure and ask it to reason within that structure. The outputs are more precise, more consistent, and directly connected to how your business thinks about marketing.

#### Example prompts

**Understand a framework distinction**

{% code overflow="wrap" %}
```
Using the AoM, what is the difference between a Channel Strategy and a Channel Plan, and where does each sit in the model?
```
{% endcode %}

**Check licensing and usage terms**

{% code overflow="wrap" %}
```
What are the attribution requirements if I want to use the AoM in my client work or build it into a product?
```
{% endcode %}

**Learn the model structure**

{% code overflow="wrap" %}
```
Give me an overview of the AoM Fundamental View. What are the six sections and what does each one cover?
```
{% endcode %}

**Tell your AI about your business and get a diagnosis**

{% code overflow="wrap" %}
```
Here is a summary of our business and where we are with marketing: [paste your context]. Using the AoM, which fundamentals should we prioritise and where are the likely gaps in our current approach?
```
{% endcode %}

**Assess existing work against the AoM**

{% code overflow="wrap" %}
```
Here is our current brand strategy brief: [paste your brief]. Using the AoM, assess whether it covers the key Brand Strategy fundamentals and identify anything missing or underdeveloped.
```
{% endcode %}

You do not need to tell your AI to use the AoM in every message. Once connected it will draw on it when relevant. For best results start a new conversation after connecting and use one of the prompts above to get going.

{% include "../.gitbook/includes/aom-divider.md" %}

#### Two ways to connect the AoM to your AI

### Temporary connection: Share a URL

The simplest starting point is to share the URL with your chosen AI model.

{% stepper %}
{% step %}
#### **Share the AoM URL directly**

Copy the below URL and paste it into your preferred AI tool.

{% code overflow="wrap" %}
```
https://wiki.anatomyofmarketing.org/llms.txt
```
{% endcode %}

<p align="center">OR</p>
{% endstep %}

{% step %}
#### **Open the copy dropdown menu on any AoM page**

<figure><img src="../.gitbook/assets/AoM_Thumbnail_Dropdown_1.png" alt=""><figcaption></figcaption></figure>

From the Copy menu in the top right of any page, click Open in 'ChatGPT' OR 'Open in Claude'.
{% endstep %}
{% endstepper %}

Both these methods give your AI access to the AoM at that moment. Your AI can browse further from there. This is useful for a one-off task or a quick question. It is not a persistent connection and does not automatically update as the AoM evolves.

{% include "../.gitbook/includes/aom-divider.md" %}

### **Persistent connection: Connect via MCP (recommended)**

Build a persistent connection to give your AI ongoing, searchable access to the full AoM wiki. It stays current as the AoM updates each quarter. Choose the method that matches your preferred AI tool from the below.

<figure><img src="../.gitbook/assets/AoM_Thumbnail_Dropdown_2.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/AoM_Thumbnail_Claude_Logo.png" alt="Claude x AoM lockup banner, the orange starburst Claude logo and wordmark, an &#x22;x&#x22; connector, and the AoM cross-mark icon and wordmark, on a cream background."><figcaption></figcaption></figure>

### **Connect to Claude**

_Available on all Claude plans including Free. Free accounts are limited to one custom connector. On Team and Enterprise plans an Owner must add the connector at organisation level before members can connect. Once configured, connectors sync automatically across web, Desktop, and mobile. Check_ [_support.claude.com_](https://support.claude.com) _for the latest plan details as this feature is in beta._

{% stepper %}
{% step %}
#### Open Connectors

Click your profile icon → Settings → Connectors.

<figure><img src="../.gitbook/assets/AoM_Thumbnail_Claude_Step 1.png" alt="Claude x AoM, Step 1: the account menu open in Claude&#x27;s interface with Settings highlighted, showing the entry point into Claude&#x27;s settings panel."><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/AoM_Thumbnail_Claude_Step 2.png" alt="Claude x AoM, Step 2: Claude&#x27;s Settings panel with Connectors highlighted under the Customize section of the sidebar."><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Add a custom connector

Click Add → Add custom connector.

<figure><img src="../.gitbook/assets/AoM_Thumbnail_Claude_Step 3.png" alt="Claude x AoM, Step 3: the Connectors list showing existing connections such as Figma, Gmail, and Slack, with the Add menu open and Add custom connector highlighted."><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Enter the AoM details

Name the connector 'AoM' and paste the following URL then click Add.

{% code overflow="wrap" %}
```
https://wiki.anatomyofmarketing.org/~gitbook/mcp
```
{% endcode %}

<figure><img src="../.gitbook/assets/AoM_Thumbnail_Claude_Step 4.png" alt="Claude x AoM, Step 4: the Add custom connector dialog filled in with the name &#x22;AoM&#x22; and the URL https://wiki.anatomyofmarketing.org/~gitbook/mcp, alongside optional OAuth fields and connection method settings."><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Set tool permissions

AoM connects automatically and shows two tools: 'Get page content' and 'Search documentation'. Set both to Always allow so Claude can use them without asking for approval each time.

<figure><img src="../.gitbook/assets/AoM_Thumbnail_Claude_Step 5.png" alt="Claude x AoM, Step 5: the connected AoM connector&#x27;s detail page showing its two read-only tools, Get page content and Search documentation, with the permission level dropdown open showing Always allow selected."><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### You are connected

Now just open a new conversation and try one of the [sample prompts](using-aom-with-ai.md#here-are-five-ways-to-start) to get started. The more context you give Claude about your business and decisions, the more useful AoM becomes.
{% endstep %}
{% endstepper %}

{% include "../.gitbook/includes/aom-divider.md" %}

<figure><img src="../.gitbook/assets/AoM_Thumbnail_Claude Code_Logo.png" alt="Claude Code x AoM lockup banner, the orange starburst Claude Code logo and wordmark, an &#x22;x&#x22; connector, and the AoM cross-mark icon and wordmark, on a cream background."><figcaption></figcaption></figure>

### Connect to Claude Code

_Requires Claude Code installed. Available across all projects using the user scope flag._

1. **Step 1: Open your terminal**
2. **Step 2: Run the following command**\
   `claude mcp add --transport http aom https://wiki.anatomyofmarketing.org/~gitbook/mcp`
3. **Step 3: Make it available across all projects (optional)**\
   Add `--scope user` to make the connection available in every Claude Code session, not just the current project:\
   `claude mcp add --transport http --scope user aom https://wiki.anatomyofmarketing.org/~gitbook/mcp`
4. **Step 4: Confirm the connection**\
   Run `/mcp` inside a Claude Code session to confirm AoM appears and is connected.
5. **Step 5: You are connected**\
   Start a session and try it with the AoM →

For the latest setup guidance see the [official Claude Code documentation](https://code.claude.com/docs/en/mcp).

{% include "../.gitbook/includes/aom-divider.md" %}

<figure><img src="../.gitbook/assets/AoM_Thumbnail_VS Code_Logo.png" alt="Visual Studio Code x AoM lockup banner, the blue Visual Studio Code logo and wordmark, an &#x22;x&#x22; connector, and the AoM cross-mark icon and wordmark, on a cream background."><figcaption></figcaption></figure>

### **Connect to VSCode**

_Requires VSCode with GitHub Copilot in Agent mode. The AoM MCP server is added as a remote HTTP server._

1. **Open the Command Palette**\
   Press `Cmd+Shift+P` on Mac or `Ctrl+Shift+P` on Windows → type MCP: Add Server → select it.
2. **Select HTTP server**\
   Choose HTTP (Streamable HTTP) as the server type.
3. **Enter the AoM URL**\
   Paste the following URL when prompted:\
   `https://wiki.anatomyofmarketing.org/~gitbook/mcp`
4. **Name the server**\
   Name it AoM when prompted → select Global to make it available across all your projects, or Workspace to limit it to the current project.
5. **Confirm the connection**\
   VSCode adds the server to your mcp.json file automatically. Open a Copilot Chat in Agent mode and the AoM tools will be available.
6. **You are connected**\
   Start a chat in Agent mode and try it with the AoM →

_Alternatively add it manually by creating or opening `.vscode/mcp.json` in your project and adding:_ json

```json
{
  "servers": {
    "aom": {
      "type": "http",
      "url": "https://wiki.anatomyofmarketing.org/~gitbook/mcp"
    }
  }
}
```

For the latest setup guidance see the [official VSCode MCP documentation](https://code.visualstudio.com/docs/agent-customization/mcp-servers).

{% include "../.gitbook/includes/aom-divider.md" %}

<figure><img src="../.gitbook/assets/AoM_Thumbnail_Open AI Codex_Logo.png" alt="OpenAI Codex x AoM lockup banner, the OpenAI Codex logo and wordmark, an &#x22;x&#x22; connector, and the AoM cross-mark icon and wordmark, on a cream background."><figcaption></figcaption></figure>

### Connect to Codex

_Requires Codex CLI installed. Configuration is shared between the CLI and the Codex IDE extension._

**Step 1: Add the AoM server via CLI**\
Run the following command in your terminal:\
`codex mcp add aom --url https://wiki.anatomyofmarketing.org/~gitbook/mcp`\
&#xNAN;_&#x41;lternatively add it manually by opening or creating `~/.codex/config.toml` and adding:_ toml

```toml
[mcp_servers.aom]
url = "https://wiki.anatomyofmarketing.org/~gitbook/mcp"
```

**Step 2: Confirm the connection**\
Run `/mcp` inside a Codex session to confirm AoM appears and is active.

**Step 3: You are connected**\
Start a session and try it with the AoM →

For the latest setup guidance see the [official Codex MCP documentation](https://developers.openai.com/codex/mcp).

{% include "../.gitbook/includes/aom-divider.md" %}

### Attribution and commercial use

The AoM is openly licensed under CC BY-SA 4.0. Using it within your business or in client work requires attribution. Building a product or service that directly uses the AoM and selling it commercially requires a closer read of the licence terms and may require a partner agreement.

{% content-ref url="../governance/usage-and-licensing.md" %}
[usage-and-licensing.md](../governance/usage-and-licensing.md)
{% endcontent-ref %}

{% include "../.gitbook/includes/aom-divider.md" %}
