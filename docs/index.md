# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Glossary** - project terms and concepts

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)

## Custom Project

### Dataset
The dataset contains system performance metrics including requests, errors, and total latency. Each row represents one observation of system activity.


### Signals
I used error_rate and avg_latency_ms, and added a new signal called success_rate to show the percentage of successful requests.


### Experiments
I modified the project by adding the success_rate signal to better understand overall system performance.


### Results
After running the project, the new success_rate column appeared in the output and provided an additional view of system health.


### Interpretation
The system appears stable when success_rate is high and error_rate is low. This helps quickly identify when performance issues may be affecting user experience.
