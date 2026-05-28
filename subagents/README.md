# Sub-agents Registry

## Active Agents

### 1. Research Agent
- **name:** research-agent
- **role:** Information gathering
- **capabilities:** Web search, web fetch, browser automation
- **reporting_to:** HQ

### 2. Email Agent  
- **name:** email-agent
- **role:** Email management
- **capabilities:** Send emails, read inbox (IMAP), manage correspondence
- **reporting_to:** HQ

### 3. Code Agent
- **name:** code-agent
- **role:** GitHub management
- **capabilities:** Create repos, push code, manage deployments
- **reporting_to:** HQ

### 4. Communication Agent
- **name:** comm-agent
- **role:** External messaging
- **capabilities:** Telegram messages, notifications
- **reporting_to:** HQ

### 5. Research & Development Agent
- **name:** rd-agent
- **role:** Building new capabilities
- **capabilities:** Browser, code execution, API integrations
- **reporting_to:** HQ

## Agent Template
Each sub-agent should have:
- name: Agent identifier
- role: Business function
- capabilities: What it can do
- reporting_to: Who it reports to
- status: active/inactive