# Project Creation Flow - Starting Point

## Step 1: Project Setup
- **Project Name**: Text input for project title
- **Project Description**: Optional text area for project overview
- **Project Type**: Dropdown (Software Development, Infrastructure, Research, etc.)
- **Start Date**: Date picker for project kickoff
- **Target End Date**: Date picker for expected completion
- **Project Manager**: Auto-filled with current user (TPM)

## Step 2: Tool Integration
- **Select PM Tool**: Radio buttons (Jira, Asana, Linear, Monday.com, Custom)
- **API Connection**: 
  - For Jira: Workspace URL + API token
  - For Asana: API key + workspace selection
  - For Linear: API key + team selection
- **Test Connection**: Button to verify integration works

## Step 3: Team Configuration
- **Add Team Members**: 
  - Name, Email, Role dropdown (Developer, Designer, QA, etc.)
  - Skill tags (Frontend, Backend, DevOps, etc.)
  - Capacity (hours per week)
- **Team Structure**: Optional org chart or team hierarchy

## Step 4: Tracking Preferences
- **Update Frequency**: How often to check for changes (15min, 1hr, 4hr, daily)
- **Alert Thresholds**:
  - Stale task warning (days without update)
  - Overdue task alert (days past due date)
  - Capacity warning (% of max workload)
- **Notification Channels**: Email, Slack, Teams, Dashboard only

## Step 5: Initial Data Import
- **Import Existing Tasks**: 
  - Upload CSV file with task data
  - Or connect to existing project in PM tool
- **Task Mapping**: Map imported fields to standard format
- **Validation**: Review imported data for accuracy

## Post-Creation Flow

### Immediate Actions
- **Dashboard Setup**: Show empty dashboard with "Getting Started" guide
- **First Sync**: Trigger initial data pull from connected PM tool
- **Welcome Tour**: Interactive walkthrough of dashboard features
- **Sample Data**: Option to load demo project for testing

### Next Steps
- **Agent Activation**: Enable Task Tracking Agent for this project
- **Team Onboarding**: Send invitation emails to team members
- **Baseline Setup**: Establish initial metrics and benchmarks

## Key Questions for Implementation
1. **Required vs Optional**: Which fields should be mandatory vs optional?
2. **Validation Rules**: What validation should we do on user inputs?
3. **Onboarding**: Should we have a guided setup wizard or simple form?
4. **Default Settings**: What should be the default values for tracking preferences?
