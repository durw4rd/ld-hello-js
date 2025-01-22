### LaunchDarkly Sample JavaScript Application

This is an interactive web application that demonstrates the key features of LaunchDarkly's JavaScript SDK. It provides a user interface for exploring LaunchDarkly's core functionality including feature flag evaluation, context management, and event tracking.

#### Features

1. **LaunchDarkly Client Management**
   - Initialize the LaunchDarkly client with your client-side ID
   - Reinitialize the client with a different ID at runtime
   - View SDK initialization status and timing

2. **Context Management**
   - View current LaunchDarkly context
   - Update context in real-time using JSON input
   - Validate context structure before applying changes

3. **Feature Flag Evaluation**
   - Evaluate any feature flag by key
   - View detailed evaluation results including reasons
   - Real-time updates when flag values change

4. **Event Tracking**
   - Track custom events with optional numeric values
   - View event tracking history
   - Real-time confirmation of tracked events

#### Getting Started

1. Open `index.html` in your browser
2. Enter your LaunchDarkly client-side ID in the "LaunchDarkly Client ID" section
3. Click "Initialize Client" to connect to LaunchDarkly

#### Usage Guide

**Managing LaunchDarkly Client**
- Use the "LaunchDarkly Client ID" section to initialize or reinitialize the client
- The SDK status section will show initialization progress and timing

**Working with Contexts**
- The "Context Details" section shows the current context
- Use the JSON input to modify the context
- Click "Update Context" to apply changes

**Evaluating Feature Flags**
- Enter a flag key in the "Flag Evaluation Detail" section
- Click "Evaluate Flag" to see the evaluation results
- Results include the flag's value and evaluation details

**Tracking Events**
- Use the "Events Tracking" section to track custom events
- Enter an event key and optional numeric value
- Click "Track Event" to send the event to LaunchDarkly
- View the history of tracked events below

#### Additional Resources
- [LaunchDarkly JavaScript SDK Documentation](https://docs.launchdarkly.com/sdk/client-side/javascript)
- [LaunchDarkly Quickstart Guide](https://app.launchdarkly.com/quickstart#/)
