<!-- ============================== -->
<!-- Section: Developer Checklist  -->
<!-- ============================== -->

## What does this PR do?

## What are the relevant tickets?

## Where should the reviewer start?

## How can this be manually tested?

## Any additional context?

## Screenshots (if appropriate)

## Definition of Done

- [ ] Meets acceptance criteria from Jira ticket
- [ ] Includes relevant automated tests
- [ ] Reviewed for performance impact (e.g. loops, queries, large payloads)
- [ ] Reviewed for security risks (e.g. XSS, injection, unsafe eval/exec, secrets in code)
- [ ] Input validation and sanitization in place
- [ ] Appropriate error handling included
- [ ] Feature flag used if appropriate
- [ ] Backwards compatibility maintained
- [ ] All TODOs are resolved or linked to a task

---

<!-- ============================== -->
<!-- Section: Reviewer Checklist   -->
<!-- ============================== -->

### Jira & Documentation

- [ ] Jira reference included and matches implementation
- [ ] New endpoints documented in Swagger/OpenAPI
- [ ] Feature documented in Confluence (if required)

### Code Quality

- [ ] PR follows [code style guidelines](https://clubspark.atlassian.net/wiki/spaces/DEV/pages/1228768243/Coding+guidelines+-+Javascript)
- [ ] Code is readable and maintainable
- [ ] Code includes unit tests with good coverage
- [ ] Integration/regression tests updated if needed

### Security

- [ ] No secrets or credentials in code/config
- [ ] Sensitive data is masked or encrypted as needed
- [ ] Secure headers, CORS, auth/permissions considered
- [ ] Third-party libraries vetted for security risks

### Deployment

- [ ] Requires SQL scripts? If yes, reviewed and safe to run
- [ ] Requires infrastructure changes? If yes, approved/communicated
- [ ] New dependencies declared and justified (e.g. Mailjet, Salesforce)
- [ ] Logging added at appropriate levels (info/warn/error)
- [ ] Monitoring/alerting added if applicable
