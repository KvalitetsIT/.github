>The PR-template can be found [here](https://github.com/KvalitetsIT/.github/blob/main/PULL_REQUEST_TEMPLATE.md)

# Jira issue
Issue number: **KH-**

<hr/>

# Changes

### What has changed - and why?
<!-- required-text-start -->
Type here
<!-- required-text-end -->
# Checklist
> Til udvikling: [Udviklingshåndbog](https://kvalitetsit.atlassian.net/wiki/x/AYAcrQ)
> 
> Til hosting: [Operations guide](https://kvalitetsit.atlassian.net/wiki/x/cYAffg) 

<!-- ignore-task-list-start -->
<!-- ignore-task-list-end -->

### Assessment
- [ ] I confirm that the change does not introduce any new privacy-related risks (privacy by design and by default)
- [ ] I confirm that the change does not introduce any new security-related risks (security by design and by default)

### Verification
- [ ] The change has been tested and works as intended
- [ ] The change only contains synthetic or anonymized data — no personal data
- [ ] There are no credentials, API keys, or secrets in the source code

### Operations
- [ ] Rollback is possible and the procedure is known
- [ ] It has been confirmed that the correct environment is being updated
- [ ] Monitoring and alerting have been considered and are in place for the relevant components

<hr/>

**Remember to add label** 
 > A label should be added to this repo if:
 >  - Repo contains infrastructure components maintained by KIT
 
 `production release tested` (After the PR is tested in prod - No matter the outcome)  
 `production release no impact` (If this pr will not impact production)
